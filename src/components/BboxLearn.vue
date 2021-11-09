<template>
  <v-container grid-list-lg>
    <v-layout row>
        <v-flex xs12 class="text-xs-center display-1 font-weight-black my-5 color blue lighten-5">Open Source Toolkit for Networked Data Science</v-flex>
    </v-layout>
    <v-layout row center>
        <v-spacer />
        <v-flex xs6 sm6 md6>
          <v-img src="../assets/bbdds.png" max-width="400" >
          </v-img>
        </v-flex>
        <v-spacer />
    </v-layout>
    <v-layout row wrap>
      <v-flex xs6 sm6 md6>
        <v-card>
          <v-card-title primary-title>
            <div>
                <h3 class="headline mb-0 font-weight-bold">Now network</h3>
                <div style="word-break: break-word" class="spacing-playground pa-3">
                  Combine networks of historical data.
                </div>
            </div>
          </v-card-title>
        </v-card>
      </v-flex>
      <v-flex xs6 sm6 md6>
        <v-card>
          <v-card-title primary-title>
            <div>
                <h3 class="headline mb-0 font-weight-bold">Future Network</h3>
                <div class="spacing-playground pa-3">
                  Aggregate data to look forward in time.
                </div>
            </div>
          </v-card-title>
        </v-card>
      </v-flex>
    </v-layout>
    <v-layout row wrap>
      <v-flex xs6 sm6 md6>
        <v-card>
          <v-card-title primary-title>
            <div>
                <h3 class="headline mb-0 font-weight-bold">Now</h3>
                <div style="word-break: break-word" class="spacing-playground pa-6 ">
                  Use historical data to make observations.
                </div>
            </div>
          </v-card-title>
        </v-card>
      </v-flex>
      <v-flex xs6 sm6 md6>
        <v-card>
          <v-card-title primary-title>
            <div>
                <h3 class="headline mb-0 font-weight-bold">Future</h3>
                <div style="word-break: break-word" class="spacing-playground pa-6">
                  Look forward to future time periods.
                </div>
            </div>
          </v-card-title>
        </v-card>
      </v-flex>
    </v-layout>
    <v-layout row>
      <v-spacer />
      <v-flex xs6 sm8 md8>
        <v-card>
          <v-card-title primary-title>
            <div>Demo
              <iframe width="640" height="350" src="https://www.youtube.com/embed/JZkBNRx8vWE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
          </v-card-title>
        </v-card>
      </v-flex>
      <v-spacer />
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: 'TaapgLearn'
}
</script>

<style scoped>
</style>
