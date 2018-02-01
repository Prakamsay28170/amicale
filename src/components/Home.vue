<template>
  <div class="home">
    <div class="navHome">
      <el-row :gutter="0">
        <el-col :span="12" :offset="7">
          <el-tabs v-model="activeName" @tab-click="handleClick">

            <!-- Accueil -->

            <el-tab-pane label="Accueil" name="first">
              <div class="accueil">
                <el-row :gutter="24">
                  <el-col :span="24" :offset="0">
                    <p>L'association "Amicale de Fontaine les Ribouts" accueille aussi bien des habitants
                      de la<br>commune que des personnes ayant un lien d'amitié pour Fontaine les Ribouts.
                      <br><br>
                      Nous souhaitons rapprocher ses adhérents en les réunissant ponctuellement à l'occasion<br>
                      d'événements locaux ou extérieurs.<br>
                      <br>
                      Notez que l'association s'interdit toute discussion à caractère politique ou religieux.
                    </p>
                  </el-col>
                </el-row>
              </div>
              <el-row :gutter="24">
                <el-col :span="24" :offset="4">
                    <h4>Convialité, amitié et tolérance sont notre devise</h4>
                </el-col>
              </el-row>
              <div class="assemblée">
                <el-row :gutter="12">
                  <el-col :span="12" :offset="5">
                    <img src="../img/Pave_assembleegenerale_2018.jpg" alt="" width="300" height="230">
                    <!-- <el-upload action="https://jsonplaceholder.typicode.com/posts/" :on-preview="handlePictureCardPreview" :on-remove="handleRemove">
                      <img src="../img/Pave_assembleegenerale_2018.jpg" alt="" width="280" height="230">
                    </el-upload> -->
                    <!-- <el-dialog :visible.sync="dialogVisible" size="tiny">
                      <a href="OBbulletinassembléegénérale2018.pdf"></a>
                      <img width="100%" :src="dialogImageUrl" alt>
                    </el-dialog> -->
                  </el-col>
                  <!-- <div class="">
                    <object data="http://amicale/OBbulletinassembléegénérale2018.pdf.pdf" type="text/html" codetype="application/pdf" ></object>
                  </div> -->
                </el-row>
              </div>
              <div class="cartePro">
                <el-row :gutter="20">
                  <el-col :span="4" :offset="0">
                    <img src="../img/Menuiserie.jpg" alt="Mérot" width="190" height="130">
                  </el-col>
                  <el-col :span="3" :offset="3">
                    <img src="../img/Plombier.jpg" alt="Chabane" width="190" height="130">
                  </el-col>
                  <el-col :span="3" :offset="4">
                    <img src="../img/Pie.jpg" alt="Pie" width="190" height="130">
                  </el-col>
                </el-row>
                <el-row :gutter="0">
                  <div class="contact">
                  <el-col :span="12" :offset="4">
                    <h3>Association Amicale de Fontaine-les-Ribouts</h3>
                    <p>13, rue de l'Eglise<br>
                       28170 Fontaine-les-Ribouts<br>
                       Benoît Aubry<br>
                       Mobile: 06 50 07 42 22<br>
                       E-mail:<a href="mailto:">o.p.c.s@orange.fr</a><br>
                    </p>
                  </el-col>
                </div>
                </el-row>
              </div>
            </el-tab-pane>

            <!-- L'association -->

            <el-tab-pane label="L'association" name="second">
              <div class="association">
                <el-row :gutter="24">
                  <el-col :span="24" :offset="0">
                    <p>L'amicale de Fontaine les Ribouts a été créée à l'initiative de Monsieur Meray en 1971.<br><br>
                      L'association a pour object l'entreprise de toute activité de nature à rapprocher les adhérents<br>
                      entre eux, par tous les moyens licites, tels que réunions, conférences, fêtes, jeux etc.<br><br>
                      Pour être membre, il faut être résident sur la commune de Fontaine les Ribouts ou être parrainé<br>
                      par deux membres et être agréé par le Conseil d'Administration.<br><br>
                      En 2016, l'association comptait 137 adhérents auxquels s'ajoutent des amis participant<br> occasionnellement
                      à nos activités.<br><br>
                      Pour l'année 2017, la cotisation est restée inchangée à 8 € par personne.
                    </p>
                  </el-col>
                </el-row>
                <el-row :gutter="24">
                  <el-col :span="12" :offset="4">
                    <p><b>L'association a été présidée successivement par :</b></p>
                  </el-col>
                </el-row>
                <el-row :gutter="24">
                  <el-col :span="12" :offset="6">
                    <p><b>Maurice Méray :</b> de 1971 à 1976</p>
                    <p><b>Jean-Marie Pelé :</b> de 1977 à 1982</p>
                    <p><b>Joël Blin :</b> de 1983 à 1993<br>
                      (Association en sommeil de 1988 à 1993)</p>
                    <p><b>Jacky Gargasson :</b> de 1994 à 2004<br>
                      (Association en sommeil de 1996 à 2004)</p>
                    <p><b>Bernard Delefosse :</b> de 2005 à 2007</p>
                    <p><b>Pascal Stinat :</b> 2008</p>
                    <p><b>Francesca Mousseau : </b> de 2009 à 2011</p>
                    <p><b>Andrée Bientz :</b> de 2012 à 2015</p>
                    <p><b>Benoît Aubry</b> 2016</p>
                  </el-col>
                </el-row>
                <el-row :gutter="24">
                  <el-col :span="12" :offset="6">
                    <h3>Bureau élu le 22 janvier 2017</h3>
                  </el-col>
                </el-row>
                <el-row :gutter="24">
                  <el-col :span="6" :offset="2">
                    <p><b>Président</b><br>
                      Benoît Aubry<br>
                      <a href="mailto:">o.c.p.s@orange.fr</a>
                    </p>
                  </el-col>
                  <el-col :span="6" :offset="6">
                    <p><b>Vice-Présidente</b><br>
                      Céline Poupardin</p>
                  </el-col>
                </el-row>
                <el-row :gutter="24">
                  <el-col :span="6" :offset="2">
                    <p><b>Trésorière</b><br>
                      Nathalie Coulomb</p>
                  </el-col>
                  <el-col :span="6" :offset="6">
                    <p><b>Trésorière Adjointe</b><br>
                      Laurence Secrétain</p>
                  </el-col>
                </el-row>
                <el-row :gutter="24">
                  <el-col :span="6" :offset="2">
                    <p><b>Secrétaire</b><br>
                      Virgile Hibert<br>
                      <a href="mailto:">virgile28@gmail.com</a><br>
                      06 60 91 72 53
                    </p>
                  </el-col>
                  <el-col :span="6" :offset="6">
                    <p><b>Secrétaire Adjoint</b><br>
                      Pascal Stinat</p>
                  </el-col>
                </el-row>
              </div>
            </el-tab-pane>

            <!-- Activités -->

            <el-tab-pane label="Activités" name="third">
              <div class="activités">
                <el-row :gutter="24">
                  <el-col :span="24" :offset="3">
                    <h3>PLANNING PREVISIONNEL DES ACTIVITES 2017</h3>
                  </el-col>
                </el-row>
                <el-row :gutter="24">
                  <el-col :span="24" :offset="5">
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                    <p><b>Dimanche 22 Janvier</b> – Assemblée générale</p>
                  </el-col>
                </el-row>
              </div>
            </el-tab-pane>

            <!-- Reportages -->

            <el-tab-pane label="Reportages" name="fourth">
              <div class="carousel1">
                <el-row :gutter="24">
                  <el-col :span="15" :offset="2">
                    <el-carousel :interval="6000" type="card" height="200px">
                      <el-carousel-item>
                        <img src="../img/test.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/1.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/2.jpg" alt="" width="230" height="v">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/3.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/4.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                    </el-carousel>
                  </el-col>
                </el-row>
                <el-row :gutter="24">
                  <el-col :span="24" :offset="5">
                    <h3>Dimanche 7 mai 2017 - Randonnée à vélo</h3>
                  </el-col>
                </el-row>
                    <p>Malgré la météo exécrable de la veille, 4 cyclistes courageux ont pris le départ de la Mare de Boutry<br>
                      à 10 heures. Par bonheur, la météo de ce matin était plutôt bonne avec un vent léger, ce qui nous a permis<br> de parcourir 21 Km sur routes sèches.<br><br>
                    Prochaine randonnée le dimanche 4 Juin 2017 avec départ de la Mare de Boutry.</p>
                    <hr align=left width=79%>
              </div>
              <div class="carousel1">
                <el-row :gutter="24">
                  <el-col :span="15" :offset="2">
                    <el-carousel :interval="6000" type="card" height="200px">
                      <el-carousel-item>
                        <img src="../img/test.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/1.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/2.jpg" alt="" width="230" height="v">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/3.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/4.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                    </el-carousel>
                  </el-col>
                </el-row>
                <el-row :gutter="24">
                  <el-col :span="24" :offset="5">
                    <h3>Dimanche 30 Avril 2017 - Randonnée Pédestre</h3>
                  </el-col>
                </el-row>
                  <p>Bien qu’au matin la météo n’était pas vraiment encourageante, pas moins d’une trentaine de personnes se<br>
                    sont réunies devant la mairie pour notre traditionnelle randonnée du printemps. La promenade de presque<br>
                    3 heures à travers champs et forets s’est achevée dans la cour de la mairie.<br>
                    Les membres du bureau ont préparé eun barbecue servi bien entendu le verre de l’amitié.<br>C’est donc dans une ambiance chaleureuse et
                    joyeuse que s’est terminé ce traditionnel événement.</p>
                  <hr align=left width=79%>
              </div>
              <div class="carousel1">
                <el-row :gutter="24">
                  <el-col :span="15" :offset="2">
                    <el-carousel :interval="6000" type="card" height="200px">
                      <el-carousel-item>
                        <img src="../img/test.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/1.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/2.jpg" alt="" width="230" height="v">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/3.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/4.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                    </el-carousel>
                  </el-col>
                </el-row>
                <el-row :gutter="24">
                  <el-col :span="24" :offset="5">
                    <h3>Dimanche 7 mai 2017 - Randonnée à vélo</h3>
                  </el-col>
                </el-row>
                    <p>Malgré la météo exécrable de la veille, 4 cyclistes courageux ont pris le départ de la Mare de Boutry<br>
                      à 10 heures. Par bonheur, la météo de ce matin était plutôt bonne avec un vent léger, ce qui nous a permis<br> de parcourir 21 Km sur routes sèches.<br><br>
                    Prochaine randonnée le dimanche 4 Juin 2017 avec départ de la Mare de Boutry.</p>
                    <hr align=left width=79%>
              </div>
              <div class="carousel1">
                <el-row :gutter="24">
                  <el-col :span="15" :offset="2">
                    <el-carousel :interval="6000" type="card" height="200px">
                      <el-carousel-item>
                        <img src="../img/test.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/1.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/2.jpg" alt="" width="230" height="v">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/3.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                      <el-carousel-item>
                        <img src="../img/4.jpg" alt="" width="230" height="210">
                      </el-carousel-item>
                    </el-carousel>
                  </el-col>
                </el-row>
                <el-row :gutter="24">
                  <el-col :span="24" :offset="5">
                    <h3>Dimanche 30 Avril 2017 - Randonnée Pédestre</h3>
                  </el-col>
                </el-row>
                  <p>Bien qu’au matin la météo n’était pas vraiment encourageante, pas moins d’une trentaine de personnes se<br>
                    sont réunies devant la mairie pour notre traditionnelle randonnée du printemps. La promenade de presque<br>
                    3 heures à travers champs et forets s’est achevée dans la cour de la mairie.<br>
                    Les membres du bureau ont préparé eun barbecue servi bien entendu le verre de l’amitié.<br>C’est donc dans une ambiance chaleureuse et
                    joyeuse que s’est terminé ce traditionnel événement.</p>
                  <hr align=left width=79%>
              </div>
                <el-row :gutter="24">
                  <el-col :span="24" :offset="2">
                    <h2>ASSEMBLÉE GÉNÉRALE DU 22 janvier 2017</h2>
                  </el-col>
                </el-row>
                <el-row :gutter="24">
                  <el-col :span="24" :offset="6">
                    <img src="../img/3.jpg" alt="" width="180" height="200">
                  </el-col>
                </el-row>
              <div class="assembléeText">
                <el-row :gutter="24">
                  <el-col :span="24">
                    <p>Le Président, Monsieur AUBRY Benoît a ouvert cette assemblée en souhaitant une très bonne année 2017<br>
                    aux membres présents de l’amicale.<br><br>
                    Des remerciements ont été adressés à la municipalité de Fontaine-les-Ribouts pour sa subvention,
                    aux municipalités<br>de Saulnières et Saint Ange-et-Torcay pour le prêt de leurs salles polyvalentes, à
                    l’Association Saulnières Loisirs pour<br> le prêt de divers matériels et à toutes les personnes qui ont
                    contribué à préparer les manifestations de l’Amicale tout<br> au long de l’année.<br><br>
                    Les membres du bureau sont intervenus pour relater les différentes activités organisées par l’association sur
                    l’année 2016.<br><br>
                    Notre trésorière, Mme Nathalie Coulomb a présenté le compte des résultats et le bilan comptable 2016-2017 qui ont<br>
                     été approuvés à l’unanimité.
                    Les détails de ces comptes sont à la disposition des membres de l'association.<br><br><br>
                    Élection du Conseil d’administration :<br><br>
                    Benoît AUBRY - Nathalie COULOMB - Philippe GEORGET - Virgile HIBERT -Laurence SECRETAIN - Céline POUPARDIN -<br>
                    Pascal STINAT - Elodie ALVAREZ - Marco VIFIAN - Medhi GENTILS - Bernard PELLETIER.<br><br><br>
                    Élection du bureau :<br><br>
                    Le vote a eu lieu à main levée et n’a enregistré aucune opposition.<br>
                    Président : Benoît Aubry<br>
                    Vice-président : Céline Poupardin<br>
                    Trésorier : Nathalie Coulomb<br>
                    Trésorier Adjoint : Laurence Secretain<br>
                    Secrétaire : Virgile Hibert<br>
                    Secrétaire Adjoint : Pascal Stinat<br><br><br>
                    Après concertation, la cotisation pour l’année 2017 est fixée à 8 €.<br>

                    S’en est suivi, le traditionnel tirage au sort pour des lots consistant en bons d’achat allant de 15 € à 60 € réservés exclusivement aux membres
                    présents et à jour de leurs cotisations 2016.<br>

                    L’ordre du jour étant épuisé, la Présidente leva la séance en invitant toute l‘assemblée à déguster la galette des rois
                    devant le verre de l’amitié.
                    </p>
                  </el-col>
                </el-row>
              </div>
            </el-tab-pane>
            <el-tab-pane label="Archives" name="fifth">
              <!-- <router-link :to="{name: 'archives2016'}">
              <el-button plain>Archives 2016</el-button>
              </router-link> -->
              <!-- <Archives2016/> -->
              <el-row :gutter="24">
                <el-col :span="24" :offset="2">
              <el-tabs v-model="activeName1" @tab-click="handleClick1">
                <el-tab-pane label="2013" name="first">
                  <Archives2013/>
                </el-tab-pane>
                <el-tab-pane label="2014" name="second">
                  <Archives2014/>
                </el-tab-pane>
                <el-tab-pane label="2015" name="third">
                  <Archives2015/>
                </el-tab-pane>
                <el-tab-pane label="2016" name="fourth">
                  <Archives2016/>
                </el-tab-pane>
                <el-tab-pane label="2017" name="fifth">
                  <Archives2017/>
                </el-tab-pane>
                <el-tab-pane label="2018" name="sixth">
                  <Archives2018/>
                </el-tab-pane>
              </el-tabs>
            </el-col>
            </el-row>
            </el-tab-pane>
            <!-- <el-tab-pane label="Contact" name="sixth">Task</el-tab-pane>
            <el-tab-pane label="Liens Favoris" name="seventh">Task</el-tab-pane> -->
          </el-tabs>
        </el-col>
      </el-row>
    </div>
    <FooterAmicale/>
  </div>
