<template>
    <div class="container hero-container d-flex flex-column justify-content-center">
        <div class="row">
            <div class="col-12 col-sm-6 col-lg-4 ">
                <h1 class="fw-lighter">Protoapp</h1>
                <p class="fw-lighter">Our landing page template works on all devices, so you onyl have to set it up
                    once, and get beautiful results forever</p>
                <button class="btn btn-primary">Get Started</button>
            </div>
        </div>
    </div>

    <div>
        <img src="/images/bg-leaves.svg" alt="" class="position-absolute bg-leaves" width="100%">
        <img src="/images/bg-decals.svg" alt="" class="position-absolute bg-decal" width="100%">
    </div>

    <hr class="divider mx-auto">
    <div class="container my-4">
        <div class="d-flex justify-content-center gap-4">
            <img src="/images/badge.play-store.svg" alt="google play store badge" width="100" class="img-fluid">
            <img src="/images/badge.app-store.svg" alt="apple play store badge" width="100" class="img-fluid">
        </div>
    </div>
    <hr class="divider mx-auto">

    <div class="container container-wrapper">
        <div class="row justify-content-center">
            <div class="col-12 col-sm-6 text-center">
                <h2 class="fw-bold">Meet Protoapp</h2>
                <p class="fw-light">The app lorem ipsum is common placeholder text used to demonstrate the graphic
                    elements of a document or visual presetation.</p>
            </div>
        </div>
        <div class="row g-2 justify-content-center my-5 py-5">
            <div class="col-12 col-md-4 order-2 order-md-1 row align-items-start">
                <div class="col-12">
                    <h4 class="fw-bold text-center text-md-end">Discover</h4>
                    <p class="text-center text-md-end">Get information on using these guidelines whenever you are using
                        therefore they have the same style and quality</p>
                </div>
            </div>
            <div class="col-12 col-md-4 order-1 order-md-2 text-center">
                <img src="/images/product-search.svg" alt="" class="img-fluid" width="80%">
            </div>
        </div>
        <div class="row g-2 justify-content-center my-5 py-5">
            <div class="col-12 col-md-4 text-center">
                <img src="/images/product-smartphone.svg" alt="" class="img-fluid" width="80%">
            </div>
            <div class="col-12 col-md-4 row align-items-start">
                <div class="col-12">
                    <h4 class="fw-bold text-center text-md-start">Augmented</h4>
                    <p class="text-center text-md-start">World salad often arouses curiosity due to its seemingly
                        intelligent and tasteful play on words</p>
                </div>
            </div>
        </div>
        <div class="row g-2 justify-content-center my-5 py-5">
            <div class="col-12 col-md-4 order-2 order-md-1 row align-items-start">
                <div class="col-12 text-center text-md-end">
                    <h4 class="fw-bold">Endless Possibilities</h4>
                    <p>Management Systems shouldn't be a bore. Run out of words? heres some lorem ipsum: Lorem ipsum
                        dolor sit amet</p>
                </div>
            </div>
            <div class="col-12 col-md-4 order-1 order-md-2 text-center">
                <img src="/images/product-work.svg " class="img-fluid" width="80%">
            </div>
        </div>
    </div>

    <div class="container-fluid bg-primary p-5 d-flex flex-column justify-content-center position-relative"
        style="height:500px">
        <div class="row justify-content-center">
            <div class="col-12 text-center text-light">
                <h2 class="fw-bold">Deep dive. Ready?</h2>
                <p class="fw-light">So are we. Unless. You're. Not. Word Filter.</p>
            </div>
        </div>
        <div class="d-flex justify-content-center gap-4 mt-5">
            <img src="/images/badge.play-store.svg" alt="google play store badge" width="100" class="img-fluid">
            <img src="/images/badge.app-store.svg" alt="apple play store badge" width="100" class="img-fluid">
        </div>
        <img src="/images/bg-decals2.svg" alt="" width="200px" class="bg-decal2">
    </div>

    <div class="container-fluid p-5 position-relative" style="min-height: 800px;">
        <h2 class="text-center fw-bold">Last Call to Action</h2>
        <p class="text-center">Another section content goes here</p>
        <div class="my-5 d-flex flex-column flex-sm-row justify-content-center gap-4 text-light">
            <div class="card-wrapper rounded bg-yellow p-4 d-flex flex-column flex-sm-row">
                <div class="col-12 col-sm-5 d-flex flex-column align-items-center pe-sm-5">
                    <img src="/images/badge.laravel-mix.svg" class="img-fluid">
                    <p class="pill-badge text-center fw-bold mt-4">AUTOMATION</p>
                </div>
                <div class="col-12 col-sm-7 text-center text-sm-start">
                    <p>ROLL OUT</p>
                    <h3 class="fw-bold">Automatic Prototyping</h3>
                    <p>Webpack is the most powerful and flexible asset compilation tool available today. With that
                        power, however, comes a certain level of complexity</p>
                </div>
            </div>
            <div class="card-wrapper rounded bg-cyan p-4 d-flex flex-column flex-sm-row">
                <div class="col-12 col-sm-5 d-flex flex-column align-items-center pe-sm-5">
                    <img src="/images/badge.how-to-read-code.svg" class="img-fluid">
                    <p class="pill-badge text-center fw-bold mt-4">SIMPLICITY</p>
                </div>
                <div class="col-12 col-sm-7 text-center text-sm-start">
                    <p>SIP COFFEE</p>
                    <h3 class="fw-bold">Complexity Simplified</h3>
                    <p>I know too many backend developers who are stifled by one glaring phobia: CSS. How do you
                        construct a layout when nothing lines up?</p>
                </div>
            </div>
        </div>
        <img src="/images/bg-decals3.svg" alt="" class="bg-decal3">
    </div>
</template>


<script>
export default {
    name: 'bodyComponent',
}

</script>