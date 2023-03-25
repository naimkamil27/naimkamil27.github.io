<template>
    <div class="container">
        <h1 class="mb-5 text-center" style="font-family: 'Roboto Mono', monospace; text-decoration: underline; font-size: 3rem;">Projects</h1>
        <div class="row">
            <div class="col-md-6 mb-4">
                <NuxtLink to="/projectdetails">
                    <img src="~/assets/images/jomdentist.png" style="width: 100%;" alt="">
                </NuxtLink>
                <h2 class="mt-3" style="font-family: 'Roboto Mono', monospace;">JomDentist</h2>
                <h5 style="font-family: 'Nunito Sans', sans-serif;">Full development • Mobile Development </h5>
            </div>
            <div class="col-md-6 mb-4">
                <NuxtLink to="/projectdetails">
                    <img src="~/assets/images/jomdobi.png" style="width: 100%;" alt="">
                </NuxtLink>
                <h2 class="mt-3" style="font-family: 'Roboto Mono', monospace;">Jom!Dobi</h2>
                <h5 style="font-family: 'Nunito Sans', sans-serif;">Full development • Mobile Development</h5></div>
            <div class="col-md-6 mb-4"><NuxtLink to="/projectdetails">
                    <img src="~/assets/images/citra.png" style="width: 100%;" alt="">
                </NuxtLink>
                <h2 class="mt-3" style="font-family: 'Roboto Mono', monospace;">Animation</h2>
                <h5 style="font-family: 'Nunito Sans', sans-serif;">Full development • Animation</h5>
            </div>  
            <div class="col-md-6 mb-4"><NuxtLink to="/projectdetails">
                    <img src="~/assets/images/jomvaccine.png" style="width: 100%;" alt="">
                </NuxtLink>
                <h2 class="mt-3" style="font-family: 'Roboto Mono', monospace;">Jom!Vaccine</h2>
                <h5 style="font-family: 'Nunito Sans', sans-serif;">UI/UX Design • Mobile Development</h5>
           </div>  
            <div class="col-md-6 mb-4"><NuxtLink to="/projectdetails">
                    <img src="~/assets/images/toshibajet.png" style="width: 100%;" alt="">
                </NuxtLink>
                <h2 class="mt-3" style="font-family: 'Roboto Mono', monospace;">Toshibajet</h2>
                <h5 style="font-family: 'Nunito Sans', sans-serif;">Full development • Website Development</h5>
            </div>  
            <div class="col-md-6 mb-4"><NuxtLink to="/projectdetails">
                    <img src="~/assets/images/wakemeup.png" style="width: 100%;" alt="">
                </NuxtLink>
                <h2 class="mt-3" style="font-family: 'Roboto Mono', monospace;">WakeMeUp</h2>
                <h5 style="font-family: 'Nunito Sans', sans-serif;">Full development • Game Development</h5>
           </div>               
        </div>
        <div class="d-flex justify-content-end">
            <NuxtLink to="/work">See More</NuxtLink>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style  scoped>

img {
    border-radius: 25px;
}

img:hover {
    box-shadow: 0 0 50px rgb(0, 255, 255, 0.3); 
    border: 10px;
}

</style>