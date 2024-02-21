<template>
  <div id="contactus">
    <v-container>
      <v-layout column>
        <v-carousel>
          <v-carousel-item src="./../../public/contactus1.jpg" cover></v-carousel-item>

          <v-carousel-item src="./../../public/contactus2.jpg" cover></v-carousel-item>

          <v-carousel-item src="./../../public/contactus3.jpg" cover></v-carousel-item>
        </v-carousel>
      </v-layout>
      <v-layout>
        <v-container>
          <v-row align="center" justify="center">
            <div class="d-flex align-center flex-column">
              <div class="text-subtitle-2">contactus</div>

              <v-card width="400" title="This is a title" subtitle="This is a subtitle" text="This is content"></v-card>

              <div class="mt-4 text-subtitle-2">Strathmore University</div>

              <v-card width="400">
                <template v-slot:title>ContactUs</template>

                <template v-slot:subtitle>How to reach us</template>

                If you need to contact Strathmore University for inquiries,
                admissions, or any other purposes, you can reach them using the
                following methods: 
                1. Phone Call: You can contact Strathmore
                University by phone during their office hours. Here's an example
                of how to place a phone call: Dial the university's main phone
                number: +254 703 034000. Listen to the automated menu options
                and select the appropriate department or extension for your
                inquiry. If you're unsure which department to contact, you can
                speak with the receptionist or administrative assistant who will
                direct your call to the appropriate party. Be prepared to
                provide your name, contact information, and a brief explanation
                of your inquiry or reason for calling. 
                2. Email: Another way to contact Strathmore University is by sending an email. 
                Here's an example of how to compose an email: Address your email to the
                university's general inquiry email address: info@strathmore.edu.
                In the subject line, briefly describe the purpose of your email
                (e.g., "Admissions Inquiry," "Faculty Recruitment," "Student
                Services"). In the body of the email, provide your name, contact
                information, and a detailed explanation of your inquiry or
                request. If applicable, attach any relevant documents or
                supporting information to your email. Double-check your email
                for accuracy and clarity before sending it. 
                3. Online Contact
                Form: Many universities, including Strathmore University, have
                online contact forms on their website that you can use to submit
                inquiries or requests. Here's an example of how to fill out an
                online contact form: Visit the university's official website
                (www.strathmore.edu). Navigate to the "Contact Us" or "Get in
                Touch" section of the website. Fill out the required fields in
                the online contact form, including your name, email address,
                phone number, and message. In the message box, provide a
                detailed explanation of your inquiry or request. Click the
                "Submit" or "Send" button to send your message to the
                university's administrative team. 
                4. Social Media:
                 Many universities, including Strathmore University, maintain active
                social media accounts on platforms like Facebook, Twitter,
                LinkedIn, and Instagram. You can reach out to the university
                through direct messages or by tagging them in your posts or
                comments. Here's an example of how to send a direct message on
                Facebook: Log in to your Facebook account and search for
                "Strathmore University." Visit the university's official
                Facebook page and click the "Message" button. Compose your
                message, providing your name, contact information, and inquiry
                or request. Click the "Send" button to submit your message to
                the university's Facebook inbox. By using these contact methods,
                you can easily reach Strathmore University and communicate with
                their administrative team for any inquiries, admissions, or
                assistance you may need.

                <template v-slot:text> </template>
              </v-card>

              <div class="mt-4 text-subtitle-2">contact us</div>

              <v-card width="400">
                <v-card-item>
                  <v-card-title>Strath Uni</v-card-title>

                  <v-card-subtitle>How to reach us</v-card-subtitle>
                </v-card-item>

                <v-card-text>Don't be afraid to reach us</v-card-text>
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
