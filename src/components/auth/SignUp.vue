<template>
  <v-container fluid>
    <v-layout row wrap>
      <v-flex xs12 class="text-xs-center mt-5">
        <h1>Sign Up</h1>
      </v-flex>
      <v-flex xs12 sm6 offset-sm3 mt-3>
        <v-form>
          <v-layout column>
            <v-flex xs12>
              <v-text-field
              name="email"
              label="Email"
              id="email"
              type="email"
              required></v-text-field>
            </v-flex>
            <v-flex>
              <v-text-field
              name="password"
              label="Password"
              id="password"
              type="password"
              required></v-text-field>
            </v-flex>
            <v-flex>
              <v-text-field
              name="password_confirmation"
              label="Confirm Password"
              id="password_confirmation"
              type="password"
              required></v-text-field>
            </v-flex>
            <v-flex class="text-xs-center" mt-5>
              <v-btn color="primary" type="submit">Sign Up</v-btn>
            </v-flex>
          </v-layout>
        </v-form>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script type="text/javascript">
export default {
  name: 'SignUp',
  data() {
    return {};
  },
};
</script>
