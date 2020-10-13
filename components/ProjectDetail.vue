<template>
  <div class="grid h-screen grid-cols-8 grid-rows-6">
    <div class="col-span-9 row-span-1">
      <nav class="w-full h-full">
        <ul class="flex items-center justify-between w-full h-full">
          <li><a href="#">one</a></li>
          <li><a href="#1">two</a></li>
          <li><a href="#2">three</a></li>
          <li><a href="#3">four</a></li>
        </ul>
      </nav>
    </div>

    <div class="w-full h-full col-start-1 col-end-6 row-start-2 row-end-6">
      <div class="w-full h-full bg-red-500 rounded-lg">
        <img src="" alt="" srcset="" />
      </div>
    </div>

    <div class="col-start-6 col-end-9 row-start-2 row-end-6">
      <div class="flex flex-col w-full h-full px-16 text-left">
        <h2 class="text-xl">About this project</h2>
        <p class="my-8 text-justify">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam velit
          quos reprehenderit officiis quis aspernatur a deserunt culpa veritatis
          in saepe, fuga, perspiciatis atque, repudiandae recusandae! Ratione
          dicta expedita doloribus dolores, labore sunt sed aut, voluptatem quos
          obcaecati fuga vero quae velit doloremque delectus excepturi eveniet
          amet consectetur? Soluta, a.
        </p>

        <button
          class="w-full h-16 py-6 text-center rounded-full shadow-2xl"
          type="button"
        >
          Visit Website
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="20"
            height="20"
            viewBox="0 0 24 24"
            class="inline"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <polyline points="9 18 15 12 9 6"></polyline>
          </svg>
        </button>

        <a href="mailto:" class="w-full mx-auto mt-8 text-center"
          >hello@snaplark.com</a
        >
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped></style>
