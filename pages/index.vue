<template>
  <div class ="container">
    <img src="../img/logo.png" alt="ロゴ">
    <NuxtLink to ="/">新規登録</NuxtLink>
    <NuxtLink to ="/login">ログイン</NuxtLink>
    <div class ="card">
      <p>新規登録</p>
      <input type="text" placeholder="ユーザーネーム">
      <input type="email" placeholder="メールアドレス">
      <input type="password" placeholder="パスワード">
      <button type="submit">新規登録</button>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container{
  background: rgb(10, 10, 78);
}
</style>
