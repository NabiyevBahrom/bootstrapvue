<template>
  <section class="py-5">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="row">
            <div class="col-lg-6 justify-content-center d-flex flex-column">
              <div class="card border-radius-lg">
                <div class="d-block blur-shadow-textarea">
                  <textarea
                    style="width: 100%"
                    class="border-radius-lg"
                    id="install"
                    readonly
                  >
npm i bootstrap@5.3.0-alpha3</textarea
                  >
                </div>
                <button class="btn btn-primary" id="installButton">copy</button>
              </div>
            </div>
            <div
              class="col-lg-6 justify-content-center d-flex flex-column ps-lg-5 pt-lg-0 pt-3"
            >
              <h3>
                <a href="javascript:;" class="text-dark"
                  >Build fast, responsive sites with Bootstrap</a
                >
              </h3>
              <p>
                Powerful, extensible, and feature-packed frontend toolkit. Build
                and customize with Sass, utilize prebuilt grid system and
                components, and bring projects to life with powerful JavaScript
                plugins.
              </p>
            </div>
          </div>
        </div>
        <div class="col-lg-12 mt-5">
          <div class="row flex-row-reverse">
            <div class="col-lg-6 justify-content-center d-flex flex-column">
              <div class="card border-radius-lg">
                <div class="blur-shadow-image">
                  <textarea
                    class="border-radius-lg"
                    id="npminstall"
                    style="width: 100%"
                    readonly
                  >
