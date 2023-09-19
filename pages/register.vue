<template>
<div class="max-sm:mt-2">
  <div class="font-semibold uppercase text-sm w-full flex flex-col shadow-xl sm:max-w-lg mx-auto md:p-12 overflow-hidden rounded-xl bg-white">
    <section class="text-center border-b-2 border-blue-300 p-2">
      <p class="cus-text-gr">fill this form to register</p>
      <!-- <div class="mt-2 uppercase p-2 gap-4">
      </div> -->
    </section>
    <form action="" method="POST">
      <div class="mb-1 mt-4 uppercase text-gray-600">
        <div class="flex justify-center">
          <label for="uname">username</label>
        </div>
        <p class="flex justify-center mb-4">
          <input
            id="uname"
            class="cus-input min-w-full"
            type="text"
            name="username"
          />
        </p>
        <div class="flex justify-center">
          <label for="email">email</label>
        </div>
        <p class="flex justify-center mb-4">
          <input
            id="email"
            class="cus-input min-w-full"
            type="text"
            name="email"
          />
        </p>
        <div class="flex justify-center">
          <label for="lname">surname</label>
        </div>
        <p class="flex justify-center mb-4">
          <input
            class="cus-input min-w-full"
            type="text"
            name="last_name"
            id="lname"
          />
        </p>
        <div class="flex justify-center">
          <label for="fname">first name</label>
        </div>
        <p class="flex justify-center mb-4">
          <input
            class="cus-input min-w-full"
            type="text"
            name="first_name"
            id="fname"
          />
        </p>
        <div class="flex justify-center">
          <label for="password">password </label>
        </div>
        <p class="flex justify-center mb-4">
          <input
            class="cus-input min-w-full"
            type="password"
            name="password1"
            id="password"
          />
        </p>
        <div class="flex justify-center">
          <label for="conpassword">confirm password </label>
        </div>
        <p class="flex justify-center mb-4">
          <input
            class="cus-input min-w-full"
            type="password"
            name="password2"
            id="conpassword"
          />
        </p>
        <div class="flex justify-center">
          <NuxtLink to="/dashboard" class="cus-btn text-center" type="submit">Register</NuxtLink>
        </div>
        <div class="mt-2 flex items-center justify-end  border-t-2 border-blue-300">
          <div class="text-green-800 text-xs">
            <NuxtLink to="/" class="cus-text-gr">login</NuxtLink>
          </div>
        </div>
      </div>
    </form>
  </div>
</div>
</template>

<script setup>

</script>

<style scoped>

</style>