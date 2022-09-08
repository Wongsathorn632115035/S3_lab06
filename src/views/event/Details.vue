<template>
  <p>{{ event.id }} on {{ event.organizer }} @ {{ event.location }}</p>
 
</template>

<script>
export default {
  props: ['event']
}
</script>
