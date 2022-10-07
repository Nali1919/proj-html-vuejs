<template>
<div>
<ImageMainComponent />
<SentenceComponent />
<PriceComponent />
<BoysImageComponent />
<StaffComponent />
<SponsorComponent/>
<PizzeMenuComponent />
</div>
</template>

<script>
import ImageMainComponent from "./ImageMainComponent.vue";
import SentenceComponent from "./SentenceComponent.vue";
import PriceComponent from "./PriceComponent.vue";
import BoysImageComponent from "./BoysImageComponent.vue";
import StaffComponent from "./StaffComponent.vue";
import SponsorComponent from "./SponsorComponent.vue";
import PizzeMenuComponent from "./PizzeMenuComponent.vue";




export default {
    name: 'MainComponent',
    components: {
    ImageMainComponent,
    SentenceComponent,
    PriceComponent,
    BoysImageComponent,
    StaffComponent,
    SponsorComponent,
    PizzeMenuComponent
}

}
</script>

<style lang="scss" scoped>




</style>