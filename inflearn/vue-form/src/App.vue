<template>
  <form action="">
    <div>
      <label for="username">id: </label>
      <input id="username" type="text" />
    </div>
    <div>
      <label for="password">pw: </label>
      <input id="password" type="password" />
    </div>
    <button>login</button>
  </form>
</template>

<script>
export default {
  // 컴포넌트 단위로 개발할 때는 값의 참조가 일어나지 않게 function 단위로 data return
  data: function () {
    return {};
  },
};
</script>

<style></style>
