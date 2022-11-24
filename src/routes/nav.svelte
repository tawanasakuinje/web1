
<script>
import {slide} from 'svelte/transition'
let open = false ;


</script>



<div class='bg-blue-800 py-4 w-full md:h-20 fixed opacity-90  h-16'>



    <svg  xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="mx-auto   md:mt-3 md:mx-12 text-white w-8 h-8">
           <path stroke-linecap="round" stroke-linejoin="round" d="M6 12L3.269 3.126A59.768 59.768 0 0121.485 12 59.77 59.77 0 013.27 20.876L5.999 12zm0 0h7.5" />
             </svg>    
               

<div class=' hidden md:flex  absolute top-0 mx-32 mt-7 text-xl  space-x-6 justify-center text-white'>

     <a class=" hover:border-b-8 ease-out  duration-200" href="">about</a>
     <a class=" hover:border-b-8 ease-out duration-200" href=   "">menu</a>
     <a class=" hover:border-b-8 ease-out duration-200  " href="">contact</a>
     
    
   
   
    </div>

 <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-7 absolute  top-0 right-0 mx-8  md:mt-7 text-white  mt-5  h-7">
        <path stroke-linecap="round" stroke-linejoin="round" d="M17.982 18.725A7.488 7.488 0 0012 15.75a7.488 7.488 0 00-5.982 2.975m11.963 0a9 9 0 10-11.963 0m11.963 0A8.966 8.966 0 0112 21a8.966 8.966 0 01-5.982-2.275M15 9.75a3 3 0 11-6 0 3 3 0 016 0z" />
      </svg>
      

<!--mobile menu -->




<div class="md:hidden ">




    <button on:click={ () => (open = !open) }>
<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 top-0 mt-4 mb:mt-6 mx-4 absolute text-white h-8">
  <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
    </svg>
      </button>


{#if open }
	
<div transition:slide class="flex space-y-4 mx-4  absolute h-64 text-bold    flex-col  text-white bg-blue-900 rounded-lg p-4 w-1/2">
<a class="hover:text-blue-300 hover:bg-slate-500 border-b p-2 " href="">about</a>
<a class="hover:text-blue-300  hover:bg-slate-500 border-b p-2 " href=   "">menu</a>
<a class="hover:text-blue-300  hover:bg-slate-500 border-b p-2 " href="">contact</a>
</div>

{/if}


</div>







</div>


