<template>
    <div>
        <mt-header class="op" title="固定在顶部"></mt-header>

        <app-swipers></app-swipers>
    </div>
</template>
<script>
import Swipers from '.././common/Swipers'
import Infobtn from ''
export default {
    components : {
        appSwipers : Swipers
    }
}
</script>


<style>
     body {
         margin: 0;
         padding: 0;
     }
</style>


