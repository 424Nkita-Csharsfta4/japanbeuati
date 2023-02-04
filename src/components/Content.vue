<template>
    <div class="relative h-64">
      <img
        :src="images[currentIndex]"
        class="w-150 h-150 object-cover"
      />
      <button
        class="absolute bottom-0 left-0 m-4 p-2 bg-gray-300 rounded-full"
        @click="previousImage"
      >
        <svg class="w-6 h-6" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor">
          <path d="M15 19l-7-7 7-7"></path>
        </svg>
      </button>
      <button
        class="absolute bottom-0 right-0 m-4 p-2 bg-gray-300 rounded-full"
        @click="nextImage"
      >
        <svg class="w-6 h-6" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor">
          <path d="M9 5l7 7-7 7"></path>
        </svg>
      </button>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        currentIndex: 0,
        images: [
          'https://sun9-west.userapi.com/sun9-12/s/v1/ig2/S4Io9X8lMZjfigRzBMP0LZsqWONDzYuLrb7EY1wwETo66uvOAyc-3EN8Q9IlWb1a-c_SxiscCaQuYAUCrGMLGmGv.jpg?size=735x919&quality=95&type=album',
          'https://sun9-west.userapi.com/sun9-3/s/v1/ig2/5Pn_k5_Up-0rDCdq672yW_q10eAoBOMJeklxr9ZRjlgZAzwn-Wavrxrv231HXeVAsJ9zVNqBMaTO5FP8vpyn_ECS.jpg?size=750x750&quality=95&type=album',
          'https://sun9-west.userapi.com/sun9-14/s/v1/ig2/2-YKiI6GbVJVtB0hhgVO0--5SR06mtri0E7UjfujT41l7XhbtjSiAqLKC1WSEABqjZuPZJ26LfzLMI8SyUZjmBoK.jpg?size=1280x1280&quality=95&type=album',
        ],
      };
    },
    methods: {
      previousImage() {
        if (this.currentIndex === 0) {
          this.currentIndex = this.images.length - 1;
        } else {
          this.currentIndex--;
        }
      },
      nextImage() {
        if (this.currentIndex === this.images.length - 1) {
          this.currentIndex = 0;
        } else {
          this.currentIndex++;
        }
      },
    },
  };
  </script>
  
  <style>
  .slider {
    width: 300px;
    height: 300px;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  </style>
  