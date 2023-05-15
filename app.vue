<script>
import '@/css/style.css';
</script>
<template>
  <div class="container">
    <div class="column">
      <h1>Built in Component</h1>
      <nuxt-img src="/img/sample.jpg" width="500" format="webp" />
      <nuxt-img src="/img/sample2.jpg" width="500" format="webp" />
      <nuxt-img src="/img/sample3.jpg" width="500" format="webp" />
    </div>
    <div class="column">
      <h1>Cloudinary Image</h1>
      <img
        width="500"
        src="https://res.cloudinary.com/tamas-demo/image/upload/w_500,f_webp,q_auto/img-component/sample.jpg"
        alt="Sample Image"
      />
      <img
        width="500"
        src="https://res.cloudinary.com/tamas-demo/image/upload/w_500,f_webp,q_auto/img-component/sample2.jpg"
        alt="Sample Image"
      />
      <img
        width="500"
        src="https://res.cloudinary.com/tamas-demo/image/upload/w_500,f_webp,q_auto/img-component/sample3.jpg"
        alt="Sample Image"
      />
    </div>
  </div>
</template>
