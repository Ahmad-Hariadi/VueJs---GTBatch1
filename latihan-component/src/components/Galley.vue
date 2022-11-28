<template>
  <div class="container-fluid d-flex mt-4 justify-content-between">
        <!-- Left -->
        <div class="col-1" style="width: 10vw; height: 80vh;">
            <div class="d-flex flex-column align-items-end mt-5">
                <div class="p-1 py-3">
                    <img src="./../assets/img/side-1.png" class="rounded" alt="" style="width: 5vw;">
                </div>
                <div class="p-1 py-3">
                    <img src="./../assets/img/side-2.png" class="rounded" alt="" style="width: 5vw;">
                </div>
                <div class="p-1 py-3">
                    <img src="./../assets/img/side-3.png" class="rounded" alt="" style="width: 5vw;">
                </div>
                <div class="p-1 py-3">
                    <img src="./../assets/img/side-1.png" class="rounded" alt="" style="width: 5vw;">
                </div>
                <div class="p-1 py-3">
                    <img src="./../assets/img/side-2.png" class="rounded border border-dark" alt="" style="width: 5vw;">
                </div>
            </div>
        </div>

        <!-- Center -->
        <div class="col-5" style="width: 10vw; height: 90vh;">
            <div class="d-flex flex-column mt-2">
                <div class="p-0 pr-4">
                    <img src="./../assets/img/chair.png" class="rounded" alt="chair">
                </div>
            </div>
        </div>

        <!-- right -->
        <div class="col-5" style="width: 10vw; height: 90vh;">
            <h1>Chair Tatty</h1>
            <p>IDR 12.000.000</p>
            <button style="background-color: #fcb8dd; border: none; border-radius:15px; width: 10vw;" type="submit">
                <img src="./../assets/img/cart-icon.png"> <b>Add to chart</b>
            </button>
            <hr>
            <p><b>About the product:</b></p>
            <p>
                Tailored to a level of perfection synonymous with that of a Savile Row suit and with understated quality in the detail, Jetty has been influenced by timeless 1950s style.
            </p>
            <p>
                Providing a subtle nod to the past, Jetty also provides a perfect solution for the way we work today. A comprehensive product family, Jetty features a variety of elegant chairs and sofas.
            </p> 
        </div>
    </div>
</template>

<script>
export default {
    name : "GalleyComponent"
}
</script>

<style>

</style>