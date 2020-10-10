<template>
  <div class="static flex items-end justify-center h-screen">
    <img
      src="~/assets/image/akash.png"
      width="800"
      style="height: 90%"
      class="absolute z-10 object-cover object-center mx-auto"
      height="800"
      alt="Akash image"
    />

    <div
      class="z-20 flex flex-col content-between h-32 max-w-md justify-evenly"
    >
      <p class="text-white">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt
        possimus ducimus ipsum perferendis ipsa illo blanditiis suscipit
      </p>

      <div class="flex items-center justify-between w-16 mx-auto text-white">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          class="text-current stroke-current"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect>
          <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path>
          <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line>
        </svg>

        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="text-current stroke-current"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path
            d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"
          ></path>
          <rect x="2" y="9" width="4" height="12"></rect>
          <circle cx="4" cy="4" r="2"></circle>
        </svg>
      </div>
    </div>

    <div class="absolute inset-0 z-0 grid h-screen grid-cols-8 grid-rows-6">
      <div class="w-full h-full col-start-1 col-end-1 row-start-5 row-end-7">
        <div class="flex items-center justify-center w-full h-full">
          <p class="capitalize transform -rotate-90">
            <span class="pr-12">scroll down</span>
            <svg
              class="inline w-px h-auto transform -rotate-90"
              viewBox="0 0 1 68"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <line
                x1="0.5"
                y1="0.5"
                x2="0.5"
                y2="67.5"
                stroke="black"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </p>
        </div>
      </div>

      <div class="w-full h-full col-start-2 col-end-6 row-start-2 row-end-6">
        <div class="flex items-center justify-center">
          <p style="font-size: 10rem">akash</p>
        </div>
      </div>
      <div class="w-full h-full col-start-8 col-end-12 row-start-2 row-end-6">
        <div class="flex items-center justify-center">
          <p style="font-size: 10rem">sekar</p>
        </div>
      </div>

      <div class="w-full h-full col-start-9 col-end-12 row-start-1 row-end-3">
        <div class="flex items-center justify-center w-full h-full">
          <button
            type="button"
            class="row-start-1 px-24 py-5 capitalize bg-white rounded-full shadow-2xl"
          >
            more about me
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
