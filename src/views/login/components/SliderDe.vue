<template>
    <carousel :per-page="1" :navigate-to="someLocalProperty" :mouse-drag="true" :loop="true" :autoplay="true" :autoplayTimeout="2500" :paginationPosition="top-overlay">
    <slide>
        <div class="arkaplan1">
        <div class="p-5 h-screen flex flex-col justify-between w-[480px]">
          <div>
            <img
              src="@/assets/SIRIUS_TEDARİK_Logo_Full Beyaz-01 1.png"
              alt=""
            />
          </div>
          <div class="text-left float-end space-y-2">
            <div class="pb-6 space-y-8 flex flex-col">
              <h4 class="font-black text-3xl text-white">
                Zamanı En İyi Şekilde Kullan
              </h4>
              <span class="text-base text-white"
                >Zamanınızı ve kaynaklarınızı etkin bir şekilde yönetin.
                Yolculuklarınızı tasarruflu bir şekilde planlayarak, hızlı ve
                zamanında teslimatlar ile iş süreçlerinizi optimize edin.</span
              >
            </div>
            <div class="space-x-2 pb-14">
              <span class="bg-white px-10 rounded-xl"></span>
              <span class="bg-white opacity-50 px-10 rounded-xl"></span>
              <span class="bg-white opacity-50 px-10 rounded-xl"></span>
            </div>
            <div class="flex space-x-8 items-center py-4">
              <span><img src="@/assets/simple-icons_x.png" alt="" /></span>
              <span><img src="@/assets/ri_instagram-fill.png" alt="" /></span>
              <span><img src="@/assets/mdi_linkedin.png" alt="" /></span>
            </div>
            <div>
              <span class="text-white"
                >Lorem ipsum dolor sit amet consectetur.</span
              >
            </div>
          </div>
        </div>
      </div>
    </slide>
    <slide>
        <div class="arkaplan2">
        <div class="p-5 h-screen flex flex-col justify-between w-[480px]">
          <div>
            <img
              src="@/assets/SIRIUS_TEDARİK_Logo_Full Beyaz-01 1.png"
              alt=""
            />
          </div>
          <div class="text-left float-end space-y-2">
            <div class="pb-6 space-y-8 flex flex-col">
              <h4 class="font-black text-3xl text-white">
                Yakıt Tüketimi Tasarrufunda Öncü
              </h4>
              <span class="text-base text-white"
                >Yenilikçi teknolojimiz sayesinde, yakıt tüketimini optimize
                ederek çevre dostu ve ekonomik bir lojistik deneyimi sunuyoruz.
                İleri seviye verimlilikle, tasarrufun keyfini çıkarın.</span
              >
            </div>
            <div class="space-x-2 pb-14">
              <span class="bg-white px-10 opacity-50 rounded-xl"></span>
              <span class="bg-white px-10 rounded-xl"></span>
              <span class="bg-white opacity-50 px-10 rounded-xl"></span>
            </div>
            <div class="flex space-x-8 items-center py-4">
              <span><img src="@/assets/simple-icons_x.png" alt="" /></span>
              <span><img src="@/assets/ri_instagram-fill.png" alt="" /></span>
              <span><img src="@/assets/mdi_linkedin.png" alt="" /></span>
            </div>
            <div>
              <span class="text-white"
                >Lorem ipsum dolor sit amet consectetur.</span
              >
            </div>
          </div>
        </div>
      </div>
    </slide>
    <slide>
        <div class="arkaplan3">
        <div class="p-5 h-screen flex flex-col justify-between w-[480px]">
          <div>
            <img
              src="@/assets/SIRIUS_TEDARİK_Logo_Full Beyaz-01 1.png"
              alt=""
            />
          </div>
          <div class="text-left float-end space-y-2">
            <div class="pb-6 space-y-8 flex flex-col">
              <h4 class="font-black text-3xl text-white">
                Araç Takibiyle Kontrol Senin Elinde
              </h4>
              <span class="text-base text-white"
                >Araçlarınızın gerçek zamanlı takibiyle güvenliği artırın,
                teslimat süreçlerini hızlandırın ve operasyonel verimliliği en
                üst düzeye çıkarın. Kontrol sizin elinizde.</span
              >
            </div>
            <div class="space-x-2 pb-14">
              <span class="bg-white px-10 opacity-50 rounded-xl"></span>
              <span class="bg-white opacity-50 px-10 rounded-xl"></span>
              <span class="bg-white px-10 rounded-xl"></span>
            </div>
            <div class="flex space-x-8 items-center py-4">
              <span><img src="@/assets/simple-icons_x.png" alt="" /></span>
              <span><img src="@/assets/ri_instagram-fill.png" alt="" /></span>
              <span><img src="@/assets/mdi_linkedin.png" alt="" /></span>
            </div>
            <div>
              <span class="text-white"
                >Lorem ipsum dolor sit amet consectetur.</span
              >
            </div>
          </div>
        </div>
      </div>
    </slide>
  </carousel>
  </template>
  
  <script>
  export default {
    
  };
  </script>
  
  <style>
  .arkaplan1 {
  background-image: url("@/assets/carousel1.png");
}
.arkaplan2 {
  background-image: url("@/assets/Rectangle 2.png");
}
.arkaplan3 {
  background-image: url("@/assets/Rectangle 10.png");
}
  </style>