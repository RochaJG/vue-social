<template>
  <span>
    <header>
      <nav-bar logo="Social" url="#" cor="green darken-1" />
    </header>

    <main>
      <div class="container">
        <div class="row">
          <grid-vue tamanho="4">
            Menu
          </grid-vue>
          <grid-vue tamanho="8">
            <router-view/>
          </grid-vue>
        </div>
      </div>
    </main>

    <footer-vue cor="green darken-1" logo="Social" descricao="Teste de descrição">
      <li><a class="grey-text text-lighten-3" href="#!">Home</a></li>
      <li><a class="grey-text text-lighten-3" href="#!">Link 2</a></li>
      <li><a class="grey-text text-lighten-3" href="#!">Link 3</a></li>
      <li><a class="grey-text text-lighten-3" href="#!">Link 4</a></li>
    </footer-vue>

  </span>
</template>

<script>
import NavBar from '@/components/layouts/NavBar'
import FooterVue from '@/components/layouts/FooterVue'
import GridVue from '@/components/layouts/GridVue'

export default {
  name: 'app',
  components:{
    NavBar,
    FooterVue,
    GridVue
  }
}
</script>

<style>

</style>
