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
        // Open Graph metadata
        // {
        //   hid: `og:image`,
        //   property: `og:image`,
        //   content: `https://www.advokats.kz/og_index_page_${this.$i18n.locale}.jpg`,
        // },
        {
          hid: `og:title`,
          property: `og:title`,
          content: `Github Play`,
        },
        {
          hid: `og:description`,
          property: `og:description`,
          content: `My github pages play website`,
        },
      ],
    }
  },
}
</script>
