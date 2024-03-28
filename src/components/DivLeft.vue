<script lang="ts">
import Contacts from './Contacts.vue';

export default {
  components: { Contacts }
};
</script>

<template>
  <main class="body">
    <div class="logo">
      <img src="@/assets/logo.svg" alt="Logo da compass UOL" class="img">
    </div>
    <div class="text">
      Let's discuss <br> on something <br>
      <span class="word">
        COOL
      </span>
      together
    </div>
    <div class="contact">
      <Contacts />
    </div>
  </main>
</template>

<style scoped>
.logo {
  padding-bottom: 60px;
}

.img {
  width: 25rem;
  height: auto;
}

.body {
  float: left;
  padding-right: 7rem;
}

.text {
  color: #FFFFFF;
  font-size: 56px;
  font-weight: 700;
  font-family: "Inter", sans-serif;
  line-height: 5rem;
}

.word {
  color: #FFCE00;
  font-size: 56px;
  font-weight: 700;
  font-family: "Inter", sans-serif;
  line-height: 60px;
  font-weight: bold;
}
</style>
