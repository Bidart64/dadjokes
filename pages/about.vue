<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card class="logo py-4 d-flex justify-center">
      </v-card>
      <v-card>
        <v-card-title class="headline">
          Welcome to the about page
        </v-card-title>
        <v-card-text>
          <p>This is for bad dad jokes</p>
          <div class="text-xs-right">
            <em><small>&mdash; Hayden Veytia</small></em>
          </div>
          <hr class="my-3">
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="blue darken-4"
            nuxt
            to="/index"
          >
            Home
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
