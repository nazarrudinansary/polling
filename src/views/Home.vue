<template>
  <div class="container">
    <section class="poll">
      <h3 class="give-poll">
        Silahkan berikan penilaian anda terhada pelayanan kami
      </h3>

      <div class="emoticon">
        <p>//ini akan menjadi icon untuk polling</p>
      </div>
    </section>

    <section class="finish">
      <h4>Terima kasih telah memberikan penilaian terhadap kami</h4>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
  },
};
</script>

<style type="text/css">
  .container{
    display: flex;
    flex-wrap: wrap;
    height: 100vh;
    align-items: center;
  }

  section{
    width: 100%;
  }
</style>