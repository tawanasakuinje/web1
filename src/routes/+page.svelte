<script>

import Nav from "./nav.svelte"


import { onMount } from "svelte";
   import {inView , animate } from "motion"
 
 //animation  section 
 
 
 onMount(() => {
 
 //list
 animate('.leap', { opacity:[1] }   ,  {duration:1} )
 
 
 
 inView(".lup", (info) => {
   animate(info.target, { opacity:[1],y:[0,-80]  } ,  {duration:1}  )}) 
 
 
   
 inView(".beem", (info) => {
   animate(info.target, { opacity:[1],x:[0,-80]  } ,  {duration:1}  )}) 
 
 
     
 inView(".yeet", (info) => {
   animate(info.target, { opacity:[1]  } ,  {duration:2}  )}) 
 
 
 
 })

</script>

<Nav/>

<div class='h-3'></div>


<!--header-->

<div class=" leap  opacity-0 mt-10  md:flex justify-center md:space-x-6 ">

<img class="md:mt-12 h-84  mx-auto  md:mx-4 p-4" src="poo.png" alt="">

   

    <div class="px-3 mt-6 md:mt-40 w-full lg:w-2/5">
    <div
        class="mx-auto mb-8 max-w-lg text-center lg:mx-0 lg:max-w-md lg:text-left">
        <h2 class="mb-4 text-3xl font-bold text-left lg:text-5xl">
            Exclusive Agency For

            <span class="text-5xl text-blue-500 leading-relaxeds"
                >Technology
            </span>

            Provide Solution
        </h2>










        <p class="visible mx-0 mt-3 mb-0 text-sm leading-relaxed text-left text-slate-400">
            Helping you maximize operations management with digitization
        </p>
    </div>

    <div class="text-center lg:text-left">
        <a
            class="block visible py-4 px-8 mb-4 text-xs font-semibold tracking-wide leading-none text-white bg-blue-500 rounded cursor-pointer sm:mr-3 sm:mb-0 sm:inline-block"
            >Key Features</a
        >

        <a
            class="block visible py-4 px-8 text-xs font-semibold leading-none bg-white rounded border border-solid cursor-pointer sm:inline-block border-slate-200 text-slate-500"
            >How We Work?</a
        >
        </div>
              </div>


                     </div>
                     
                     
                     
<!--header-->




<!--content1-->


<section class="py-20 bg-white   mt-12">
    <div class="flex flex-col px-8 mx-auto space-y-12 max-w-7xl xl:px-12">
        <div class="relative">
            <h2 class="w-full text-3xl font-bold text-center sm:text-4xl md:text-5xl"> Level Up Your Designs</h2>
            <p class="w-full py-8 mx-auto -mt-2 text-lg text-center text-gray-700 intro sm:max-w-3xl">Add some nice touches to your interface with our latest designs, components, and templates. We've crafted a beautiful user experience that your visitors will love. </p>
        </div>
        <div class="flex flex-col mb-8 yeet opacity-0  sm:flex-row">
            <div class="flex items-center mb-8 sm:w-1/2 md:w-5/12 sm:order-last">
                <img class="rounded-lg shadow-xl " src="https://cdn.devdojo.com/images/december2020/dashboard-011.png" alt="">
            </div>
            <div class="flex flex-col justify-center mt-5 mb-8 md:mt-0 sm:w-1/2 md:w-7/12 sm:pr-16">
                <p class="mb-2 text-sm font-semibold leading-none text-left text-indigo-600 uppercase">Drag-n-drop design</p>
                <h3 class="mt-2 text-2xl sm:text-left md:text-4xl">Design Made Easy</h3>
                <p class="mt-5 text-lg text-gray-700 text md:text-left">Crafting your user experience has never been easier, with our intuitive drag'n drop interface you will be creating beatiful designs in no time.</p>
            </div>
        </div>
        <div class="flex mb:mt-32 flex-col mb-8 yeet opacity-0 sm:flex-row">
            <div class="flex items-center mb-8 sm:w-1/2 md:w-5/12">
                <img class="rounded-lg shadow-xl" src="https://cdn.devdojo.com/images/december2020/dashboard-04.png" alt="">
            </div>
            <div class="flex flex-col justify-center mt-5 mb-8 md:mt-0 sm:w-1/2 md:w-7/12 sm:pl-16">
                <p class="mb-2 text-sm font-semibold leading-none text-left text-indigo-600 uppercase">know your data</p>
                <h3 class="mt-2 text-2xl sm:text-left md:text-4xl">Optimized For Conversions</h3>
                <p class="mt-5 text-lg text-gray-700 text md:text-left">Backed by data, these templates have been crafted for ultimate optimization. Now, converting your visitors into customers is easier than ever before.</p>
            </div>
        </div>
        <div class="flex flex-col mb-8 yeet opacity-0 sm:flex-row">
            <div class="flex items-center mb-8 sm:w-1/2 md:w-5/12 sm:order-last">
                <img class="rounded-lg shadow-xl" src="https://cdn.devdojo.com/images/december2020/dashboard-03.png" alt="">
            </div>
            <div class="flex flex-col justify-center mt-5 mb-8 md:mt-0 sm:w-1/2 md:w-7/12 sm:pr-16">
                <p class="mb-2 text-sm font-semibold leading-none text-left text-indigo-600 uppercase">Easy to customize</p>
                <h3 class="mt-2 text-2xl sm:text-left md:text-4xl">Make It Your Own</h3>
                <p class="mt-5 text-lg text-gray-700 text md:text-left">All templates and components are fully customizable. You can use these templates to tell your personal story and convey your message.</p>
            </div>
        </div>

    </div>
</section>


<!-- component -->
<!-- This is an example component -->
<div class=" bg-gray-900">
    <div class="max-w-2xl mx-auto text-white py-10">
        <div class="text-center">
            <h3 class="text-3xl mb-3"> Download our  app </h3>
            <p>  All day, every day. </p>
            <div class="flex justify-center my-10">
                <div class="flex items-center border w-auto rounded-lg px-4 py-2 w-52 mx-2">
                    <img src="https://cdn-icons-png.flaticon.com/512/888/888857.png" class="w-7 md:w-8">
                    <div class="text-left ml-3">
                        <p class='text-xs text-gray-200'>Download on </p>
                        <p class="text-sm md:text-base"> Google Play Store </p>
                    </div>
                </div>
                <div class="flex items-center border w-auto rounded-lg px-4 py-2 w-44 mx-2">
                    <img src="https://cdn-icons-png.flaticon.com/512/888/888841.png" class="w-7 md:w-8">
                    <div class="text-left ml-3">
                        <p class='text-xs text-gray-200'>Download on </p>
                        <p class="text-sm md:text-base"> Apple Store </p>
                    </div>
                </div>
            </div>
        </div>
        <div class="mt-28 flex flex-col md:flex-row md:justify-between items-center text-sm text-gray-400">
            <p class="order-2 md:order-1 mt-8 md:mt-0"> &copy; Beautiful Footer, 2021. </p>
            <div class="order-1 md:order-2">
                <span class="px-2">About us</span>
                <span class="px-2 border-l">Contact us</span>
                <span class="px-2 border-l">Privacy Policy</span>
            </div>
        </div>
    </div>
</div>