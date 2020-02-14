<template>
  <div class="companies">
      <h4>More than 2.1 million businesses and organizations use GitHub</h4>
      <main>
          <img src="@/assets/airbnb-logo.png" alt="" srcset="">
          <img src="@/assets/sap-logo.png" alt="" srcset="">
          <img src="@/assets/ibm-logo.png" alt="" srcset="">
          <img src="@/assets/google-logo.png" alt="" srcset="">
          <img src="@/assets/paypal-logo.png" alt="" srcset="">
          <img src="@/assets/bloomberg-logo.png" alt="" srcset="">
          <img src="@/assets/spotify-logo.png" alt="" srcset="">
          <img src="@/assets/swift-logo.png" alt="" srcset="">
          <img src="@/assets/facebook-logo.png" alt="" srcset="">
          <img src="@/assets/node-logo.png" alt="" srcset="">
          <img src="@/assets/nasa-logo.png" alt="" srcset="">
          <img src="@/assets/walmart-logo.png" alt="" srcset="">
      </main>
  </div>
</template>

<script>
export default {
    name:'Companies'
}
</script>

<style lang="scss" scoped>
    .companies{
        height: 323px;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        h4{
            color: #aaa;
            font-size: 20px;
            margin-bottom: 24px;
        }
    }
    main{
        height: 111px;
        width: 100%;
        display: flex;
        max-width: 980px;
        justify-content: center;
        flex-wrap: wrap;
        img{
            width: auto;
            height: 25px;
            margin: 16px 10px;
            padding: 0 32px;
        }
    }
</style>