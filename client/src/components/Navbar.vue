<template>
  <nav class="navbar navbar-expand-lg navbar-dark menu shadow fixed-top">
    <div class="container">
      <a class="navbar-brand" href="">
        <img src="/src/assets/images/logo-karantina-putih.png" alt="logo image" width="50">
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">

        <ul class="navbar-nav">

          <!-- Home -->

          <li class="nav-item">
            <RouterLink to="/" class="nav-link active" aria-current="page">Home</RouterLink>
          </li>

          <!-- Tentang Kami -->

          <li class="nav-item dropdown">
            <RouterLink to="#" class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">Tentang Kami</RouterLink>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
              <li>
                <a class="dropdown-item text-dark" href="#">Profil</a>
              </li>
              <li>
                <a class="dropdown-item text-dark" href="#">Visi & Misi action</a>
              </li>
              <li>
                <a class="dropdown-item text-dark" href="#">Struktur Organisasi</a>
              </li>
              <li>
                <a class="dropdown-item text-dark" href="#">Tugas Pokok & Fungsi</a>
              </li>
              <li>
                <a class="dropdown-item text-dark" href="#">Profil Pomponan</a>
              </li>
              <li>
                <a class="dropdown-item text-dark" href="#">Wilayah Layanan</a>
              </li>
            </ul>
          </li>

          <!-- Informasi Publik -->

          <li class="nav-item dropdown" id="myDropdown">
            <RouterLink to="#" class="nav-link dropdown-toggle" href="#" data-bs-toggle="dropdown" aria-expanded="false">Informasi Publik</RouterLink>
            <ul class="dropdown-menu">

              <!-- PPID -->

              <li>
                <a class="dropdown-item" href="#"> PPID &raquo; </a>
                <ul class="submenu dropdown-menu">
                  <li>
                    <a class="dropdown-item" href="#">Portal PPID</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Hak Atas Informasi</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Prosedur Permohonan</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Tim PPID</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Informasi Berkala</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Informasi Setiap Saat</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Informasi Serta Merta</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Regulasi</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Evakuasi & Peringatan Dini</a>
                  </li>
                </ul>
              </li>

              <!-- SPP -->
               <li>
                <a class="dropdown-item" href="#"> Standar Pelayanan Publik &raquo; </a>
                <ul class="submenu dropdown-menu">
                  <li>
                    <a class="dropdown-item" href="#">Dasar Hukum</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Maklumat Pelayanan</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Standar Waktu Pelayanan</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Jam Layanan</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Prosedr Pelayanan</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Alur Pelayanan</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Informasi & pengaduan</a>
                  </li>
                </ul>
              </li>

               <!-- Kinerja -->
               <li>
                <a class="dropdown-item" href="#"> Kinerja &raquo; </a>
                <ul class="submenu dropdown-menu">
                  <li>
                    <a class="dropdown-item" href="#">RENSTRA</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Renacana Kera tahunan</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Laporan Kinerja</a>
                  </li>
                </ul>
              </li>

               <!-- Keuangan -->
               <li>
                <a class="dropdown-item" href="#">Keuangan &raquo; </a>
                <ul class="submenu dropdown-menu">
                  <li>
                    <a class="dropdown-item" href="#">DIPA</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">RKA-KL</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Rencana Anggaran</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Realisasi Anggaran</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Neraca Keuangan</a>
                  </li>
                </ul>
              </li>

              <!-- Laporan-Laporan -->
               <li>
                <a class="dropdown-item" href="#">Laporan-laporan &raquo; </a>
                <ul class="submenu dropdown-menu">
                  <li>
                    <a class="dropdown-item" href="#">Laporan Tahunan</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Laporan Keuangan</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Laporan PPID</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Laporan Kinerja</a>
                  </li>
                </ul>
              </li>

              <li>
                <a class="dropdown-item" href="#"> Unduh Dokumen </a>
              </li>

            </ul>
          </li>

          <!-- Layanan Karantina -->


          <li class="nav-item dropdown" id="myDropdown">
            <RouterLink to="#" class="nav-link dropdown-toggle" href="#" data-bs-toggle="dropdown" aria-expanded="false">Layanan Karantina</RouterLink>
            <ul class="dropdown-menu">
              <li>
                <a class="dropdown-item" href="#"> Karantina Hewan </a>
              </li>
              <li>
                <a class="dropdown-item" href="#"> Karantina Tumbuhan </a>
              </li>
              <li>
                <a class="dropdown-item" href="#"> Alur Pelayanan </a>
              </li>
              <li>
                <a class="dropdown-item" href="#"> Regulasi Perkarantinaan </a>
              </li>
              <li>
                <a class="dropdown-item" href="#"> Tarif & Jasa Karantina </a>
              </li>
               <li>
                <a class="dropdown-item" href="#"> Basis Data &raquo; </a>
                <ul class="submenu dropdown-menu">
                  <li>
                    <a class="dropdown-item" href="#">Daftar Hama Penyakit Hewan</a>
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Daftar Hama Penyakit Tumbuhan</a>
                  </li>
                  
                </ul>
              </li>
              <li>
                <a class="dropdown-item" href="#"> FAQ </a>
              </li>
            </ul>
          </li>


        </ul>
        <button type="button" class="rounded-pill btn-rounded"> +62813 3990 1664 <span>
            <i class="fas fa-phone-alt"></i>
          </span>
        </button>
      </div>
    </div>
  </nav>
  <RouterView />
