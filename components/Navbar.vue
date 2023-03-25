<template>
    <nav class="navbar navbar-expand-md navbar-light bg-light sticky-top shadow-lg"
        style="background-color: #242423 !important;">
        <div class="container p-2">
            <router-link class="navbar-brand" style="font-family: 'Caveat', cursive; font-size: 1.5rem; color: white;" to="/">NaimKamil</router-link>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto p-2">
                    <li class="nav-item">
                        <router-link class="nav-link test" to="/work" style="color: #d3d3d3;">Work</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link test" to="/about" style="color: #d3d3d3;">About</router-link>
                    </li>
                    <li class="nav-item">
                        <a target="_blank"
                            href="https://drive.google.com/file/d/1Hrr9p7mu5_qQMgCLVQYSukkeZqf1ae9n/view?usp=share_link"
                            class="btn" style="color: #d3d3d3;">Resume</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>
  
<script>
export default {
}
</script>
<style scoped>
.router-link-exact-active {
    color: aqua;
}

.test:hover {
    color: aqua;
}

.btn {
    background-color: gray;
    color: white;
    padding-top: 5px;
    padding-bottom: 5px;
    padding-left: 8px;
    padding-right: 8px;
    margin-top: 2px;
    border-radius: 10px;
}

.btn:hover {
    background-color: aqua;
    color: black !important;
}

</style>