<template>
  <v-card class="mx-auto my-16 px-6 py-8" max-width="100%">
    <v-row>
      <v-col cols="6" :style="{ backgroundColor: '#D3D3D3' }">
        <h1>Information</h1>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Optio ratione corporis eveniet doloribus, accusamus
          est animi, consequuntur in natus quaerat commodi delectus nisi facilis? Error at quas ad cum officia.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos dolore neque minima quas saepe incidunt impedit
          cum esse sunt cupiditate, optio nisi! Maxime officia distinctio sequi adipisci suscipit quaerat recusandae!
        </p>
        <v-btn to="/login">Have An Account</v-btn>
      </v-col>
      <v-col cols="6" :style="{ backgroundColor: '#003366' }">
        <h1 class="mx-16">REGISTER FORM </h1>
        <div class="d-flex justify-center ">
          <v-text-field class="mx-2" label="First Name" variant="outlined"></v-text-field>
          <v-text-field class="mx-2" label="Last Name"></v-text-field>
        </div>
        <div>
          <v-text-field label="Email"></v-text-field>
        </div>
        <div class="d-flex justify-center">
          <v-text-field class="mx-2" label="Password"></v-text-field>
          <v-text-field class="mx-2" label="Confirm Password"></v-text-field>
        </div>
        <div class="d-flex ">
          <v-checkbox></v-checkbox>
          <p class="my-5">I agree to the <a href="#">terms of service</a></p>
        </div>
        <div>
          <v-btn to="/home">Register</v-btn>
        </div>
      </v-col>
    </v-row>
  </v-card>
</template>

<script>
export default {
}
</script>
