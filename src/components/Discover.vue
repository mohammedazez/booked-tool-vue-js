<template>
<section class="discover-area">
  <div class="discover-part">
    <img class="img-discover" src="https://res.cloudinary.com/dulqd0xea/image/upload/v1609903357/Ice%20Message%20Indonesia/presentation_nezovw.png"/>
    <h1 class="title-discover-one">DISCOVER</h1>
    <p class="title-discover-two">BOOKED TOOL</p>
  </div>

  <div class="container-tab">
    <Tabs>
      <Tab name="Discover A" selected="true">
        <p class="text-tab">
          | Ciuman di pipi, ciuman di dahi, Apa yang dicium sesudah lah cinta?
          | Dua tiga kacang tanah, enggak ada pacar yang datang ke rumah.
          | Dapet kado isinya tomat, Bodo amat!!
          | Ke pasar, nyari obat gatal, Dasar, gak modal!
          | Dulu delman, sekarang gokar, dulu teman, sekarang pacar.
        </p>
      </Tab>
      <Tab name="Discover B">
        <p class="text-tab">
         | Mata belo, ala komedian.gue sama elo? maunya jadian.
         | Tunda lapar, makan indomi. hati menggelepar, cintapun bersemi.
         | Potong kuku, pendek-pendek. hatiku beku, si abang mendadak ngondek.
         | Beli ketan, beli kain songket. biar udah mantan, kita tetep lengket.
        </p>
      </Tab>
      <Tab name="Discover C">
        <p class="text-tab">
          | Makan semangka, makan kedondong. kalau suka, nyatain dong.
          | Ga punya pendirian, bikin jemu. ga mau sendirian, maunya bobo sama kamu.
          | Nembak itik, langsung kena. kamu cantik, hey nona!
          | Kotak amal, digoyang-goyang. kemarin aku diramal, jodohnya sama abang.
        </p>
      </Tab>
      <Tab name="Discover D">
        <p class="text-tab">
          | Buah semangka buah duren nggak nyangka gue keren
          | Jambu merah di dinding jangan marah just kidding
          | Buah semangka buah manggis nggak nyangka gue manis
          | Men sana in corpore sano gue maen ke sana, elo maen ke sono!
        </p>
      </Tab>
    </Tabs>
  </div>
</section>
</template>


<script>
import "../styles/Discover.scss"
import Tab from '@/components/Tab'
import Tabs from '@/components/Tabs'


export default {
    name: 'Discoversection',
    components: {
      Tab,
      Tabs
    }
  }



</script>