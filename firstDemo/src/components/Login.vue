
<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <table class="test">
      <tr>
        <td>用户名:</td>
        <td><input  :placeholder="nameTip" /></td>
      </tr>
      <tr>
        <td>密码:</td>
        <td><input  :placeholder="pwdTip" /></td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  data () {
    return {
      // note: changing this line won't causes changes
      // with hot-reload because the reloaded component
      // preserves its current state and we are modifying
      // its initial state.
      msg: '用户登录!'
    }
  }
}
</script>


