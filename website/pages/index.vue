<template>
  <v-col>
    <h1
    class="mb-6"
    >Quick Access</h1>
    <div class="scroll-container">
    <v-row 
    class="mx-auto">

    <v-slide-group
      show-arrows
    >
    <div style="display: flex; flex-direction: column;">
  <v-card class="mr-5 rounded-lg" width="150" height="150" theme="dark" image="https://www.nationalretail.org.au/app/uploads/2023/10/StockImages_01.jpg">
  </v-card>
  <div style="margin-top: 10px; font-weight: bold;">AES Course</div>
</div>


    <div style="display: flex; flex-direction: column;">
  <v-card class="mr-5 rounded-lg" width="150" height="150" theme="dark" image="https://imagevars.gulfnews.com/2023/03/27/Cybersecurity-_18723400af9_large.jpg">
  </v-card>
  <div style="margin-top: 10px; font-weight: bold;">RSA Course</div>
</div>

<div style="display: flex; flex-direction: column;">
  <v-card class="mr-5 rounded-lg" width="150" height="150" theme="dark" image="https://img.etimg.com/thumb/msid-102489123,width-300,height-225,imgsize-122134,resizemode-75/cyber-security-istock.jpg">
  </v-card>
  <div style="margin-top: 10px; font-weight: bold;">3DES Course</div>
</div>



</v-slide-group>
</v-row>

<h1
class="mt-6">
  Previews
</h1>
 
<v-row>

  <v-slide-group
      show-arrows>
  <v-card
  class="ma-5 rounded-lg"
    max-width="400" >
    <v-img
      class="align-end text-white"
      height="200"
      src="https://www.simplilearn.com/ice9/free_resources_article_thumb/Use_Cases_for_Cyber_Security.jpg"
      cover
    >
      <v-card-title>
        <div style="margin-top: 10px; font-weight: bold;">Advanced Encryption Standard</div></v-card-title>
    </v-img>

    <v-card-subtitle class="pt-4">
      Course #1
    </v-card-subtitle>

    <v-card-text>
      <div>Take a closer look into the encryption algorithm used by WhatsApp</div>

    </v-card-text>

    <v-card-actions>
      <v-btn color="orange">
        Begin
      </v-btn>

      <v-btn color="orange">
        More
      </v-btn>
    </v-card-actions>
  </v-card>

  <v-card
  class="ma-5 rounded-lg"
    max-width="400" >
    <v-img
      class="align-end text-white"
      height="200"
      src="https://www.cgtechnologies.com/wp-content/uploads/2023/01/what-is-cyber-security-1024x683.jpg"
      cover
    >
      <v-card-title>
        <div style="margin-top: 10px; font-weight: bold;">Triple Data Encryption Standard</div></v-card-title>
    </v-img>

    <v-card-subtitle class="pt-4">
      Course #2
    </v-card-subtitle>

    <v-card-text>
      <div>Take a closer look into this 3 layer encryption standard</div>

    </v-card-text>

    <v-card-actions>
      <v-btn color="orange">
        Begin
      </v-btn>

      <v-btn color="orange">
        More
      </v-btn>
    </v-card-actions>
  </v-card>

  <v-card
  class="ma-5 rounded-lg"
    max-width="400" >
    <v-img
      class="align-end text-white"
      height="200"
      src="https://cioafrica.co/wp-content/uploads/2024/01/cyber-security.jpeg"
      cover
    >
      <v-card-title>
        <div style="margin-top: 10px; font-weight: bold;">Data Encryption Standard</div></v-card-title>
    </v-img>

    <v-card-subtitle class="pt-4">
      Course #3
    </v-card-subtitle>

    <v-card-text>
      <div>Get to know the basics of criptography with the first version DES</div>

    </v-card-text>

    <v-card-actions>
      <v-btn color="orange">
        Begin
      </v-btn>

      <v-btn color="orange">
        More
      </v-btn>
    </v-card-actions>
  </v-card>
  </v-slide-group>
</v-row>

<h1
    class="mb-6">Progress</h1>

  </div>

  <v-row>
    <v-slide-group
      show-arrows
    >
    <v-col>      
      <v-card width="400">
        <v-img
           class="ma-5 rounded-lg"
          height="200"
          src="https://www.eaton.com/content/dam/eaton/company/news-insights/cybersecurity/cybersecurity-1499538400.png.transform/default-desktop/image.jpg"
          cover
        >
          <v-toolbar
            color="rgba(0, 0, 0, 0)"
            theme="dark"
          >
            <v-toolbar-title class="text-h6">
              <div style="margin-top: 10px; font-weight: bold;">AES</div>
            </v-toolbar-title>

            <template v-slot:append>
              <v-btn icon="mdi-dots-vertical"></v-btn>
            </template>
          </v-toolbar>
        </v-img>

        <v-card-text>
          <div class="font-weight-bold ms-1 mb-2">
            Today
          </div>

          <v-timeline density="compact">
            <v-timeline-item
              v-for="message in messages"
              :key="message.time"
              :dot-color="message.color"
              size="x-small"
            >
              <div class="mb-4">
                <div class="font-weight-normal">
                  <strong>{{ message.from }}</strong> @{{ message.time }}
                </div>
                <div>{{ message.message }}</div>
              </div>
            </v-timeline-item>
          </v-timeline>
        </v-card-text>
      </v-card>
    </v-col>

    <v-col>      
      <v-card width="400">
        <v-img
           class="ma-5 rounded-lg"
          height="200"
          src="https://www.securitymagazine.com/ext/resources/images/cybersecurity-freepik.jpg?1626304720"
          cover
        >
          <v-toolbar
            color="rgba(0, 0, 0, 0)"
            theme="dark"
          >
            <v-toolbar-title class="text-h6">
              <div style="margin-top: 10px; font-weight: bold;">3DES</div>
            </v-toolbar-title>

            <template v-slot:append>
              <v-btn icon="mdi-dots-vertical"></v-btn>
            </template>
          </v-toolbar>
        </v-img>

        <v-card-text>
          <div class="font-weight-bold ms-1 mb-2">
            Today
          </div>

          <v-timeline density="compact">
            <v-timeline-item
              v-for="message in messages"
              :key="message.time"
              :dot-color="message.color"
              size="x-small"
            >
              <div class="mb-4">
                <div class="font-weight-normal">
                  <strong>{{ message.from }}</strong> @{{ message.time }}
                </div>
                <div>{{ message.message }}</div>
              </div>
            </v-timeline-item>
          </v-timeline>
        </v-card-text>
      </v-card>
    </v-col>

  
  </v-slide-group>
  </v-row>
  </v-col>

</template>

<script>


  export default {
    data: () => ({
      messages: [
        {
          from: 'Successful',
          message: `Completed assignment 1`,
          time: '10:42am',
          color: 'green',
        },
        {
          from: 'Successful',
          message: 'Completed task 1',
          time: '10:37am',
          color: 'green',
        },
        {
          from: 'In Progress',
          message: 'Task 2 to be completed',
          time: '9:47am',
          color: 'red',
        },
      ],
    }),
  };
</script>

<style scoped>
.container {
  padding: 20px;
}

.search-container {
  position: relative;
}

.search-bar {
  width: calc(100% - 30px); /* Adjust to accommodate the icon width */
  padding: 10px;
  padding-right: 30px; /* Space for the icon */
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 16px;
  outline: none;
}

.search-icon {
  position: absolute;
  top: 50%;
  right: 10px;
  transform: translateY(-50%);
  color: #888;
}



/* Add your scoped styles here */
</style>
