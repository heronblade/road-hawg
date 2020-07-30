<template>
  <div class="navigation__bottom">
    <!--    <nuxt-link to="/">Home</nuxt-link>-->
    <!--    <nuxt-link to="/menu">Menu</nuxt-link>-->
    <!--    <nuxt-link to="/catering">Catering</nuxt-link>-->
    <!--    <nuxt-link to="/online-order">Online Order</nuxt-link>-->
    <!--    Made by Erik Terwan    -->
    <!--   24th of November 2015   -->
    <!--        MIT License        -->
    <nav role="navigation">
      <p>Menu</p>
      <div id="menuToggle">
        <!--
        A fake / hidden checkbox is used as click reciever,
        so you can use the :checked selector on it.
        -->
        <input type="checkbox" />

        <!--
        Some spans to act as a hamburger.
        They are acting like a real hamburger,
        not that McDonalds stuff.
        -->
        <span></span>
        <span></span>
        <span></span>

        <!--
        Too bad the menu has to be inside of the button
        but hey, it's pure CSS magic.
        -->
        <ul id="menu">
          <a href="#"><li>Home</li></a>
          <a href="#"><li>About</li></a>
          <a href="#"><li>Info</li></a>
          <a href="#"><li>Contact</li></a>
          <a href="https://erikterwan.com/" target="_blank">
            <li>Show me more</li>
          </a>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'bottomNavigation'
};
</script>
