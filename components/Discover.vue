<template>
  <div class="relative h-screen">
    <div class="overlay"></div>

    <img
      src="~/assets/image/akash.png"
      width="800"
      style="height: 90%; mix-blend-mode: multiply"
      class="object-cover object-center pr-1 mx-auto transform rotate-180 translate-x-20"
      height="800"
      alt="Akash image"
    />

    <div
      class="absolute inset-0 z-0 grid w-full h-full grid-cols-8 grid-rows-6"
    >
      <div class="w-full h-full col-start-1 col-end-1 row-start-5 row-end-7">
        <div class="flex items-center justify-center w-full h-full">
          <p class="capitalize transform -rotate-90">
            <span class="pr-12">film maker</span>
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

      <h2 class="col-start-3 col-end-7 row-start-3 text-6xl text-white">
        film maker
      </h2>

      <button
        class="w-1/3 h-12 col-start-3 col-end-7 row-start-5 m-auto bg-white rounded-full"
        type="button"
      >
        Discover my work

        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          class="inline"
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
</template>

<script>
export default {}
</script>

<style scoped>
.overlay {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  margin: 0 calc(-50vw + 50%) 0 calc(-50vw + 50%);
  width: auto;
  height: 100%;
  background: linear-gradient(to left, #ea38c1, #ea352e);
}
</style>
