<template>
  <div>
    <div class="profile">
      <div class="photo">
        <img
          src="../assets/eu.jpg"
          width="166"
          height="166"
          alt="profile photo"
        />
        <div class="border">
          <img
            width="204"
            height="204"
            src="https://cdn.akamai.steamstatic.com/steamcommunity/public/images/items/322330/beaee5e90d93bfafa5f5f55acb23abfd28ad180c.png"
          />
        </div>
      </div>
      <div class="description">
        <span class="text">Tullio Rohers Rauber</span>
        <img
          class="profile_flag"
          src="https://community.akamai.steamstatic.com/public/images/countryflags/br.gif"
          height="12"
        />
        <span class="text">Santa Cruz do Sul, Rio Grande do Sul, Brasil</span>
      </div>
      <div>
        <div>2 anos de exp</div>
        <div>medalhazinha</div>
        <div><button>tente</button> <button>teste2</button></div>
      </div>
    </div>
    <div class="info-content">
      <div>oii</div>
    </div>
  </div>
</template>

<script></script>

<style scoped>
.text {
  color: #c4c4c4;
  font-size: 13px;
}
.description {
  padding-inline: 24px;
  gap: 4px;
  display: flex;
}
.photo {
  position: relative;
}

.border {
  position: absolute;
  top: -20px;
  left: -20px;
}

.profile {
  display: flex;
  padding: 24px;
  background-color: rgba(51, 27, 16, 0.93);
  background: radial-gradient(
      farthest-side at bottom right,
      rgba(252, 197, 16, 0.301),
      transparent 800px
    ),
    radial-gradient(
      farthest-corner at bottom left,
      rgba(9, 243, 153, 0.247),
      transparent 800px
    );
}
.info-content {
  display: flex;
  background-color: rgba(51, 27, 16, 0.93);
  background: radial-gradient(
      farthest-side at top right,
      rgba(252, 197, 16, 0.301),
      transparent 500px
    ),
    radial-gradient(
      farthest-corner at top left,
      rgba(9, 243, 153, 0.247),
      transparent 600px
    ),
    radial-gradient(
      farthest-corner at bottom right,
      rgba(252, 197, 16, 0),
      transparent 500px
    ),
    radial-gradient(
      farthest-corner at bottom left,
      rgba(48, 243, 9, 0.13),
      transparent 600px
    );
}
</style>
