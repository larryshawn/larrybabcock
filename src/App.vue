// <template>
//   <div id="app">
//     <img src="./assets/logo.png">
//     <router-view/>
//   </div>
// </template>

<template>
    <div id="app">
        <div class="wrap-banner">
            <div class="main-title">
                <h1>{{ title }}</h1>
                <p>{{ msg }}</p>
            </div>
            <vue-particles
                color="#dedede"
                :particleOpacity="0.7"
                :particlesNumber="80"
                shapeType="circle"
                :particleSize="4"
                linesColor="#dedede"
                :linesWidth="1"
                :lineLinked="true"
                :lineOpacity="0.4"
                :linesDistance="150"
                :moveSpeed="3"
                :hoverEffect="true"
                hoverMode="grab"
                :clickEffect="true"
                clickMode="push"
            >
            </vue-particles>
        </div>
        <v-container grid-list-md text-xs-center>
            <div class="main-section">
                <h2>About me</h2>
                <v-layout class="ma-3">
                    <v-flex xs12 sm6 offset-sm3>
                        <v-card hover="true">
                            <v-card-media src="https://vuetifyjs.com/static/doc-images/cards/desert.jpg" height="200px">
                            </v-card-media>
                            <v-card-title primary-title>
                                <div>
                                    <h3 class="headline mb-0">Kangaroo Valley Safari</h3>
                                    <div>Located two hours south of Sydney in the <br>Southern Highlands of New South Wales, ...</div>
                                </div>
                            </v-card-title>
                            <v-card-actions>
                                <v-btn flat color="orange">Share</v-btn>
                                <v-btn flat color="orange">Explore</v-btn>
                            </v-card-actions>
                        </v-card>
                    </v-flex>
                </v-layout>
                <v-layout class="ma-3">
                    <v-flex xs12 sm6 offset-sm3>
                        <v-card hover="true">
                            <v-card-media
                            class="white--text"
                            height="200px"
                            src="https://vuetifyjs.com/static/doc-images/cards/docks.jpg"
                            >
                                <v-container fill-height fluid>
                                    <v-layout fill-height>
                                        <v-flex xs12 align-end flexbox>
                                            <span class="headline">Top 10 Australian beaches</span>
                                        </v-flex>
                                    </v-layout>
                                </v-container>
                            </v-card-media>
                            <v-card-title>
                                <div>
                                    <span class="grey--text">Number 10</span><br>
                                    <span>Whitehaven Beach</span><br>
                                    <span>Whitsunday Island, Whitsunday Islands</span>
                                </div>
                            </v-card-title>
                            <v-card-actions>
                                <v-btn flat color="orange">Share</v-btn>
                                <v-btn flat color="orange">Explore</v-btn>
                            </v-card-actions>
                        </v-card>
                    </v-flex>
                </v-layout>
                <v-layout class="ma-3">
                    <v-flex xs12 sm6 offset-sm3>
                        <v-card hover="true">
                            <v-card-media
                            src="http://larrybabcock.com/images/v2/q-oasis.jpg"
                            height="200px"
                            >
                            </v-card-media>
                            <v-card-title primary-title>
                                <div>
                                    <div class="headline">Top western road trips</div>
                                    <span class="grey--text">1,000 miles of wonder</span>
                                </div>
                            </v-card-title>
                            <v-card-actions>
                                <v-btn flat>Share</v-btn>
                                <v-btn flat color="purple">Explore</v-btn>
                                <v-spacer></v-spacer>
                                <v-btn icon @click.native="show = !show">
                                    <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
                                </v-btn>
                            </v-card-actions>
                            <v-slide-y-transition>
                                <v-card-text v-show="show">
                                    I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
                                </v-card-text>
                            </v-slide-y-transition>
                        </v-card>
                    </v-flex>
                </v-layout>
                <p>
                    In the future, will you be able to iteratively incentivize deliverables in your business? Our business integrates siloes to ethically and conservatively strategize our long-term action point. We use our company-wide low hanging fruit to proactively manage our executive search expectations. It's critical that we give 110% when intelligently aligning enterprises.
                </p>
                <p>
                    Mission critical dot-bombs are becoming knowledge transfer bandwidth experts. Best-of-breed synergies dynamically enable world-class platforms for our standpoints. Virtually touching base about impacting user experiences will make us leaders in the immersive vertical industry. We use our unparalleled big datas to reliably manage our proposition expectations.
                </p>
                <p>
                    It's critical that we give 110% when effectively relaying core assets. Going forward, our competitive innovation will deliver value to paradigm shifts. We aim to globally reuse our agile workflow by strategically growing our best-in-class value-added industry leaders. Our ballpark figure development lifecycle enables innovative, wholesale brands.
                </p>
                <p>
                    We aim to reliably monetize our architecture by effectively transforming our end-to-end proactive alignments. Our Senior Capability solution offers clouds a suite of mobile offerings. Our Seamless Best Practice solution offers stand-ups a suite of customer-focused offerings. Conservatively facilitating globally holistic game changers is crucial to our next-generation team player.
                </p>
                <p>
                    Efficiencies will come from intelligently engineering our market foci. We use our corporate organic growths to iteratively manage our step-change expectations. Actionable visibilities proactively enable corporate milestones for our capabilities. Change the way you do business - adopt innovative standard setters.
                </p>
                <p>
                    You need to dynamically synergise your stacks to increase your driver velocity. In the future, will you be able to strategically connect prince2 practitioners in your business? Is your emerging market prepared for best-in-class diversity growth? Senior core competencies are becoming end-to-end enterprise experts.
                </p>
                <p>
                    Efficiencies will come from ethically offshoring our stakeholders. Value-added user experiences virtually enable long-term big datas for our brands. Key players will take ownership of their clouds by proactively calibrating knowledge transfer synergies. We aim to effectively revolutionize our dot-bomb by virtually virtualising our company-wide proactive emerging markets.
                </p>
                <p>
                    In the future, will you be able to dynamically invest platforms in your business? So we can hit the ground running, we will be ethically deep-diving every team player in our space. Globally touching base about right-sizing capabilities will make us leaders in the best-of-breed visibility industry. Next-generation ballpark figures reliably enable mission critical enterprises for our propositions.
                </p>
            </div>
        </v-container>
    </div>
</template>

<script>

export default {
  name: 'app',
  data () {
    return {
      title: 'Hello',
      msg: 'My name is Larry Babcock. I build web applications.',
      show: false
    }
  }
}
</script>

<style>
    body, html {
        height: 100%;
    }
    body {
        margin: 0;
        background-color: white;
    }
</style>

<style scoped>
    #app {
        height: 100%;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
    }

    .wrap-banner {
        position: relative;
        -ms-flex-align: center;
        -webkit-box-align: center;
        align-items: center;
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        height: 100%;
        -webkit-box-pack: center;
        -ms-flex-pack: center;
        justify-content: center;
    }
    .main-title {
        color: #fff;
        z-index: 999;
    }
    .main-title h1 {
        font-size: 7rem;
        text-shadow: 8px 8px #000;
        text-transform: uppercase;
        margin: 0;
    }
    #particles-js {
        background-image: url(./assets/night-sky.jpg);
        background-size: cover;
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
    canvas {
        width: 100%;
        height: 100%;
        display: inline-block;
    }
    .card-hero {
        background-position: top!important;
    }
</style>
