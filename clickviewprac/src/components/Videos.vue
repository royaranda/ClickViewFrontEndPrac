<template>

  <vue-images :imgs="images" :showcaption="true" :showclosebutton="true">
    
  </vue-images>
  
</template>

<script>
import vueImages from 'vue-images/dist/vue-images'
import Video from './videos.js'

console.log(window.videos)
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },

  data() {
    return {
      listOfVideos: window.videos,
      images: [
        {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1977',
          caption: 'Catalyst: Out of Africa'
        },
        {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1976',
          caption: 'The Diet Myth'
        },
        {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1975',
          caption: 'Insight: Placebo'
        },
        {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1974',
          caption: 'Afghanistan: Inside Australias War'
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1890',
          caption: 'Behind the News: 1/03/2016'
        },
        {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1882',
          caption: 'The Valley of the Kings: Death, Burial and the Afterlife'
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1878',
          caption: 'Opera Stories: Arabella"'
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1877',
          caption: 'Full Proof: Magnets'
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1876',
          caption: 'Jila: Painted Waters Of The Great Sandy'
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1875',
          caption: 'Gayby Baby'
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1542',
          caption: 'Exploration India'
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1262',
          caption: 'Talking Language: Gunditjmara'
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1148',
          caption: "Stephen Hawking's Future Universe: Episode 2 - Code Red"
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1146',
          caption: 'Absolute Genius With Dick and Dom: Fox Talbot'
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1145',
          caption: 'Changing Minds: The Inside Story - Episode 2'
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1144',
          caption: 'Changing Minds: The Inside Story - Episode 1'
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1138',
          caption: 'The Valley Of The Kings: Life'
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1137',
          caption: 'Full Proof: Action Reaction'
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1133',
          caption: 'We Are Young'
        },
                {
          imageUrl: 'http://api-image.clickviewapp.com/v1/thumbnails/1131',
          caption: 'Molly: The Real Thing'
        }
      ]
    }
  },

  components: {
    vueImages
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.calculator {
  margin: 0 auto;
  width: 400px;
  font-size: 40px;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
}

.display {
  grid-column: 1 / 5;
  background-color: #333;
  color: white;
}

.image {
  width: 300px;
  height: 200px;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