</template>
<script setup>
  import { RouterLink, RouterView } from 'vue-router'

  document.addEventListener("DOMContentLoaded", function() {
    // make it as accordion for smaller screens
    if (window.innerWidth < 992) {
      // close all inner dropdowns when parent is closed
      document.querySelectorAll('.navbar .dropdown').forEach(function(everydropdown) {
        everydropdown.addEventListener('hidden.bs.dropdown', function() {
          // after dropdown is hidden, then find all submenus
          this.querySelectorAll('.submenu').forEach(function(everysubmenu) {
            // hide every submenu as well
            everysubmenu.style.display = 'none';
          });
        })
      });
      document.querySelectorAll('.dropdown-menu a').forEach(function(element) {
        element.addEventListener('click', function(e) {
          let nextEl = this.nextElementSibling;
          if (nextEl && nextEl.classList.contains('submenu')) {
            // prevent opening link if link needs to open dropdown
            e.preventDefault();
            if (nextEl.style.display == 'block') {
              nextEl.style.display = 'none';
            } else {
              nextEl.style.display = 'block';
            }
          }
        });
      })
    }
    // end if innerWidth
  });
  // DOMContentLoaded  end

  /*Collapse In Hover*/

  document.addEventListener("DOMContentLoaded", function(){
// make it as accordion for smaller screens
if (window.innerWidth > 992) {

  document.querySelectorAll('.navbar .nav-item').forEach(function(everyitem){

    everyitem.addEventListener('mouseover', function(e){

      let el_link = this.querySelector('a[data-bs-toggle]');

      if(el_link != null){
        let nextEl = el_link.nextElementSibling;
        el_link.classList.add('show');
        nextEl.classList.add('show');
      }

    });
    everyitem.addEventListener('mouseleave', function(e){
      let el_link = this.querySelector('a[data-bs-toggle]');

      if(el_link != null){
        let nextEl = el_link.nextElementSibling;
        el_link.classList.remove('show');
        nextEl.classList.remove('show');
      }


    })
  });

}
// end if innerWidth
}); 
// DOMContentLoaded  end
</script>
<style scoped>
  .dropdown-item {
    padding: 15px 10px;
    color: #000;
  }

  .dropdown-item:hover {
    background-color: #b0afa9;
    color: #fff;
    font-weight: bold;
    border-radius: 20%;
  }

  /* ============ desktop view ============ */
  @media all and (min-width: 992px) {
    .dropdown-menu li {
      position: relative;
    }

    .nav-item .submenu {
      display: none;
      position: absolute;
      left: 100%;
      top: -7px;
    }

    .nav-item .submenu-left {
      right: 100%;
      left: auto;
    }

    .dropdown-menu>li:hover {
      background-color: #f1f1f1
    }

    .dropdown-menu>li:hover>.submenu {
      display: block;
    }
  }

  /* ============ desktop view .end// ============ */
  /* ============ small devices ============ */
  @media (max-width: 991px) {
    .dropdown-menu .dropdown-menu {
      margin-left: 0.7rem;
      margin-right: 0.7rem;
      margin-bottom: .5rem;
    }
  }

  /* ============ small devices .end// ============ */
</style>