<template>
<div>
<ImageMainComponent />
<SentenceComponent />
<PriceComponent />
<BoysImageComponent />
<StaffComponent />
</div>
</template>

<script>
import ImageMainComponent from "./ImageMainComponent.vue";
import SentenceComponent from "./SentenceComponent.vue";
import PriceComponent from "./PriceComponent.vue";
import BoysImageComponent from "./BoysImageComponent.vue";
import StaffComponent from "./StaffComponent.vue";


export default {
    name: 'MainComponent',
    components: {
    ImageMainComponent,
    SentenceComponent,
    PriceComponent,
    BoysImageComponent,
    StaffComponent
}

}
</script>

<style lang="scss" scoped>




</style>