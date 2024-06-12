<template>
    <h2>{{ firstname }} {{ lastname }}</h2>
</template>

<script>
export default {
    props: ['firstname', 'lastname']
}
</script>