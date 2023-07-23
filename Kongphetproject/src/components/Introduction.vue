<template>
    <div>
        <!-- Section1 -->
        <div class="Background1 position-relative">
            <!-- Navigation bar -->
            <div class="row">
                <div class="col-md-5 col-sm-12">
                    <div class="d-flex">
                        <div>
                            <span class="material-symbols-outlined text-warning">
                                account_box
                            </span>
                        </div>
                        <div class="text-warning">
                            KONGPHET
                        </div>
                    </div>
                </div>
                <div class="col-md-7 col-sm-12 row">
                    <div class="col-md-4 col-sm-12 row">
                        <div class="col text-warning">Home</div>
                        <div class="col">About</div>
                        <div class="col">Contact</div>
                    </div>
                    <div class="col-md-8 col-sm-12 d-flex justify-content-end">
                        <button type="button" class="btn btn-outline-light">Contact Me</button>
                    </div>
                </div>
            </div>
            <!-- Introduction -->
            <div class="row h-100 d-flex align-items-center">
                <div class="col-6">
                    <div style="font-size: 2rem; color: #575757;">Hello, i'm Bebie</div>
                    <div style="font-size: 2rem;color: #000000;">UI & UX </div>
                    <div style="font-size: 2rem;color: #FFBA2E;">Designer</div>
                    <div style="font-size: 2rem;color: #000000;">Member CEIT Robot</div>
                    <button type="button" class="btn btn-warning text-white">HIRE ME</button>
                </div>
                <div class="col-5">
                    <img class="img-fluid" src="/images/phanda.png" style="margin-top: 180px;">
                </div>
            </div>
        </div>
        <!-- Section2 -->
        <div class="Background2 position-relative">
            <!-- About me -->
            <div class="container text-center">
                <div style="font-size: 2rem;" class="col-12 text-white">
                    ABOUT ME
                    <div>
                        <span class="material-symbols-outlined text-warning">
                            cruelty_free
                        </span>
                    </div>
                    <div style="font-size: 1rem;">Hello I am Bebie vkvd jbvkjdbk jdkbvdkbv znkbvbvbbv</div>
                    <div style="font-size: 1rem;">Hello I am Bebie vkvd jbvkjdbk jdkbvdkbv znkbvbvbbv bjdbg hfbjh hjfj fhj
                    </div>
                </div>
            </div>
            <!-- Skills -->
            <div class="col-6">
                <img src="/images/Skills.png" style="margin-top: 450px;">
            </div>
        </div>
    </div>
</template>

<style scoped>
.Background1 {
    background-image: url("/images/Background1.png");
    background-size: 100%;
    height: 100vh;
    padding-left: 3rem;
    padding-right: 3rem;
    padding-top: 2rem;
}

.Background2 {
    background-image: url("/images/Background2.png");
}

.navigate-btn {
    padding-left: 1.5rem;
    padding-right: 1.5rem;
}

.panda {
    height: 400px;
    width: 400px;
}

.hire-btn {
    background-color: #FFBA2E;

}
</style>