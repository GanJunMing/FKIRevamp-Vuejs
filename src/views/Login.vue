<template>
<v-card color="#E0E0E0" height="500px" width=500px elevation>
  <v-container>
  <v-form
    ref="form"
    v-model="valid"
    lazy-validation
  >
  <v-img style="text-align:center">
    <img :src="require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/fki.png')" height="100px">
  </v-img>
  <v-toolbar color="light-blue accent-1">
    <v-spacer />
    <v-toolbar-title class="font-weight-light"> Login to Event Management System</v-toolbar-title>
    <v-spacer />
  </v-toolbar>
    
    <v-text-field
      v-model="email"
      :rules="emailRules"
      label="UMS E-mail"
      hint="Using UMS staff or student email"
      required
    ></v-text-field>

    <v-text-field
      :append-icon="show1 ? 'mdi-eye' : 'mdi-eye-off'"
      :rules="[rules.required, rules.min]"
      :type="show1 ? 'text' : 'password'"
      name="input-10-1"
      label="Password"
      hint="At least 8 characters with 1 Uppercase and symbol"
      counter
      @click:append="show1 = !show1">
      </v-text-field>

    <v-row>
      <v-container class="text-center">
        <v-btn
        :disabled="!valid"
        color="success"
        class="mr-4"
        @click="validation"
        rounded>
        Login
        </v-btn>

        <v-btn
          color="error"
          class="mr-4"
          @click="reset"
          rounded>
          Reset
        </v-btn>
      </v-container>
    </v-row>
    
    <p></p>
    <p class="text--secondary" style="text-align:center">*If you not register yet, proceed to Registeration</p>
    <v-container class="text-center">
      <v-btn color="#EEEEEE" light flat router-link to="/register">Register</v-btn>
    </v-container>
  </v-form>
  </v-container>
</v-card>  
</template>

<script>
  export default {
    data: () => ({
      valid: true,
      email: '',
      emailRules: [
        v => !!v || 'E-mail is required',
        v => /.+@.+\..+/.test(v) || 'E-mail must be valid',
      ],
      show1:false,
      password:'Password',
      rules: {
          required: value => !!value || 'Required.',
          min: v => v.length >= 8 || 'Min 8 characters',
          emailMatch: () => ('The email and password you entered don\'t match'),
        },
    }),

    methods: {
      validate () {
        this.$refs.form.validate()
      },
      reset () {
        this.$refs.form.reset()
      },
    },
  }
</script>