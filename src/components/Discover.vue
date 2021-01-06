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
    <img class="img-discover-two" src="https://res.cloudinary.com/dulqd0xea/image/upload/v1609849445/Ice%20Message%20Indonesia/pexels-vito-gori%C4%8Dan-6253568_squkey.jpg"/>
        <p class="text-tab">
          | Ciuman di pipi, ciuman di dahi, Apa yang dicium sesudah lah cinta?
          | Dua tiga kacang tanah, enggak ada pacar yang datang ke rumah.
          | Dapet kado isinya tomat, Bodo amat!!
          | Ke pasar, nyari obat gatal, Dasar, gak modal!
          | Dulu delman, sekarang gokar, dulu teman, sekarang pacar.
        </p>
      </Tab>
      <Tab name="Discover B">
          <img class="img-discover-two" src="https://res.cloudinary.com/dulqd0xea/image/upload/v1609849431/Ice%20Message%20Indonesia/pexels-cottonbro-5076534_qegrzw.jpg"/>
        <p class="text-tab">
         | Mata belo, ala komedian.gue sama elo? maunya jadian.
         | Tunda lapar, makan indomi. hati menggelepar, cintapun bersemi.
         | Potong kuku, pendek-pendek. hatiku beku, si abang mendadak ngondek.
         | Beli ketan, beli kain songket. biar udah mantan, kita tetep lengket.
        </p>
      </Tab>
      <Tab name="Discover C">
          <img class="img-discover-two" src="https://res.cloudinary.com/dulqd0xea/image/upload/v1609849426/Ice%20Message%20Indonesia/pexels-kevin-ku-577585_vgioja.jpg"/>
        <p class="text-tab">
          | Makan semangka, makan kedondong. kalau suka, nyatain dong.
          | Ga punya pendirian, bikin jemu. ga mau sendirian, maunya bobo sama kamu.
          | Nembak itik, langsung kena. kamu cantik, hey nona!
          | Kotak amal, digoyang-goyang. kemarin aku diramal, jodohnya sama abang.
        </p>
      </Tab>
      <Tab name="Discover D">
          <img class="img-discover-two" src="https://res.cloudinary.com/dulqd0xea/image/upload/v1609849428/Ice%20Message%20Indonesia/pexels-cottonbro-5076530_q9lisn.jpg"/>
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