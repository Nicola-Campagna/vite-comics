<script>
export default {


}
</script>

<template>
    <main>
        <div>--> Content goes here --> </div>
    </main>
</template>

<style lang="scss" scoped>
@use "../scss/mixin.scss" as *;

div {
    @include flex-center();
    background-color: #000;
    color: #fff;
    height: 100px;
}
</style>