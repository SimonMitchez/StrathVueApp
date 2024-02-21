<template>
  <div id="homepage">
    <v-container>
      <v-layout column>
        <v-carousel>
          <v-carousel-item
            src="./../../public/home1.jpg"
            cover
          ></v-carousel-item>

          <v-carousel-item
            src="./../../public/home2.jpg"
            cover
          ></v-carousel-item>

          <v-carousel-item
           src="./../../public/home3.jpg"
            cover
          ></v-carousel-item>
          <v-carousel-item
           src="./../../public/home4.jpg"
            cover
          ></v-carousel-item>
        </v-carousel>
      </v-layout>
      <v-layout>
        <v-container>
          <v-row align="center" justify="center">
            <div class="d-flex align-center flex-column">
              <div class="text-subtitle-2">With props</div>

             
              <div class="mt-4 text-subtitle-2"></div>

              <v-card width="400">
                <template v-slot:title> Welcome </template>

                <template v-slot:subtitle>
                  Home to all Students of different diversities
                </template>

                <template v-slot:text>
                  Welcome to the Strathmore University! At Strathmore University 
                  , we believe in empowering students to reach their
                  full potential and become leaders in their chosen fields. As a
                  premier institution of higher learning, we are dedicated to
                  fostering academic excellence, cultivating a vibrant
                  community, and inspiring innovation and creativity. Our
                  university is home to a diverse and talented student body,
                  hailing from different backgrounds, cultures, and
                  perspectives. Here, students are encouraged to explore their
                  passions, engage in interdisciplinary learning, and contribute
                  meaningfully to society. With a commitment to providing a
                  dynamic learning environment, we offer a wide range of
                  programs and opportunities that cater to the unique interests
                  and aspirations of our students. From cutting-edge research
                  initiatives to experiential learning opportunities, our
                  curriculum is designed to equip students with the knowledge,
                  skills, and experiences they need to succeed in a rapidly
                  evolving world. At the Strathmore University, we pride
                  ourselves on our world-class faculty who are experts in their
                  fields and dedicated mentors committed to guiding students on
                  their academic journey. Our state-of-the-art facilities and
                  resources provide students with the tools they need to excel
                  in their studies and pursue their passions. Beyond the
                  classroom, our university offers a vibrant campus life
                  enriched by a wealth of extracurricular activities, clubs, and
                  organizations. From cultural celebrations to community service
                  projects, there are endless opportunities for students to
                  explore their interests, develop leadership skills, and build
                  lifelong friendships. We invite you to explore our website and
                  discover all that the Strathmore University has to offer.
                  Whether you are a prospective student, current student,
                  faculty member, or alumni, we are excited to welcome you to
                  our community and support you in achieving your academic and
                  personal goals. Welcome to Strathmore University! –
                  where your journey to success begins!
                </template>
              </v-card>

              <div class="mt-4 text-subtitle-2">With markup</div>

              <v-card width="400">
                <v-card-item>
                  <v-card-title>{{  }}</v-card-title>

                  <v-card-subtitle>Strath Uni </v-card-subtitle>
                </v-card-item>

                <v-card-text>We value our students!</v-card-text>
              </v-card>
            </div>
          </v-row>
        </v-container>
      </v-layout>
    </v-container>
  </div>
</template>
<script setup>
const variants = ["elevated", "flat", "tonal", "outlined"];
</script>
