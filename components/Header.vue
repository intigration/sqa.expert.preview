<template>
    <header class="header">
      <nuxt-link to="/" class="logo">
        <!-- Update your site logo text -->
        SQA.Expert
      </nuxt-link>
      <input class="menu-btn" type="checkbox" id="menu-btn" v-model="menuChecked"/>
      <label class="menu-icon" for="menu-btn"><span class="navicon"></span></label>
      <ul class="menu">
        <!-- Page Links -->
        <li><nuxt-link to="/blog" @click.native="menuChecked=false">Learn</nuxt-link></li>
        <li><nuxt-link to="/contact" @click.native="menuChecked=false">Compete</nuxt-link></li>
        <li><nuxt-link to="/about" @click.native="menuChecked=false">Lead</nuxt-link></li>
      </ul>
    </header>
</template>

<script>
export default {
    props: ['menuChecked']
}
</script>