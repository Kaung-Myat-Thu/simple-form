<template>
  <nav class="text-center mt-4 font-bold text-2xl font-serif">
    <router-link active-class="text-violet-500" to="/">Login</router-link> |
    <router-link active-class="text-violet-500" to="/sign-up"
      >Sign up</router-link
    >
  </nav>
  <div class="w-screen h-screen flex flex-col justify-center items-center">
    <router-view></router-view>
  </div>
</template>
