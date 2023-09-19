<template>
    <div>
        <header class="shadow-xl ">
            <nav class="container mx-auto p-8 flex justify-between uppercase">
                <NuxtLink to="/" class="font-bold cus-text-gr">apc</NuxtLink>
                <div>

                    <ul class="flex gap-4">
                    <li>
                        <div class="cus-btn bg-white w-full">
                            <NuxtLink to="/">report</NuxtLink>
                        </div> 
                    </li>
                    <li class="cus-btn w-full">
                        <NuxtLink to="/about">statistics</NuxtLink>
                    </li>
                </ul>
                </div>
            <div class="flex">
                <form action="" method="POST" class="flex">
                <div class="flex items-center uppercase text-gray-600">
                    <input class="py-2 px-3 focus:outline-none border border-blue-300 rounded shadow-lg hover:shadow-xl uppercase" type="text" name="search" id="search" placeholder="enter a keyword"/>
                    <button class="py-2 px-4 focus:opacity-10 uppercase focus:border-blue-600 bg-gradient-to-r from-blue-500 via-blue-400 to-blue-500 text-white rounded shadow-lg hover:shadow-xl " type="submit">search</button>
                </div>
            </form>
            </div>
            </nav>
        </header>

        <!-- output page content -->
        <div class="container mx-auto p-4">
            <slot />
        </div>
    </div>
</template>

<style scoped>
.router-link-exact-active {
    color: #12b488;
}
</style>