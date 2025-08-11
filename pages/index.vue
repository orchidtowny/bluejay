<script setup>
import PageHeader from '../components/PageHeader.vue'
import PageFooter from '../components/PageFooter.vue'
import CopyIPButton from '../components/CopyIPButton.vue'
import Button from '../components/Button.vue'
import Heading from '../components/Heading.vue'
import Card from '../components/Card.vue'
import VotingSite from '../components/VotingSite.vue'
import Supporter from '../components/Supporter.vue'
import SupportBox from '../components/SupportBox.vue'
</script>

<template>
  <div>
    <div class="pageHeader">
      <PageHeader />
      <div class="pageHeaderContent">
        <div class="pageHeaderItemContainer">
          <div class="pageHeaderItem">
            <span class="pageHeaderItemText">
              <strong>Welcome to Orchid!</strong> We're a community built on the hope to make Minecraft a more accepting and comfortable
              place, while still offering the best non-pay-to-win gameplay possible.
            </span>
            <br><br>
            <CopyIPButton />
            <Button href="https://discord.orchidmc.org">Join us on Discord</Button>
          </div>
        </div>
      </div>
    </div>
    <div id="features" class="pageContent">
      <div class="pageItemContainer">
        <Heading>Some of our Features</Heading>
        <div class="pageItemContent">
          <Card icon="sf" title="Slimefun"
            body="Here on Orchid we have a plugin called Slimefun, which is a plugin similar to a technology modpack for Spigot. We don't just have the basics of Slimefun though, we have several addons to make your Slimefun adventure more challenging. Once you finish one thing, you can almost always find another with our Slimefun setup!" />
          <Card icon="ty" title="Towny"
            body="Using Towny, you can build the empire you've always wanted to. Start up towns and build with other players, and grow your own nation with the help of others. Attack your enemies in flag-based wars, or become the next ally to a great nation. It's all your choice with Towny!" />
          <Card icon="nptw" title="Not Pay-to-Win"
            body="We try our best to avoid pay to win aspects on Orchid, and that's why all of our supporter ranks only have perks that can be acheived in the survival ranks. Aside from different chat appearances, there aren't huge advantages for supporters." />
          <Card icon="ca" title="Custom & Advanced"
            body="With our years of experience in this game, we've been able to craft a unique and custom experience, including some of our own plugins and unique ideas. Alongside that, the support we've received over the past few months has allowed us to further improve the server and deliver a lag-free experience and premium plugins that improves the lives of the staff and players." />
        </div>
      </div>
      <div id="vote" class="pageItemContainer">
        <Heading>Vote for Orchid</Heading>
        <div class="pageItemContent">
          <p class="pageItemContentItemBody">Currently Unavailable</p>
        </div> 
      </div>
      <!--
      <div id="supporters" class="pageItemContainer">
        <Heading>Our Supporters</Heading>
        <div class="pageItemContent pageItemContentSupporters">
          <SupportBox />
        </div>
      </div>
      -->
    </div>
    <PageFooter />
  </div>
  <NuxtPage />
</template>
