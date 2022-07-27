<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>About</template>

    Hi there! I'm Mirik. Software Engineer from Uzbekistan!
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tooling</template>

      I use PHP (Laravel), JavaScript (Vue js), Docker to build amazing projects.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Experience</template>

      Freelancing: January 2021 - January 2022
      <br>
      <a target="_blank" href="https://techcells.com">Techcells:</a> January 2022 - Current
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

    <a target="_blank" href="https://t.me/brogrammerblog">Brogrammer's blog</a>, My telegram chanel about programming
    <a target="_blank" href="https://t.me/laravelengineer">Laravel Engineer</a>, Want to talk about <a target="_blank" href="https://laravel.com">Laravel</a>
      <br>
    Also subscribe to my social societies:
      <br>
      <a href="https://instagram.com/akhmirik"><img src="/src/assets/icons8-instagram-48.png" alt=""></a>
      <a href="https://www.facebook.com/mirsaid.axmedov.9/"><img src="/src/assets/icons8-facebook-48.png" alt=""></a>
      <a href="https://instagram.com/akhmirik"><img src="/src/assets/icons8-github-48.png" alt=""></a>
      <a href="https://www.linkedin.com/in/mirsaid-akhmedov-1581b01b9/"><img src="/src/assets/icons8-linkedin-48.png" alt=""></a>
      <a href="https://www.codegrepper.com/profile/mirsaid-akhmedov"><img style="width: 48px; height: 48px" src="/src/assets/download.jpeg" alt=""></a>
      <br>
    Contact me: <br>
      <a href="https://t.me/akhmirik"><img src="/src/assets/icons8-telegram-app-48.png" alt=""></a>
      <a href="mailto:mirsaid@mirik.engineer"><img src="/src/assets/icons8-mail-48.png" alt=""></a>
  </WelcomeItem>
</template>