</template>

<script>
import Archives2013 from '../components/Archives2013.vue'
import Archives2014 from '../components/Archives2014.vue'
import Archives2015 from '../components/Archives2015.vue'
import Archives2016 from '../components/Archives2016.vue'
import Archives2017 from '../components/Archives2017.vue'
import Archives2018 from '../components/Archives2018.vue'
import FooterAmicale from '../components/FooterAmicale.vue'
export default {
  name: 'Home',
  components: {
    Archives2013,
    Archives2014,
    Archives2015,
    Archives2016,
    Archives2017,
    Archives2018,
    FooterAmicale
  },
  data () {
    return {
      activeName: 'first',
      activeName1: 'first',
      dialogImageUrl: '',
      dialogVisible: false
      // msg: 'Welcome to Your Vue.js App corentin'
    }
  },
  methods: {
    handleClick (tab, event) {
      console.log(tab, event)
    },
    handleClick1 (tab, event) {
      console.log(tab, event)
    },
    handleRemove (file, fileList) {
      console.log(file, fileList)
    },
    handlePictureCardPreview (file) {
      this.dialogImageUrl = file.url
      this.dialogVisible = true
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.navHome {
  padding-top: 30px;
}
.el-tab-pane {
  font-size: 15px;
  text-align: left;
}
.el-tabs__item {
  font-size: 20px;
}
.el-tabs__nav-wrap::after {
  width: 0px;;
}
/*h4, h3 {
  text-align: center;
}*/
.assemblée img {
  padding-bottom: 15px;
}
.assembléeText {
  padding-bottom: 10px;
  font-size: 12px;
}
.cartePro img {
}
.contact h3 p {
  text-align: center;
}
.association p {
  text-align: left;
}
.activités p {
  text-align: left;
}
.carousel1 {
  font-size: 12px;
  padding-top: 10px;
}
.carousel1 h3 {
  padding-top: 0px;
}
.carousel1 p {
  padding-top: 0px;
  padding-bottom: 10px;
}
.el-carousel__item h3 {
  color: #475669;
  font-size: 14px;
  opacity: 0.75;
  line-height: 200px;
  margin: 0;
}
.el-carousel__item:nth-child(2n) {
  background-color: #99a9bf;
}
.el-carousel__item:nth-child(2n+1) {
  background-color: #d3dce6;
}
.el-carousel__indicator {
  width: 0px; height: 0px;
}
.el-carousel__indicators--outside button {
  width: 0px; height: 0px;
}
/*h1, h2 {
  font-weight: normal;
}*/
/*ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}*/
</style>
