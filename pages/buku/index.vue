<template>
    <div class="container-fluid">
        <div class="row content">
            <div class="col-lg-12">
                <h2 class="text-center my-4 just" style="color: rgb(0, 0, 0);">RAK BUKU</h2>
                <div class="my-3 d-flex justify-content-center">
                    <input type="search" class="form-control rounded-5 cari" placeholder="SEARCH?..." style="background-color: #c9c9c9;">
                </div>
                <div class="my-3 text-muted"></div>
                <div class="row layer m-5 rounded-5">
                    <h1 class="text-center" style="color: rgb(255, 255, 255);">Koleksi Buku</h1>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="@/assets/img/images1.png" class="cover" alt="cover 1" style="width: 100%;">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="@/assets/img/images2.png" class="cover" alt="cover 2" style="width: 100%;">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="@/assets/img/download3.png" class="cover" alt="cover 3" style="width: 100%;">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="@/assets/img/download4.png" class="cover" alt="cover 3" style="width: 100%;">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <!-- <img src="~/assets/img/Y.jpg" class="cover" alt="cover 3" style="width: 100%;"> -->
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>

.content {
    background-color: 3894FF;
}

.cari{
    width: 40rem;
}
/* .cover{
    height: 50%;
    width: 50%;
} */
.layer {
    background-color: #d1d1d1;
}

h2{
    color: white;
    font-family: "Irish Grover", system-ui;
}

h1{
    color: white;
    font-family: "Irish Grover", system-ui;
}
</style>