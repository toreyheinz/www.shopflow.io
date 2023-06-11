<template lang="pug">
div.has-text-centered.mb-4
  h1.title Getting Started
  h2.subtitle With Shopflow you can track your customer jobs and streamline your workflow.

div.container.mb-4
  div.content.narrow
    h3.title.mb-2 Schedule a Demo
    p This is the best way for you to find out more about Shopflow and determine if Shopflow is a good fit. We only want to offer Shopflow where the value will far exceed the investment, and you think it's absolutely worth every penny!

    p Discover how you can track your customer jobs and streamline your workflow with Shopflow.

    p
      |Schedule your Shopflow demo here:&nbsp;
      a(href="https://calendly.com/shopflow-marine/shopflow-demo") https://calendly.com/shopflow-marine/shopflow-demo

  div.content.narrow
    h3.title.mt-4.mb-2 Follow up with a Shopflow consultation
    p Once we have determined that Shopflow will be a good fit, we'll schedule a one to two hour consultation.

    p During this time we'll gather info and provide as much value as we can. Often times we can eliminate some daily frustrations during our first session.

    p The goal is to gain trust on both sides. You want confidence that Shopflow will work for your shop, and that we know what we are doing. We want to make sure that you will put the work into streamlining your shop, and most importantly, we want to make sure you are fun to work with :)


    p
      |Schedule a Shopflow consultation here:&nbsp;
      br
      a(href="https://calendly.com/shopflow-marine/initial-shopflow-consultation") https://calendly.com/shopflow-marine/initial-shopflow-consultation

  div.content.narrow
    h3.title.mt-4 Commit to a Shopflow Membership Plan
    p At this stage, the next step is to commit to a Shopflow membership plan and implementation package.

  div
    stripe-pricing-table(
      pricing-table-id="prctbl_1M9DPeDbE68GNJbzJreUKZWi"
      publishable-key="pk_live_51M8spZDbE68GNJbzzcMJv3rXaGBNnPtkhLfKDkXIplB7x0japoyyitVeBoWMb9wzz6707nlJQRmJcLNiShj14HSu009EHQjNMd"
    )

  div.content.narrow
    p It is not required to sign up for an implementation package, but it is highly recommended. The payment process is similar to the annual membership, 50% down with the remainder due one month after we go live.
</template>

<script setup>
import { useScriptTag } from '@vueuse/core'

useScriptTag('https://js.stripe.com/v3/pricing-table.js')
</script>