npm install bootstrap@5.3.0-alpha3</textarea
                  >
                  <button id="npminstallButton" class="btn btn-primary">
                    copy
                  </button>
                  <textarea
                    class="border-radius-lg"
                    id="geminstall"
                    style="width: 100%"
                    readonly
                  >
                  gem install bootstrap -v 5.3.0.alpha3
                  </textarea>
                  <button id="geminstallButton" class="btn btn-primary">
                    Copy
                  </button>
                </div>
              </div>
            </div>
            <div
              class="col-lg-6 pe-lg-5 justify-content-center d-flex flex-column pt-lg-0 pt-3"
            >
              <h3>
                <a href="javascript:;" class="text-dark"
                  >Install via package manager</a
                >
              </h3>
              <p>
                Install Bootstrap’s source Sass and JavaScript files via npm,
                RubyGems, Composer, or Meteor. Package managed installs don’t
                include documentation or our full build scripts. You can also
                use any demo from our Examples repo to quickly jumpstart
                Bootstrap projects.
                <a
                  href="javascript:;"
                  class="text-darker icon-move-right text-sm"
                  >Read More
                  <i class="fas fa-arrow-right text-xs ms-1"></i>
                </a>
              </p>
              <p class="author">
                <a href="javascript:;" class="ms-1"
                  ><span class="font-weight-bold text-info"
                    >Read our installation docs for more info and additional
                    package managers.</span
                  ></a
                >
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="py-4 position-relative">
    <div
      id="carousel-testimonial-pricing"
      class="carousel slide carousel-team"
      data-bs-ride="carousel"
    >
      <div class="carousel-inner">
        <div class="carousel-item active">
          <div class="container">
            <div class="row align-items-center">
              <div class="col-md-5 p-lg-5 ms-lg-auto">
                <div class="p-3">
                  <img
                    class="w-100 border-radius-md shadow-lg"
                    src="./logo/logo-netflix.svg"
                    alt="First slide"
                  />
                </div>
              </div>
              <div class="col-lg-5 col-md-7 me-lg-auto position-relative">
                <p class="text-sm font-weight-bold mb-1">- Customer Story</p>
                <h3 class="text-dark">
                  Excelent payment service. You guys are the best!
                </h3>
                <p class="my-4">
                  <i
                    >"Let the brain, muscles, nerves, every part of your body,
                    be full of that idea, and just leave every other idea alone.
                    This is the way to success."</i
                  >
                </p>
                <div class="author align-items-center">
                  <div class="avatar rounded-circle shadow bg-gradient-dark">
                    <img src="./logo/logo-netflix.svg" alt="logo" />
                  </div>
                  <div class="name ps-2">
                    <span>Mathew Glock</span>
                    <div>
                      <small>Marketing Manager - Slack</small>
                    </div>
                  </div>
                </div>
                <div class="w-25 ms-auto opacity-2 mt-n8">
                  <svg
                    width="110px"
                    height="110px"
                    viewBox="0 0 270 270"
                    version="1.1"
                    xmlns="http://www.w3.org/2000/svg"
                    xmlns:xlink="http://www.w3.org/1999/xlink"
                  >
                    <title>quote-down</title>
                    <g
                      stroke="none"
                      stroke-width="1"
                      fill="none"
                      fill-rule="evenodd"
                    >
                      <path
                        d="M107.000381,49.033238 C111.792099,48.01429 115.761022,48.6892564 116.625294,50.9407629 C117.72393,53.8028077 113.174473,58.3219079 107.017635,60.982801 C107.011653,60.9853863 107.00567,60.9879683 106.999688,60.990547 C106.939902,61.0219589 106.879913,61.0439426 106.820031,61.0659514 C106.355389,61.2618887 105.888177,61.4371549 105.421944,61.5929594 C88.3985192,68.1467602 80.3242628,76.9161885 70.3525495,90.6906738 C60.0774843,104.884196 54.9399518,119.643717 54.9399518,134.969238 C54.9399518,138.278158 55.4624127,140.716309 56.5073346,142.283691 C57.2039492,143.328613 57.9876406,143.851074 58.8584088,143.851074 C59.7291771,143.851074 61.0353294,143.241536 62.7768659,142.022461 C68.3497825,138.016927 75.4030052,136.01416 83.9365338,136.01416 C93.8632916,136.01416 102.658051,140.063232 110.320811,148.161377 C117.983572,156.259521 121.814952,165.88151 121.814952,177.027344 C121.814952,188.695638 117.417572,198.970703 108.622813,207.852539 C99.828054,216.734375 89.1611432,221.175293 76.6220807,221.175293 C61.9931745,221.175293 49.3670351,215.166992 38.7436627,203.150391 C28.1202903,191.133789 22.8086041,175.024577 22.8086041,154.822754 C22.8086041,131.312012 30.0359804,110.239421 44.490733,91.6049805 C58.2196377,73.906272 74.3541002,59.8074126 102.443135,50.4450748 C102.615406,50.3748509 102.790055,50.3058192 102.966282,50.2381719 C104.199241,49.7648833 105.420135,49.3936487 106.596148,49.1227802 L107,49 Z M233.000381,49.033238 C237.792099,48.01429 241.761022,48.6892564 242.625294,50.9407629 C243.72393,53.8028077 239.174473,58.3219079 233.017635,60.982801 C233.011653,60.9853863 233.00567,60.9879683 232.999688,60.990547 C232.939902,61.0219589 232.879913,61.0439426 232.820031,61.0659514 C232.355389,61.2618887 231.888177,61.4371549 231.421944,61.5929594 C214.398519,68.1467602 206.324263,76.9161885 196.352549,90.6906738 C186.077484,104.884196 180.939952,119.643717 180.939952,134.969238 C180.939952,138.278158 181.462413,140.716309 182.507335,142.283691 C183.203949,143.328613 183.987641,143.851074 184.858409,143.851074 C185.729177,143.851074 187.035329,143.241536 188.776866,142.022461 C194.349783,138.016927 201.403005,136.01416 209.936534,136.01416 C219.863292,136.01416 228.658051,140.063232 236.320811,148.161377 C243.983572,156.259521 247.814952,165.88151 247.814952,177.027344 C247.814952,188.695638 243.417572,198.970703 234.622813,207.852539 C225.828054,216.734375 215.161143,221.175293 202.622081,221.175293 C187.993174,221.175293 175.367035,215.166992 164.743663,203.150391 C154.12029,191.133789 148.808604,175.024577 148.808604,154.822754 C148.808604,131.312012 156.03598,110.239421 170.490733,91.6049805 C184.219638,73.906272 200.3541,59.8074126 228.443135,50.4450748 C228.615406,50.3748509 228.790055,50.3058192 228.966282,50.2381719 C230.199241,49.7648833 231.420135,49.3936487 232.596148,49.1227802 L233,49 Z"
                        fill="#48484A"
                        fill-rule="nonzero"
                        transform="translate(135.311778, 134.872794) scale(-1, -1) translate(-135.311778, -134.872794) "
                      ></path>
                    </g>
                  </svg>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <div class="container">
            <div class="row align-items-center">
              <div class="col-md-5 p-lg-5 ms-lg-auto">
                <div class="p-3">
                  <img
                    class="w-100 border-radius-md shadow"
                    src="./logo/logo-coinbase.svg"
                    alt="First slide"
                  />
                </div>
              </div>
              <div class="col-lg-5 col-md-7 me-lg-auto">
                <p class="text-sm font-weight-bold mb-1">- Customer Story</p>
                <h3 class="text-dark">Awesome services! Fast and secure.</h3>
                <p class="my-4">
                  <i
                    >"Wealth creation is an evolutionarily recent positive-sum
                    game. Status is an old zero-sum game. Those attacking wealth
                    creation are often just seeking status."</i
                  >
                </p>
                <div class="author align-items-center">
                  <div class="avatar rounded-circle shadow bg-gradient-dark">
                    <img src="" alt="logo" />
                  </div>
                  <div class="name ps-2">
                    <span>Ivana Goerge</span>
                    <div>
                      <small>CFO - Google</small>
                    </div>
                  </div>
                </div>
                <div class="w-25 ms-auto opacity-2 mt-n8">
                  <svg
                    width="110px"
                    height="110px"
                    viewBox="0 0 270 270"
                    version="1.1"
                    xmlns="http://www.w3.org/2000/svg"
                    xmlns:xlink="http://www.w3.org/1999/xlink"
                  >
                    <title>quote-down</title>
                    <g
                      stroke="none"
                      stroke-width="1"
                      fill="none"
                      fill-rule="evenodd"
                    >
                      <path
                        d="M107.000381,49.033238 C111.792099,48.01429 115.761022,48.6892564 116.625294,50.9407629 C117.72393,53.8028077 113.174473,58.3219079 107.017635,60.982801 C107.011653,60.9853863 107.00567,60.9879683 106.999688,60.990547 C106.939902,61.0219589 106.879913,61.0439426 106.820031,61.0659514 C106.355389,61.2618887 105.888177,61.4371549 105.421944,61.5929594 C88.3985192,68.1467602 80.3242628,76.9161885 70.3525495,90.6906738 C60.0774843,104.884196 54.9399518,119.643717 54.9399518,134.969238 C54.9399518,138.278158 55.4624127,140.716309 56.5073346,142.283691 C57.2039492,143.328613 57.9876406,143.851074 58.8584088,143.851074 C59.7291771,143.851074 61.0353294,143.241536 62.7768659,142.022461 C68.3497825,138.016927 75.4030052,136.01416 83.9365338,136.01416 C93.8632916,136.01416 102.658051,140.063232 110.320811,148.161377 C117.983572,156.259521 121.814952,165.88151 121.814952,177.027344 C121.814952,188.695638 117.417572,198.970703 108.622813,207.852539 C99.828054,216.734375 89.1611432,221.175293 76.6220807,221.175293 C61.9931745,221.175293 49.3670351,215.166992 38.7436627,203.150391 C28.1202903,191.133789 22.8086041,175.024577 22.8086041,154.822754 C22.8086041,131.312012 30.0359804,110.239421 44.490733,91.6049805 C58.2196377,73.906272 74.3541002,59.8074126 102.443135,50.4450748 C102.615406,50.3748509 102.790055,50.3058192 102.966282,50.2381719 C104.199241,49.7648833 105.420135,49.3936487 106.596148,49.1227802 L107,49 Z M233.000381,49.033238 C237.792099,48.01429 241.761022,48.6892564 242.625294,50.9407629 C243.72393,53.8028077 239.174473,58.3219079 233.017635,60.982801 C233.011653,60.9853863 233.00567,60.9879683 232.999688,60.990547 C232.939902,61.0219589 232.879913,61.0439426 232.820031,61.0659514 C232.355389,61.2618887 231.888177,61.4371549 231.421944,61.5929594 C214.398519,68.1467602 206.324263,76.9161885 196.352549,90.6906738 C186.077484,104.884196 180.939952,119.643717 180.939952,134.969238 C180.939952,138.278158 181.462413,140.716309 182.507335,142.283691 C183.203949,143.328613 183.987641,143.851074 184.858409,143.851074 C185.729177,143.851074 187.035329,143.241536 188.776866,142.022461 C194.349783,138.016927 201.403005,136.01416 209.936534,136.01416 C219.863292,136.01416 228.658051,140.063232 236.320811,148.161377 C243.983572,156.259521 247.814952,165.88151 247.814952,177.027344 C247.814952,188.695638 243.417572,198.970703 234.622813,207.852539 C225.828054,216.734375 215.161143,221.175293 202.622081,221.175293 C187.993174,221.175293 175.367035,215.166992 164.743663,203.150391 C154.12029,191.133789 148.808604,175.024577 148.808604,154.822754 C148.808604,131.312012 156.03598,110.239421 170.490733,91.6049805 C184.219638,73.906272 200.3541,59.8074126 228.443135,50.4450748 C228.615406,50.3748509 228.790055,50.3058192 228.966282,50.2381719 C230.199241,49.7648833 231.420135,49.3936487 232.596148,49.1227802 L233,49 Z"
                        fill="#48484A"
                        fill-rule="nonzero"
                        transform="translate(135.311778, 134.872794) scale(-1, -1) translate(-135.311778, -134.872794) "
                      ></path>
                    </g>
                  </svg>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <a
        class="carousel-control-prev text-dark text-lg"
        href="#carousel-testimonial-pricing"
        role="button"
        data-bs-slide="prev"
      >
        <i class="fas fa-chevron-left"></i>
        <span class="sr-only">Previous</span>
      </a>
      <a
        class="carousel-control-next text-dark text-lg"
        href="#carousel-testimonial-pricing"
        role="button"
        data-bs-slide="next"
      >
        <i class="fas fa-chevron-right"></i>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </section>
  <section class="bg-gradient-primary position-relative overflow-hidden">
    <img
      src="./logo/logo-coinbase.svg"
      alt="pattern-lines"
      class="position-absolute opacity-6"
    />
    <div class="container pt-5 pb-7">
      <div class="row">
        <div class="col-lg-6 d-flex justify-content-center flex-column">
          <div
            id="carouselExampleIndicator"
            class="carousel slide py-7"
            data-bs-ride="carousel"
          >
            <ol class="carousel-indicators justify-content-start ms-0">
              <a href="javascript:;">
                <img
                  src="./logo/logo-facebook.svg"
                  alt="..."
                  class="avatar avatar-sm border-radius-lg avatar-scale-up shadow border-0 active"
                  data-bs-target="#carouselExampleIndicator"
                  data-bs-slide-to="0"
                />
                <span class="text-white mx-2">&#124;</span>
              </a>

              <a href="javascript:;">
                <img
                  src="./logo/logo-apple.svg"
                  alt="..."
                  class="avatar avatar-sm border-radius-lg avatar-scale-up shadow border-0"
                  data-bs-target="#carouselExampleIndicator"
                  data-bs-slide-to="1"
                />
                <span class="text-white mx-2">&#124;</span>
              </a>

              <a href="#">
                <img
                  src="./logo/logo-apple.svg"
                  alt="..."
                  class="avatar avatar-sm border-radius-lg avatar-scale-up shadow border-0"
                  data-bs-target="#carouselExampleIndicator"
                  data-bs-slide-to="2"
                />
              </a>
            </ol>
            <div class="carousel-inner">
              <h2 class="text-white mb-0">Work with us</h2>
              <p class="text-white opacity-8 mb-1">
                Whatever your qualification is - we got you!
              </p>
              <hr
                class="text-white horizontal opacity-6 mb-4 mt-2 w-25 text-start"
              />
              <div class="carousel-item active">
                <h6 class="text-white opacity-8 pe-5">
                  "Take up one idea. Make that one idea your life - think of it,
                  dream of it, live on that idea. Let the brain, muscles,
                  nerves, every part of your body, be full of that idea, and
                  just leave every other idea alone. This is the way to success.
                  A single rose can be my garden... a single friend, my world."
                </h6>
                <div class="author mt-4">
                  <div class="name">
                    <span class="text-white">Ludwig Siato</span>
                    <div class="stats">
                      <small class="text-white opacity-6"
                        >Project manager, Apple</small
                      >
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item">
                <h6 class="text-white opacity-8 pe-5">
                  "Take up one idea. Make that one idea your life - think of it,
                  dream of it, live on that idea. Let the brain, muscles,
                  nerves, every part of your body, be full of that idea, and
                  just leave every other idea alone. This is the way to success.
                  A single rose can be my garden... a single friend, my world."
                </h6>
                <div class="author mt-4">
                  <div class="name">
                    <span class="text-white">John Down</span>
                    <div class="stats">
                      <small class="text-white opacity-6">CFO, Google</small>
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item">
                <h6 class="text-white opacity-8 pe-5">
                  "Take up one idea. Make that one idea your life - think of it,
                  dream of it, live on that idea. Let the brain, muscles,
                  nerves, every part of your body, be full of that idea, and
                  just leave every other idea alone. This is the way to success.
                  A single rose can be my garden... a single friend, my world."
                </h6>
                <div class="author mt-4">
                  <div class="name">
                    <span class="text-white">Mark Jojansen</span>
                    <div class="stats">
                      <small class="text-white opacity-6"
                        >Fullstack Developer, Atlassian</small
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="col-md-6 justify-content-center flex-column d-sm-none d-md-none d-lg-flex d-xl-flex"
        >
          <div class="row justify-content-center d-none d-md-flex">
            <div class="col-3 mb-4">
              <div
                class="d-block bg-white avatar avatar-lg border-radius-lg p-3 mt-n4 ms-8 fadeIn2 fadeInBottom"
              >
                <img src="./logo/logo-apple.svg" alt="Logo Image" />
              </div>
            </div>
            <div class="col-4 mb-4">
              <div
                class="d-block bg-white avatar avatar-lg border-radius-lg p-3 ms-8 mt-n6 fadeIn1 fadeInBottom"
              >
                <img src="./logo/logo-vodafone.svg" alt="Logo Image" />
              </div>
            </div>
            <div class="col-4 mb-4">
              <div
                class="d-block bg-white avatar avatar-lg border-radius-lg p-3 ms-6 mt-2 fadeIn3 fadeInBottom"
              >
                <img src="./logo/logo-coinbase.svg" alt="Logo Image" />
              </div>
            </div>
          </div>

          <div class="row justify-content-end d-none d-md-flex">
            <div class="col-4 my-4">
              <div
                class="d-block bg-white avatar avatar-lg border-radius-lg p-3 ms-4 fadeIn1 fadeInBottom"
              >
                <img
                  class="avatar-img"
                  src="./logo/logo-nasa.svg"
                  alt="Logo Image"
                />
              </div>
            </div>
            <div class="col-3 my-4">
              <div
                class="d-block bg-white avatar avatar-lg border-radius-lg p-3 me-auto fadeIn1 fadeInBottom"
              >
                <img
                  class="avatar-img"
                  src="./logo/logo-facebook.svg"
                  alt="Logo Image"
                />
              </div>
            </div>
            <div class="col-3 my-4">
              <div
                class="d-block bg-white avatar avatar-lg border-radius-lg p-3 fadeIn3 fadeInBottom ms-3 mt-3"
              >
                <img
                  class="avatar-img"
                  src="./logo/logo-netflix.svg"
                  alt="Logo Image"
                />
              </div>
            </div>
          </div>

          <div class="row d-none d-md-flex">
            <div class="col-6">
              <!-- Logo -->
              <div
                class="d-block bg-white avatar avatar-lg border-radius-lg p-3 ms-auto mt-5 fadeIn2 fadeInBottom"
              >
                <img
                  class="avatar-img"
                  src="./logo/logo-digitalocean.svg"
                  alt="Logo Image"
                />
              </div>
              <!-- End Logo -->
            </div>
            <div class="col-6 mt-6">
              <!-- Logo -->
              <div
                class="d-block bg-white avatar avatar-lg border-radius-lg p-3 mx-auto mt-n3 fadeIn3 fadeInBottom"
              >
                <img
                  class="avatar-img"
                  src="./logo/logo-pinterest.svg"
                  alt="Logo Image"
                />
              </div>
              <!-- End Logo -->
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "BootstrapvueHelloWorld",

  data() {
    return {};
  },

  mounted() {
    let install = document.getElementById("install");
    let installButton = document.getElementById("installButton");
    installButton.onclick = function () {
      install.select();
      document.execCommand("copy");
      installButton.innerText = "Codes Copied";
    };
    let npminstall = document.getElementById("npminstall");
    let npminstallButton = document.getElementById("npminstallButton");
    npminstallButton.onclick = function () {
      npminstall.select();
      document.execCommand("copy");
      npminstallButton.innerText = "Codes Copied";
    };
    let geminstall = document.getElementById("geminstall");
    let geminstallButton = document.getElementById("geminstallButton");
    geminstallButton.onclick = function () {
      geminstall.select();
      document.execCommand("copy");
      geminstallButton.innerText = "Codes Copied";
    };
  },

  methods: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
