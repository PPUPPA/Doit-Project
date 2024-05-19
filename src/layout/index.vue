<template>
    <section id="wrap">
        <h1 class="blind">이지스 퍼블리싱</h1>
        <Header />
        <section id="container">
            <!-- 각 메뉴에 따라 변경할 컴포넌트 영역 라우터 태그 -->
            <router-view />
        </section>
        <Footer />
    </section>
</template>
<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
export default{
    components: {
        Header,
        Footer,
    },
}
</script>