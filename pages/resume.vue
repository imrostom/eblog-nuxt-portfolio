<template>
    <div class="container-fluid">

        <!-- Sidebar Panel Load-->
        <TheSidebar></TheSidebar>

        <div class="main-content-wrapper">
            <div class="container-fluid">

                <!-- Topbar Load -->
                <TheTopbar></TheTopbar>

                <div class="resume-wrapper mx-auto rounded-2">

                    <AuthorInformation></AuthorInformation>

                    <div class="resume-body p-4 p-lg-5">
                        <div class="row">
                            <div class="col-main col-12 col-lg-8 pe-lg-4">
                                <section class="resume-summary-section resume-section">
                                    <h3 class="resume-section-heading text-uppercase py-2 py-lg-3 py-2 py-lg-3">
                                        <i class="resume-section-heading-icon bi bi-person me-2"></i>
                                        About Me
                                    </h3>

                                    <div class="resume-summary-desc">
                                        Summarise your career profile here lorem ipsum dolor sit amet, consectetuer
                                        adipiscing elit. Aenean commodo ligula eget dolor aenean massa. Cum sociis natoque
                                        penatibus et magnis dis parturient montes, nascetur ridiculus mus.
                                    </div>
                                </section>

                                <hr>

                                <section class="resume-experience-section resume-section">
                                    <h3 class="resume-section-heading text-uppercase py-2 py-lg-3 py-3">
                                        <i class="resume-section-heading-icon bi bi-briefcase me-2"></i>Work Experience
                                    </h3>
                                    <div class="resume-timeline position-relative">
                                        <WorkExperience></WorkExperience>

                                        <WorkExperience></WorkExperience>
                                        
                                        <WorkExperience></WorkExperience>
                                    </div>
                                </section>
                            </div>

                            <div class="col-12 col-lg-4 ps-lg-4">
                                <TechStack></TechStack>

                                <hr>

                                <SoftSkill></SoftSkill>

                                <hr>
                                
                                <EducationHistory></EducationHistory>

                                <hr>

                                <LanguageHistoy></LanguageHistoy>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer Load -->
    <TheFooter></TheFooter>
</template>