<template>
  <div class="team-member">
    <div class="member-photo"></div>
    <p class="member-info">
      <strong>{{ name }}</strong><br />
      {{ position }}
    </p>
  </div>
</template>

<script>
export default {
  name: 'TeamMember',
  props: {
    name: {
      type: String,
      required: true,
    },
    position: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped>
.team-member {
  display: flex;
  flex-direction: column;
  color: #000;
  text-align: center;
  font: 400 30px/36px TT Fors Trial, -apple-system, Roboto, Helvetica, sans-serif;
}

.member-photo {
  background-color: #475eea;
  border-radius: 50%;
  height: 373px;
  aspect-ratio: 1;
}

.member-info {
  margin-top: 45px;
}

@media (max-width: 991px) {
  .team-member {
    margin-top: 40px;
  }

  .member-info {
    margin-top: 40px;
  }
}
</style>