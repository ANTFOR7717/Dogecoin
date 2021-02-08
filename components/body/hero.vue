<template>
  <div class="reduce-margin tile is-ancestor">
    <section class="container is-hd">

    <div class="tile is-parent">

      <article class="doge-gradient category tile is-clipped is-child notification is-primary is-rounded">

        <div class="columns">

          <div class="column is-one-quarter"></div>
          <div class="column">
            <div>
            <span class="speech-bubble title has-text-weight-bold mt-4 is-pulled-right is-wide-tracking has-text-black is-size-3">
              Dogecoin is an open-source peer-to-peer digital currency, favored by Shiba Inus worldwide.</span>
              </div>
          </div>

        </div>

        <div class="columns">

          <div class="column">
            <img class="dogedog" width="300rem" src="https://raw.githubusercontent.com/drjdaverth/doge_assets/master/assets/Logos/Vector/clean.vector.svg" alt="dogedog">
            </div>

          <div class="column">

            <div class="columns section">

           <div class="column">

            <p class="block"></p>
            <p class="pb-4 is-size-7 has-text-grey has-text-weight-bold">Start using dogecoin today:</p>

           <div class="columns">

               <div class="column">
                 <button class="button">
                   <span class="icon">
                    <i class="fab fa-github"></i>
                   </span>
                   <span class="is-block is-size-7 has-text-weight-bold">Download</span>
                 </button>

                 <button class="button">
                   <span class="icon">
                    <i class="fab fa-github"></i>
                   </span>
                   <span class="is-block is-size-7 has-text-weight-bold">Purchase</span>
                 </button>

               </div>





             </div>

           </div>




            </div>

          </div>

          <div class="column is-one-quarter"></div>



        </div>

      </article>

    </div>
    </section>

  </div>
</template>

<script>
export default {
  name: "hero"
}
</script>

<style scoped>

.dogedog {
  transform: scaleX(-1);
  float: left;
  margin-top: -70px;
  margin-bottom: -80px;
}

.speech-bubble {
  padding: 1.5rem 0 1.5rem 1rem;
  margin-right: 8rem;
  border-radius: .5rem;
  border: 1px solid #f4e4c0;
  background: rgb(251,235,200);
  background: linear-gradient(49deg, rgba(251,235,200,1) 0%, rgba(254,245,229,1) 21%, rgba(255,250,242,1) 100%);
}

.doge-gradient {
  background: rgb(248,211,142);
  background: linear-gradient(49deg, rgba(248,211,142,1) 0%, rgba(251,227,183,1) 38%, rgba(255,254,252,1) 100%);
}

.is-rounded {
  border-radius: 1.5rem;
}

.reduce-margin {
  margin-top: -2.5rem;
}

.is-wide-tracking {
  line-height: 2.75rem;
}
</style>
