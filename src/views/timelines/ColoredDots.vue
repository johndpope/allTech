<template>
   <div class="hover-wrapper colored-dots-wrapper">
      <page-title-bar></page-title-bar>
      <v-container custom-flex grid-list-xl pt-0>
         <v-layout row wrap>
            <app-card
               colClasses="xl12 lg12 md12 sm12 xs12"
            >
               <div class="mb-4">
                  <p>Colors dots create visual breakpoints that make your timelines easier to read.</p>
               </div>
               <v-card
                  class="mx-auto"
                  max-width="400"
               >
                  <v-card
                     flat
                     class="white--text"
                  >
                     <v-btn
                        absolute
                        bottom
                        color="pink"
                        right
                        fab
                     >
                       <v-icon class="white--text">mdi-plus</v-icon>
                     </v-btn>
                     <v-card-title class="pa-2 purple lighten-3">
                        <v-btn icon>
                          <v-icon class="white--text">mdi-menu</v-icon>
                        </v-btn>
                        <h3 class="title font-weight-light text-xs-center grow">Timeline</h3>
                        <v-avatar>
                           <v-img src="https://avataaars.io/?avatarStyle=Circle&topType=LongHairStraight&accessoriesType=Blank&hairColor=BrownDark&facialHairType=Blank&clotheType=BlazerShirt&eyeType=Default&eyebrowType=Default&mouthType=Default&skinColor=Light"></v-img>
                        </v-avatar>
                     </v-card-title>
                     <v-img
                        src="https://cdn.vuetifyjs.com/images/cards/forest.jpg"
                        gradient="to top, rgba(0,0,0,.44), rgba(0,0,0,.44)"
                     >
                        <v-container fill-height>
                           <v-layout align-center>
                              <strong class="display-4 font-weight-regular mr-4 text-bold">8</strong>
                              <v-layout column justify-end>
                                 <div class="headline font-weight-light">Monday</div>
                                 <div class="text-uppercase font-weight-light">February 2015</div>
                              </v-layout>
                           </v-layout>
                        </v-container>
                     </v-img>
                  </v-card>
                  <v-card-text class="py-0">
                     <v-timeline
                        align-top
                        dense
                     >
                        <v-timeline-item
                           color="pink"
                           small
                        >
                           <v-layout pt-3>
                              <v-flex xs3>
                                 <strong>5pm</strong>
                              </v-flex>
                              <v-flex>
                                 <strong>New Icon</strong>
                                 <div class="caption">Mobile App</div>
                              </v-flex>
                           </v-layout>
                        </v-timeline-item>

                        <v-timeline-item
                           color="teal lighten-3"
                           small
                        >
                           <v-layout wrap pt-3>
                              <v-flex xs3>
                                 <strong>3-4pm</strong>
                              </v-flex>
                              <v-flex>
                                 <strong>Design Stand Up</strong>
                                 <div class="caption mb-2">Hangouts</div>
                                 <div>
                                 <v-avatar>
                                    <v-img
                                       src="https://avataaars.io/?avatarStyle=Circle&topType=LongHairFrida&accessoriesType=Kurt&hairColor=Red&facialHairType=BeardLight&facialHairColor=BrownDark&clotheType=GraphicShirt&clotheColor=Gray01&graphicType=Skull&eyeType=Wink&eyebrowType=RaisedExcitedNatural&mouthType=Disbelief&skinColor=Brown"
                                    ></v-img>
                                 </v-avatar>
                                 <v-avatar>

                                    <v-img
                                       src="https://avataaars.io/?avatarStyle=Circle&topType=ShortHairFrizzle&accessoriesType=Prescription02&hairColor=Black&facialHairType=MoustacheMagnum&facialHairColor=BrownDark&clotheType=BlazerSweater&clotheColor=Black&eyeType=Default&eyebrowType=FlatNatural&mouthType=Default&skinColor=Tanned"
                                    ></v-img>
                                 </v-avatar>
                                 <v-avatar>
                                    <v-img
                                       src="https://avataaars.io/?avatarStyle=Circle&topType=LongHairMiaWallace&accessoriesType=Sunglasses&hairColor=BlondeGolden&facialHairType=Blank&clotheType=BlazerSweater&eyeType=Surprised&eyebrowType=RaisedExcited&mouthType=Smile&skinColor=Pale"
                                    ></v-img>
                                 </v-avatar>
                                 </div>
                              </v-flex>
                           </v-layout>
                        </v-timeline-item>

                        <v-timeline-item
                           color="pink"
                           small
                        >
                           <v-layout pt-3>
                              <v-flex xs3>
                                 <strong>12pm</strong>
                              </v-flex>
                              <v-flex>
                                 <strong>Lunch break</strong>
                              </v-flex>
                           </v-layout>
                        </v-timeline-item>

                        <v-timeline-item
                           color="teal lighten-3"
                           small
                        >
                           <v-layout pt-3>
                              <v-flex xs3>
                                 <strong>9-11am</strong>
                              </v-flex>
                              <v-flex>
                                 <strong>Finish Home Screen</strong>
                                 <div class="caption">Web App</div>
                              </v-flex>
                           </v-layout>
                        </v-timeline-item>
                     </v-timeline>
                  </v-card-text>
               </v-card>
            </app-card>
         </v-layout>
      </v-container>
   </div>
</template>
