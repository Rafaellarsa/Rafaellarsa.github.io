<template>
  <v-container class="fill-height">
    <v-responsive class="align-centerfill-height mx-auto" max-width="900">
      <!-- <div class="py-4"></div> -->

      <v-row>
        <v-col cols="4" class="text-center">
          <v-card color="basil" flat height="100%">
            <v-card-text>
              <v-img class="mb-4" height="150" src="@/assets/profile-img.jpg" />

              <div class="text-body-2 font-weight-bold mb-n1">
                Rafaella Sampaio
              </div>
              <div class="text-body-2 font-weight-light mb-1">
                Ph.D. Student
              </div>
              <div class="text-body-2 font-weight-light mb-n1">
                School of Computing and Information
              </div>
              <div class="text-body-2 font-weight-light mb-1">
                University of Pittsburgh
              </div>
              <div class="text-body-2 font-weight-light mb-1">
                ras555(at)pitt.edu
              </div>
              <div class="text-body-2 font-weight-light">
                <a
                  href="https://www.linkedin.com/in/rafaella-sampaio-de-alencar/"
                  >LinkedIn</a
                >
                &nbsp;&nbsp;
                <a href="https://github.com/Rafaellarsa">GitHub</a>
              </div>
            </v-card-text>
          </v-card>
        </v-col>
        <v-col cols="8">
          <v-card color="basil" flat height="100%">
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
            <v-card-text>
              <b>Research Interests:</b> Learning Technologies; Personalization;
              Artificial Intelligence in Education; Equity.
            </v-card-text>
            <v-divider inset />
            <v-card-text>
              <!-- CV_Rafaella_Sampaio.pdf -->
              <a href="../files/CV_Rafaella_Sampaio.pdf" target="_blank"
                ><v-btn variant="outlined">Curriculum Vitae</v-btn></a
              >
            </v-card-text>
            <v-divider inset />
            <v-card-text>
              <v-card-title class="px-0">News</v-card-title>
              <v-list>
                <v-list-item
                  ><b>October/2024 - </b>Our poster, titled "Utilizing Visual
                  Teacher Dashboards to Identify Difficult Topics for Student
                  Learning in an Anatomy Course", was accepted in the
                  <a href="https://csm.apta.org/"
                    >50th Annual APTA Combined Sections Meeting (2025)</a
                  >.</v-list-item
                >
                <v-list-item
                  ><b>August/2024 - </b>Started a PhD in Information Science in
                  the University of Pittsburgh.</v-list-item
                >
                <v-list-item
                  ><b>August/2024 - </b>
                  <a
                    href="https://learnlab.org/certificate-manager/verify-summer-school.php?certificate_id=e9ygWHPXs2Nj8t7"
                    >Completed</a
                  >
                  the 2024 LearnLab Summer School (Computer Science Education
                  Research Track) of the Carnegie Mellon
                  University.</v-list-item
                >
                <v-list-item
                  ><b>January/2024 - </b>Joined the University of Pittsburgh and
                  started the Master of Science in Information Science
                  program.</v-list-item
                >
              </v-list>
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
