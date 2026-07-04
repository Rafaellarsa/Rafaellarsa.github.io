<template>
  <v-container class="fill-height">
    <v-responsive class="align-centerfill-height mx-auto" max-width="900">
      <!-- <div class="py-4"></div> -->

      <v-row>
        <v-col cols="4" class="text-center">
          <v-card color="basil" flat height="100%">
            <v-card-text>
              <v-img class="mb-4" height="250" src="@/assets/profile-img.jpg" />

              <div class="text-body-2 font-weight-bold mb-n1">
                Rafaella Sampaio de Alencar
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
              <div>
                <v-tooltip text="LinkedIn">
                  <template v-slot:activator="{ props }">
                    <v-btn
                      v-bind="props"
                      density="compact"
                      variant="plain"
                      color="primary"
                      target="_blank"
                      icon="mdi-linkedin"
                      href="https://www.linkedin.com/in/rafaella-sampaio-de-alencar/"
                    />
                  </template>
                </v-tooltip>
                &nbsp;&nbsp;

                <v-tooltip text="Google Scholar">
                  <template v-slot:activator="{ props }">
                  <v-btn
                    v-bind="props"
                    density="compact"
                    variant="plain"
                    color="primary"
                    target="_blank"
                    icon="mdi-school"
                    href="https://scholar.google.com/citations?user=vtyWdE8AAAAJ/"
                  />
                  </template>
                </v-tooltip>
                &nbsp;&nbsp;

                <v-tooltip text="GitHub">
                  <template v-slot:activator="{ props }">
                    <v-btn
                      v-bind="props"
                      density="compact"
                      variant="plain"
                      color="primary"
                      target="_blank"
                      icon="mdi-github"
                      href="https://github.com/Rafaellarsa/"
                    />
                  </template>
                </v-tooltip>
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
            <v-card-text>
              <a href="files/CV_Rafaella_Sampaio.pdf" target="_blank"
                ><v-btn variant="outlined">Curriculum Vitae</v-btn></a
              > (Last Updated on October 31st, 2024)
            </v-card-text>
            <v-divider inset />
            <v-card-text>
              <v-card-title class="px-0">News</v-card-title>
              <b>Last Updated:</b> October 31st, 2024.
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
            <v-divider inset />
            <v-card-text>
              <v-card-title class="px-0">Publications</v-card-title>
              <!-- <b>Upcoming</b>
              <v-list>

              </v-list> -->

              <b>2026</b>
              <v-list>
                <v-list-item>
                  <a href="https://sites.google.com/view/csedm-workshop-edm26/schedule-proceedings"><b>
                    Ontology-Guided Knowledge Component Extraction for Programming Exercises
                  </b></a> <br />
                  Rully Agus Hendrawan, Shravya Suresh, <u>Rafaella Sampaio de Alencar</u>, Alice Micheli, Peter Brusilovsky and Sergey Sosnovsky <br />
                  <i>10th Educational Data Mining in Computer Science Education Workshop (CSEDM @ EDM'26)</i>
                </v-list-item>
                <v-list-item>
                  <a href="https://aclanthology.org/2026.findings-acl.1670/"><b>
                    Automated Knowledge Component Generation and Interpretable Knowledge Tracing in Coding Problems
                  </b></a> <br />
                  Zhangqi Duan, Nigel Fernandez, Arun Balajiee Lekshmi Narayanan, Mohammad Hassany, <u>Rafaella Sampaio de Alencar</u>, Peter Brusilovsky, Bita Akram, and Andrew Lan <br />
                  <i>Findings of the Association for Computational Linguistics (ACL 2026)</i>
                </v-list-item>
                <v-list-item>
                  <a href="https://dl.acm.org/doi/10.1145/3796496.3811773"><b>
                    Cracking the Case, Missing the Data: Design Tensions in Community-Led Critical Data Literacy Instruction
                  </b></a> <br />
                  <u>Rafaella Sampaio de Alencar</u>, Xingyu Song, Daniel Steve Cheng, Jimmara Scott, and Aakash Gautam <br />
                  <i>2026 Conference on Research on Equity and Sustained Participation in Engineering, Computing, and Technology (RESPECT 2026)</i>
                  <br />* Exemplary Paper
                </v-list-item>
                <v-list-item>
                  <a href="https://dl.acm.org/doi/10.1145/3774935.3806183"><b>
                    Using Elo to Operationalize Modeling of Aphasia Patients’ Word-Recall Practice During Recovery
                  </b></a> <br />
                  <u>Rafaella Sampaio de Alencar</u>, Michael Yudelson, Peter Brusilovsky, and William S. Evans <br />
                  <i>34th ACM Conference on User Modeling, Adaptation and Personalization (UMAP '26)</i>
                </v-list-item>
                 <v-list-item>
                  <a href="https://dl.acm.org/doi/10.5555/3820586.3820612"><b>
                    Integrating Smart Learning Content with Project-Based Introductory Programming Course at Community Colleges
                  </b></a> <br />
                  Mohammad Hassany, Can Kultur, <u>Rafaella Sampaio de Alencar</u>, Kamil Akhuseyinoglu, Christopher Bogart, Jaromir Savelka, and Peter Brusilvosky <br />
                  <i>30th Annual Consortium for Computing Sciences in Colleges - Northeastern Conference (CCSCNE '26)</i>
                </v-list-item>
                <v-list-item>
                  <a href="https://doi.org/10.1080/08923647.2026.2669412"><b>
                    Supplemental AI in a Hybrid Human Anatomy Course and Its Effect on Student Performance and Engagement
                  </b></a> <br />
                  Reivian Berrios Barillas, Mariano de Leon, Scott Fraundorf, Peter Brusilvosky, <u>Rafaella Sampaio de Alencar</u>, Kim Nixon-Cave, and Yanshan Wang <br />
                  <i>American Journal of Distance Education</i>
                </v-list-item>
                <v-list-item>
                  <a href="https://doi.org/10.1145/3785022.3785106"><b>
                    Data-Driven Evaluation of LLM-Based Ontology Concept Extraction from Programming Learning Content
                  </b></a> <br />
                  Rully Agus Hendrawan, <u>Rafaella Sampaio de Alencar</u>, Alice Micheli, Peter Brusilovsky, Jordan Barria-Pineda, and Sergey Sosnovsky <br />
                  <i>16th International Learning Analytics and Knowledge Conference (LAK '26)</i>
                </v-list-item>
                <v-list-item>
                  <a href="https://doi.org/10.1145/3770761.3777243"><b>
                    Knowledge Component-Driven Alignment of CS1 Textbooks and Exercises
                  </b></a> <br />
                  Samantha Smith, Arun-Balajiee Lekshmi Narayanan, Anurata Prabha Hridi, <u>Rafaella Sampaio de Alencar</u>, Bita Akram, Arto Hellas, Juho Leinonen, Peter Brusilovsky, and Narges Norouzi <br />
                  <i>57th ACM Technical Symposium on Computer Science Education V.2 (SIGCSE TS 2026)</i>
                </v-list-item>
              </v-list>

              <b>2025</b>
              <v-list>
                <v-list-item>
                  <a href="https://doi.org/10.1145/3699682.3728348"><b>
                    Integrating Expert Knowledge With Automated Knowledge Component Extraction for Student Modeling
                  </b></a> <br />
                  <u>Rafaella Sampaio de Alencar</u>,, Mehmet Arif Demirtas, Adittya Soukarjya Saha, Yang Shi, and Peter Brusilovsky <br />
                  <i>33rd ACM Conference on User Modeling, Adaptation and Personalization (UMAP '25)</i>
                </v-list-item>
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
