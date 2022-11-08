<template>
  <section>
    <div class="container">
      <div class="content">
        <div class="card">
          <div class="card-content">
            <div class="image">
              <img
                class="img-game"
                src="https://cdn.cloudflare.steamstatic.com/steam/apps/1172470/capsule_616x353.jpg?t=1664321959"
              />
            </div>

            <div class="media-icons gap-5">
              <i><remix-icon icon="world" :size="20"></remix-icon></i>
              <i><remix-icon icon="user" :size="20"></remix-icon></i>
              <i><remix-icon icon="lupa" :size="20"></remix-icon></i>
            </div>

            <div class="name-profession">
              <span class="name">Someone Name</span>
              <span class="profession">Web Developer</span>
            </div>


            
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts" setup>
import RemixIcon from "./RemixIcon.vue";
</script>
