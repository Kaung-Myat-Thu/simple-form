<template>
  <h1 class="font-bold text-3xl font-serif">LOGIN PAGE</h1>
  <form @submit.prevent="" class="flex flex-col justify-center">
    <input
      type="text"
      placeholder="Username"
      class="rounded-sm bg-gray-300 px-4 py-2 my-4 w-96 placeholder:text-gray-600"
    />
    <input
      type="email"
      placeholder="Email"
      class="rounded-sm bg-gray-300 px-4 py-2 my-4 w-96 placeholder:text-gray-600"
    />
    <input
      type="password"
      placeholder="Password"
      class="rounded-sm bg-gray-300 px-4 py-2 my-4 w-96 placeholder:text-gray-600"
    />
    <div class="flex justify-between items-center">
      <div>
        <input
          type="checkbox"
          class="text-violet-500 rounded mr-2 focus:ring-0"
        />Remember me
      </div>
      <div>
        <router-link to="/" class="text-violet-500 font-bold"
          >Forget?</router-link
        >
      </div>
    </div>
    <button
      class="bg-gradient-to-r from-violet-500 via-purple-500 to-indigo-500 font-bold text-white rounded-md py-2 my-2 hover:from-violet-700 hover:via-purple-700 hover:to-indigo-700"
    >
      LOGIN
    </button>
  </form>
  <div>
    <p class="font-semibold">
      Haven't any account? Please
      <router-link class="text-violet-500 underline" to="/sign-up"
        >Sign up</router-link
      >
      here.
    </p>
  </div>
</template>

<script>
export default {};
</script>
