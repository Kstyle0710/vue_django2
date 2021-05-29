<template>
    <v-container>
      <v-row align="center" justify="center">
        <v-col cols="12" lg="10">
          <h1>Post Title here</h1>
          <p>2021-07-10, written by Kstyle</p>
        </v-col>
      </v-row>
      <v-row align="start" justify="center">
        <v-col cols="12" sm="8" lg="7">
          <v-card class="pa-2" outlined tile>
            <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
            <div>
              <strong>Tags</strong>
              <v-chip class="ma-2" outlined>
                python
              </v-chip>

            </div>
          </v-card>
        </v-col>
        <v-col cols="12" sm="4" lg="3">
          <v-card class="pa-2 mb-5" tile>
            <p>prev post</p>
            <h2>
              Previous Title here
            </h2>
          </v-card>
          <v-card class="pa-2 mb-5" tile>
            <p>next post</p>
            <h2>
              Next Title here
            </h2>
          </v-card>
          <v-card class="pa-2 mb-5" tile>
            <h2>
              Tag Cloud
            </h2>
            <v-chip class="ma-2" color="green" text-color="white">
              <v-avatar left class="green darken-4">
                1
              </v-avatar>
              python
            </v-chip>
            <v-chip class="ma-2" color="orange" text-color="white">
              django
              <v-icon right>
                mdi-star
              </v-icon>
            </v-chip>

          </v-card>
        </v-col>
      </v-row>
    </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      ecosystem: [
        {
          text: 'vuetify-loader',
          href: 'https://github.com/vuetifyjs/vuetify-loader',
        },
        {
          text: 'github',
          href: 'https://github.com/vuetifyjs/vuetify',
        },
        {
          text: 'awesome-vuetify',
          href: 'https://github.com/vuetifyjs/awesome-vuetify',
        },
      ],
      importantLinks: [
        {
          text: 'Documentation',
          href: 'https://vuetifyjs.com',
        },
        {
          text: 'Chat',
          href: 'https://community.vuetifyjs.com',
        },
        {
          text: 'Made with Vuetify',
          href: 'https://madewithvuejs.com/vuetify',
        },
        {
          text: 'Twitter',
          href: 'https://twitter.com/vuetifyjs',
        },
        {
          text: 'Articles',
          href: 'https://medium.com/vuetify',
        },
      ],
      whatsNext: [
        {
          text: 'Explore components',
          href: 'https://vuetifyjs.com/components/api-explorer',
        },
        {
          text: 'Select a layout',
          href: 'https://vuetifyjs.com/getting-started/pre-made-layouts',
        },
        {
          text: 'Frequently Asked Questions',
          href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
        },
      ],
    }),
  }
</script>
