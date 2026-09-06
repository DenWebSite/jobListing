<script setup>
import Hero from '@/components/Hero.vue';
import HomeCards from '@/components/HomeCards.vue';
import JobListing from '@/components/JobListings.vue';
</script>

<template>
    <Hero title="Become a Vue Dev" subtitlle="Find the Vue job that fits your skills and needs" />
    <HomeCards />
    <JobListing :limit="3" :showButton="true" />
</template>