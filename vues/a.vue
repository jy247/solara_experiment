<template>
  <div>
    <vcard :color="color_a">
      <vcard-title> {{ color_a }}</vcard-title>
      <vcard-text>A Contents</vcard-text>
    </vcard>
    <childCard someInput='something else'></childCard>
    <h1>The End</h1>
  </div>
</template>