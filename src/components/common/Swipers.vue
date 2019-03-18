<template lang="html">
    <div>
        <mt-swipe :auto="4000" class="s">
            <mt-swipe-item v-for="item in 5">{{item}}</mt-swipe-item>
        </mt-swipe>
    </div>
</template>

}

<script>
export default {
    creat () {
        this.$axios.get()
    }
}
</script>

<style>
.s{
    height: 200px;
    background: red

}
</style>


