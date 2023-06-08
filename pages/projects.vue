<template>
    <div class="container-fluid">
        
        <!-- Sidebar Panel Load-->
        <TheSidebar></TheSidebar>

        <div class="main-content-wrapper">
            <div class="container-fluid">

                <!-- Topbar Load -->
                <TheTopbar></TheTopbar>

                <!-- Author Info Load -->
                <AuthorIntroduction></AuthorIntroduction>

                <section class="projects-section section mx-auto">
                    <div class="row justify-content-center gx-lg-5">
                        <SingleProject></SingleProject>
                        <SingleProject></SingleProject>
                        <SingleProject></SingleProject>
                        <SingleProject></SingleProject>
                        <SingleProject></SingleProject>
                    </div>

                    <div class="section-cta text-center d-grid col-6 mx-auto">
                        <a class="btn btn-secondary">
                            Load More <span class="d-none d-lg-inline">projects</span>
                        </a>
                    </div>
                </section>

                <section class="leadgen-section section mx-auto">
                    <h3 class="section-heading text-start text-md-center text-highlight">
                        Need Help With Your Project?
                    </h3>

                    <div class="intro text-md-center">
                        Lead generation intro goes here lorem ipsum dolor sit
                        amet, consectetur adipiscing elit. Suspendisse placerat
                        egestas dui, quis ullamcorper massa pellentesque quis.
                    </div>
                    
                    <div class="text-center mt-4">
                        <a class="btn btn-secondary" href="https://themes.3rdwavemedia.com/profolio/bs5/contact.html">
                            Get In Touch
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                width="24"
                                height="24"
                                fill="currentColor"
                                class="bi bi-arrow-right-short"
                                viewBox="0 0 16 16"
                            >
                                <path
                                    fill-rule="evenodd"
                                    d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8z"
                                ></path>
                            </svg
                        >
                        </a>
                    </div>
                </section>

            </div>
        </div>
    </div>

    <TheFooter></TheFooter>

</template>
