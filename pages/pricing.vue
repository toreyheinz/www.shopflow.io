<template lang="pug">
div.has-text-centered
  h1.title Shopflow Pricing
  h2.subtitle With Shopflow you can track your customer jobs and streamline your workflow.
  //- script(async src="https://js.stripe.com/v3/pricing-table.js")
  stripe-pricing-table(
    pricing-table-id="prctbl_1M9DPeDbE68GNJbzJreUKZWi"
    publishable-key="pk_live_51M8spZDbE68GNJbzzcMJv3rXaGBNnPtkhLfKDkXIplB7x0japoyyitVeBoWMb9wzz6707nlJQRmJcLNiShj14HSu009EHQjNMd"
  )
</template>

<script setup>
import { useScriptTag } from '@vueuse/core'

useScriptTag('https://js.stripe.com/v3/pricing-table.js')
</script>
