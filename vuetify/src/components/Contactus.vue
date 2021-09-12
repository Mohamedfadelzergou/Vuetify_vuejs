<template>
  <v-container class="my-15">
      <v-row justify="center">
          <v-col lg="12" class="text-center">
              <v-subheader class="text-h4 justify-center">
                  Contact Us
              </v-subheader>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam, quam!</p>
          </v-col>
          <v-col lg="6">
              <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d4663.975224467514!2d-6.654711850506265!3d34.250367835293744!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xda759f872e481eb%3A0x6205db86f328949!2sALLIANCE%20MEHDIA!5e0!3m2!1sfr!2sma!4v1631475345717!5m2!1sfr!2sma" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
          </v-col>
          <v-col lg="6">
              <v-form ref="form" >
                    <v-text-field
                    v-model="contactinfo.name"
                    :counter="10"
                    label="Name"
                    required
                    ></v-text-field>

                    <v-text-field
                    v-model="contactinfo.email"
                    label="E-mail"
                    required
                    ></v-text-field>
                    <v-textarea label="Massage" v-model="contactinfo.message"></v-textarea>
                    <v-btn
                    color="success"
                    class="mr-4"
                    >
                    Send
                    </v-btn>
                </v-form>
          </v-col>
      </v-row>
  </v-container>
</template>

<script>
export default {
    name:'Contactus',
    data(){
        return {
            contactinfo:{
                name:'',
                email:'',
                message:''
            }
        }
    }
}
</script>

<style>

</style>