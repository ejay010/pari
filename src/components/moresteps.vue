  <template>
<!-- Contact Section -->
<section id="stepstosov" class="contact-section bg-black">
  <div class="container-fluid">
    <div class="row d-flex justify-content-center m-4 mb-5">
      <h1 class="text-uppercase color3">Best for Africa...</h1>
    </div>
    <div class="row d-flex justify-content-center pb-3">
      <div class="card col-md-3 speechbubble">
        <div class="card-body">
          1. Learn & teach the TRUE History of our Past
        </div>
      </div>

      <div class="card col-md-3 speechbubble">
        <div class="card-body">
          3. Eliminate ideologies & misconceptions that maintain manipulated division, hostilities & conflicts between us.
        </div>
      </div>

      <div class="card col-md-3 speechbubble-alt">
        <div class="card-body">
          5. Develop 1st Quality "In-Africa" training & finishing industries & markets for our native resources
        </div>
      </div>

      <div class="card col-md-3 speechbubble-alt">
        <div class="card-body">
          7. Equitably Enhance Global import, export, wholesale & retail trade inside & outside of Africa
        </div>
      </div>
    </div>

    <div class="row mt-4 mb-4 pathrow d-flex justify-content-around">
      <div class="card arrow-card col-md-8">
        <div class="card-body text-white text-uppercase text-center my-auto">
          <h3>Self-Empowered steps to true continetal sovereignty</h3>
        </div>
      </div>

      <div class="card col-md-3">
        <div class="card-body text-uppercase text-center">
          <h5>socio-economic viability</h5>
        </div>
      </div>
    </div>

    <div class="row pt-3">
      <div class="card col-md-3 speechbubble-top">
        <div class="card-body">
2. Teach the Truth about:  method, purpose & cost of Colonial & Post-Colonial systems
        </div>
      </div>

      <div class="card col-md-3 speechbubble-top">
        <div class="card-body">
          4. Identify & Associate Equitable Int’l Partners to help develop and co-own Pan-African industries
        </div>
      </div>

      <div class="card col-md-3 speechbubble-top-alt">
        <div class="card-body">
          6. Develop profitable products & services for continental &
global consumption
        </div>
      </div>

      <div class="card col-md-3 speechbubble-top-alt">
        <div class="card-body">
          8. Structure & Fund Sustainable Economic & Social Development resulting in billions of jobs &  increasing Foreign Exchange
        </div>
      </div>
    </div>
    <div class="row d-flex justify-content-center">
      <h1 class="text-uppercase m-4 mt-5" style="color: #3C64C9;">IS GOOD FOR THE WORLD!</h1>
    </div>
  </div>
</section>
</template>

<style>
/* #stepstosov {
  background-image: url("https://news.artnet.com/app/news-upload/2017/05/boris-nzebo-1-1024x1024.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
} */
.speechbubble:before {
  content: ' ';
  position: absolute;
  width: 0;
  height: 0;
  left: 82%;
  top: 100%;
  border: 25px solid;
  border-color: #f5a914 #f5a914 transparent transparent;
}

.speechbubble:after {
  content: ' ';
  position: absolute;
  width: 0;
  height: 0;
  left: 85%;
  top: 100%;
  border: 15px solid;
  border-color: #fff #fff transparent transparent;
}

.speechbubble-alt:before {
  content: ' ';
  position: absolute;
  width: 0;
  height: 0;
  right: 80%;
  top: 100%;
  border: 25px solid;
  border-color: #f5a914 transparent transparent #f5a914;
}

.speechbubble-alt:after {
  content: ' ';
  position: absolute;
  width: 0;
  height: 0;
  right: 85%;
  top: 100%;
  border: 16px solid;
  border-color: #fff transparent transparent #fff;
}

.speechbubble-top::before {
  content: ' ';
  position: absolute;
  width: 0;
  height: 0;
  left: 82%;
  bottom: 100%;
  border: 25px solid;
  border-color: transparent #f5a914 #f5a914 transparent;
}

.speechbubble-top::after {
  content: ' ';
  position: absolute;
  width: 0;
  height: 0;
  left: 85%;
  bottom: 100%;
  border: 16px solid;
  border-color: transparent #fff #fff transparent;
}

.speechbubble-top-alt::before {
  content: ' ';
  position: absolute;
  width: 0;
  height: 0;
  right: 82%;
  bottom: 100%;
  border: 25px solid;
  border-color: transparent transparent #f5a914 #f5a914;
}

.speechbubble-top-alt::after {
  content: ' ';
  position: absolute;
  width: 0;
  height: 0;
  right: 85%;
  bottom: 100%;
  border: 16px solid;
  border-color: transparent transparent #fff #fff;
}

.speechbubble-top {
  border-top: 0.25rem solid #f5a914 !important;
  border-bottom: none !important;
}

.speechbubble-top-alt {
  border-top: 0.25rem solid #f5a914 !important;
  border-bottom: none !important;
}

.pathrow {
  position: relative;
  z-index: 1;
}

.arrow-card {
  background-color: #f5a914 !important;
}

.arrow-card::before {
  content: ' ';
  position: absolute;
  width: 0;
  height: 0;
  border: 100px solid;
  left: 97%;
  bottom: -40%;
  z-index: 2;
  border-color: transparent transparent transparent #f5a914;
}
</style>
