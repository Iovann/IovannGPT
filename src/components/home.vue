<template>
  <section class="container-fluid">
    <div class="row">
      <div class="col-lg-2 black vh-100 flex-column justify-content-between position-relative ">
          <div class="container open p-2 mt-4 rounded-pill">
            <div class="row justify-content-between align-items-center">
              <div class="col-6">
                <img src="../../public/icons/mini.svg" alt="" class="bg-white p-1 rounded-circle">
                <span class="ms-3 text-white fw-bolder">New chat</span>
              </div>

              <div class="col-1 me-3 ">
                <img src="../../public/icons/write.svg" alt="" class="point">
              </div>
            </div>
        </div>

        <div class="row position-absolute bottom-0 py-3">
            <div class="d-flex align-items-center">
              <img src="../../public/icons/upgrade.svg" alt="" class="p-2 bg-violet rounded-circle">
              <div class="text-white fw-bold ms-3">
                <span>Upgrade</span><br>
                <span class="fw-normal">Get GPT-4, DALLE, and more</span>
              </div>
            </div>
            <div class="d-flex align-items-center py-3">
              <div class="px-2 py-1 rounded-circle ia text-white fw-bolder">IA</div>
              <div class="text-white fw-bold ms-3">
                <span>Iovann Don-Dy ATCHO</span>
              </div>
            </div>
        </div>
      </div>

      <div class="col-lg-10 vh-100 bg-violet container">
        <!-- menu -->
          <div class="row mt-4 justify-content-between align-items-center">
            <div class="col-6">
              <div class="dropdown">
                <a class="btn text-white dropdown-toggle fw-bolder " href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Chat GPT 3.5
                </a>
                <!-- <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul> -->
              </div>
            </div>

            <div class="col-3 d-flex justify-content-end ">
                <img src="../../public/icons/export.svg" alt="" class=" me-3" style="width: 6%;">
            </div>
          </div>

          <!-- middle -->
          <div class="row  align-items-center h-75">
              <div class="text-center">
                <img src="../../public/icons/chat.svg" alt="" class=" bg-white p-3 rounded-circle">
                <p class="text-center fw-bold text-white fs-4 mt-3 ">How can I help you today?</p>
              </div>
              <div class="container px-5 text-white">
                  <div class="row justify-content-center gap-3">
                    <div class="col-md-3 rounded-4 px-4 py-2 border border-1 border-white open2">
                      <p class="fw-bold fs-5 mb-2">Brainstorm contest ideas</p>
                      <p class="">for my new podcast on urban design</p>
                    </div>

                    <div class="col-md-3 rounded-4 px-4 py-2 border border-1 border-white open2">
                      <p class="fw-bold fs-5 mb-2">Design a database schema</p>
                      <p class="">for an online merch store</p>
                    </div>

                  </div>

                  <div class="row justify-content-center gap-3 mt-4">
                    <div class="col-md-3 rounded-4 px-4 py-2 border border-1 border-white open2">
                      <p class="fw-bold fs-5 mb-2">Come up with concepts</p>
                      <p class="">for a retro-style arcade game</p>
                    </div>

                    <div class="col-md-3 rounded-4 px-4 py-2 border border-1 border-white open2">
                      <p class="fw-bold fs-5 mb-2">Help me oick</p>
                      <p class="">an outfit that will look good on camera</p>
                    </div>
                  </div>
              </div>
          </div>
          
      </div>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>
  .black{
    background-color: #171717 !important;
  }

  .bg-violet{
    background-color: #212121;
  }

  .point{
    cursor: pointer;
  }
  .open:hover{
    background-color: #212121;
  }
  .ia{
    background-color: #BF360C;
  }

  .open2:hover{
    background-color: #9B9B9B;
  }
</style>