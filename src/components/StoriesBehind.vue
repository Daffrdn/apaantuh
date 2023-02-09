<template>
    <div class="stories_behind">
        <meta charset="UTF-8">
        <!-- Header -->
        <el-row class="stories_behind_header">
            <el-col :xs="2" :sm="2" :md="2" :lg="2" :xl="2">
                <el-button @click="goBack()" class="back_button" type="danger" circle
                           icon="el-icon-d-arrow-left"></el-button>
            </el-col>
            <el-col :xs="24" :sm="24" :md="20" :lg="24" :xl="24">
                <h1>Doa Untuk Mbull &#128151;</h1>
            </el-col>
        </el-row>

        <el-row type="flex" justify="center">
            <el-col :xs="24" :sm="24" :md="20" :lg="16" :xl="16">
                <!-- Content -->
                <div class="block" style="overflow:auto">

                    <el-card class="SB_card">
                        <h3>Patmasari Febriyana&#128105;</h3>
                        <el-button @click="goGitHub()" type="danger" round>Happy Birthday for 22 Years Old </el-button>
                    </el-card>

                    <!-- TODO : Change these messages to your own words ... -->
                    <el-card class="SB_card">
                        <h3>Halloo sayangg yang ngeselin </h3>
                        <p>
                            Selamat ulang tahun sayangg yang ke 22 tahun<br>
                            Semoga sehat rohani dan jasmani<br>
                            Keinginannya dikabulkan, semoga cepet dapet kerja <br>
                            Rezekinya berlimpah, nurut samaa orang tua <br>
                            Amiiinn.. <br>
                        </p>
                        <p>
                            Jangan lupa sering sering solat kamutuh &#128512;<br>
                            Malem lupa suka cumuk, sering sering cumuk &#128512;<br>
                            Jan suka kesel kesel, soalnya kalau km kesel suka nular ke aku hehe &#128512;<br>
                            Dan yang terakhir, semoga kita langgeng, LUV U SAYANGNYA AKUU.. &#128151;&#128151;&#128151;<br>
                            SELAMAT ULANG TAHUN YANG KE 22 TAHUN SAYANG
                        </p>
                    </el-card>

                </div>
            </el-col>
        </el-row>
        

    </div>

</template>

<script>
    export default {
        name: "StoriesBehind",
        methods: {
            goBack() {
                this.$router.go(-1);
            },
            goGitHub() {
                
            }
        }
    }
</script>

<style scoped>
    .stories_behind_header {
        position: fixed;
        width: 100%;
        background: #ffffff;
        z-index: 1;
    }

    .block {
        margin-top: 80px;
        margin-bottom: 50px;
    }

    .back_button {
        margin-top: 15px;
        position: absolute;
    }

    .SB_card {
        width: 80%;
        margin: 0 auto 20px;
    }
    p{
        font-family: cursive;
    }

</style>