<template>
    <div class="content">
      <div class="container-fluid">
        <div class="row">
          <div class="col-lg-12">
            <h2 class="text-center my-4 text-dark">RIWAYAT KUNJUNGAN</h2>
            <div class="my-3">
            </div>
            <div class="my-3 text-muted">menampilkan 1 dari </div>
            <table class="table table-bordered border-dark text-black ">
              <thead>
                <tr>
                  <td>#</td>
                  <td>NAMA</td>
                  <td>KATEGORI</td>
                  <td>WAKTU</td>
                  <td>KEPERLUAN</td>
                </tr>
              </thead>
              <tbody>+
                <tr>
                  <td>1.</td>
                  <td>zeeen</td>
                  <td>Siswa</td>
                  <td>24 Februari 2024, 23.31.00</td>
                  <td>Baca</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
      <!-- <button type="submit" class="btn btn-dark btn-lg rounded-5 px-5">Mencari Buku</button> -->
      <nuxt-link to="/buku" class="btn btn-dark btn-lg rounded-5 px-5 mx-2">Mencari Buku</nuxt-link>
    
      <!-- <button type="submit" class="btn btn-dark btn-lg rounded-5 px-5">Selesai</button> -->
      <nuxt-link to="/" class="btn btn-dark btn-lg rounded-5 px-5">Selesai</nuxt-link>
     
    </div>
</template>