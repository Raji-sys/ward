<template>
    <div>
    <h1 class="cus-text-gr text-center uppercase text-xl">sharada</h1>
<div class="p-1 mt-1 max-sm:p-2 text-sm rounded-lg text-center">
    <table class="table-auto mt-0 max-sm:flex flex rounded-lg items-center justify-center">
        <tbody class=" border-2 shadow-2xl rounded-xl max-sm:p-4 p-1 overflow-x-auto border-blue-300 ">            
            <tr class="text-md bg-gradient-to-r from-blue-500 via-blue-400 to-blue-500  text-white">
                <th scope="col" class="border-l-2 border-b-2 border-b-white border-blue-300 border-t-2 border-t-white p-2">S/N</th>
                <th scope="col" class="border-2 border-white p-2">NAME</th>
                <th scope="col" class="border-2 border-white p-2">SEX</th>
                <th scope="col" class="border-2 border-white p-2">EMAIL</th>
                <th scope="col" class="border-2 border-white p-2">PHONE</th>
                <th scope="col" class="border-2 border-white p-2">ADDRESS</th>
                <th scope="col" class="border-2 border-white p-4">ZONE</th>
                <th scope="col" class="border-2 border-white p-2">STATE</th>
                <th scope="col" class="border-2 border-white p-2" >LGA</th>
                <th scope="col" class="border-2 border-white p-2">WARD</th>
                <th scope="col" class="border-2 border-blue-300 text-gray-100 p-2 border-t-2 border-t-white border-b-white">FULL DETAILS</th>
            </tr>
        <tr class="text-xs uppercase cus-text-gr">
           <td class="border-2 border-blue-300 p-1 text-center">
            1
        </td> 
            <td class="border-2 border-blue-300 p-4 text-center">
            musa mansa
            </td>
            <td class="border-2 border-blue-300 p-4 text-center">
            male
            </td>
            <td class="border-2 border-blue-300 p-4 text-center">
            mm@gmail.com
            </td>
            <td class="border-2 border-blue-300 p-1 text-center">
            09089799331 
            </td>
            <td class="border-2 border-blue-300 p-1 text-center">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab, voluptatem
            </td>
            <td class="border-2 border-blue-300 p-4 text-center">
                north-west
            </td>
            <td class="border-2 border-blue-300 p-4 text-center">
            kano
            </td>
            <td class="border-2 border-blue-300 p-2 text-center">                
            kano municipal
            </td>
            <td class="border-2 border-blue-300 p-4 text-center">
            sharada
            </td>
             <td class="p-1 border-2 border-blue-300"> 
            <NuxtLink to="/nc/niger/bida/bakiri/member">profile</NuxtLink>
                </td> 
            </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td class="p-4 text-center">
                
                <div class="pagination flex justify-center text-green-800">
                    <span class="step-links">

        </span>
    </div>
    </td>
    </tr>
</tbody>
</table>
    </div>

    </div>
</template>

<script setup>
definePageMeta({
    layout:'dashboard'
})
</script>

<style scoped>
</style>