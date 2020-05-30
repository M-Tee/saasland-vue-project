<template>
   <div class="has-text-centered our_services">
      <p class="title is-3">Our Services</p>
      <hr class="underline" />

      <div class="columns column_style">
        <div class="column " v-for="(obj, key) in  ServicesJSON" :key='key'>
          <div class="card card_style "> 
            <img
              src=""
              alt="icon"
              class="image is-48x48 is-rounded"
            />
            <p class="title is-5"> {{obj.title}} </p>
            <p class="description">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Itaque culpa recusandae, aspernatur aliquam voluptates
              mollitia
            </p>
          </div>
        </div> 
      </div>
      <div class="columns column_style">
        <div class="column">
          <div class="card card_style">
            <img
              src="https://image.flaticon.com/icons/png/512/148/148813.png"
              alt="icon"
              class="image is-48x48 is-rounded"
            />
            <p class="title is-5">UI/UX DESIGN</p>
            <p class="description">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Itaque culpa recusandae, aspernatur aliquam voluptates
              mollitia
            </p>
          </div>
        </div>
        <div class="column">
          <div class="card card_style">
            <img
              src="https://image.flaticon.com/icons/svg/814/814134.svg"
              alt="icon"
              class="image is-48x48 is-rounded"
            />
            <p class="title is-5">APP DEVELOPMENT</p>
            <p class="description">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Itaque culpa recusandae, aspernatur aliquam voluptates
              mollitia
            </p>
          </div>
        </div>
        <div class="column">
          <div class="card card_style">
            <img
              src="https://image.flaticon.com/icons/svg/814/814120.svg"
              alt="icon"
              class="image is-48x48 is-rounded"
            />
            <p class="title is-5">USER FRIENDLY INTERFACE</p>
            <p class="description">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Itaque culpa recusandae, aspernatur aliquam voluptates
              mollitia
            </p>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  data() {
    return{
      ServicesJSON: [
        {
          icon:'https://www.flaticon.com/premium-icon/icons/svg/2838/2838746.svg"',
          title: 'EASY TO USE',
          description: ` Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Itaque culpa recusandae, aspernatur aliquam voluptates
              mollitia`
        },
        {
          icon:'https://image.flaticon.com/icons/svg/148/148917.svg',
          title: 'AWESOME DESIGN',
          description: ` Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Itaque culpa recusandae, aspernatur aliquam voluptates
              mollitia`
        },
        {
          icon:'https://image.flaticon.com/icons/png/512/148/148752.png',
          title: 'EASY TO CUSTOMIZE',
          description: ` Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Itaque culpa recusandae, aspernatur aliquam voluptates
              mollitia`
        },
        {
          icon:'https://image.flaticon.com/icons/png/512/148/148752.png',
          title: 'EASY TO CUSTOMIZE',
          description: ` Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Itaque culpa recusandae, aspernatur aliquam voluptates
              mollitia`
        }
      ]
      
    }
  }
  
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
