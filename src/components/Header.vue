<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  
  {
    'src': 'https://static.vecteezy.com/system/resources/thumbnails/002/294/883/small/digital-library-web-banner-design-students-reading-book-on-online-library-web-online-education-digital-classroom-e-learning-concept-header-or-footer-banner-free-vector.jpg',
    'alt': 'Picture 1 ',
  },
  {
    'src': 'https://static.vecteezy.com/system/resources/thumbnails/002/294/871/small/reading-book-web-banner-design-open-book-with-stack-of-books-header-or-footer-banner-illustration-free-vector.jpg',
    'alt': 'Picture 2 ',
  },
  {
    'src': 'https://static.vecteezy.com/system/resources/thumbnails/002/294/883/small/digital-library-web-banner-design-students-reading-book-on-online-library-web-online-education-digital-classroom-e-learning-concept-header-or-footer-banner-free-vector.jpg',
    'alt': 'Picture 3 ',
  },
  {
    'src': 'https://static.vecteezy.com/system/resources/thumbnails/002/294/871/small/reading-book-web-banner-design-open-book-with-stack-of-books-header-or-footer-banner-illustration-free-vector.jpg',
    'alt': 'Picture 4 ',
  },
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>
