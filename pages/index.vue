<template>
  <v-app class="darken-3" :dark="theme==0 ? true : false">
    <v-content>
      <v-container id="main-container">
        
        <v-layout wrap>
          <v-flex xs12 sm12 class="pa-2">
            
            <v-card>
              <v-card-text>
                <v-layout wrap>
                  <v-flex xs12 sm3>
                    <div style="display: flex;
                                flex-wrap: nowrap;
                                align-content: center;
                                justify-content: center;
                                align-items: center;">
                      <!-- <img style="max-width: 158px; margin-top: -12px; margin-left: -11px;" src="profil.jpg" alt="photo-profil-gorce-pierre"> -->
                    <img style="width: 60%;" src="~/assets/profil.jpg" />
                      <!-- <v-img contain src="/assets/profil.jpg" aspect-ratio="1.6">
                        <template v-slot:placeholder>
                          <v-layout fill-height align-center justify-center ma-0>
                            <v-progress-circular indeterminate color="grey lighten-5"></v-progress-circular>
                          </v-layout>
                        </template>
                      </v-img> -->
                    </div>
                    <div class="hidden-print" style="text-align: right; position:absolute; top : 0px">
                      <v-btn flat icon small @click="theme==0 ? theme=1 : theme=0">
                        <div v-if="theme==0">
                          <v-icon small>brightness_5</v-icon>
                        </div>
                        <div v-if="theme==1">
                          <v-icon small>brightness_2</v-icon>
                        </div>
                      </v-btn>
                    </div>
                  </v-flex>
                  <v-flex xs12 sm8 pl-3>

                    <h2>Marion ACETO</h2>
                    <div class="green" style="height:10px"></div>

                  <v-layout wrap pt-3 pr-3>
                    <v-flex xs12 sm4>
                    <div>
                      <v-icon left>mail</v-icon>
                      <span>marion.aceto@gmail.com</span>
                    </div>
                    <div>
                      <v-icon left>directions_car</v-icon>
                      <span>Permis B</span>
                    </div>
                    <div>
                      <v-icon left>cake</v-icon>
                      <span>N??e le 17/05/1990</span>
                    </div>
                  </v-flex>
                  <v-flex xs12 sm4 pr-3 style="overflow:hidden;">

                      <v-layout wrap>
                        <v-flex xs1>
                          <v-icon left>home</v-icon>
                        </v-flex>
                        <v-flex xs11 pl-3>
                      <!-- <span>900 avenue de la Pompignane<br/>
                            Batiment 7<br/>
                            34000 Montpellier<br/>
                      </span> -->
                      <span>38 Chemin de Pr??le<br/>
                            07800 Saint Georges les Bains<br/>
                      </span>
                        </v-flex>
                      </v-layout>
                      
                  </v-flex>
                  <v-flex xs12 sm4 style="overflow:hidden;">
                    <div>
                      <v-icon>format_quote</v-icon>
                      <i>
                        <b>
                          En recherche d'un emploi administratif dans les secteurs du commerce et/ou de la logistique
                        </b>
                      </i>
                    </div>
                  </v-flex>
                  </v-layout>

                  </v-flex>

                </v-layout>
              </v-card-text>
            </v-card>

          </v-flex>

          <v-flex xs12 sm12 class="pa-2">
            <v-card>
              <v-card-text>
                

<v-icon  style="font-size:50px">format_quote</v-icon> 

