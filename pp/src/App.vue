<script setup lang="ts">
import {
  faTelegram,
  faGithub,
  faStackOverflow,
} from "@fortawesome/free-brands-svg-icons";
import { library } from "@fortawesome/fontawesome-svg-core";
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";

library.add(faTelegram, faGithub, faStackOverflow);
</script>

<template>
  <div class="block">
    <div class="text">Contacts:</div>
    <p>
      <a href="https://telegram.me/n1creator" target="_blank" rel="noopener">
        <FontAwesomeIcon :icon="['fab', 'telegram']" class="icon-link" />
      </a>
      <a
        href="https://stackoverflow.com/users/11086065/n1creator"
        target="_blank"
        rel="noopener"
      >
        <FontAwesomeIcon :icon="['fab', 'stack-overflow']" class="icon-link" />
      </a>
      <a href="https://github.com/an1creator" target="_blank" rel="noopener">
        <FontAwesomeIcon :icon="['fab', 'github']" class="icon-link" />
      </a>
    </p>
  </div>
</template>

<style scoped>
.block {
  margin: 8px;
  padding: 150px;
}
.text {
  font-size: 20px;
  font-weight: 500;
  margin: 20px 0;
}
.icon-link {
  color: black;
  height: 32px;
  width: 32px;
}
</style>
