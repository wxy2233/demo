<template>
  <div>
    <van-button type="info">信息按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
  </div>
</template>

<script>
import { Button } from "vant";

export default {
  name: "vantTest",
  components: {
    [Button.name]: Button
  }
};
</script>
