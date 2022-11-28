<template>
    <div class="px-5 py-5 bg-light">
        <h3><b>Complete Your Room</b></h3>
        <h3><b>With What We Designed</b></h3>
        <div class="d-flex flex-row justify-content-between py-5">
            <Card v-for="(item, i) in arrCardTitle"
            :key="i" :cardTitle="item"
            :cardPrice="arrCardPrice[i]"
            :cardImage="arrCardImage[i]"></Card>
        </div>
    </div>
</template>

<script>
import Card from "./Card.vue"
export default {
    name : "SliderComponent",
    components : {
        Card
    },
    data : function() {
        return {
            arrCardTitle : ["Cangkir Mauttie", "Saman Kakka", "Lino Dino", "Syail Ammeno"],
            arrCardPrice : ["89.300.000", "14.500.000", "22.000.000", "12.000.000"],
            arrCardImage : ["chair-4", "chair-3", "chair-2", "chair-1"]
        }
    }
}
</script>

<style>

</style>