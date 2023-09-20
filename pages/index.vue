<template>
        <div class="grid grid-cols-2 gap-10 ">
            <div class="p-7">
                <img src="logo1.png" alt="product image" class="mx-auto my-4">
                <div class="cus-text-gr text-lg uppercase text-center">
                    <p>all progressive congress</p>
                </div>
            </div>
      <div class="p-7">
      <div class="font-semibold uppercase text-sm w-full flex flex-col shadow-xl sm:max-w-lg mx-auto md:p-12 overflow-hidden rounded-xl bg-white">
        <section class="text-center border-b-2 border-blue-300 p-4 mb-4">
          <p class="cus-text-gr pt-4">sign in to your account</p>
        </section>
        <form action="" method="POST" class="">
          <div class="mb-2 uppercase text-gray-600">
            <div class="flex justify-center">
              <label for="uname">username</label>
            </div>
            <div class="flex justify-center mb-6">
              <input class="cus-input" type="text" name="username" id="uname"/>
            </div>
            <div class="flex justify-center">
              <label for="password">password </label>
            </div>
            <div class="flex justify-center mb-4">
              <input class="cus-input" type="password" name="password" id="password"/>
            </div>
            <div class="flex justify-center">
              <div class="w-1/2 flex justify-center align-middle">
                <NuxtLink to="/dashboard" class="cus-btn text-center" type="submit" value="Login">Login</NuxtLink>
              </div>
            </div>
          </div>
        </form>
        <section class="text-center border-t-2 border-blue-300 mt-4">
          <div class="mt-2 flex items-center justify-end">
            <div class="mt-4 text-gray-400">
            <NuxtLink class="cus-text-gr" to="/register">register</NuxtLink>
            </div>
          </div>
        </section>
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