<script setup lang="ts">
import ProfileItem from './profile-item.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
</script>

<template>
  <ProfileItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>About me</template>
    I help companies to achieve agile-friendly implementation technology (like microservices) and
    architecture. I have extensive experience in building highly functional lean and agile
    organizations and designing and building robust, highly scalable software suitable for agile
    environments. As a software engineer, I am always curious about how things are working.
    Engineering skills are embedded in my DNA. Programming languages never laid barriers in my
    journey. For me logic is important, it may be expressed in a variety of languages. During my
    career journey, I mastered several languages and technologies but my quick learning skills are
    ready to absorb any new technology at my will.
  </ProfileItem>

  <ProfileItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Skills</template>

    Agile Software Development・Engineering Leadership・Machine Learning・Recommendation
    Engine・Search Engine・Compiler Design・Artificial Intelligence・Data Science・JavaScript・
    TypeScript・React ・ Vue・Angular・HTML・CSS・ExpressJS・NestJS・NodeJS・Python・Django・
    Java・Spring Boot・SQL・GLSL・C++・Qt・WebGL・WebGPU・WebAssembly・Terraform・NGINX・
    Docker・Kubernetes・AWS・Google Cloud Platform・Heroku・Salesforce・PostgreSQL・MySQL
    ・ElasticSearch・MongoDB・Redis・IoT・MQTT・PlatformIO・Arduino・Google Assistant・ Matter
  </ProfileItem>

  <ProfileItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Talks & Community Projects</template>
    <ul>
      <li>Webassembly & WebGPU W3C Community Member</li>
      <li>
        <a href="https://www.meetup.com/WebAssembly/events/252271717/"
          >Introduction to AssemblyScript (WebAssemblyEU 2018)</a
        >
      </li>
      <li>
        <a
          href="https://2017.jsconf.eu/speakers/nidin-vinayakan-shared-memory-parallel-programming-with-javascript"
          >Shared Memory & Parallel Programming with JavaScript (JS Conference EU 2017)</a
        >
      </li>
      <li><a href="https://github.com/01alchemist/TurboScript">TurboScript</a></li>
      <li><a href="https://github.com/AssemblyScript/assemblyscript">AssemblyScript</a></li>
      <li><a href="https://github.com/01alchemist/x-ray.js">X-Ray Renderer</a></li>
      <li><a href="https://github.com/nidin/TS-LZMA">LZMA</a></li>
      <li><a href="https://github.com/nidin/as3-XFL-compiler">Adobe Flash XFL Compiler</a></li>
    </ul>
  </ProfileItem>
</template>
