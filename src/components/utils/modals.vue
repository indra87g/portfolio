<template>
  <div
    class="modal fade"
    id="AboutSiteModal"
    tabindex="-1"
    aria-labelledby="AboutSiteModal"
    aria-hidden="true"
  >
    <div class="modal-dialog modal-fullscreen">
      <div class="modal-content">
        <div class="modal-header">
          <h1 class="modal-title text-white fs-4" id="AboutSiteModal">Tentang Situs</h1>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
          ></button>
        </div>
        <div class="modal-body">
          <b>Website version: dev-0.1.0</b><br /><b>Built with:</b>
          <ul>
            <li>Node v21.x.x</li>
            <li>Bun v1.1.4</li>
            <li>Vue v3.4.21</li>
            <li>Bootstrap v5.2.3</li>
            <li>Vite v5.2.8</li>
          </ul>
          <h2>Bonus Meme!</h2>
          <img src="/meme.jpg" width="369" height="369" />
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        </div>
      </div>
    </div>
  </div>
  <div
    class="modal fade"
    id="StarterPackModal"
    tabindex="-1"
    aria-labelledby="StarterPackModal"
    aria-hidden="true"
  >
    <div class="modal-dialog modal-fullscreen">
      <div class="modal-content">
        <div class="modal-header">
          <h1 class="modal-title text-white fs-4" id="StarterPackModal">Starter Pack Ngoding</h1>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
          ></button>
        </div>
        <div class="modal-body">
          <h3>Hardware</h3>
          <h4>Laptop</h4>
          <ul>
            <li><b>ASUS E402Y</b></li>
            <li>OS: Windows 10 Home SingleLanguage</li>
            <li>Processor:</li>
            <li>RAM: 4GB</li>
            <li>HDD: 1TB</li>
            <li><a href="#">Beli</a></li>
          </ul>
          <h4>Smartphone</h4>
          <ul>
            <li><b>SAMSUNG A10</b></li>
            <li>OS: Android 11</li>
            <li>Processor:</li>
            <li>RAM: 3GB</li>
            <li>Penyimpanan: 32GB</li>
            <li><a href="#">Beli</a></li>
          </ul>
          <h3>Software</h3>
          <h4>ASUS E402Y</h4>
          <ul>
            <li>Windows Terminal + MSYS2</li>
            <li>VSCode</li>
            <li>Localpride</li>
            <li>Vagrant</li>
            <li>Virtualbox</li>
            <li><a href="#">Setup</a></li>
          </ul>
          <h4>SAMSUNG A10</h4>
          <ul>
            <li>Termux</li>
            <li>ACode</li>
            <li>LazyVim</li>
            <li>LAMPP</li>
            <li><a href="#">Setup</a></li>
          </ul>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        </div>
      </div>
    </div>
  </div>
  <div
    class="modal fade"
    id="FormModal"
    tabindex="-1"
    aria-labelledby="FormModal"
    aria-hidden="true"
  >
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h1 class="modal-title text-white fs-4" id="FormModal">Formspree</h1>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
          ></button>
        </div>
        <div class="modal-body">
          <h3>Pesan terkirim!</h3>
          <p class="lead text-white">
            Terima kasih telah mengisi form kontak. Saya akan segera membalas pesan anda!
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
