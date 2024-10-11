<template>
  <v-container class="fill-height">
    <v-responsive class="align-centerfill-height mx-auto" max-width="900">
      <!-- <div class="py-4"></div> -->

      <v-row>
        <v-col cols="4" class="text-center">
          <v-card color="basil" flat>
            <v-card-text>
              <v-img class="mb-4" height="150" src="@/assets/profile-img.jpg" />

              <div class="text-body-2 font-weight-bold mb-n1">
                Rafaella Sampaio
              </div>
              <div class="text-body-2 font-weight-light mb-n1">
                Ph.D. Student
              </div>
              <div class="text-body-2 font-weight-light mb-n1">
                School of Computing and Information
              </div>
              <div class="text-body-2 font-weight-light mb-n1">
                University of Pittsburgh
              </div>
              <div class="text-body-2 font-weight-light mb-n1">
                ras555(at)pitt.edu
              </div>
              <div class="mb-n1">
                <v-btn icon="fa-linkedin" size="x-small" />
              </div>
            </v-card-text>
          </v-card>
        </v-col>
        <v-col cols="8">
          <v-card color="basil" flat>
            <v-card-text
              >I am Rafaella Sampaio de Alencar, a first-year Ph.D. student at
              the University of Pittsburgh's
              <a href="https://www.sci.pitt.edu/"
                >School of Computing and Information</a
              >. My advisor is
              <a href="https://sites.pitt.edu/~peterb/"
                >Prof. Dr. Peter Brusilovsky</a
              >, head of the
              <a href="http://adapt2.sis.pitt.edu/wiki/PAWS">PAWS Lab</a>. I am
              a recipient of the
              <a
                href="https://www.gradstudies.pitt.edu/2024-25-k-leroy-irvis-fellowship"
                >K. Leroy Irvis Fellowship</a
              >.
            </v-card-text>
          </v-card>
        </v-col>
      </v-row>
    </v-responsive>
  </v-container>
</template>

<script setup lang="ts">
//
</script>
