<template>
  <div id="alumni">
    <v-container>
      <v-layout column>
        <v-carousel>
          <v-carousel-item
            src="./../../public/alumni4.jpg"
            cover
          ></v-carousel-item>

          <v-carousel-item
            src="./../../public/alumni1.jpg"
            cover
          ></v-carousel-item>

          <v-carousel-item
            src="./../../public/alumni2.jpg"
            cover
          ></v-carousel-item>
          <v-carousel-item
            src="./../../public/alumni3.jpg"
            cover
          ></v-carousel-item>
          <v-carousel-item
            src="./../../public/alumni5.jpg"
            cover
          ></v-carousel-item>
        </v-carousel>
      </v-layout>
      <v-layout>
        <v-container>
          <v-row align="center" justify="center">
            <div class="d-flex align-center flex-column">
              <div class="text-subtitle-2">With props</div>

              <v-card
                width="400"
                title="This is a title"
                subtitle="This is a subtitle"
                text="This is content"
              ></v-card>

              <div class="mt-4 text-subtitle-2">Our Alumnis</div>

              <v-card width="400">
                <template v-slot:title>Their Experiences</template>

                <template v-slot:subtitle
                  >How Strath Has helped them achieve their goals</template
                >

                <template v-slot:text>
                  As an alumni of Strathmore University, I look back on my
                  experience with immense gratitude and fondness. My journey at
                  Strathmore was not just about acquiring knowledge and skills;
                  it was a transformative experience that shaped me into the
                  person I am today. From the moment I stepped onto the campus,
                  I was welcomed into a vibrant community of scholars,
                  innovators, and change-makers. The atmosphere at Strathmore
                  was electric with enthusiasm for learning, and I was inspired
                  by the passion and dedication of my professors and peers. One
                  of the most memorable aspects of my time at Strathmore was the
                  emphasis on holistic development. While the academic rigor
                  challenged me to push my boundaries and strive for excellence,
                  the university also provided ample opportunities for personal
                  and professional growth. Whether through leadership
                  development programs, extracurricular activities, or community
                  service initiatives, I was encouraged to explore my interests,
                  hone my talents, and contribute meaningfully to society. The
                  values-based education at Strathmore was another defining
                  aspect of my experience. Rooted in the principles of
                  integrity, ethics, and social responsibility, the university
                  instilled in me a strong sense of moral compass and a
                  commitment to ethical leadership. I learned not only how to
                  excel in my chosen field but also how to make a positive
                  impact in the world and lead with integrity and compassion.
                  Beyond the classroom, the sense of camaraderie and camaraderie
                  at Strathmore was palpable. I forged lifelong friendships with
                  classmates from diverse backgrounds, cultures, and
                  perspectives, and together, we navigated the highs and lows of
                  college life. The bonds we formed were strengthened through
                  shared experiences, late-night study sessions, and memorable
                  moments that I will cherish forever. As I reflect on my time
                  at Strathmore, I am grateful for the opportunities it afforded
                  me and the lessons it taught me. The university equipped me
                  with the knowledge, skills, and values needed to succeed in my
                  career and make a difference in the world. But more
                  importantly, it instilled in me a lifelong love for learning,
                  a spirit of resilience, and a commitment to excellence that
                  will guide me wherever life may take me. In conclusion, my
                  experience at Strathmore University was nothing short of
                  transformative. It was a journey of self-discovery, growth,
                  and empowerment that prepared me not only for a successful
                  career but for a meaningful and purposeful life. As an alumni,
                  I am proud to carry forward the values and traditions of
                  Strathmore and to be part of a global community of
                  change-makers making a difference in the world.
                </template>
              </v-card>

              <div class="mt-4 text-subtitle-2">alumni</div>

              <v-card width="400">
                <v-card-item>
                  <v-card-title>Alumnis</v-card-title>

                  <v-card-subtitle>Our Alumnis</v-card-subtitle>
                </v-card-item>

                <v-card-text>Their experiences</v-card-text>
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
