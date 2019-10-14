<template>
  <q-page class="flex flex-center">
    <img alt="Quasar logo" src="~assets/quasar-logo-full.svg">
  </q-page>
</template>

<script>
import AmazonCognitoIdentity from 'amazon-cognito-identity-js'
const poolData = {
  UserPoolId: 'us-east-1_600Y779bG',
  ClientId: '30rfub86h78pjl65p3rr2eoc8j'
}
console.log('>', AmazonCognitoIdentity, poolData)
export default {
  name: 'PageIndex'
}
</script>
