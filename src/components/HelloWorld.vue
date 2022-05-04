<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Tryk linket for at se min
      <a href="https://youtu.be/p4xbGPZ1sdI" target="_blank" rel="noopener">Præsentationsvideo</a>.
    </p>
    <h3>Om mig</h3>
    <h2>Hvem er jeg?</h2>
    <div>Navn: Pilunnguaq M. Poulsen, 37 år gammel, født og opvokset i Nuuk, Grønland.</div>
    <div>Gift med 3 børn på 5, 10 og 15 år</div>
    <div>Jeg er uddannet kontorassistent fra Handelsskolen Nuuk og nu er jeg igang med at studere mig som multimedidesigner på Erhvervsakademi Sydvest, Esbjerg.</div>
    <div>Jeg har lavet denne portfolio hjemmeside i forbindelse med mit uddannelse som multimediedesigner.</div>
    <div></div>
    <ul>
      <li><a href="https://drive.google.com/file/d/1TKwtaZa_kGvHVMUQR7jI8XGHuIdKhtHK/view?usp=sharing" target="_blank" rel="noopener">CV</a></li>
      <li><a href="https://drive.google.com/file/d/1FpvgT1NKzrDt0Y075JtRJ-Jiqrb6VW0g/view?usp=sharing" target="_blank" rel="noopener">Visitkort</a></li>
    </ul>
    <h2>Portfolio</h2>
    <h3></h3>
    <ul>
      <div class="row wow fadeInUp" style="visibility: visible; animation-name: fadeInUp;">
         <div class="col-md-4">
            <a href="BeatUpFace.vue">
              <div class="hovereffect">
                  <img class="img-responsive" src="https://drive.google.com/file/d/12twiryhbMMpQlo2sGAqyZY5P2VPhhG4R/view?usp=sharing" alt="BeatUpFace">
                  <div class="overlay">
                </div>
              </div>
                        </a>
                        <h2 class="work">
                    <a class="more" href="BeatUpFace.vue">Beat Up Face</a>
                </h2>
                        <h4>Photoshop</h4>
                        <p class="work">Fotoredigeringsopgave med Photoshop fra Erhvervsakademi Sydvest omkring Beat Up Face.</p>
                    </div>

                    <!-- Photoshopbillede -->

                    <div class="col-md-4">
                        <a href="Hybrid dyr.jpg">
                            <div class="hovereffect">
                                <img class="img-responsive" src="https://drive.google.com/file/d/12twiryhbMMpQlo2sGAqyZY5P2VPhhG4R/view?usp=sharing" alt="Hybrid dyr &amp; Photoshop.jpg">
                                <div class="overlay">
                                </div>
                            </div>
                        </a>
                        <h2 class="work">
                    <a class="more" href="Hybriddyr.vue">Hybrid &amp; Hybrid dyr</a>
                </h2>
                        <h4>Trapholt Logo</h4>
                        <p class="work">Logo Illustrator &amp; Erhvervsakademi Sydvest. projektopgave 1 semester</p>
                    </div>


                    <!-- Hybriddyr billede -->


          <div class="col-md-4">
             <a href="Trapholtlogo.vue">
                 <div class="hovereffect">
                   <img class="img-responsive" src="https://drive.google.com/file/d/1TNrEsC3Q8bf7_Pzxev05M_pe3hUzqYHr/view?usp=sharing" alt="Trapholtlogo">
                      <div class="overlay">
                          </div>
                     </div>
                   </a>
                <h2 class="work">
              <a class="more" href="Trapholtlogo.vue">Trapholt Logo</a>
          </h2>
            <h4>Min allerførste hjemmesidedesign</h4>
               <p class="work">Den overordne ide med "Siku Tolkeservice" er at give en nemmere kommunikation blandt danske og grønlandske borgere i Danmark.</p>
                 </div>
                 <div class="col-md-4">
             <a href="Trapholtlogo.vue">
                 <div class="hovereffect">
                   <img class="img-responsive" src="https://drive.google.com/file/d/1TNrEsC3Q8bf7_Pzxev05M_pe3hUzqYHr/view?usp=sharing" alt="Nørrebro brand">
                      <div class="overlay">
                          </div>
                     </div>
                   </a>
                <h2 class="work">
              <a class="more" href="Trapholtlogo.vue">Trapholt Logo</a>
          </h2>
            <h4>Min allerførste hjemmesidedesign</h4>
               <p class="work">Den overordne ide med "Siku Tolkeservice" er at give en nemmere kommunikation blandt danske og grønlandske borgere i Danmark.</p>
                 </div>
                 
              </div>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Min allerførste hjemmeside design</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Min første logodesign</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Beat Up Face</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Kontakt</h3>
    <div>Pilunnguaq M. Poulsen</div>
    <div>6715 Esbjerg N</div>
    <div>Danmark</div>
    <div>E-mail: pilunnguaqmp@gmail.com</div>
    <div>Hjemmeside: www.pilunnguaq.dk</div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
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
  color: #415c9f;
}
</style>
