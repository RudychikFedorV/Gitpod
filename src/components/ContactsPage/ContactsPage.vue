<template>
  <div class="ContactsPage">
    <div class="container">
      <div class="ContactsPage__Gitpods indentation">
        <div class="ContactsPage__Gitpod title">Gitpod</div>
        <router-link to="/"><div class="ContactsPage__Home tx">Home</div></router-link>
        <router-link to="/"
          ><div class="ContactsPage__Features tx">Features</div></router-link
        >
        <router-link to="/"
          ><div class="ContactsPage__Pricing tx">Pricing</div></router-link
        >
        <router-link to="/"
          ><div class="ContactsPage__Changelog tx">Changelog</div></router-link
        >
        <router-link to="/"
          ><div class="ContactsPage__SelfHosted tx">Self-Hosted</div></router-link
        >
        <router-link to="/"
          ><div class="ContactsPage__Gitpod tx">Gitpod vs GitHub</div></router-link
        >
        <router-link to="/"
          ><div class="ContactsPage__Codespaces tx">Codespaces</div></router-link
        >
        <router-link to="/"
          ><div class="ContactsPage__Status tx">Status</div></router-link
        >
      </div>

      <div class="ContactsPage__Developers indentation">
        <div class="ContactsPage__Developer title">Developer</div>
        <router-link to="/"
          ><div class="ContactsPage__Getting tx">Getting started</div></router-link
        >
        <router-link to="/"
          ><div class="ContactsPage__Screencasts tx">Screencasts</div></router-link
        >
        <router-link to="/"><div class="ContactsPage__Blog tx">Blog</div></router-link>
        <router-link to="/"
          ><div class="ContactsPage__Documentation tx">Documentation</div></router-link
        >
        <router-link to="/"
          ><div class="ContactsPage__Report tx">Report a bug</div></router-link
        >
        <router-link to="/"
          ><div class="ContactsPage__Community tx">Community</div></router-link
        >
      </div>

      <div class="ContactsPage__Companies indentation">
        <div class="ContactsPage__Company title">Company</div>
        <router-link to="/"><div class="ContactsPage__About tx">About</div></router-link>
        <router-link to="/"
          ><div class="ContactsPage__Careers tx">Careers</div></router-link
        >
        <router-link to="/"
          ><div class="ContactsPage__Contact tx">Contact</div></router-link
        >
        <router-link to="/"
          ><div class="ContactsPage__Media tx">Media Kit</div></router-link
        >
      </div>

      <div class="ContactsPage__Legals indentation">
        <div class="ContactsPage__Legal title">Legal</div>
        <router-link to="/"
          ><div class="ContactsPage__Imprint tx">Imprint</div></router-link
        >
        <router-link to="/"
          ><div class="ContactsPage__Terms tx">Terms of Service</div></router-link
        >
        <router-link to="/"
          ><div class="ContactsPage__Privacy tx">Privacy Policy</div></router-link
        >
      </div>
    </div>

    <div class="ContactsPage__icons">
      <div class="ContactsPage__gitpods">
        <router-link to="/"
          ><div class="ContactsPage__gitpod">
            <img src="@/assets/ContactsPage/g.svg" alt="icon" /></div
        ></router-link>
        <div class="ContactsPage__inform">Copyright © 2124 Gitpod</div>
      </div>

      <div class="ContactsPage__icon">
        <router-link to="/"
          ><div class="ContactsPage__1">
            <img src="@/assets/ContactsPage/1.svg" alt="icon" /></div
        ></router-link>

        <router-link to="/"
          ><div class="ContactsPage__2">
            <img src="@/assets/ContactsPage/2.svg" alt="icon" /></div
        ></router-link>

        <router-link to="/"
          ><div class="ContactsPage__3">
            <img src="@/assets/ContactsPage/3.svg" alt="icon" /></div
        ></router-link>
      </div>
    </div>
  </div>
</template>
<script></script>
<style lang="scss" scoped>
@import "@/components/ContactsPage/ContactsPage.scss";
</style>
