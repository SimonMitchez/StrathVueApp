<template>
  <div id="library">
    <v-container>
      <v-layout column>
        <v-carousel>
          <v-carousel-item
            src="./../../public/library1.jpg"
            cover
          ></v-carousel-item>

          <v-carousel-item
            src="./../../public/library2.jpg"
            cover
          ></v-carousel-item>

          <v-carousel-item
            src="./../../public/library3.jpg"
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

              <div class="mt-4 text-subtitle-2">The Brains Domain</div>

              <v-card width="400">
                <template v-slot:title> Our Library</template>

                <template v-slot:subtitle> Nurturing our brains </template>

                The Library is A Timeless Haven of Knowledge, Exploration,
                and Inspiration The library stands as a beacon of learning and
                enlightenment, offering a sanctuary for minds thirsty for
                knowledge, exploration, and inspiration. Throughout history,
                libraries have played a central role in preserving the
                collective wisdom of humanity and providing access to
                information that fuels intellectual curiosity and scholarly
                pursuits. A Treasure Trove of Knowledge: At its core, the library is a repository of
                knowledge, housing a vast collection of books, journals,
                manuscripts, and other resources that span a myriad of subjects
                and disciplines. From timeless classics to cutting-edge research
                publications, the library offers an unparalleled wealth of
                information that serves as a foundation for academic inquiry,
                intellectual exploration, and lifelong learning. Whether one
                seeks to delve into the annals of history, unravel the mysteries
                of science, or explore the depths of human creativity through
                literature and the arts, the library provides a gateway to a
                world of knowledge waiting to be discovered. 2. A Hub for
                Intellectual Exchange: Beyond serving as a storehouse of
                information, the library serves as a hub for intellectual
                exchange and scholarly discourse. It is a place where students,
                scholars, and researchers come together to engage in dialogue,
                debate ideas, and collaborate on projects. Through seminars,
                workshops, and academic events hosted within its hallowed halls,
                the library fosters a culture of intellectual curiosity and
                critical thinking, encouraging individuals to question
                assumptions, challenge existing paradigms, and push the
                boundaries of knowledge in their respective fields. 3. A
                Catalyst for Personal Growth: For many, the library serves as a
                catalyst for personal growth and self-improvement. It is a place
                where individuals can embark on journeys of self-discovery,
                pursuing their passions, interests, and aspirations. Whether one
                seeks to acquire new skills, expand their horizons, or explore
                different perspectives, the library offers resources and support
                to facilitate personal development and lifelong learning. From
                self-help books to educational workshops, the library empowers
                individuals to cultivate their talents, fulfill their potential,
                and lead fulfilling lives. 4. A Sanctuary for Reflection and
                Contemplation: Amidst the hustle and bustle of modern life, the
                library provides a tranquil oasis where individuals can escape
                the distractions of the outside world and immerse themselves in
                the pursuit of knowledge and understanding. It is a place of
                quiet contemplation and reflection, where one can ponder life's
                big questions, explore the depths of their own thoughts and
                emotions, and find solace in the pages of a book. Whether
                seeking inspiration for creative endeavors or simply seeking a
                moment of respite from the chaos of everyday life, the library
                offers a sanctuary for the mind and soul. 5. Adapting to the
                Digital Age: In an increasingly digital world, the library has
                evolved to meet the changing needs and preferences of its
                patrons. While traditional print collections remain a
                cornerstone of library offerings, many libraries have embraced
                digital technologies to expand access to information and enhance
                the user experience. From online databases and e-books to
                multimedia resources and virtual learning environments,
                libraries have embraced digital innovation to ensure that
                knowledge remains accessible to all, regardless of geographical
                location or socioeconomic status. In conclusion, the library
                stands as a timeless bastion of learning, exploration, and
                inspiration, enriching the lives of individuals and communities
                alike. From its humble origins as repositories of ancient
                manuscripts to its modern incarnation as digital hubs of
                information and innovation, the library continues to play a
                vital role in shaping the intellectual landscape of society. As
                we look to the future, the library remains an enduring symbol of
                the enduring quest for knowledge and the boundless possibilities
                that await those who dare to seek it.

                <template v-slot:text> </template>
              </v-card>

              <div class="mt-4 text-subtitle-2">With markup</div>

              <v-card width="400">
                <v-card-item>
                  <v-card-title>Student's library</v-card-title>

                  <v-card-subtitle>Strath Uni </v-card-subtitle>
                </v-card-item>

                <v-card-text> Where brains are nurtured </v-card-text>
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
