<template>
  <div class="ds-work-section">
    <div class="container">
        <div class="gambar">
        <RouterLink to="/"><img src="@/assets/images/back(1).png" alt=""></RouterLink>
      <h2 class="ds-heading ms-3">Latest works</h2>
        </div>
      <div class="ds-work-list-section">
        <div class="ds-work-list">
          <div class="row">
            <div class="col-12 col-sm-12 col-md-7 col-lg-7 col-xl-7 col-xxl-7">
              <section>
                <h3 class="ds-work-tilte">Aplikasi Peminjaman Barang Sarpras</h3>
                <p>Aplikasi peminjaman dan pengembalian barang untuk Sarana Prasarana SMK Taruna Bhakti menggunakan Laravel dipadukan dengan template Stisla Admin </p>
              </section>
            </div>
            <div class="col-12 col-sm-12 col-md-5 col-lg-5 col-xl-5 col-xxl-5">
              <figure><img src="@/assets/images/dasbor-sarpras.png"></figure>
            </div>
          </div>
        </div>
        <div class="ds-work-list">
          <div class="row">
            <div class="col-12 col-sm-12 col-md-7 col-lg-7 col-xl-7 col-xxl-7">
              <section>
                <h3 class="ds-work-tilte">Technology Landing Page</h3>
                <p>Bootstrap Landing Page  dengan beberapa CSS tambahan.</p>
              </section>
            </div>
            <div class="col-12 col-sm-12 col-md-5 col-lg-5 col-xl-5 col-xxl-5">
              <figure><img src="@/assets/images/tech.png"></figure>
            </div>
          </div>
        </div>
        <div class="ds-work-list">
          <div class="row">
            <div class="col-12 col-sm-12 col-md-7 col-lg-7 col-xl-7 col-xxl-7">
              <section>
                <h3 class="ds-work-tilte">Landing Page CSS</h3>
                <p>Landing Pages CSS Native dengan berbagai macam tema.</p>
              </section>
            </div>
            <div class="col-12 col-sm-12 col-md-5 col-lg-5 col-xl-5 col-xxl-5">
              <figure><img src="@/assets/images/vespa.png"></figure>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.gambar img{
    width: 30px;
    height: 30px;
}
figure img{
  border: 5px solid #576F72;
  border-radius: 15px;
}
</style>