<!--index is usually the first thing in web application-->
<template>
  <div class="bg-grayish-white-1 relative">
    <!-- DISPLAY IMAGE -->
    <div class="h-screen w-2/3">
      <img
        class="w-full h-full object-cover"
        src="https://images.pexels.com/photos/331684/pexels-photo-331684.jpeg?cs=srgb&dl=pexels-math-331684.jpg&fm=jpg
"
      />
    </div>
    <!--DISPLAY NAME-->
    <div class="absolute h-screen w-1/2 top-0 right-0">
      <div class="flex h-full w-full">
        <div class="my-auto w-full">
          <div class="flex flex-col">
            <div class="text-4xl font-poppins text-gray-800">
              <span class="font-thin">Welcome to</span>
              <span class="font-semibold">Steven's Page</span>
              <span class="text-6xl text-lead-yellow">.</span>
            </div>
            <div class="font-thin font-sans text-gray-600 -mt-4">
              Data enthusiast | Master's in Statistics | Trader
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
