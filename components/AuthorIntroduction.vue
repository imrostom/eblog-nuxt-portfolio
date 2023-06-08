<template>
    <section class="page-intro-section section has-profile-image mx-auto">

        <div class="profile-holder text-center">
            <img class="profile-pic rounded-circle" src="~/assets/images/profile.png" alt="image">
        </div><!--//profile-holder-->

        <div class="intro-holder">
            <h2 class="intro-name text-center mb-3">Md Rostom Ali</h2>
            <div class="profile-intro text-md-center limit-max-width mx-auto">
                <p>Hi! I’m a Senior Developer with more than ten years of experience working in mobile banking apps. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Welcome to my online portfolio! Check out my <NuxtLink to="/projects">latest projects and case studies</NuxtLink>.</p>
            </div>
        </div><!--//intro-holder-->

        <div class="section-cta text-center mt-4">
            <NuxtLink to="/resume" class="btn btn-secondary theme-btn-cta">
                View Resume
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor"
                    class="bi bi-arrow-right-short" viewBox="0 0 16 16">
                    <path fill-rule="evenodd"
                        d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8z">
                    </path>
                </svg>
            </NuxtLink>
        </div>

    </section>
</template>