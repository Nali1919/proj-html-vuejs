<template>
<div>
<ImageMainComponent />
<SentenceComponent />
<PriceComponent />
</div>
</template>

<script>
import ImageMainComponent from "./ImageMainComponent.vue";
import SentenceComponent from "./SentenceComponent.vue";
import PriceComponent from "./PriceComponent.vue";
export default {
    name: 'MainComponent',
    components: {
    ImageMainComponent,
    SentenceComponent,
    PriceComponent
}

}
</script>

<style lang="scss" scoped>




</style>