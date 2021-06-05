<template>
    <div style="text-align:center">
        <h1 class="font-weight-black">CONTACT US</h1>
        <p class="font-weight-bold">WELCOME TO FACULTY COMPUTER AND INFORMATICS</p>
        <v-row justify="space-around">
            <span class="group pa-3">
                <v-icon x-large>{{facebook}}</v-icon>
                <v-icon x-large>{{instagram}}</v-icon>
                <v-icon x-large>{{gmail}}</v-icon>
                <v-icon x-large>{{whatsapp}}</v-icon>
                <v-icon x-large>{{telegram}}</v-icon>
            </span>
        </v-row>
        <v-spacer></v-spacer>
        <v-row>
            <v-img>
                <img :src="require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/soaring.png')" height="150px" alt="logo">
            </v-img>
            <v-divider></v-divider>
            <v-list>
                <v-list-item>
                    <v-row>
                    <v-icon large>{{map}}</v-icon>
                    <p style="font-size:20px">University Malaysia Sabah, Jalan UMS, Kota Kinabalu, Sabah</p>
                </v-row>
                </v-list-item>
                <v-list-item>
                <v-row>
                    <v-icon large>{{phone}}</v-icon>
                    <p style="font-size:20px">Phone: (+6088) 320000  Ext.: 613708 / 613710</p>
                </v-row>
                </v-list-item>
                <v-list-item>
                <v-row>
                    <v-icon large>{{email}}</v-icon>
                    <p style="font-size:20px">Email: Fki@ums.edu.my</p>
                </v-row>
                </v-list-item>
            </v-list>
        </v-row>
    </div>
</template>

<script>
import { mdiFacebook } from '@mdi/js'
import { mdiCellphone } from '@mdi/js'
import { mdiEmailSendOutline } from '@mdi/js'
import { mdiInstagram } from '@mdi/js'
import { mdiGmail } from '@mdi/js'
import { mdiWhatsapp } from '@mdi/js'
import { mdiTelegram } from '@mdi/js'
import { mdiMapOutline } from '@mdi/js'

export default{
    props: {
        source: String,
    },
    data: () =>({
        map: mdiMapOutline,
        phone: mdiCellphone,
        email: mdiEmailSendOutline,
        facebook: mdiFacebook,
        instagram: mdiInstagram,
        gmail: mdiGmail,
        whatsapp:mdiWhatsapp,
        telegram: mdiTelegram,
        soaring: require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/soaring.png')
    })
}
</script>