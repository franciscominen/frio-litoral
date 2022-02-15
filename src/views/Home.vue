<template>
  <main class="home_container">
    <h1>
      Encontrá el repuesto<br />
      que estás buscando<span>.</span>
    </h1>
    <ul>
      <li>
        <img src="@/assets/img/lavarropa.png" alt="" />
        <h2>Lavarropas</h2>
      </li>
      <li>
        <img src="@/assets/img/aire.png" alt="" />
        <h2>
          Aires<br />
          Acondicionados
        </h2>
      </li>
      <li>
        <img src="@/assets/img/heladera.png" alt="" />
        <h2>Heladeras</h2>
      </li>
      <li>
        <img src="@/assets/img/automotor.png" alt="" />
        <h2>Automotor</h2>
      </li>
    </ul>
  </main>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style lang='scss' src='@/scss/views/home.scss'>
</style>