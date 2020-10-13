<template>
  <div class="grid h-screen grid-cols-8 grid-rows-6">
    <div
      class="w-full h-full col-start-1 col-end-9 row-start-1 row-end-5 bg-green-100"
    >
      <div class="flex w-full h-full">
        <div class="block w-full h-full m-1 border border-black">one</div>
        <div class="block w-full h-full m-1 border border-black">two</div>
        <div class="block w-full h-full m-1 border border-black">three</div>
        <div class="block w-full h-full m-1 border border-black">four</div>
        <div class="block w-full h-full m-1 border border-black">five</div>
      </div>
    </div>

    <div class="w-full h-full col-start-1 col-end-9 row-start-5 row-end-7">
      <div class="flex items-center justify-between w-full h-full">
        <div class="flex flex-col items-start max-w-lg text-left">
          <h2 class="mb-6 text-2xl">About this project</h2>
          <p class="text-justify">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores
            ipsa tempore vero eveniet blanditiis! Deserunt voluptatum doloremque
            provident perferendis odit culpa veritatis rem pariatur autem,
            aperiam, quasi ea atque quod, exercitationem velit qui commodi.
            Ducimus reiciendis ipsam natus iure cum.
          </p>
        </div>
        <div class="">
          <h2 class="block mb-6 text-2xl">Cast</h2>
          <p class="block mb-3">Akash Sekar - Camera man</p>
          <p class="block mb-3">Armit - Creative Designer</p>
          <p class="block mb-3">Shoib - Light Handler</p>
        </div>
        <div class="flex flex-col items-center justify-around">
          <button
            class="w-48 h-full py-6 mb-6 text-center rounded-full shadow-2xl"
            type="button"
          >
            Next
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
          <button
            class="w-48 h-full py-6 text-center rounded-full shadow-2xl"
            type="button"
          >
            Previous
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
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped></style>
