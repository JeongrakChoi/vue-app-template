<template>
    <div>
        <div>
            <h1>메인 페이지</h1>
            <Example/>
        </div>
        <br/>
        <router-link to="/Login">로그인 화면으로</router-link>
    </div>
</template>

<script>
    import Example from '@/components/Example.vue';

    export default {
        name: '메인페이지 입니다',
        props: {
            msg: String
        },
        components: {
            Example
        }
    }
</script>

<style scoped>
    div{
        background:#dcdcdc
    }
</style>
  