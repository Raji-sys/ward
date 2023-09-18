<template>
    <div class="">
        <div class="grid grid-cols-2 gap-10 ">
            <div class="p-7">
                <img src="coa.jpg" alt="product image" class="mx-auto my-7">
                <div class="card-sm uppercase text-center font-bold text-2xl bg-gradient-to-r
            from-blue-700 via-blue-400 to-blue-700 text-transparent bg-clip-text">
                    <h3>progressive change</h3>
                </div>
            </div>
            <div class="p-7">
    
      <div class="font-semibold uppercase text-sm w-full flex flex-col shadow-xl sm:max-w-lg mx-auto md:p-12 overflow-hidden rounded-xl bg-white"
      >
        <section class="text-center border-b-2 border-blue-300 p-4 mb-4">
          <p class="bg-gradient-to-r from-blue-700 via-blue-400 to-blue-700 text-transparent bg-clip-text pt-4">sign in to your account</p>
        </section>
        <form action="" method="POST" class="">
          <div class="mb-2 uppercase text-gray-600">
            <div class="flex justify-center">
              <label for="uname">username</label>
            </div>
            <div class="flex justify-center mb-6">
              <input
                class="mt-2 text-xs focus:outline-none border border-blue-300 inBtn py-2 rounded shadow-lg hover:shadow-xl"
                type="text"
                name="username"
                id="uname"
              />
            </div>
            <div class="flex justify-center">
              <label for="password">password </label>
            </div>
            <div class="flex justify-center mb-4">
              <input
                class="mt-2 border text-xs border-blue-300 inBtn  py-2 rounded shadow-lg hover:shadow-xl"
                type="password"
                name="password"
                id="password"
              />
            </div>
            <div class="flex justify-center">
              <div class="w-1/2 flex justify-center align-middle">
                <input
                class="mt-2 focus:opacity-10 uppercase  focus:border-blue-600 bg-gradient-to-r
            from-blue-500 via-blue-400 to-blue-500 text-white py-2 rounded shadow-lg hover:shadow-xl w-1/2"
                type="submit"
                value="Login"
                />
              </div>
            </div>
          </div>
        </form>
        <section class="text-center border-t-2 border-blue-300 mt-4">
          <div class="mt-2 flex items-center justify-end">
            <div class="mt-4 text-gray-400 text-xs">
            <NuxtLink class="bg-gradient-to-r
            from-blue-700 via-blue-500 to-blue-700 text-transparent bg-clip-text text-sm text-bold" to="/register">register</NuxtLink>
            </div>
          </div>
        </section>
      </div>
    </div>
            </div>
        </div>
</template>

<script setup>

</script>

<style scoped>
img{
    max-width:400px;
}
</style>