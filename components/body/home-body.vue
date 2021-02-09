<template>
<section class="section container is-max-desktop">
  <div class="columns">
    <div class="column">
      <section class="section">
      <h1 class="block title is-size-9 has-text-weight-bold has-text-black">How to get started with Dogecoin</h1>
      <p class="block has-text-weight-medium has-text-gray is-size-8"> Setting up a Dogecoin wallet is easy as 1, 2, 3 Seriously! <br>
      If you don't have a wallet, download one below.</p>
      <button class="block button button-large-padding is-rounded is-primary has-text-weight-semibold"><span class="has-text-weight-bold has-text-black is-size-6">iPhone Wallet</span></button>
        <button class="block button button-large-padding is-rounded is-primary has-text-weight-semibold"><span class="has-text-weight-bold has-text-black is-size-6">Android Wallet</span></button>
        <p class="block has-text-weight-medium has-text-gray is-size-8"> Once you're done, you're ready to use the Dogecoin exchanger!
        The cheapest way to get Dogecoin is to convert it from its origin Litecoin.
        Purchase LTC to store in your wallet down below!</p>

        <iframe src="https://changelly.com/static/payment-button-widget/index.html?paymentButtonTheme=default&buttonTextId=003&widgetLink=https%3A%2F%2Fwidget.changelly.com%3Ffrom%3Dusd%26to%3Dltc%252Ceth%252Cbtc%26amount%3D250%26address%3D%26fromDefault%3Dusd%26toDefault%3Dltc%26theme%3Ddefault%26merchant_id%3Dfhbf7e5w7h8xqpux%26payment_id%3D%26v%3D3&isPopUp=false" width="220" height="48" frameborder="0"></iframe>

      </section>
      <div class="height-holder"></div>
    </div>
    <div class="column">

      <iframe width="100%" height="100%" frameborder='none' src="https://widget.changelly.com?from=ltc%2Cbtc%2Ceth&to=doge&amount=1.272&address=&fromDefault=ltc&toDefault=doge&theme=default&merchant_id=fhbf7e5w7h8xqpux&payment_id=&v=3">Can't load widget</iframe>

    </div>

  </div>
</section>
</template>

<script>
export default {
  name: "home-body"
}
</script>

<style scoped>

.is-size-8 {
  font-size: .90rem;
}
.is-size-9 {
  font-size: 1.5rem;
}

.height-holder {
  height: 7.5rem;
}

.button-large-padding {
  padding: 1.2rem 2.5rem 1.2rem 2.5rem;
}

.has-text-gray {
  color: #777676;
}


</style>
