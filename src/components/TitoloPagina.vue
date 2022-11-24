<template>
  <div>
    <h1>Ciao a tutti dal primo componente</h1>
    <h2>Il secondo componente</h2>
    <h3>Il terzo componente</h3>
  </div>
</template>

<script>
export default {
  name: 'TitoloPagina',
};
</script>

<style lang="scss" scoped>
  $title_color: rgb(1, 200, 250);

  h1{
    text-align: center;
    padding: 1rem;
    color: rgb(255, 156, 7);

    &:hover {
      transform: scale(1.2);
      color: $title_color;
    }
  }
  h2{
    text-align: center;
    padding: 1rem;
    color: rgb(6, 31, 253);

    &:hover {
      transform: scale(1.2);
      color: rgb(255, 156, 7);
    }
  }
  h3{
    text-align: center;
    padding: 1rem;
    color: $title_color;

    &:hover {
      transform: scale(1.2);
      color: rgb(6, 31, 253);
    }
  }
</style>
