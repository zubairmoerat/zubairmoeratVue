<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid">
            <img src="https://drive.google.com/uc?id=1Uawwx3E8Yfw8vMGHBGycEhHsceacEClP" class="img-thumbnail" alt="logo"
                loading="lazy">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText"
                aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarText">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <router-link to="/" class="nav-link active">
                            Home
                        </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/about" class="nav-link active">
                            About Me
                        </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/resume" class="nav-link active">
                            Resume
                        </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/projects" class="nav-link active">
                            Projects
                        </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/testimonials" class="nav-link active">
                            Testimonials
                        </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/contact" class="nav-link active">
                            Contact Me
                        </router-link>
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

<style scoped></style>