<template>
  <div class="home">
    <div class="grid grid-cols-12">
      <div class="col-span-3 bg-blue-700  h-screen"> 
       <!-- <div class="p-5 h-screen flex flex-col justify-between">
          <div>          
            <img src="@/assets/SIRIUS_TEDARİK_Logo_Full Beyaz-01 1.png" alt="">
          </div>
          <div class="text-left float-end space-y-2">
            <div class="pb-6 space-y-8 flex flex-col">
              <h4 class="font-black text-3xl text-white">Zamanı En İyi Şekilde Kullan</h4>
              <span class="text-base text-white">Zamanınızı ve kaynaklarınızı etkin bir şekilde yönetin. Yolculuklarınızı tasarruflu bir şekilde planlayarak, hızlı ve zamanında teslimatlar ile iş süreçlerinizi optimize edin.</span>
            </div>
            <div class="space-x-2 pb-14">
              <span class="bg-white px-10 rounded-xl"></span>
              <span class="bg-white opacity-50 px-10 rounded-xl"></span>
              <span class="bg-white opacity-50 px-10 rounded-xl"></span>
            </div>
            <div class="flex space-x-8 items-center py-4">
              <span><img src="@/assets/simple-icons_x.png" alt=""></span>
              <span><img src="@/assets/ri_instagram-fill.png" alt=""></span>
              <span><img src="@/assets/mdi_linkedin.png" alt=""></span>
            </div>
            <div>
              <span class="text-white">Lorem ipsum dolor sit amet consectetur.</span>
            </div>
          </div>
        </div>        -->
        <!-- <swiper-component>
        </swiper-component> -->
        <SliderDe></SliderDe>
      </div>
      <div class="col-span-9 flex items-center">
        <div class="flex flex-col justify-between h-5/6 items-center mx-auto">
          <div class="flex flex-col items-center">  
            <img src="@/assets/SEFERİ_Logo1.png" alt="" class="w-4/6">
          </div>
          <div class="flex flex-col">
            <h2 class="text-3xl text-[#0066B1] font-black">Lojistikte Yenilik Başlasın!</h2>
            <span class="text-base text-[#A8A8A8]">Lorem ipsum dolor sit amet consectetur.</span>
          </div>
          <div class="flex flex-col w-2/5">
            <h4 class="text-2xl text-[#0066B1] py-4 font-bold">Giriş</h4>
            <div class="flex flex-col text-left py-3">
              <span class="text-base text-[#A8A8A8] py-2">Kullanıcı Ad</span>
              <input type="text" name="" id="" class="border-[#0066B1] bg-[#F6F6F6] border rounded-lg p-2 caret-[#0066B1] focus:outline-none focus:border-[#0066B1] focus:ring-1 focus:ring-[#0066B1]">
            </div>
            <div class="flex flex-col text-left">
              <span class="text-base text-[#A8A8A8] py-2">Şifre</span>
              <input type="password" name="" id="" class="border-[#0066B1] bg-[#F6F6F6] border rounded-lg p-2 caret-[#0066B1] focus:outline-none focus:border-[#0066B1] focus:ring-1 focus:ring-[#0066B1]">
              <div class="flex flex-row justify-between items-center pt-2">
                <div class="flex items-center">
                  <input type="checkbox" name="" id="" class="bg-[#D9D9D9]">
                  <span class="text-[#A8A8A8] text-sm px-2">Beni Hatırla</span>
                </div>
                
              <span class="text-[#A8A8A8] text-sm text underline">
                <router-link to="#">Şifremi unuttum</router-link>
                
              </span>
            </div>
              
            </div>
          
          <button class="bg-[#0066B1] hover:bg-opacity-90 w-3/3 p-3 rounded-lg my-8">
            <router-link to="#" class="w-full text-white text-xl w-3/3 font-bold">Giriş Yap</router-link>
          </button>
        </div>
            <p class="text-[#A8A8A8] text-lg">Lorem ipsum dolor sit amet consectetur. Et scelerisque massa rutrum nibh varius in purus justo ornare.</p>
        </div>
        <div class="bg-blue-700 h-screen">
            <span class="p-2"></span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// import SwiperComponent from './components/SwiperComponent.vue';
import SliderDe from './components/SliderDe.vue' ;
export default {

  name: 'HomeView',
  components: {
    // SwiperComponent,
    SliderDe,
  },
}
</script>
<style scoped>
/* .bgimage{
  background-image:('../../assets/carousel1.png');

} */
</style>