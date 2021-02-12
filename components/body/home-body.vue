<template>
<section class="section container is-max-desktop">
  <div class="columns">
    <div class="column">
      <section class="section">
      <h1 class="block title is-size-9 has-text-weight-bold has-text-color">How to get started with Dogecoin</h1>
      <p class="block has-text-weight-medium has-text-gray is-size-8 has-tracking-wider"> Setting up a Dogecoin wallet is easy as 1, 2, 3 Seriously!
      If you don't have a wallet, download one below.</p>
      <a href="https://apps.apple.com/us/app/exodus-mobile/id1414384820" class="block button button-large-padding is-rounded is-white has-text-weight-semibold">
        <span class="icon">
          <img src="/apple-icon.svg" alt="" height="auto">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </span>
        <span class="has-text-weight-bold has-text-black is-size-6">
          iPhone Wallet
        </span>
      </a>
        <a href="https://play.google.com/store/apps/details?id=exodusmovement.exodus" class="block button has-color-green is-white button-large-padding is-rounded has-text-weight-semibold">
          <span class="icon">
            <img src="/android-icon.svg" alt="" height="auto">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          </span>
          <span class="has-text-weight-bold has-text-black is-size-6">
            Android Wallet
          </span>
        </a>
        <p class="block has-text-weight-medium has-text-gray has-tracking-wider is-size-8"> Once you're done, you're ready to use the Dogecoin exchanger!
        The fastest way to get Dogecoin is to Convert it from LTC.
        Purchase LTC to store in your wallet down below!</p>
        <p class="block has-text-weight-medium has-text-gray has-tracking-wider is-size-8">
          You can also use Coinbase after signing up and get rewarded with over <b>$100 in crypto!</b>
        </p>

        <a href="https://widget.changelly.com/?from=usd&to=ltc%2Ceth%2Cbtc&amount=250&address=&fromDefault=usd&toDefault=ltc&theme=default&merchant_id=fhbf7e5w7h8xqpux&payment_id=&v=3"
           class="block button button-large-padding is-rounded is-white has-text-weight-semibold">
        <span class="icon">
          <img  src="/changelly-icon.png" alt="" height="200">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </span>
          <span class="has-text-weight-bold has-text-black is-size-6">
          Exchange Instantly
        </span>
        </a>
        <a href="https://www.coinbase.com/join/forest_w" class="block button button-large-padding is-rounded has-color-blue has-text-weight-semibold">
        <span class="icon">
          <img src="/coinbase_icon.svg" class="has-white-background" alt="" height="auto">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </span>
          <span class="has-text-weight-bold has-text-white is-size-6">
            Signup
        </span>
        </a>

      </section>
      <div class="height-holder"></div>
    </div>
    <div class="column">

      <iframe width="370px" height="600px" src="https://widget.changelly.com?from=ltc%2Cbtc%2Ceth&to=doge&amount=1.272&address=&fromDefault=ltc&toDefault=doge&theme=default&merchant_id=fhbf7e5w7h8xqpux&payment_id=&v=3">Can't load widget</iframe>

    </div>

  </div>
</section>
</template>

<script>
export default {
  name: "home-body",


}
</script>

<style scoped>

.has-tracking-wider {
  letter-spacing: .5px;
}

.is-size-8 {
  font-size: .90rem;
}
.is-size-9 {
  font-size: 1.5rem;
}

.button-large-padding {
  padding: 1.2rem 2.5rem 1.2rem 2.5rem;
}

.has-text-gray {
  color: #777676;
}

.has-text-color {
  color: #404040;
}

.has-color-green {
  color: #65b01d;
}

.has-color-blue {
  background-color: #1552f0;
}

.has-white-background {
  border: 1px solid white;
  border-radius: 5px;
}



</style>
