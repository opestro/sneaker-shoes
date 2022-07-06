<template>
    <div>

            <div class="l-header" id="header">
        <nav class="nav bd-grid">
            <div class="nav__toggle" id="nav-toggle">
                <i data-feather="menu"></i>
            </div>
            <a href="#" class="nav__logo">
                <h3> <b>Sneaker</b> Shoes Store </h3>
            </a>

            <div class="nav__menu" id="nav-menu">
                <ul class="nav__list">
                    <li class="nav__item"><router-link to="/">Home</router-link></li>
                    <li class="nav__item"><a href="#featured" class="nav__link">Featured</a></li>
                    <li class="nav__item"><a href="#collection" class="nav__link">Collections</a></li>
                    <li class="nav__item"><a href="#men" class="nav__link">Men</a></li>
                    <li class="nav__item"><a href="#women" class="nav__link">Women</a></li>
                    <li class="nav__item"><router-link to="/product">Shop</router-link></li>
                    
                </ul>
            </div>

            <div class="nav__shop">
                <i data-feather="shopping-bag"></i>
            </div>
        </nav>
    </div>
    </div>
</template>
<script>
export default {
    head() {
        return {
    script: [
      {
        
      },
      
    ],
  /*  link: [
      {rel: 'stylesheet', href: require('assets/css/styles.css')},
      {rel: 'stylesheet', href: require('assets/fontawesome-free-5.15.0-web/css/all.css')},
      {rel: 'icon', href: require('assets/logo.png')},
      {rel: 'shortcut', href: require('assets/logo.png')},
      {rel: 'apple-touch-icon', href: require('assets/logo.png')},
    ]*/
    }
  }
}


</script>
