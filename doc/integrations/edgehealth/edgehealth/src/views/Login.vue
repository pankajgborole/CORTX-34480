<template>
  <div class="about">
      <v-container fill-height fluid>
        <br>

  <v-row align="center"
      justify="center" class="mt-4">
      <v-card height="80vh" width="80vw" >
        <v-subheader   style="background-color:#f1f1f1;"  :inset="inset">
          <v-row>
            <v-btn text icon><v-icon size="30">mdi-arrow-left</v-icon></v-btn>
          </v-row>
      </v-subheader>
      <div class="mt-3" style="overflow:hidden;overflow-y:scroll;height:68vh">
        <p class="text-h4 font-weight-bold text-center">Login</p>
        <p class="text-body1 text-center">Hello! Log in with your email.</p>

        <v-row>
          <v-col cols="12" xs="12" sm="12" md="3" lg="3" xl="3"></v-col>
          <v-col cols="12" xs="12" sm="12" md="6" lg="6" xl="6">
            <div>
          <label class="text-caption font-weight-bold" style="color:grey" for="">Email Address:</label>
          <v-text-field style="font-size:14px" type="email" required outlined placeholder="Email Address"></v-text-field>
        </div>
        <div>
          <label class="text-caption font-weight-bold" style="color:grey" for="">Password:</label>
          <v-text-field style="font-size:14px" type="password" outlined placeholder="Password"></v-text-field>
        </div>
          <div>
            <v-checkbox
              v-model="checkbox"
              class="font-weight-bold text-caption"
              :label="`Remember me`"
            ></v-checkbox>
          </div>
          <div>
             <v-btn large block>
              Login
            </v-btn>
          </div>
          <div>
            <br>
            <p class="text-caption text-center">or enter with:</p>
          </div>
          <div>
            <v-row>
              <v-spacer></v-spacer>
                <v-icon class="mr-5">mdi-twitter</v-icon>
                <v-icon class="mr-5">mdi-facebook-messenger</v-icon>
                <v-icon >mdi-github</v-icon>
              <v-spacer></v-spacer>
            </v-row>
          </div>
          <div>
            <p class="text-body1 text-center mt-5">Don't have an account? <a href="/register" style="color:grey">Register</a></p>
          </div>
          </v-col>
          <v-col cols="12" xs="12" sm="12" md="3" lg="3" xl="3"></v-col>
        </v-row>
      </div>
      </v-card>
  </v-row>
</v-container>
  </div>
</template>
<script>
export default {
  
}
</script>
<style>
::-webkit-scrollbar-thumb{
   
}
</style>
