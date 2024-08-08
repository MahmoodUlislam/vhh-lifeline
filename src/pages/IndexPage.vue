<template>
  <q-page class="flex flex-center">
    <div class="q-pa-md">
      <q-card>
        <q-card-section>
          <div class="text-h6">Welcome to My Quasar App</div>
          <div class="text-subtitle1">This is a single-page application.</div>
        </q-card-section>

        <q-card-actions align="right">
          <q-btn flat label="Learn More" @click="learnMore" />
        </q-card-actions>
      </q-card>
    </div>
  </q-page>
</template>

<script>
export default {
  name: "IndexPage",
  methods: {
    learnMore() {
      alert("This is a demo single-page application using Quasar.");
    },
  },
};
</script>

<style scoped>
.q-page {
  max-width: 600px;
  margin: 0 auto;
}
</style>
