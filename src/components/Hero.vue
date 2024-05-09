<template>
  <div class="container col-xxl-8 px-4">
    <div class="row flex-lg-row-reverse align-items-center g-5">
      <div class="col-10 col-sm-8 col-lg-6">
        <img
          src="/profile.jpg"
          class="d-block mx-lg-auto img-fluid rounded-circle"
          alt="Bootstrap Themes"
          width="700"
          height="500"
          loading="lazy"
        />
      </div>
      <div class="col-lg-6">
        <h1 class="display-5 fw-bold text-body-emphasis lh-1 mb-3">Hai👋</h1>
        <b>Saya seorang Full-Stack Developer Pemula</b><br />
        <code>print(nama)</code>
        <p class="lead text-white">Indra Sah Noeldy Girsang</p>
        <code>echo $tanggal_Lahir</code>
        <p class="lead text-white">07 Mei 2009</p>
        <code>console.log(hobi);</code>
        <p class="lead text-white">Programming, Gaming</p>
        <div class="d-grid gap-2 d-md-flex justify-content-md-start">
          <button type="button" href="#bd-theme" class="btn btn-primary btn-lg px-4 me-md-2">
            Download CV
          </button>
          <button
            type="button"
            class="btn btn-primary btn-lg px-4 me-md-2"
            data-bs-toggle="modal"
            data-bs-target="#AboutSiteModal"
          >
            Tentang Situs
          </button>
          <button
            type="button"
            class="btn btn-primary btn-lg px-4 me-md-2"
            data-bs-toggle="modal"
            data-bs-target="#StarterPackModal"
          >
            Starter Pack Ngoding
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
