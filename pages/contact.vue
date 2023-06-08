<template>
    <div class="container-fluid">

        <!-- Sidebar Panel Load-->
        <TheSidebar></TheSidebar>

        <div class="main-content-wrapper">
            <div class="container-fluid">
                
                <!-- Topbar Load -->
                <TheTopbar></TheTopbar>

                <section class="page-intro-section section has-profile-image mx-auto ">

                    <div class="profile-holder text-center">
                        <img class="profile-pic rounded-circle" src="~/assets/images/profile.png" alt="image">
                    </div>
                    
                    <div class="intro-holder">
                        <h2 class="intro-name text-center">Get In Touch</h2>
                        <div class="contact-intro text-md-center limit-max-width mx-auto">
                            <p>Contact intro goes here. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis placerat sodales massa vitae ornare. Quisque ac ipsum quam. </p>
                        </div>


                        <!-- Social Menu Load For Responsive -->
                        <TheSocialList class="d-block d-lg-none py-3 text-center"></TheSocialList>

                    </div>

                    <!-- Contact Form Load -->
                    <TheContactForm></TheContactForm>

                </section>
            </div>
        </div>
    </div>

    <!-- Footer Load -->
    <TheFooter></TheFooter>
</template>