<template>
  <div class="container py-4">
    <h2>Kontak</h2>
    <form
      id="fs-frm"
      name="complaint-form"
      accept-charset="utf-8"
      action="https://formspree.io/f/mrgnkpzy"
      method="post"
    >
      <fieldset id="fs-frm-inputs">
        <div class="form-floating mb-3">
          <b>Nama</b>
          <input
            type="text"
            name="name"
            id="full-name"
            placeholder="John Doe"
            class="form-control"
            required="true"
            data-twofas-input-listener="true"
            data-twofas-element-number="0"
          />
        </div>
        <div class="form-floating mb-3">
          <b>Email</b>
          <input
            type="email"
            name="_replyto"
            id="email-address"
            class="form-control"
            placeholder="email@domain.com"
            required="true"
          />
        </div>
        <div class="form-floating mb-3">
          <b>Nomor Telepon (Opsional)</b>
          <input
            type="telephone"
            name="telephone"
            id="telephone"
            class="form-control"
            placeholder="+62 123 4567 8910"
          />
        </div>
        <div class="form-floating mb-3">
          <b>Pesan</b>
          <textarea
            rows="6"
            name="complaint"
            id="complaint"
            class="form-control"
            placeholder="Aenean lacinia bibendum nulla sed consectetur. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Donec ullamcorper nulla non metus auctor fringilla nullam quis risus."
            required="true"
            data-twofas-input-listener="true"
            data-twofas-element-number="1"
          ></textarea>
        </div>
        <input
          type="hidden"
          name="_subject"
          id="email-subject"
          class="form-control"
          value="Pesan untuk Indra Sah Noeldy"
        />
      </fieldset>
      <input
        type="submit"
        value="Kirim"
        data-twofas-element-number="2"
        class="btn btn-primary bg-gradient"
        data-bs-toggle="modal"
        data-bs-target="#FormModal"
      /><br />
    </form>
  </div>
</template>
