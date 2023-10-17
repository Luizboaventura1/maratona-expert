<template>
  <div class="background">
    <v-container class="h-screen d-flex align-center overflow-hidden">
      <v-row class="flex-column-reverse flex-sm-row">
        <v-col
          class="px-3"
          cols="12"
          sm="6"
        >
          <h1
            class="text-white font-weight-bold"
          >
            Se inscreva na maratona <span class="text-light-blue-darken-1">Expert 2.0</span> que acontecerá nos dias 18 a 22 de outubro!
          </h1>
          <p
            class="text-grey-lighten-1 my-3"
          >
            Aprenda as melhores estratégias do mercado e viva <strong>100% do Marketing Digital.</strong>
          </p>
          <div class="d-flex flex-column w-100">
            <EmailInput />
            <div class="my-2"></div>
            <SubscribeButton>
              Me inscrever agora!
            </SubscribeButton>
          </div>
        </v-col>
        <v-col
          cols="12"
          sm="6"
        >
          <img
            class="w-100"
            src="./assets/manoel-gomes-e1677602876152-removebg-preview.png"
            alt="Manoel Gomes"
          >
        </v-col>
      </v-row>

    </v-container>
  </div>
</template>

<script setup>
import SubscribeButton from './components/SubscribeButton.vue';
import EmailInput from './components/EmailInput.vue'


</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Inter',sans-serif !important;
}

.background {
  background-color: #121214;
}

::-webkit-scrollbar {
  background-color: #121214;
  width: 10px;
}

::-webkit-scrollbar-thumb {
  background-color: rgb(46, 46, 46);
}

@media screen and (max-width: 768px) {
  .background {
    h1 {
      font-size: 25px;
    }

    p {
      font-size: 15px;
    }
  }
}

</style>