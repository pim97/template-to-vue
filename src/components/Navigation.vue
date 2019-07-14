<template>

  <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
    <div class="container">
      <a class="navbar-brand js-scroll-trigger" href="#page-top">Start Bootstrap</a>
      <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
        Menu
        <i class="fas fa-bars"></i>
      </button>
      <div class="collapse navbar-collapse" id="navbarResponsive">
        <ul class="navbar-nav text-uppercase ml-auto" v-for="(obj, key) in nJSON" :key = "key">
          <li class="nav-item">
            <a class="nav-link js-scroll-trigger" :href="obj.link">{{obj.name}}</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

</template>

<script>
export default {
    data: () => ({
        nJSON : [
            {
                'name' : 'Services',
                'link' : '#services'
            },
            {
                'name' : 'Portfolio',
                'link' : '#portfolio'
            },
            {
                'name' : 'About',
                'link' : '#about'
            },
            {
                'name' : 'Team',
                'link' : '#team'
            },
            {
                'name' : 'Contact',
                'link' : '#contact'
            }
        ]
    })
}
</script>

<style lang="sass" scoped>

</style>
