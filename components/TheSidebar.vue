<template>
    <div class="side-panel position-relative">
        <nav class="navbar">
            <div class="offcanvas offcanvas-start show d-flex" id="offcanvasNavbar">
                <div class="offcanvas-body d-flex align-items-center ">
                    <ul class="main-nav navbar-nav text-center">

                        <li class="nav-item">
                            <NuxtLink to="/" class="nav-link d-flex flex-column">
                                <span class="icon-holder">
                                    <svg class="svg-inline--fa fa-circle-user" aria-hidden="true"
                                        focusable="false" data-prefix="fas" data-icon="circle-user" role="img"
                                        xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M399 384.2C376.9 345.8 335.4 320 288 320H224c-47.4 0-88.9 25.8-111 64.2c35.2 39.2 86.2 63.8 143 63.8s107.8-24.7 143-63.8zM512 256c0 141.4-114.6 256-256 256S0 397.4 0 256S114.6 0 256 0S512 114.6 512 256zM256 272c39.8 0 72-32.2 72-72s-32.2-72-72-72s-72 32.2-72 72s32.2 72 72 72z">
                                        </path>
                                    </svg>
                                </span>
                                <span class="nav-text">About</span>
                            </NuxtLink>
                        </li>

                        <li class="nav-item">
                            <NuxtLink to="/projects" class="nav-link d-flex flex-column">
                                <span class="icon-holder">
                                    <svg class="svg-inline--fa fa-briefcase" aria-hidden="true"
                                        focusable="false" data-prefix="fas" data-icon="briefcase" role="img"
                                        xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M184 48H328c4.4 0 8 3.6 8 8V96H176V56c0-4.4 3.6-8 8-8zm-56 8V96H64C28.7 96 0 124.7 0 160v96H192 320 512V160c0-35.3-28.7-64-64-64H384V56c0-30.9-25.1-56-56-56H184c-30.9 0-56 25.1-56 56zM512 288H320v32c0 17.7-14.3 32-32 32H224c-17.7 0-32-14.3-32-32V288H0V416c0 35.3 28.7 64 64 64H448c35.3 0 64-28.7 64-64V288z">
                                        </path>
                                    </svg>
                                </span>
                                <span class="nav-text">Projects</span>
                            </NuxtLink>
                        </li>

                        <li class="nav-item">
                            <NuxtLink to="blog" class="nav-link d-flex flex-column">
                                <span class="icon-holder">
                                    <svg class="svg-inline--fa fa-pen-fancy" aria-hidden="true"
                                        focusable="false" data-prefix="fas" data-icon="pen-fancy" role="img"
                                        xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M373.5 27.1C388.5 9.9 410.2 0 433 0c43.6 0 79 35.4 79 79c0 22.8-9.9 44.6-27.1 59.6L277.7 319l-10.3-10.3-64-64L193 234.3 373.5 27.1zM170.3 256.9l10.4 10.4 64 64 10.4 10.4-19.2 83.4c-3.9 17.1-16.9 30.7-33.8 35.4L24.4 510.3l95.4-95.4c2.6 .7 5.4 1.1 8.3 1.1c17.7 0 32-14.3 32-32s-14.3-32-32-32s-32 14.3-32 32c0 2.9 .4 5.6 1.1 8.3L1.7 487.6 51.5 310c4.7-16.9 18.3-29.9 35.4-33.8l83.4-19.2z">
                                        </path>
                                    </svg>
                                </span>
                                <span class="nav-text">Blog</span>
                            </NuxtLink>
                        </li>

                        <li class="nav-item">
                            <NuxtLink to="/resume" class="nav-link d-flex flex-column">
                                <span class="icon-holder">
                                    <svg class="svg-inline--fa fa-file-lines" aria-hidden="true"
                                        focusable="false" data-prefix="fas" data-icon="file-lines" role="img"
                                        xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512" data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M64 0C28.7 0 0 28.7 0 64V448c0 35.3 28.7 64 64 64H320c35.3 0 64-28.7 64-64V160H256c-17.7 0-32-14.3-32-32V0H64zM256 0V128H384L256 0zM112 256H272c8.8 0 16 7.2 16 16s-7.2 16-16 16H112c-8.8 0-16-7.2-16-16s7.2-16 16-16zm0 64H272c8.8 0 16 7.2 16 16s-7.2 16-16 16H112c-8.8 0-16-7.2-16-16s7.2-16 16-16zm0 64H272c8.8 0 16 7.2 16 16s-7.2 16-16 16H112c-8.8 0-16-7.2-16-16s7.2-16 16-16z">
                                        </path>
                                    </svg>
                                </span>
                                <span class="nav-text">Resume</span>
                            </NuxtLink >
                        </li>

                        <li class="nav-item">
                            <NuxtLink to="/contact" class="nav-link d-flex flex-column">
                                <span class="icon-holder">
                                    <svg class="svg-inline--fa fa-comment-dots" aria-hidden="true"
                                        focusable="false" data-prefix="fas" data-icon="comment-dots" role="img"
                                        xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M256 448c141.4 0 256-93.1 256-208S397.4 32 256 32S0 125.1 0 240c0 45.1 17.7 86.8 47.7 120.9c-1.9 24.5-11.4 46.3-21.4 62.9c-5.5 9.2-11.1 16.6-15.2 21.6c-2.1 2.5-3.7 4.4-4.9 5.7c-.6 .6-1 1.1-1.3 1.4l-.3 .3 0 0 0 0 0 0 0 0c-4.6 4.6-5.9 11.4-3.4 17.4c2.5 6 8.3 9.9 14.8 9.9c28.7 0 57.6-8.9 81.6-19.3c22.9-10 42.4-21.9 54.3-30.6c31.8 11.5 67 17.9 104.1 17.9zM128 272c-17.7 0-32-14.3-32-32s14.3-32 32-32s32 14.3 32 32s-14.3 32-32 32zm128 0c-17.7 0-32-14.3-32-32s14.3-32 32-32s32 14.3 32 32s-14.3 32-32 32zm160-32c0 17.7-14.3 32-32 32s-32-14.3-32-32s14.3-32 32-32s32 14.3 32 32z">
                                        </path>
                                    </svg>
                                </span>
                                <span class="nav-text">Contact</span>
                            </NuxtLink>
                        </li>

                        <li class="nav-item nav-item-close">
                            <button class="btn-close" type="button">
                                <i class="bi bi-x"></i>
                            </button>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </div>
</template>