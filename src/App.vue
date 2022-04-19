<script setup>
import PresentationContainer from './components/PresentationContainer.vue';
import TitleSlide from './components/slides/TitleSlide.vue';
import TopicOverview from './components/slides/TopicOverview.vue';
import FirstTopicSlide from './components/slides/FirstTopicSlide.vue';
import TopicOverviewReminder from './components/slides/TopicOverviewReminder.vue';
import SecondTopicSlide from './components/slides/SecondTopicSlide.vue';
import FinalTopicReminder from './components/slides/FinalTopicReminder.vue';
import SecondTopicSlideCont from './components/slides/SecondTopicSlideCont.vue';
import TopicOverviewRecap from './components/slides/TopicOverviewRecap.vue';

const bigIdeas = [
  "What is the Franck-Hertz Experiment?",
  "Can we show that atoms only accept quantized energy amounts?",
  "Can we determine the value of Mercury's first excitation level?"
]
</script>

<template>
  <PresentationContainer id="#app">
    <TitleSlide />
    <TopicOverview :bigIdeas="bigIdeas" />
    <FirstTopicSlide />
    <TopicOverviewReminder :bigIdeas="bigIdeas" />
    <SecondTopicSlide />
    <FinalTopicReminder :bigIdeas="bigIdeas" />
    <SecondTopicSlideCont />
    <TopicOverviewRecap :bigIdeas="bigIdeas" />
  </PresentationContainer>
</template>

<style>
#app {
  margin-top: 20px;
  height: 90vh;
}
</style>

