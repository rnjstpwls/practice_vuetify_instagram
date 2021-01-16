<template>
  <v-card
    class="mx-auto"
    flat
    tile
  >
    <v-img
      height="100%"
      gradient="to top right, rgba(255,255,255,.9), rgba(0,0,0,.1)"

      src="https://cdn.vuetifyjs.com/images/cards/server-room.jpg"
    >
      <v-row
        align="end"
        class="fill-height"
      >
        <v-col
          align-self="start"
          class="my-auto pl-5"
          cols="4"
        >
          <v-avatar
            class="profile"
            color="grey"
            size="100"
            
          >
            <v-img src="https://img1.daumcdn.net/thumb/R800x0/?scode=mtistory2&fname=https%3A%2F%2Ft1.daumcdn.net%2Fcfile%2Ftistory%2F9958E83F5A6C4B6D30" />
          </v-avatar>
        </v-col>

        <v-col
          cols="8"
          class="my-auto"
        >
          <v-list-item
            color="rgba(0, 0, 0, 0.5)"
            
          >
            <v-list-item-content>
              <v-list-item-title class="title">
                virat.kohli
                <v-btn icon>
                  <v-icon>mdi-check-decagram</v-icon>
                </v-btn>
                <v-btn icon x-large>
                  <v-icon>mdi-dots-horizontal</v-icon>
                </v-btn>
              </v-list-item-title>
              <v-list-item-subtitle
                class="text-end"
              >
                
                <v-btn
                  elevation="2"
                  small
                  style="border: 1px solid gray; font-weight: bold;"
                  max-width="100"
                >메시지 보내기</v-btn>

                <v-btn
                  small
                  style="border: 1px solid gray;"
                  class="ml-1"
                >
                  <v-icon>mdi-account-check</v-icon>
                </v-btn>

                <v-btn
                  small
                  style="border: 1px solid gray;"
                  class="ml-1"
                  width="10"
                >
                  <v-icon>mdi-menu-down</v-icon>
                </v-btn>
                
              </v-list-item-subtitle>
            </v-list-item-content>

          </v-list-item>

        </v-col>

      </v-row>

    </v-img>
  
  </v-card>
</template>

<script>
export default {

}
</script>

<style>

</style>