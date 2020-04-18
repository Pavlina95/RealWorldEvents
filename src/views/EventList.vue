<template>
  <div>
    <h1>Events List:</h1>
    <!-- <router-link :to="{ name: 'event-show', params: { id: 'Pavlina' } }">
      Show Pavlina's Event
    </router-link> -->
    <EventCard />
  </div>
</template>

<script>
import EventCard from '../components/EventCard.vue'

export default {
  components: {
    EventCard
  }
}
</script>