<span style="font-size:15px; line-height:26px;">
Le sourire, le sens de l'??coute et mes capacit??s d'adaptations font partie de mes qualit??s. 
Je recherche un poste administratif dans les secteurs du commerce et/ou de la logistique, dans lequel je pourrai apporter ma polyvalence et mes comp??tences.
J'aime ce cot?? "couteau-suisse" qui me qualifie, je souhaiterai le conserver et l'enrichir dans ma prochaine aventure professionnelle. 
Pourquoi pas au sein de votre ??quipe !
</span>



              </v-card-text>
            </v-card>
          </v-flex>


          <v-flex xs12 sm8>
            <div class="pa-2">
              <v-card>
                <v-card-text>
                  <h2 class="mb-2">
                    <v-icon left>work</v-icon>Exp??riences
                  </h2>

                  <v-layout wrap>

                    <v-flex xs2>
                      <div class="timeline">
                        <h3 class="timeline-date hidden-sm-and-down">depuis 2021</h3>
                        <div class="timeline-point"></div>
                      </div>
                    </v-flex>
                    <v-flex xs10>
                      <h3 class="timeline-date text-xs-center hidden-md-and-up hidden-print">depuis 2021</h3>
                      <v-card flat class="cv-card">
                        <div class="cv-card triangle"></div>
                        <v-card-text>
                          <h3>Responsable Service SAV & Administratif des ventes BtoB</h3>

                          <v-layout wrap>
                            <v-flex xs12 sm12>
                            <div class="pa-0">
                            <v-icon>chevron_right</v-icon>
                            <b>Co-Responsable service SAV (soci??t?? Antin??a)</b>
                            <div class="pl-4">
                              <v-icon small>arrow_right</v-icon>
                              Gestion mails  / Standard t??l??phonique
                            </div>
                            <div class="pl-4">
                              <v-icon small>arrow_right</v-icon>
                              Gestion litiges transporteurs et clients
                            </div>
                            <div class="pl-4">
                              <v-icon small>arrow_right</v-icon>
                              Gestion SAV clients et fournisseurs
                            </div>
                             <div class="pl-4">
                              <v-icon small>arrow_right</v-icon>
                              Logistique / V??rification des stocks
                            </div>
                            <div class="pl-4">
                              <v-icon small>arrow_right</v-icon>
                              Communication inter-services
                            </div>
                             <div class="pl-4">
                              <v-icon small>arrow_right</v-icon>
                              Mise en place de proc??dures de prise en charge de litiges en vue d???un usage interne
                            </div>
                          </div>
                            </v-flex>

                          <br>

                             <v-flex xs12 sm12 class="mt-2">
                          <div class="pa-0">
                            <div class="pa-0">
                              <v-icon>chevron_right</v-icon>
                              <b>Administratif des ventes / Entretien client??le (soci??t?? Atothis)</b>
                            </div>
                            <div class="pl-4">
                                <v-icon small>arrow_right</v-icon>
                                Gestion mails / Standard t??l??phonique
                            </div>
                            <div class="pl-4">
                                <v-icon small>arrow_right</v-icon>
                                Traitement des commandes et facturation
                            </div>
                            <div class="pl-4">
                                <v-icon small>arrow_right</v-icon>
                                Recouvrement en lien avec le service comptabilit??
                            </div>
                          </div>
                            </v-flex>
                          </v-layout>

                          <br>

                          <div class="pt-2 text-color-red">
                            <i>
                              <v-icon small>build</v-icon>Sage (ERP) & CPA (CRM passerelle Sage), Wavesoft (ERP & CRM), Excel, Outlook, Word, Powerpoint
                            </i>
                          </div>

                          <div class="pt-2">
                            <i>
                              <b><v-icon small>store</v-icon>Groupe Antin??a : Soci??t??s Atothis et Antin??a / <v-icon small>room</v-icon>Montpellier (34)</b>
                            </i>
                          </div>
                        </v-card-text>
                      </v-card>
                    </v-flex>

                    <v-flex xs12>
                      <v-layout>
                        <v-flex xs2>
                          <div class="timeline">
                            <div class="pt-3"></div>
                          </div>
                        </v-flex>
                        <v-flex xs10></v-flex>
                      </v-layout>
                    </v-flex>

                    <v-flex xs2>
                      <div class="timeline">
                        <h3 class="timeline-date hidden-sm-and-down">2019-2021</h3>
                        <div class="timeline-point"></div>
                      </div>
                    </v-flex>
                    <v-flex xs10>
                      <h3 class="timeline-date text-xs-center hidden-md-and-up hidden-print">2019-2021</h3>
                      <v-card flat class="cv-card">
                        <div class="cv-card triangle"></div>
                        <v-card-text>
                          <h3>Caviste</h3>
                          <div class="pa-0">
                            <v-icon>chevron_right</v-icon>Encaissement, conseils clients, service bar
                          </div>
                          <div class="pa-0">
                            <v-icon>chevron_right</v-icon>Organisation, conduite d???ateliers de d??couverte et d'initiation ?? la bi??re
                          </div>
                          <div class="pa-0">
                            <v-icon>chevron_right</v-icon>D??veloppement rayon bi??re craft, contact commercial d??veloppement de relations avec des partenaires locaux
                          </div>
                          <div class="pa-0">
                            <v-icon>chevron_right</v-icon>Gestion des stocks (bon de livraison, commandes, r??ception fournisseurs)
                          </div>
                          <div class="pt-2 text-color-red">
                            <i>
                              <v-icon small>build</v-icon>Excel, Gmail, Powerpoint, Logiciels internes V&B (caisse, stock, commande, facturation), R??seaux-sociaux
                            </i>
                          </div>

                          <div class="pt-2">
                            <i>
                              <b><v-icon small>store</v-icon>SAS K&S V and B / <v-icon small>room</v-icon>Le Cr??s (34)</b>
                            </i>
                          </div>
                        </v-card-text>
                      </v-card>
                    </v-flex>

                    <v-flex xs12>
                      <v-layout>
                        <v-flex xs2>
                          <div class="timeline">
                            <div class="pt-3"></div>
                          </div>
                        </v-flex>
                        <v-flex xs10></v-flex>
                      </v-layout>
                    </v-flex>

                    <v-flex xs2>
                      <div class="timeline">
                        <!-- <h3 class="timeline-date hidden-sm-and-down">2015-2018</h3> -->
                        <h3 class="timeline-date hidden-sm-and-down">2012-2019</h3>
                        <div class="timeline-point"></div>
                      </div>
                    </v-flex>
                    <v-flex xs10>
                      <!-- <h3 class="timeline-date text-xs-center hidden-md-and-up">2015-2018</h3> -->
                      <h3 class="timeline-date text-xs-center hidden-md-and-up hidden-print">2012-2019</h3>
                      <v-card flat class="cv-card">
                        <div class="cv-card triangle"></div>
                        <v-card-text>
                        <h3>Responsable Boutique</h3>
                          <div class="pa-0">
                            <v-icon>chevron_right</v-icon>Organisation de l'??v??nementiel (visite brasserie, soir??e ?? th??me), communication sur les r??seaux sociaux (facebook et instagram), 
                            gestion de newsletters et animation d???un blog.
                          </div>
                          <div class="pa-0">
                            <v-icon>chevron_right</v-icon>Aide commerciale
                          </div>
                          <div class="pa-0">
                            <v-icon>chevron_right</v-icon>Logistique des commandes / facturation
                          </div>
                          <div class="pa-0">
                            <v-icon>chevron_right</v-icon>Responsable qualit?? produit (analyses, proc??dures)
                          </div>
                          <div class="pa-0">
                            <v-icon>chevron_right</v-icon>Participation ?? la production, brassin, mise en bouteille
                          </div>
                          <div class="pt-2 text-color-red">
                            <i>
                              <v-icon small>build</v-icon>Wavesoft (ERP & CRM), Excel, Gmail, Logiciel de caisse, YLMP, Mail Chimp, R??seaux-sociaux
                            </i>
                          </div>
                          <div class="pt-2">
                            <i>
                              <b><v-icon small>store</v-icon>Brasserie Artisanale du Dauphin?? (Mandrin), SARL Alpes Bi??re / <v-icon small>room</v-icon>Grenoble (38)</b>
                            </i>
                          </div>
                        </v-card-text>
                      </v-card>
                    </v-flex>

                    <v-flex xs12>
                      <v-layout>
                        <v-flex xs2>
                          <div class="timeline">
                            <div class="pt-3"></div>
                          </div>
                        </v-flex>
                        <v-flex xs10></v-flex>
                      </v-layout>
                    </v-flex>

                    <v-flex xs2>
                      <div class="timeline">
                        <!-- <h3 class="timeline-date hidden-sm-and-down">2015-2018</h3> -->
                        <h3 class="timeline-date hidden-sm-and-down">2012</h3>
                        <div class="timeline-point"></div>
                      </div>
                    </v-flex>
                    <v-flex xs10>
                      <!-- <h3 class="timeline-date text-xs-center hidden-md-and-up">2015-2018</h3> -->
                      <h3 class="timeline-date text-xs-center hidden-md-and-up hidden-print">2012</h3>
                      <v-card flat class="cv-card">
                        <div class="cv-card triangle"></div>
                        <v-card-text>
                        <h3>Technicienne de laboratoire</h3>
                          <div class="pa-0">
                            <v-icon>chevron_right</v-icon>Pr??paration de solution m??re en vue d'analyses microbiologiques sur des produits alimentaires
                          </div>
                          <div class="pt-2">
                            <i>
                              <b><v-icon small>store</v-icon> Silliker / <v-icon small>room</v-icon>Grenoble (38)</b>
                            </i>
                          </div>
                        </v-card-text>
                      </v-card>
                    </v-flex>

                    <v-flex xs12>
                      <v-layout>
                        <v-flex xs2>
                          <div class="timeline">
                            <div class="pt-3"></div>
                          </div>
                        </v-flex>
                        <v-flex xs10></v-flex>
                      </v-layout>
                    </v-flex>

                    <v-flex xs2>
                      <div class="timeline">
                        <!-- <h3 class="timeline-date hidden-sm-and-down">2015-2018</h3> -->
                        <h3 class="timeline-date hidden-sm-and-down">2011</h3>
                        <div class="timeline-point"></div>
                      </div>
                    </v-flex>
                    <v-flex xs10>
                      <!-- <h3 class="timeline-date text-xs-center hidden-md-and-up">2015-2018</h3> -->
                      <h3 class="timeline-date text-xs-center hidden-md-and-up hidden-print">2011</h3>
                      <v-card flat class="cv-card">
                        <div class="cv-card triangle"></div>
                        <v-card-text>
                        <h3>Agent des Services Hospitaliers</h3>
                          <div class="pa-0">
                            <v-icon>chevron_right</v-icon>Succession de plusieurs CDD
                          </div>
                          <div class="pa-0">
                            <v-icon>chevron_right</v-icon>Brancardi??re
                          </div>
                          <div class="pa-0">
                            <v-icon>chevron_right</v-icon>Distribution des repas - M??nage aux ??tages et aux blocs op??ratoires
                          </div>
                          <div class="pt-2">
                            <i>
                              <b><v-icon small>store</v-icon> Clinique Belledonne /<v-icon small>room</v-icon>Grenoble (38)</b>
                            </i>
                          </div>
                        </v-card-text>
                      </v-card>
                    </v-flex>

                    <v-flex xs12>
                      <v-layout>
                        <v-flex xs2>
                          <div class="timeline">
                            <div class="pt-3"></div>
                          </div>
                        </v-flex>
                        <v-flex xs10></v-flex>
                      </v-layout>
                    </v-flex>

                  </v-layout>
                </v-card-text>
              </v-card>
            </div>
          </v-flex>

          <v-flex xs12 sm4>
            <v-layout wrap>
 
          <v-flex xs12 sm12>

            <div class="pa-2">
              <v-card>

                <v-card-text>
                  <h3>
                    <v-icon left>computer</v-icon>Informatique
                  </h3>
                    <v-chip label>Wavesoft (ERP & CRM)</v-chip>
                    <v-chip label>SAGE (ERP & CRM)</v-chip>
                    <v-chip label>YLMP (newsletter)</v-chip>
                    <v-chip label>Mail Chimp (newsletter)</v-chip>
                    <v-chip label>Office (Word, Excel, Powerpoint, Outlook)</v-chip>
                </v-card-text>

                <v-card-text>
                  <h3>
                    <v-icon left>extension</v-icon>Autres
                  </h3>

                  <div>
                    <v-chip label>Bonne maitrise de l'anglais</v-chip>
                    <v-chip label>Consciencieuse</v-chip>
                    <v-chip label>Responsable</v-chip>
                    <v-chip label>Optimiste</v-chip>
                    <v-chip label>Curieuse</v-chip>
                    <v-chip label>Bonne communication</v-chip>
                  </div>
                </v-card-text>
              </v-card>
            </div>

            <div class="pa-2">
              <v-card>
                <v-card-text>
                  <h2 class="mb-2">
                    <v-icon left>account_balance</v-icon>Formation
                  </h2>
                  <v-layout wrap>

                    <v-flex md6 sm12 xs12 pa-2 class="timeline-horizontal">
                      <h3 class="text-xs-center mb-1">2009</h3>
                      <div class="timeline-point"></div>
                      <v-card flat class="cv-card">
                        <v-card-text>
                          <h3 class="text-xs-center">BAC</h3>
                          <div class="pa-3">Baccalaur??at Sciences et Technologies de l???Agronomie et du Vivant Option am??nagement de l???espace
                            <br>
                            <br>
                            <i>
                              <b>Lyc??e Horticole de Saint Ismier /
                                <br>
                               <v-icon small>room</v-icon>Saint Ismier (38)</b>
                            </i>
                            </div>
                        </v-card-text>
                      </v-card>
                    </v-flex>

                    <v-flex md6 sm12 xs12 pa-2 class="timeline-horizontal">
                      <h3 class="text-xs-center mb-1">2011</h3>
                      <div class="timeline-point"></div>
                      <v-card flat class="cv-card">
                        <v-card-text>
                          <h3 class="text-xs-center">BAC +2 </h3>
                          <div class="pa-3">
                            BTS Sciences et Technologies de l???Aliment
                            <br>
                            <br>
                            <i>
                              <b>Lyc??e du Valentin /
                                <br> 
                                <v-icon small>room</v-icon>Bourg-l??s-Valence (26)</b>
                            </i>

                          </div>
                        </v-card-text>
                      </v-card>
                    </v-flex>

              
                  </v-layout>
                </v-card-text>

                <v-card-text style="display:none;">
                  <v-layout wrap>
                    <v-flex xs3>
                      <div class="timeline">
                        <!-- <h3 class="pt-4 pr-3">2014 - 2015</h3> -->
                        <h3 class="pt-4 pr-3">2014</h3>
                        <div class="timeline-point"></div>
                      </div>
                    </v-flex>
                    <v-flex xs9>
                      <v-card flat class="cv-card">
                        <div class="cv-card triangle"></div>
                        <v-card-text>
                          <h3>BAC+4</h3>
                          <div class="pa-0">Concepteur-d??veloppeur informatique Option J2EE - AFPA - Pont de Claix (38)</div>
                        </v-card-text>
                      </v-card>
                    </v-flex>

                    <v-flex xs12>
                      <v-layout>
                        <v-flex xs3>
                          <div class="timeline">
                            <div class="pt-3"></div>
                          </div>
                        </v-flex>
                        <v-flex xs9></v-flex>
                      </v-layout>
                    </v-flex>
                  </v-layout>

                  <v-layout wrap>
                    <v-flex xs3>
                      <div class="timeline">
                        <h3 class="pt-4 pr-3 study-year">2010 - 2011</h3>
                        <div class="timeline-point"></div>
                      </div>
                    </v-flex>
                    <v-flex xs9>
                      <v-card flat color="cv-card">
                        <div class="cv-card triangle"></div>
                        <v-card-text>
                          <h3>BAC+3</h3>
                          <div class="pa-0">Licence Professionnelle Charg?? d???Affaires en G??nie Climatique - Mention AB - Universit?? Blaise Pascal - Montlu??on (03)</div>
                        </v-card-text>
                      </v-card>
                    </v-flex>

                    <v-flex xs12>
                      <v-layout>
                        <v-flex xs3>
                          <div class="timeline">
                            <div class="pt-3"></div>
                          </div>
                        </v-flex>
                        <v-flex xs9></v-flex>
                      </v-layout>
                    </v-flex>
                  </v-layout>

                  <v-layout wrap>
                    <v-flex xs3>
                      <div class="timeline">
                        <h3 class="pt-4 pr-3 study-year">2008 - 2010</h3>
                        <div class="timeline-point"></div>
                      </div>
                    </v-flex>
                    <v-flex xs9>
                      <v-card flat class="cv-card">
                        <div class="cv-card triangle"></div>
                        <v-card-text>
                          <h3>BAC+2</h3>
                          <div class="pa-0">DUT G??nie Thermique et Energie - Universit?? Joseph Fourier - Grenoble (38)</div>
                        </v-card-text>
                      </v-card>
                    </v-flex>

                    <v-flex xs12>
                      <v-layout>
                        <v-flex xs3>
                          <div class="timeline">
                            <div class="pt-3"></div>
                          </div>
                        </v-flex>
                        <v-flex xs9></v-flex>
                      </v-layout>
                    </v-flex>
                  </v-layout>

                  <v-layout wrap>
                    <v-flex xs3>
                      <div class="timeline">
                        <h3 class="pt-4 pr-3 study-year">2007 - 2008</h3>
                        <div class="timeline-point"></div>
                      </div>
                    </v-flex>
                    <v-flex xs9>
                      <v-card flat class="cv-card">
                        <div class="cv-card triangle"></div>
                        <v-card-text>
                          <h3>Classe Pr??paratoire</h3>
                          <div class="pa-0">Classe pr??paratoire ??cole d'ing??nieur (E.S.I.S.A.R) - Valence (26)</div>
                        </v-card-text>
                      </v-card>
                    </v-flex>

                    <v-flex xs12>
                      <v-layout>
                        <v-flex xs3>
                          <div class="timeline">
                            <div class="pt-3"></div>
                          </div>
                        </v-flex>
                        <v-flex xs9></v-flex>
                      </v-layout>
                    </v-flex>
                  </v-layout>

                  <v-layout wrap>
                    <v-flex xs3>
                      <div class="timeline">
                        <h3 class="pt-4 pr-3 study-year">2006 - 2007</h3>
                        <div class="timeline-point"></div>
                      </div>
                    </v-flex>
                    <v-flex xs9>
                      <v-card flat class="cv-card">
                        <div class="cv-card triangle"></div>
                        <v-card-text>
                          <h3>BAC</h3>
                          <div class="pa-0">Baccalaur??at G??n??ral S??rie S - Mention AB - Privas (07)</div>
                        </v-card-text>
                      </v-card>
                    </v-flex>

                    <v-flex xs12>
                      <v-layout>
                        <v-flex xs3>
                          <div class="timeline">
                            <div class="pt-3"></div>
                          </div>
                        </v-flex>
                        <v-flex xs9></v-flex>
                      </v-layout>
                    </v-flex>
                  </v-layout>
                </v-card-text>
              </v-card>
            </div>

          </v-flex>

          <v-flex xs12 sm12>
            <div class="pa-2">
              <v-card>
                <v-card-text>
                  <h2>
                    <v-icon left>terrain</v-icon>Loisirs
                  </h2>
                </v-card-text>
                <v-card-text>
                  <div class="text-xs-center">
                    <div class="tags">
                      <div class="tag" style="bottom:140px; left:10px">
                        <v-avatar v-ripple color="transparent" size="100" style="background-color: rgba(101, 193, 120, 0.9)  !important; cursor: pointer;">
                          <div>
                            <div>
                              <v-icon>directions_run</v-icon>
                            </div>
                            <h4><b>RANDONNEE</b></h4>
                          </div>
                        </v-avatar>
                      </div>

                      <div class="tag" style="bottom:150px; left:110px">
                        <v-avatar v-ripple color="transparent" size="100" style="background-color: rgba(0, 191, 221, 0.9) !important; cursor: pointer;">
                          <div>
                            <div>
                              <v-icon>local_florist</v-icon>
                            </div>
                            <h3>JARDINAGE</h3>
                          </div>
                        </v-avatar>
                      </div>

                      <div class="tag" style="bottom:95px; left:80px">
                        <v-avatar v-ripple color="transparent" size="80" style="background-color: rgba(197, 214, 54, 0.8) !important; cursor: pointer;">
                          <div>
                            <div>
                              <v-icon>restaurant_menu</v-icon>
                            </div>
                            <h3>CUISINE</h3>
                          </div>
                        </v-avatar>
                      </div>

                      <div class="tag" style="bottom:80px; left:150px">
                        <v-avatar v-ripple color="transparent" size="80" style="background-color: rgba(1, 0, 0, 0.4) !important; cursor: pointer;">
                          <div>
                            <div>
                              <v-icon>elderly_woman</v-icon>
                            </div>
                            <h3>COUTURE</h3>
                          </div>
                        </v-avatar>
                      </div>

                      <div class="tag" style="bottom:170px; left:190px">
                        <v-avatar v-ripple color="transparent" size="120" style="background-color: rgba(149, 151, 255, 0.9) !important; cursor: pointer;">
                          <div>
                            <div>
                              <v-icon>palette</v-icon>
                            </div>
                            <h3>AQUARELLE</h3>
                          </div>
                        </v-avatar>
                      </div>
                      <div class="tag" style="bottom:120px; left:230px">
                        <v-avatar v-ripple color="transparent" size="80" style="background-color: rgba(24, 217, 163, 0.7) !important; cursor: pointer;">
                          <div>
                            <div>
                              <v-icon>sailing</v-icon>
                            </div>
                            <h3>VOYAGE</h3>
                          </div>
                        </v-avatar>
                      </div>
                    </div>
                  </div>
                </v-card-text>
              </v-card>
            </div>
          </v-flex>

            </v-layout>
          </v-flex>

          

        </v-layout>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {
  components: {},
  data: function () {
    return {
      theme: 1
    }
  },
  created: function () { },

  methods: {
    getRandomPosition: function (size) {
      var left = Math.round(Math.random() * 500);
      var top = Math.round(Math.random() * 500);

      return {
        top: top / 2,
        left: left / 2
      };
    }
  }
};
</script>

<style lang="scss">
</style>