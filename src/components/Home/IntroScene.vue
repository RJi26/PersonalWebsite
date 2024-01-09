<template>
  <section class="scene-intro" id="intro">
    <div class="static-container">
      <h1 class="title">
        <span class="iuri">richard</span>
        <span class="func">.is()</span>
      </h1>

      <TextBlock>
        <p class="-purple">Richard Ji</p>
        <p class="-gray typing">
          <vue-typed-js :strings="['AI Researcher and Engineer', 'International Baccalaureate Student']" :typeSpeed="100" :backSpeed="20" :loop="true">
            <p class="typing"></p>
          </vue-typed-js>
        </p>
      </TextBlock>
    </div>
  </section>
</template>

<script>
import TextBlock from '../TextBlock.vue'
import Vue from 'vue'
import VueTypedJs from 'vue-typed-js'
Vue.use(VueTypedJs)

export default {
  name: 'IntroScene',
  components: { TextBlock },
}
</script>
