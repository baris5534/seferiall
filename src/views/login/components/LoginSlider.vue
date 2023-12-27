<template>
  <carousel :per-page="1" :navigate-to="someLocalProperty" :mouse-drag="true" :loop="true" :autoplay="true"
    :autoplayTimeout="2500">
    <slide>
      <div class="arkaplan1">
        <div class="p-5 h-screen flex flex-col justify-between w-[480px] lg:w-[260px] xl:w-[320px] 2xl:w-[380px] min-[1920px]:w-[420px]">
          <div>
            <img src="@/assets/SIRIUS_TEDARİK_Logo_Full Beyaz-01 1.png" alt="" class="lg:w-3/6 xl:w-2/6 2xl:w-3/6 min-[1920px]:w-4/6"/>
          </div>
          <div class="text-left float-end space-y-2 w-full">
            <div class="pb-20 xl:pb-20 lg:pb-5 space-y-8 flex flex-col w-full">
              <h4 class="font-black text-3xl lg:text-xl xl:text-2xl 2xl:text-3xl min-[1920px]:text-3xl text-white w-full">
                Zamanı En İyi Şekilde Kullan
              </h4>
              <span class="text-base lg:text-xs xl:text-base 2xl:text-sm min-[1920px]:text-xl text-white">Zamanınızı ve kaynaklarınızı etkin bir şekilde yönetin.
                Yolculuklarınızı tasarruflu bir şekilde planlayarak, hızlı ve
                zamanında teslimatlar ile iş süreçlerinizi optimize edin.</span>
            </div>
            <div class="flex space-x-8 lg:space-x-4 items-center py-4 lg:py-2">
              <span><img src="@/assets/simple-icons_x.png" alt="" class="lg:w-4/6"/></span>
              <span><img src="@/assets/ri_instagram-fill.png" alt="" class="lg:w-4/6"/></span>
              <span><img src="@/assets/mdi_linkedin.png" alt="" class="lg:w-4/6"/></span>
            </div>
            
            <div>
              <span class="text-white lg:text-xs xl:text-sm min-[1920px]:text-lg">Lorem ipsum dolor sit amet consectetur.</span>
            </div>
          </div>
        </div>
      </div>
    </slide>
    <slide>
      <div class="arkaplan2">
        <div class="p-5 h-screen flex flex-col justify-between w-[480px] lg:w-[260px] xl:w-[320px] 2xl:w-[380px] min-[1920px]:w-[420px]">
          <div>
            <img src="@/assets/SIRIUS_TEDARİK_Logo_Full Beyaz-01 1.png" alt="" class="lg:w-3/6 xl:w-3/6 2xl:w-3/6 min-[1920px]:w-4/6"/>
          </div>
          <div class="text-left float-end space-y-2">
            <div class="pb-20 xl:pb-20 lg:pb-5 space-y-8 flex flex-col">
              <h4 class="font-black lg:text-xl text-3xl xl:text-2xl 2xl:text-3xl min-[1920px]:text-3xl text-white">
                Yakıt Tüketimi Tasarrufunda Öncü
              </h4>
              <span class="text-base lg:text-xs xl:text-base 2xl:text-sm min-[1920px]:text-xl text-white">Yenilikçi teknolojimiz sayesinde, yakıt tüketimini optimize
                ederek çevre dostu ve ekonomik bir lojistik deneyimi sunuyoruz.
                İleri seviye verimlilikle, tasarrufun keyfini çıkarın.</span>
            </div>
            <div class="flex space-x-8 lg:space-x-4 items-center py-4 lg:py-2">
              <span><img src="@/assets/simple-icons_x.png" alt="" class="lg:w-4/6"/></span>
              <span><img src="@/assets/ri_instagram-fill.png" alt="" class="lg:w-4/6"/></span>
              <span><img src="@/assets/mdi_linkedin.png" alt="" class="lg:w-4/6"/></span>
            </div>
            
            <div>
              <span class="text-white lg:text-xs xl:text-sm min-[1920px]:text-lg">Lorem ipsum dolor sit amet consectetur.</span>
            </div>
          </div>
        </div>
      </div>
    </slide>
    <slide>
      <div class="arkaplan3">
        <div class="p-5 h-screen flex flex-col justify-between w-[480px] lg:w-[260px] xl:w-[320px] 2xl:w-[380px] min-[1920px]:w-[420px]">
          <div>
            <img src="@/assets/SIRIUS_TEDARİK_Logo_Full Beyaz-01 1.png" alt="" class="lg:w-3/6 xl:w-3/6 2xl:w-3/6 min-[1920px]:w-4/6"/>
          </div>
          <div class="text-left float-end space-y-2 ">
            <div class="pb-20 xl:pb-20 lg:pb-5 space-y-8 flex flex-col">
              <h4 class="font-black lg:text-xl text-3xl xl:text-2xl 2xl:text-3xl min-[1920px]:text-3xl text-white">
                Araç Takibiyle Kontrol Senin Elinde
              </h4>
              <span class="text-base lg:text-xs xl:text-base 2xl:text-sm min-[1920px]:text-xl text-white">Araçlarınızın gerçek zamanlı takibiyle güvenliği artırın,
                teslimat süreçlerini hızlandırın ve operasyonel verimliliği en
                üst düzeye çıkarın. Kontrol sizin elinizde.</span>
            </div>
            <div class="flex space-x-8 lg:space-x-4 items-center py-4 lg:py-2">
              <span><img src="@/assets/simple-icons_x.png" alt="" class="lg:w-4/6"/></span>
              <span><img src="@/assets/ri_instagram-fill.png" alt="" class="lg:w-4/6"/></span>
              <span><img src="@/assets/mdi_linkedin.png" alt="" class="lg:w-4/6"/></span>
            </div>
            
            <div>
              <span class="text-white lg:text-xs xl:text-sm min-[1920px]:text-lg">Lorem ipsum dolor sit amet consectetur.</span>
            </div>
          </div>
        </div>
      </div>
    </slide>
  </carousel>
  
