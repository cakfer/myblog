<script>
	export let name;
</script>

<header role="banner" class="ui-section-header">
      <div class="ui-layout-container">
        <div class="ui-section-header__layout ui-layout-flex">
          <!-- LOGO -->
          <a href="." role="link" aria-label="#">
            <img src="img/logo.svg" alt="Logo" style="width:18px;height:18px;">
          </a>
          <!-- MENU -->
          <a href="https://github.com/cakfer" role="link" aria-label="#">
            <img src="img/github.svg" alt="Github" style="width:18px;height:18px;">
          </a>
        </div>
      </div>
    </header>
    <main role="main">
      <section class="ui-section-hero">
        <div class="ui-layout-container">
          <!-- COPYWRITING -->
          <div class="ui-layout-column-6 ui-layout-column-center">
            <h1>Hello {name}.</h1>
            <p class="ui-text-intro">Selamat datang di blog saya. Silakan, lihat sekeliling dan periksa apakah ini yang Anda cari.</p>
            <!-- CTA -->
            <div class="ui-component-cta ui-layout-flex">
              <form action="." class="ui-component-form ui-layout-grid ui-layout-column-4">
                <input type="email" placeholder="Email" class="ui-component-input ui-component-input-medium" required>
                <button type="submit" class="ui-component-button ui-component-button-medium ui-component-button-primary">Join Waitlist</button>
              </form>
              <p class="ui-text-note"><small>Tersedia di Mac, Windows, dan Linux.</small></p>
            </div>
          </div>
        </div>
      </section>
      <section class="ui-section-content">
        <div class="ui-layout-container">
          <div class="ui-section-content__layout ui-layout-grid ui-layout-grid-2">
            <a href="https://kela.pages.dev/">
            <div class="ui-component-card ui-layout-column-4">
              <img src="img/preview.png" alt="Demo Twibbon" loading="lazy" class="ui-component-card--image">
              <h4 class="ui-component-card--title">Twibbon Generator.</h4>
              <p>Twibbon generator untuk membuat gambar kampanye media sosial.</p>
            </div>
            </a>
            <a href="https://kela.pages.dev/qr-code">
            <div class="ui-component-card ui-layout-column-4">
              <img src="img/qr-code.png" alt="QR Code" loading="lazy" class="ui-component-card--image">
              <h4 class="ui-component-card--title">QR Code Generator.</h4>
              <p>Ketik teks atau url untuk membuat kode QR.</p>
            </div>
            </a>
            <a href="https://kela.pages.dev/love-calculator">
            <div class="ui-component-card ui-layout-column-4">
              <img src="img/love.png" alt="#" loading="lazy" class="ui-component-card--image">
              <h4 class="ui-component-card--title">Hitung Cintamu.</h4>
              <p>Inilah Kalkulator Cinta yang memungkinkan Anda menghitung kecocokan cinta dan peluang Anda untuk hubungan yang sukses.</p>
            </div>
            </a>
          </div>
        </div>
      </section>
      <section class="ui-section-close">
        <div class="ui-layout-container">
          <div class="ui-layout-column-6 ui-layout-column-center">
            <h2>Ada pertanyaan? Saya punya jawaban.</h2>
            <p class="ui-text-intro">Ingin menghubungi? Isi formulir di bawah ini untuk mengirimi saya pesan dan saya akan segera menghubungi Anda kembali!</p>
            <!-- CTA -->
            <div class="ui-component-cta ui-layout-flex">
              <form action="." class="ui-component-form ui-layout-grid ui-layout-column-4">
                <input type="email" placeholder="Email" class="ui-component-input ui-component-input-medium" required>
                <button type="submit" class="ui-component-button ui-component-button-medium ui-component-button-primary">Join Waitlist</button>
              </form>
              <p class="ui-text-note"><small>Tersedia di Mac, Windows, dan Linux.</small></p>
            </div>
          </div>
        </div>
      </section>
    </main>
    <footer role="contentinfo" class="ui-section-footer">
      <div class="ui-layout-container">
        <div class="ui-section-footer__layout ui-layout-flex">
          <!-- COPYRIGHT -->
          <p class="ui-section-footer--copyright ui-text-note"><small>&copy; Ferry Ayunda</small></p>
          <!-- MENU -->
          <a href="https://saweria.co/bungferry" role="link" aria-label="#" class="ui-text-note"><small>Features</small></a>
          <a href="https://www.facebook.com/bungferry.wa" role="link" aria-label="#" class="ui-text-note"><small>Help</small></a>
          <a href="https://www.facebook.com/profile.php?id=100059526018762" role="link" aria-label="#" class="ui-text-note"><small>Terms</small></a>
        </div>
      </div>
    </footer>
