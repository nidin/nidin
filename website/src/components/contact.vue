<script setup lang="ts">
import ProfileItem from './profile-item.vue'
import IconCommunity from './icons/IconCommunity.vue'
</script>

<template>
  <ProfileItem>
    <template #icon>
      <IconCommunity />
    </template>
    <template #heading>Contact</template>
    <ul>
      <li>
        <a href="https://github.com/nidin" target="_blank">Github</a>
      </li>
      <li>
        <a href="https://www.linkedin.com/in/nidinvinayakan/" target="_blank">LinkedIn</a>
      </li>
      <li>
        <a href="https://twitter.com/01alchemist" target="_blank">Twitter</a>
      </li>
    </ul>
  </ProfileItem>
</template>
