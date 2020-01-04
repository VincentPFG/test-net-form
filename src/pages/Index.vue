<template lang='pug'>
Layout

</template>

<script lang='coffee'>
export default
    mounted: -> console.log await @$axios.get 'f/test'
</script>