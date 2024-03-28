<script lang="ts">
import Form from './Form.vue';

export default {
  components: { Form },
}
</script>

<template>
  <main class="body">
    <div class="tags">
      <div class="interested">
        <h1 class="header_text">
          I'm interested in...
        </h1>
      </div>
    </div>
    <div class="back">
      <Form />
    </div>
  </main>
</template>

<style scoped>
.header_text {
  font-size: 25px;
  font-weight: 1000;
  line-height: 30px;
  padding-top: 2rem;
  margin-top: 2rem;
}

.interested {
  width: 300px;
  height: 55px;
  gap: 24px;
}

.tag {
  width: 92px;
  height: 34px;
  border-radius: 8px;
  padding: 8px 20px 8px 20px;
  gap: 5px;
}

.tags {
  width: 18.75rem;
  height: 3.125rem;
  gap: .75rem;
  margin-top: -2rem;
}

.body {
  width: 600px;
  height: 650px;
  margin-top: -3rem;
  border-radius: 32px 0px 32px 2px;
  float: right;
  background-color: #FFCE00;
  padding: 2rem 2rem 2rem 2rem;
}

.button {
  width: 100px;
  color: #FFFFFF;
  border-radius: 16px;
  background-color: black;
  padding: 24px 64px 24px 64px;
  width: 572px;
  height: 78px;
  cursor: pointer;
}

</style>
