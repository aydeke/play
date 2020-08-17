<template lang="pug">
h1 Added meta array
</template>
<script>
export default {
  head() {
    return {
      meta: [
        // Keywords
        {
          hid: `keywords`,
          name: `keywords`,
          content: `github pages play`,
        },
        // Description
        {
          hid: `description`,
          name: `description`,
          content: `My github pages play website`,
        },
      ],
    }
  },
}
</script>
