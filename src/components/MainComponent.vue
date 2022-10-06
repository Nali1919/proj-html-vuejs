<template>
<div>
<ImageMainComponent />
<SentenceComponent />
</div>
</template>

<script>
import ImageMainComponent from "./ImageMainComponent.vue";
import SentenceComponent from "./SentenceComponent.vue";
export default {
    name: 'MainComponent',
    components: {
    ImageMainComponent,
    SentenceComponent
}

}
</script>

<style lang="scss" scoped>




</style>