<template>
  <SimpleGallery galleryID="my-test-gallery" :images="images" />
</template>

<script>
import SimpleGallery from './SimpleGallery.vue';

export default {
  name: 'App',
  components: {
    SimpleGallery,
  },
  data() {
    return {
      images: [
        {
          largeURL:
            'https://i.postimg.cc/R0V895rK/IMG-20260128-132716194.jpg',
          thumbnailURL:
            'https://i.postimg.cc/R0V895rK/IMG-20260128-132716194.jpg',
          width: 1875,
          height: 2500,
        },
        {
          largeURL:
            'https://cdn.photoswipe.com/photoswipe-demo-images/photos/2/img-2500.jpg',
          thumbnailURL:
            'https://cdn.photoswipe.com/photoswipe-demo-images/photos/2/img-200.jpg',
          width: 1669,
          height: 2500,
        },
        {
          largeURL:
            'https://cdn.photoswipe.com/photoswipe-demo-images/photos/3/img-2500.jpg',
          thumbnailURL:
            'https://cdn.photoswipe.com/photoswipe-demo-images/photos/3/img-200.jpg',
          width: 2500,
          height: 1666,
        },
      ],
    };
  },
};
</script>