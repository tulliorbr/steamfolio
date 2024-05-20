<template>
  <div class="container">
    <video
      playsinline
      autoplay
      muted
      loop
      poster="https://cdn.cloudflare.steamstatic.com/steamcommunity/public/images/items/1272160/180e4ddb43b4c567670a3186c3c636ef93f6d0b1.JPG"
    >
      <source
        src="https://cdn.cloudflare.steamstatic.com/steamcommunity/public/images/items/1272160/b3a767c82f40ab060368a341f88c9ea35e532277.webm"
        type="video/webm"
      />
      <source
        src="https://cdn.cloudflare.steamstatic.com/steamcommunity/public/images/items/1272160/1a44c57d0db1f5ce697124473aba9a16ede5846c.mp4"
        type="video/mp4"
      />
    </video>
      <slot class="content" />
  </div>
</template>

<script lang="ts"></script>

<style scoped>
video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: -1;
  object-fit: cover;
}

.container {
  justify-content: center;
  display: flex;
}

.content {
  max-width: 800px;
  height: max-content;
}
</style>
