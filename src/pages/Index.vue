<template lang='pug'>
Layout
    v-form(netlify name='test1')
        input(name='contenu')

    v-btn(@click='dialog = true')
    v-dialog(v-model='dialog')
        v-form(netlify name='test2')
    v-form(netlify name='test3')
</template>

<script lang='coffee'>
export default
    data: ->
        dialog: null
</script>