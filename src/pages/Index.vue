<template lang='pug'>
Layout
    v-form(netlify name='test1')
        input(name='contenu')

    v-btn(@click='dialog = true')
    v-dialog
        v-form(netlify nae='test2')
</template>

<script lang='coffee'>
export default
    data: ->
        dialog: null
</script>