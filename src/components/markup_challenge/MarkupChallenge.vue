<template>
  <div class="">
    <div class="row">
      <div class="col-12 pt-5 pb-2">
        <h3>Markup cards airbnb</h3>
        <p></p>
      </div>
    </div>
    <div class="container-fluid special-container">
      <div class="d-flex flex-column">
        <div class="explore-section py-5">
          <h3 class="text-left p-0 m-0 h4 font-weight-bold pb-4">Explore Airbnb</h3>
          <div class="content-cards d-flex justify-content-between">
            <div class="card-arb d-flex w-25 mr-3" v-for="(item, index) in items" :key="index">
              <img v-bind:src="item.pic" alt="">
              <div class="text-left pl-3 align-self-center">
                <p class="font-weight-bold m-0 p-0">{{item.title}}</p>
                <span class=" m-0 p-0">{{item.content}}</span>
              </div>
            </div>
          </div>
        </div>
        <div class="introducing-airbnb">
          <h3 class="text-left p-0 m-0 h4 font-weight-bold">Introducing Airbnb Luxe</h3>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MarkupChallenge',
  data() {
    return {
      items: [
        { pic: 'https://a0.muscache.com/4ea/air/v2/pictures/8b7519ec-2c82-4c09-8233-fd4d2715bbf9.jpg?t=r:w375-h250-sfit,e:fjpg-c80', title: 'Stays', content: 'Experiences'},
        { pic: 'https://a0.muscache.com/4ea/air/v2/pictures/cb8b3101-d419-4c17-8e2f-4989b39b98c3.jpg?t=r:w375-h250-sfit,e:fjpg-c80', title: 'Experiences', content: 'Activities hosted by locals'},
        { pic: 'https://a0.muscache.com/4ea/air/v2/pictures/38f2bfd6-1f4d-46d7-babf-61657deef302.jpg?t=r:w375-h250-sfit,e:fjpg-c80', title: 'Adventures', content: 'Hosted trips including lodging'},
        { pic: 'https://a0.muscache.com/4ea/air/v2/pictures/da2d8e97-90b7-409f-94ac-5ab0327c289b.jpg?t=r:w375-h250-sfit,e:fjpg-c80', title: 'Restaurants', content: 'Popular spots to eat & drink'}
      ]
    }

  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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

  .special-container {
    max-width: 1680px;
    padding: 0 80px;
  }

  .content-cards .card-arb {
    box-shadow: rgba(0, 0, 0, 0.06) 0px 2px 4px 0px;
    border: 1px solid rgba(0, 0, 0, 0.1);
  }

  .card-arb p {
    font-size: 16px;
  }

  .card-arb span {
    color: rgb(118, 118, 118);
    font-size: 12px;
    font-weight: 500;
    line-height: 1.3em;
    display: inherit;
  }

  .card-arb img {
    height: 72px;
    width: 86px;
  }

  .jobs-container {
    height: 100vh;
    background-color:#efefef;
  }
</style>
