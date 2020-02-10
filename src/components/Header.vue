<template>
  <header class="header" id="header">
    <kinesis-container>
      <kinesis-element class="header_fon" type="depth_inv" :strength="10" />
      <nav class="menu">
        <a class="link" href="#">About</a>
        <a class="link" href="#">Work</a>
        <a class="link" href="#">Contact</a>
      </nav>
    </kinesis-container>
  </header>
</template>

<script>
import { KinesisContainer, KinesisElement } from "vue-kinesis";

export default {
  components: {
    KinesisContainer,
    KinesisElement
  }
};
</script>