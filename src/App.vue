<template>
  <v-app>
    <v-content>
      <header-menu />
      <router-view />
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: 'App'
  // data () {
  //   return {
  //     データの置き場所
  //   }
  // },
  // props: {
  //   データの受け取り
  // },
  // computed: {
  //   データの算出
  // },
  // methods: {
  //   メソッドの組み込み
  // },
  // created: function() {
  //   インスタンスが作成された後に同期的に呼ばれるフック
  // },
  // mounted: function() {
  //   インスタンスがマウントされたちょうど後に呼ばれるフック
  // }
};
</script>
