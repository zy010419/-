<template>
    <NavBar />
    <router-view></router-view>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import "bootstrap/dist/css/bootstrap.min.css";
import "bootstrap/dist/js/bootstrap";
//import $ from "jquery";

export default {
    components: {
        NavBar
    },
    setup() {
        // $.ajax({
        //     url: "http://localhost:3000/user/account/register/",
        //     type: "post",
        //     data: {
        //         username: "zhaoyu1",
        //         password: "123",
        //         confirmedPassword: "123"
        //     },
        //     success(resp) {
        //         console.log(resp);
        //     },
        //     error(resp) {
        //         console.log(resp);
        //     }
        // });
    }
};
</script>

<style>
body {
    background-image: url("@/assets/images/background.jpg");
    background-size: cover;
    background-attachment: fixed; /* 不设置的话页面滑动时，背景会不铺满*/
}
</style>
