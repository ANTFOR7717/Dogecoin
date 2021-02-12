<template>
  <div class="reduce-margin tile is-ancestor">
    <section class="container is-hd">

    <div class="tile is-parent">

      <article class="doge-gradient category tile is-clipped is-child notification is-primary is-rounded">

        <div class="columns">

          <div class="column is-one-quarter"></div>
          <div class="column">
            <div>
            <span class="speech-bubble tracking-tighter title has-text-weight-bold mt-4 is-pulled-right is-wide-tracking is-size-4-tablet is-size-5-mobile is-size-3-widescreen">
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
            <p class="pb-4 is-size-6 has-opacity has-text-weight-bold float-right">Start using Dogecoin today:</p>

           <div class="columns">

               <div class="column">
                 <a href="https://www.coinbase.com/join/forest_w" class="button is-rounded button-large-padding">
                   <span class="icon">
                    <img src="/coinbase_icon.svg" height="auto" alt="">&nbsp;&nbsp;&nbsp;&nbsp;
                   </span>
                   <span class="is-block is-size-7 has-text-weight-bold">
                     <span class="is-size-6">Earn crypto</span> <span class="coinbase-promo">up to $100</span></span>
                 </a>

                 <a href="https://dogecoin.ogn.app" class="button is-rounded button-large-padding">
                   <span class="icon">
                    <img src="/storefront-icon.png" alt="" height="100">&nbsp;&nbsp;&nbsp;
                   </span>
                   <span class="is-block is-size-6 has-text-weight-bold">Buy Merchandise</span>
                 </a>

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

.tracking-tighter {
  letter-spacing: -2.25px;
  color: #4a4a4a;
}

.dogedog {
  transform: scaleX(-1);
  float: left;
  margin-top: -70px;
  margin-bottom: -80px;
}

.coinbase-promo {
  background-color: #0cae69;
  color: white;
  padding: 5px 5px 5px 5px;
  border-radius: 2.5px;

 }

.float-right {
  margin-left: 4rem;
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

.has-opacity {
  opacity: 65%;
}

.button-large-padding {
  padding: 1.25rem 1.5rem 1.25rem 1.5rem;
}


.is-wide-tracking {
  line-height: 2.75rem;
}
</style>
