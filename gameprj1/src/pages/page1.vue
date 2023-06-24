<template>
    <div id="page1" class="page">
        <Menu />
        <div class="content">
            <Header />
            <Body1 />
            <Footer />
        </div>
    </div>
</template>
<script>
import Menu from '../scgcomponents/menu.vue';
import Header from '../scgcomponents/header.vue';
import Body1 from '../scgcomponents/body1.vue';
import Footer from '../scgcomponents/footer.vue';

export default {
    name: 'scgPage1',
    components: {
        Menu, Body1, Header, Footer,
    },
}
</script>
<style scoped>
.page {
height:100vh;
width:100vw;
display:flex; 
}
.content{
    display:flex;
    flex-direction: column;
    height:100%;
    width:100%;

}

</style>