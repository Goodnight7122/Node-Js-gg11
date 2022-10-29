<template>
    <div>
        <Navbar />
        <section class="home">
            <div class="image">
                <img src="images/profile.png" alt="">
            </div>
            <div class="content">
                <h3>hi, i am Suramesuan Saknitinad</h3>
                <span>Learning by Doing.</span>
                <p>Hi am Good im now study at Bangkok Universit,School of Engineering</p>
                <a href="about.html" class="btn"> about me <i class="fas fa-user"></i> </a>
            </div>
        </section>
    </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";

export default {
    components: { Navbar }
}
</script>

<style>

</style>