<template>
    <div class="top-bar text-center position-relative">
        <div class="top-bar-inner">

            <a class="menu-toggler" href="https://themes.3rdwavemedia.com/profolio/bs5/contact.html#offcanvasNavbar" role="button" aria-controls="offcanvasNavbar">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-list"
                    viewBox="0 0 16 16">
                    <path fill-rule="evenodd"
                        d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z">
                    </path>
                </svg>
            </a>

            <div class="mode-toggle text-center">
                <input class="toggle" id="darkmode" type="checkbox">
                <label class="toggle-btn mx-auto mb-0" for="darkmode">
                    <span class="day-icon toggle-icon"> <i class="bi bi-sun-fill"></i></span>
                    <span class="night-icon toggle-icon"><i class="bi bi-moon-fill"></i></span>
                </label>
            </div><!--//mode-toggle-->

            <a class="btn btn-primary top-bar-cta" href="https://themes.3rdwavemedia.com/profolio/bs5/contact.html">
                Hire Me
            </a>

            <!-- Social Menu -->
            <TheSocialList class="d-none d-lg-block"></TheSocialList>

        </div><!--//top-bar-inner-->
    </div><!--//top-bar-->
</template>