<template>
  <div class="grid h-screen grid-cols-8 grid-rows-6 py-16">
    <div class="col-start-1 col-end-5 px-10">
      <div class="max-w-xs text-left">
        <h2 class="text-4xl">Say Hello ✏</h2>
        <p class="my-6">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dignissimos,
          error?
        </p>
      </div>

      <form class="my-16">
        <div class="flex">
          <label class="text-left" for="name">
            Enter your name<input
              id="name"
              class="border-b-2 border-black appearance-none"
              type="text"
          /></label>
          <label class="text-left" for="email"
            >Enter your email<input
              id="email"
              class="border-b-2 border-black appearance-none"
              type="email"
          /></label>
        </div>

        <div class="flex mt-8">
          <label class="text-left" for="country"
            >Country<input
              id="country"
              class="border-b-2 border-black appearance-none"
              type="text"
          /></label>
          <label class="text-left" for="phone"
            >Mobile number<input
              id="phone"
              class="border-b-2 border-black appearance-none"
              type="number"
          /></label>
        </div>

        <div class="flex">
          <label class="mt-8 text-left" for="message"
            >Write your message here<input
              id="message"
              class="w-full border-b-2 border-black appearance-none"
              type="text"
          /></label>
        </div>

        <button type="submit" class="px-20 py-6 mt-16 rounded-full shadow-2xl">
          Submit
        </button>
      </form>
    </div>
    <div class="col-start-6 col-end-9">
      <div class="flex flex-col content-between justify-between">
        <div
          class="flex flex-col items-center justify-center h-64 bg-gray-200 rounded-md"
        >
          <h2 class="text-5xl">Akash Sekar</h2>
          <span class="text-2xl">hello@akashofficial.com</span>
          <a
            class="px-16 py-6 transform translate-y-16 bg-white rounded-full shadow-2xl"
            href="#"
            download=""
            >Download Resume</a
          >
        </div>

        <div class="flex flex-col mt-32">
          <h3>Featured in</h3>
          <div class="">logo1</div>
          <div class="">logo2</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped></style>
