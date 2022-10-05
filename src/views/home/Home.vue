<template>
    <div>
        <div>
            <h1>메인 페이지</h1>
            <p>{msg}</p>
        </div>
        <br/>
        <router-link to="/Login">로그인 화면으로</router-link>
    </div>
</template>

<script>
    export default {
        name: '메인페이지 입니다',
        props: {
            msg: String
        }
    }
</script>

<style scoped>

</style>
  