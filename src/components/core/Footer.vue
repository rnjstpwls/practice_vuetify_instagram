<template>
  <v-footer
    padless
    width="100%"
  >
    <v-card
      flat
      tile
      class="pink lighten-4 black--text text-center"
      width="100%"
    >
      <v-card-text>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4 black--text"
          icon
        >
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="black--text pt-0 pb-0">
        
        <span v-for="(link, idx) in links" :key="idx">
          <a href="#" style="color: black; text-decoration:none; word-break: keep-all">{{link}} </a>
        </span>
        
      </v-card-text>
      <v-card-text class="black--text pt-0">
        <v-row>
          <v-col cols="4">
            <v-select
                  :items="items"
                  :menu-props="{ top: true, offsetY: true }"
                  label="언어설정"
                  
                ></v-select>
          </v-col>

          <v-col cols="8" class="my-auto px-0">
            {{ new Date().getFullYear() }} — <strong>Instagram from Facebook</strong>
          </v-col>
        </v-row>
      </v-card-text>
    </v-card>
  </v-footer>
</template>


<script>
export default {
  name: 'CoreFooter',
  data: () => ({
    icons: [
      'mdi-facebook',
      'mdi-twitter',
      'mdi-linkedin',
      'mdi-instagram',
    ],
    links: [
      '소개',
      '블로그',
      '채용정보',
      '도움말',
      'API',
      '개인정보처리방침',
      '약관',
      '인기계정',
      '해시태그',
      '위치',
      '추천계정',
    ],
    items: [
      '한국어',
      '일본어',
      '영어',
      '독일어',
    ]
  }),
}
</script>


<style>

</style>