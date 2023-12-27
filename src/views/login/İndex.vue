<template>
  <div class="home">
    <div class="grid grid-cols-12">
      <div class="col-span-3 bg-blue-700  h-screen "> 
        <LoginSlider></LoginSlider>
      </div>
      <div class="col-span-9 flex items-center">
        <div class="flex flex-col justify-between h-5/6 items-center mx-auto">
          <div class="flex flex-col items-center">  
            <img src="@/assets/SEFERİ_Logo1.png" alt="" class="w-4/6 xl:w-4/6 lg:w-3/6 min-[1920px]:w-5/6">
          </div>
          <div class="flex flex-col">
            <h2 class="text-3xl min-[1920px]:text-4xl xl:text-3xl lg:text-2xl text-[#0066B1] font-black">Lojistikte Yenilik Başlasın!</h2>
            <span class="text-base min-[1920px]:text-xl xl:text-base lg:text-sm text-[#A8A8A8]">Lorem ipsum dolor sit amet consectetur.</span>
          </div>
          <div class="flex flex-col w-2/5">
            <h4 class="text-2xl min-[1920px]:text-3xl xl:text-2xl lg:text-xl text-[#0066B1] py-4 font-bold">Giriş</h4>
            <div class="flex flex-col text-left py-3">
              <span class="text-base min-[1920px]:text-xl xl:text-base lg:text-sm text-[#A8A8A8] py-2">Kullanıcı Ad</span>
              <input type="text" name="" id="" class="border-[#0066B1] bg-[#F6F6F6] border rounded-lg p-2 caret-[#0066B1] focus:outline-none focus:border-[#0066B1] focus:ring-1 focus:ring-[#0066B1]">
            </div>
            <div class="flex flex-col text-left">
              <span class="text-base min-[1920px]:text-xl xl:text-base lg:text-sm text-[#A8A8A8] py-2">Şifre</span>
              <input type="password" name="" id="" class="border-[#0066B1] bg-[#F6F6F6] border rounded-lg p-2 caret-[#0066B1] focus:outline-none focus:border-[#0066B1] focus:ring-1 focus:ring-[#0066B1]">
              <div class="flex flex-row justify-between items-center pt-2">
                <div class="flex items-center">
                  <input type="checkbox" name="" id="" class="bg-[#D9D9D9]">
                  <span class="text-[#A8A8A8] text-sm xl:text-sm lg:text-xs min-[1920px]:text-base px-2">Beni Hatırla</span>
                </div>
                
              <span class="text-[#A8A8A8] text-sm min-[1920px]:text-base xl:text-sm lg:text-xs text underline">
                <router-link to="#">Şifremi unuttum</router-link>
                
              </span>
            </div>
              
            </div>
          
          <button class="bg-[#0066B1] hover:bg-opacity-90 w-3/3 p-3 rounded-lg my-8">
            <router-link to="#" class="w-full text-white text-xl min-[1920px]:text-2xl xl:text-xl w-3/3 font-bold lg:text-base">Giriş Yap</router-link>
          </button>
        </div>
            <p class="text-[#A8A8A8] text-base min-[1920px]:text-xl xl:text-base lg:text-sm">Lorem ipsum dolor sit amet consectetur. Et scelerisque massa rutrum nibh varius in purus justo ornare.</p>
        </div>
        <div class="bg-blue-700 h-screen">
            <span class="p-2"></span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import LoginSlider from './components/LoginSlider.vue' ;
export default {

  name: 'HomeView',
  components: {
    LoginSlider,
  },
}
</script>
<style scoped>

</style>