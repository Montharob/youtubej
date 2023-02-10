<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>💜 VITAMIN ENRICHED FACE BASE💄</template>

    <a href="https://vuejs.org/" target="_blank" rel="noopener">www.bobbibrown.co.th</a>
    It is a pre-makeup skin preparation product that combines with many vitamins that will make the skin look full, soft and bouncy. Adjust the skin to be consistent so that the makeup can be lasting and more beautiful.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>💜 INTENSIVE SERUM FOUNDATION SPF 40 PA++++💄</template>

    This project is served and bundled with
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener">Vite</a>This model is a foundation designed to have a light texture, not heavy on the skin. It can also be applied to become one with the skin easily. Makes the face not floating, not white and also gives a look of skin work that looks very natural.

    <br />

    More instructions are available in <code>www.bobbibrown.co.th</code>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>💜SKIN WEIGHTLESS POWDER FOUNDATION💄</template>

    Lightness and comfort on the face and add moisture at the same time, can be smoothly attached to the skin seamlessly. Helps to hide unwanted pores and wrinkles for naturally beautiful skin. With a special semi-creamy texture, it fuses a light touch with a healthy-looking complexion. Sweat and moisture protection Maintain the condition for the skin to look bright. Does not change color or look dull during the day.
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">www.bobbibrown.co.th</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>💜BRIGHTENING BLUSH COLLECTION💄</template>

    Create a beautiful look to welcome spring with Brightening Blush products that are available in 3 shades in a single compact.
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener">www.bobbibrown.co.th</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>💜CRUSHED LIP COLOR💄</template>

    Get a matte look that's comfortable and comfortable with a balm-like texture, rich in pigments and nourishing ingredients that last and every time, every time used.
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">www.bobbibrown.co.th</a>.
  </WelcomeItem>
</template>