</template>

<script>

export default {
  components: {
 }
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

.içi-beyaz-çizgi {
  border-left-width: 70px;
  height: 7px;
  background-color: white;
  border-radius: 20px;
}
.VueCarousel-dot{
  width: 30px!important;
  height: 7px!important;
  border-radius: 20px!important;
}
.VueCarousel-pagination{
  position: absolute;
  top: 80%;
  padding: 0 10px;
}
.VueCarousel-dot-container{
  float:left;
}

.VueCarousel-dot{
  background-color: white!important;
  opacity: 50%!important;
}
.VueCarousel-dot--active{
  background-color: #fff!important;
  opacity: 100%!important;
}
.VueCarousel-dot[data-v-438fd353]:focus {
    outline: 0px solid lightblue!important;
}
@media only screen and (max-width: 1920px) {
  .VueCarousel-dot{
  width: 50px!important;
  height: 7px!important;
  border-radius: 20px!important;
}
  .VueCarousel-pagination{
  position: absolute;
  top: 85%;
  padding: 0 10px;
}
}
@media only screen and (max-width: 1280px){
  .VueCarousel-dot{
  width: 50px!important;
  height: 7px!important;
  border-radius: 20px!important;
}
.VueCarousel-pagination{
  position: absolute;
  top: 80%;
  padding: 0 10px;
}
}
@media only screen and (max-width: 1024px){
  .VueCarousel-dot{
  width: 30px!important;
  height: 7px!important;
  border-radius: 20px!important;
}
.VueCarousel-pagination{
  position: absolute;
  top: 75%;
  padding: 0 10px;
}
}
@media only screen and (max-width: 1536px){
  .VueCarousel-dot{
  width: 50px!important;
  height: 7px!important;
  border-radius: 20px!important;
}
.VueCarousel-pagination{
  position: absolute;
  top: 73%;
  padding: 0 10px;
}
}
</style>