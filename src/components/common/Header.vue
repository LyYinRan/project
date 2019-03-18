<template>
    <div>
        <mt-header class="op" title="固定在顶部"></mt-header>

        <app-swipers></app-swipers>
        <app-infobtn></app-infobtn>
    </div>
</template>
<script>
import Swipers from '.././common/Swipers'
import Infobtn from '.././common/Infobtn'
export default {
    components : {
        appSwipers : Swipers,
        appInfobtn : Infobtn
    }
}
</script>


<style>
     body {
         margin: 0;
         padding: 0;
     }
</style>


