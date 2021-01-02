<template>
     <div class="section-one">
          <div class="row">
               <div class="col1">
                    <img src="../assets/sect1-img.png" alt="" srcset="">
               </div>
               <div class="col2">
                    <h3>Say goodbye to busywork</h3>
                    <p>Most “productivity” tools get in your way and constantly disrupt your flow. There’s a more enlightened way to work. Dropbox helps people be organized, stay focused, and get in sync with their teams.
                    </p>
               </div>
          </div>
     </div>
</template>

<script>
     export default {
          name: 'SectionOne',
     }
</script>

<style scoped>
.section-one {
     /* display: flex; */
     height: 924px;
     background: #FFE7AA;
     align-items: center;
     padding: 0px 100px;
}

.row {
     display: flex;

}

.col2 {
     padding-left: 100px;
}

.col2 h3 {
     font-size: 32px;
     font-weight: normal;
     color: #0D2F81;
     width: 284px;
     margin-bottom: 30px;
     margin-top: 270px;
}

.col2 p {
     font-size: 16px;
     font-weight: normal;
     color: #000000;
     width: 315px;
}

img {
     margin-top: -40px;
     max-height: 790px;
     max-width: 632px;
}
</style>