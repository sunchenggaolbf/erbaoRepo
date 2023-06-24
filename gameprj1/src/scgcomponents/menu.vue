<template>
    <div class="menu">
        <div class="menuitem">item1</div>
        <div class="menuitem">item1</div>
        <div class="menuitem">item1</div>
    </div>
</template>
<script>
export default {
    name: 'scgMenu',
    data(){
        return {

        };
    },
    methods: {
        menuClick(){
          console.log("menuClick");
        },
    },
};
</script>
<style scoped>
.menu {
width:20%;
background-color:blue;
padding:1px;
margin:1px;

}
.menuitem {
    padding:10px;
    color:white;
    background-color: green;
    margin: 10px;
    cursor:pointer;
}
.menuitem:hover{
    background-color: yellow;
}
</style>