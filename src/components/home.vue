<template>
  <section class="container-fluid">
    <div class="offcanvas offcanvas-start black d-lg-none" tabindex="-1" id="offcanvasExample" aria-labelledby="offcanvasExampleLabel">
        <p class="text-end mb-0">
          <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
        </p>
      <div class="offcanvas-header">
        <div class="container open px-1 py-2 mt-lg-4 rounded-pill">
              <div class="col-9 me-3 ">
                <div class="row justify-content-between align-items-center">
                  <div class="row justify-content-between align-items-center">
                    <div class="col-9">
                      <img src="/icons/mini.svg" alt="" class="bg-white p-1 rounded-circle">
                      <span class="ms-1 text-white fw-bolder">New chat</span>
                    </div>
                  </div>
                </div>
        </div>

        

      </div>
      </div>
      <div class="offcanvas-body">
        <div class="row position-absolute bottom-0 py-3">
            <div class="d-flex align-items-center">
              <img src="/icons/upgrade.svg" alt="" class="p-2 bg-violet rounded-circle">
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
    </div>


    <div class="row">
      <div class="col-lg-3 col-xl-2 d-none d-lg-flex black vh-100 flex-column justify-content-between position-relative">
          <div class="container open px-1 py-2 mt-4 rounded-pill">
            <div class="row justify-content-between align-items-center">
              <div class="col-9">
                <img src="/icons/mini.svg" alt="" class="bg-white p-1 rounded-circle">
                <span class="ms-1 text-white fw-bolder">New chat</span>
              </div>

              <div class="col-1 me-3 ">
                <img src="/icons/write.svg" alt="" class="point">
              </div>
            </div>
        </div>

        <div class="row position-absolute bottom-0 py-3">
            <div class="d-flex align-items-center">
              <img src="/icons/upgrade.svg" alt="" class="p-2 bg-violet rounded-circle">
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

      <div class="col-lg-9 col-xl-10 bg-violet container vh-100 ">
        <!-- menu -->
          <div class="row mt-4 justify-content-between d-none d-lg-flex">
            <div class="col-6 d-flex justify-content-between">
              <div class="dropdown">
                <a class="btn text-white dropdown-toggle fw-bolder " href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">Chat GPT 3.5</a>
              </div>
            </div>

            <div class="col-3 d-none d-lg-flex justify-content-end ">
                <p class="text-end">
                  <img src="/icons/export.svg" alt="" class="me-3">
                </p>
            </div>
          </div>

          <div class="row mt-4 justify-content-between d-lg-none">
            <div class="col d-flex justify-content-between">
              <button class="btn d-lg-none" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasExample" aria-controls="offcanvasExample"><img src="/icons/hmg.svg" alt=""></button>
              <div class="dropdown">
                <a class="btn text-white dropdown-toggle fw-bolder " href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">Chat GPT 3.5</a>
              </div>

              <img src="/icons/write.svg" alt="" class=" me-3">
            </div>
          </div>

          <!-- middle -->

          <div class="row justify-content-center align-items-center h-50">
            <div class="col-8">
                <p class="text-center"><img src="/icons/chat.svg" alt="" class=" bg-white p-3 rounded-circle"></p>
                <p class="text-center fw-bold text-white fs-4 mt-3 ">How can I help you today?</p>
            </div>
          </div>
                
          <div class="row justify-content-center align-content-center pt-5">
            <div class="col-lg-9 col-xl-10 col-12  mt-auto">
              <div class="container text-white">
                  <div class="row justify-content-center gap-2 gap-lg-3">
                    <div class="col-lg-5 col-11 rounded-4 px-2 px-lg-2 px-xl-4  py-2 border border-1 whitebord open2">
                      <p class="fw-bold fs2 mb-2">Brainstorm contest ideas</p>
                      <p class="fs1">for my new podcast on urban design</p>
                    </div>

                    <div class="col-lg-5 col-11 rounded-4 px-2 px-lg-2 px-xl-4  py-2 border border-1 whitebord open2">
                      <p class="fw-bold fs2 mb-2">Design a database schema</p>
                      <p class="fs1">for an online merch store</p>
                    </div>
                  </div>

                  <div class="row justify-content-center d-none d-xl-flex gap-2 gap-lg-3 mt-4">
                    <div class="col-lg-5 rounded-4 px-4 py-2 border border-1 whitebord open2">
                      <p class="fw-bold fs2 mb-2">Come up with concepts</p>
                      <p class="fs1">for a retro-style arcade game</p>
                    </div>

                    <div class="col-lg-5 rounded-4 px-4 py-2 border border-1 whitebord open2">
                      <p class="fw-bold  fs2 mb-2">Help me oick</p>
                      <p class="fs1">an outfit that will look good on camera</p>
                    </div>


                    <div class="row justify-content-center ">
                    <div class="col-12 col-sm-11 mx-2 px-sm-1 ">
                      <form action="">
                      <div class="input-group mt-3 mb-2">
                        <input class="form-control form-control-lg rounded-start-4" v-model="message" type="text" placeholder="Message ChatGPT..." style="background-color: #212121; color:white; border-right-color: #212121 !important;" id="message" aria-describedby="basic-addon2">
                        <button class="input-group-text rounded-end-4 bg-violet bord p-3" style="border-left-color:#212121 !important;"  type="submit" id="basic-addon2"><img src="/icons/arrow.svg" :style="{backgroundColor: message? 'white': '#A2A2A8'}" alt="" class="p-2 rounded-2"></button>
                      </div>
                    </form>
                    </div>
                  </div>
                  </div>
                  <p class="text-center text-white position-relative">
                    <span class="ps-lg-5 ms-lg-5 ">ChatGPT can make mistakes. Consider checking important information.</span>
                  </p>
              </div>
          </div>
        </div>
      </div> 
    </div>
  </section>
</template>

<script>
export default {
  data(){
    return{
      message: "",
    }
    
  }
}
</script>

<style>

  input::-webkit-input-placeholder{
    color: white !important;
  }
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
    background-color: #474444;
  }

  .whitebord{
    border-color: #777880 !important;
  }

  .fs1{
    font-size: small !important;
  }

  .fs2{
    font-size: medium !important;
  }
</style>