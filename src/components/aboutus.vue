<template>
  <div id="aboutus">
    <v-container>
      <v-layout column>
        <v-carousel>
          <v-carousel-item
            src="./../../public/aboutus1.jpg"
            cover
          ></v-carousel-item>

          <v-carousel-item
            src="./../../public/aboutus2.jpg"
            cover
          ></v-carousel-item>

          <v-carousel-item
            src="./../../public/aboutus3.jpg"
            cover
          ></v-carousel-item>
        </v-carousel>
      </v-layout>
      <v-layout>
        <v-container>
          <v-row align="center" justify="center">
            <div class="d-flex align-center flex-column">
              <div class="text-subtitle-2"></div>

              <div class="mt-4 text-subtitle-2">About Us</div>

              <v-card width="400">
                <template v-slot:title> Welcome </template>

                <template v-slot:subtitle> All About Strathmore Uni </template>

                <template v-slot:text>
                  Strathmore University: A Beacon of Excellence in African
                  Education Located in Nairobi, Kenya, Strathmore University
                  stands as a beacon of excellence in African education,
                  renowned for its commitment to academic rigor, innovation, and
                  holistic development. Since its inception in 1961, the
                  university has remained dedicated to providing high-quality
                  education that empowers students to make meaningful
                  contributions to society and thrive in a rapidly changing
                  world. In this essay, we will explore the rich history, core
                  values, academic offerings, and impact of Strathmore
                  University on the African continent and beyond. A Legacy of
                  Excellence: 
                  
                  Founded by the St. Josemaría Escrivá de Balaguer
                  Foundation, Strathmore University began as a small college
                  offering accountancy courses. Over the years, it has grown
                  into a leading institution of higher learning, offering a
                  diverse range of undergraduate and postgraduate programs in
                  business, information technology, law, humanities, and social
                  sciences. 
                  <hr/>
                  The university's commitment to academic excellence
                  and ethical leadership has earned it recognition as one of the
                  top universities in Africa and a preferred destination for
                  students seeking quality education. Ethical Leadership and
                  Values-Based Education: At the heart of Strathmore
                  University's mission is the belief in ethical leadership and
                  values-based education. The university strives to instill in
                  its students a strong sense of integrity, responsibility, and
                  service to others, preparing them to become ethical leaders
                  and change agents in their communities and professions.
                  Through its holistic approach to education, Strathmore
                  University equips students not only with academic knowledge
                  but also with the moral and ethical principles needed to
                  navigate complex ethical dilemmas and make principled
                  decisions in their personal and professional lives.   
                  <hr/>
                  Academic
                  Excellence and Innovation: Strathmore University is committed
                  to fostering academic excellence and innovation across all its
                  programs and disciplines. The university boasts a team of
                  highly qualified faculty members who are experts in their
                  respective fields and are dedicated to providing students with
                  a rigorous and intellectually stimulating learning experience.
                  Through innovative teaching methods, cutting-edge research
                  initiatives, and partnerships with industry leaders,
                  Strathmore University prepares students to excel in a rapidly
                  evolving global economy and drive positive change in their
                  communities. Global Perspective and Impactful Research: With a
                  diverse student body representing over 40 nationalities,
                  Strathmore University embraces a global perspective in its
                  approach to education and research. The university encourages
                  cross-cultural exchange, collaboration, and engagement with
                  global issues, preparing students to thrive in an
                  interconnected world. Additionally, Strathmore University is
                  committed to conducting impactful research that addresses
                  pressing societal challenges and contributes to the
                  advancement of knowledge in various fields. From sustainable
                  development to information technology, the university's
                  research endeavors are making a significant impact on the
                  African continent and beyond. Community Engagement and Social
                  Responsibility: Strathmore University is deeply committed to
                  community engagement and social responsibility, recognizing
                  the importance of giving back to society and making a positive
                  difference in the lives of others. Through initiatives such as
                  community service projects, volunteerism, and social
                  entrepreneurship programs, the university empowers students to
                  use their skills and talents to address social, economic, and
                  environmental challenges facing their communities. By
                  nurturing a culture of service and social responsibility,
                  Strathmore University is cultivating a new generation of
                  leaders who are committed to creating a more just, inclusive,
                  and sustainable world. In conclusion, Strathmore University
                  stands as a shining example of excellence in African
                  education, embodying a commitment to academic rigor, ethical
                  leadership, innovation, and social responsibility. Through its
                  values-based approach to education, the university is
                  empowering students to become ethical leaders, critical
                  thinkers, and compassionate global citizens who are equipped
                  to tackle the complex challenges of the 21st century. As it
                  continues to expand its reach and impact, Strathmore
                  University remains dedicated to its mission of transforming
                  lives and communities through education, research, and
                  service.
                </template>
              </v-card>

              <div class="mt-4 text-subtitle-2">AboutUs</div>

              <v-card width="400">
                <v-card-item>
                  <v-card-title>Strathmore</v-card-title>

                  <v-card-subtitle>For A Better Future </v-card-subtitle>
                </v-card-item>

                <v-card-text>Change to the world</v-card-text>
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
