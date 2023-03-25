<template>
    <div class="container-lg mainpage">
        <h1 class="mb-5" style="text-decoration: underline; font-size: 3rem;">
            Projects</h1>
        <div class="row">
            <div class="col-md-6 mb-3">
                <div id="container">
                    <img src="../assets/images/jomdobi.png" style="width:100%" alt="naim">
                </div>
            </div>
            <div class="col-md-6 mb-3">
                <h1>Jom!Dobi</h1>
                <p>
                    <span style="color: grey;">Case Study</span> <br>
                    Mobile application that helps laundry users to do laundry more efficiently.
                </p>
                <div class="mt-4">
                    <NuxtLink style="text-decoration: underline;" to="/projectdetails">See more</NuxtLink>
                </div>
            </div>
            <div class="col-md-6 mb-3">
                <div id="container">
                    <img src="../assets/images/jomdentist.png" style="width:100%" alt="naim">
                </div>
            </div>
            <div class="col-md-6 mb-3">
                <h1>JomDentist</h1>
                <p>
                    <span style="color: grey;">Case Study • Final Year Project</span> <br>
                    Mobile application for primary schools student to learn and get to know how to take care of their dental
                    health.
                </p>
                <div class="mt-4">
                    <NuxtLink style="text-decoration: underline;" to="/projectdetails">See more</NuxtLink>
                </div>
            </div>
            <div class="col-md-6 mb-3">
                <div id="container">
                    <img src="../assets/images/jomvaccine.png" style="width:100%" alt="naim">
                </div>
            </div>
            <div class="col-md-6 mb-3">
                <h1>Jom!Vaccine</h1>
                <p>
                    <span style="color: grey;">Case Study</span> <br>
                    A user-friendly mobile application that helps everyone book a vaccination appointment for a variety of
                    vaccines - minus the fuss & long waits.
                </p>
                <div class="mt-4">
                    <NuxtLink style="text-decoration: underline;" to="/projectdetails">See more</NuxtLink>
                </div>
            </div>
            <div class="col-md-6 mb-3">
                <div id="container">
                    <img src="../assets/images/citra.png" style="width:100%" alt="naim">
                </div>
            </div>
            <div class="col-md-6 mb-3">
                <h1>Animation</h1>
                <p>
                    <span style="color: grey;">Freelance</span> <br>
                    Animation video to promote Sains Citra,UKM course to the students that want to pursue degree.
                </p>
                <div class="mt-4">
                    <NuxtLink style="text-decoration: underline;" to="/projectdetails">See more</NuxtLink>
                </div>
            </div>
            <div class="col-md-6 mb-3">
                <div id="container">

                    <img src="../assets/images/toshibajet.png" style="width:100%" alt="naim">
                </div>
            </div>
            <div class="col-md-6 mb-3">
                <h1>Toshibajet</h1>
                <p>
                    <span style="color: grey;">Case Study</span> <br>
                    Web application for Toshiba products, with new experience and simpler design to match the aesthetics.
                </p>
                <div class="mt-4">
                    <NuxtLink style="text-decoration: underline;" to="/projectdetails">See more</NuxtLink>
                </div>
            </div>
            <div class="col-md-6 mb-3">
                <div id="container">

                    <img src="../assets/images/wakemeup.png" style="width:100%" alt="naim">
                </div>
            </div>
            <div class="col-md-6 mb-3">
                <h1>WakeMeUp!</h1>
                <p>
                    <span style="color: grey;">Case Study</span> <br>
                    A horror game with challenging puzzles that require the player to think critically and creatively to
                    progress through the game.
                </p>
                <div class="mt-4">
                    <NuxtLink style="text-decoration: underline;" to="/projectdetails">See more</NuxtLink>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    head: {
    title: 'NaimKamil | Work',
  }
}
</script>

<style scoped>

* {
    font-family: 'Roboto Mono', monospace;
}

img {
    border-radius: 25px;
}

.mainpage {
    margin-top: 8% !important;
}

#container img {
    display: block;
    transition: transform .4s;
}

#container:hover img {
    transform: scale(1.2);
    transform-origin: 50% 50%;
}

#container {
    overflow: hidden;
    border-radius: 25px;
}</style>