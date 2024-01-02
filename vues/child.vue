<template>
  <div>
      <vcard-title>child</vcard-title>
      <vcard-text>{{ someInput }} </vcard-text>
  </div>
</template>
<script>
module.exports = { 
                    components: {
                          childCard
                        },
                    props: ['someInput']}

</script>