<template>
     <div class="jumbo">
          <h1 class="title">Dropbox</h1>
          <h1 class="campaign">Focus on the work that matters</h1>
          <h2 class="lead">Dropbox is the world’s first smart workspace. We bring all your team’s content together while letting you use the tools you love. And we help cut through the clutter, surfacing what matters most.
          </h2>
     </div>
</template>

<script>
     export default {
          name: 'Jumbo',
     }
</script>

<style scoped>
.jumbo {
     padding: 0px 75px ;
     color: white;
     background-color: transparent;
}

.title {
     color: #ffe7aa;
     font-size: 30px;
     /* line-height: 32px; */
     font-weight: 600;
     margin-bottom: 20px;
}

.campaign {
     color: #ffe7aa;
     font-size: 73px;
     font-weight: 500;
     margin-bottom: 40px;
     width: 512px;
}

.lead {
     font-size: 20px;
     font-weight: 400;
     margin-bottom: 20px;
     width: 410px;
}
</style>