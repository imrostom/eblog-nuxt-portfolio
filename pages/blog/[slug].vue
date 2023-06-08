<template>
    <div class="container-fluid">

        <!-- Sidebar Panel Load-->
        <TheSidebar></TheSidebar>

        <div class="main-content-wrapper">
            <div class="container-fluid">

                <!-- Topbar Load -->
                <TheTopbar></TheTopbar>

                <section class="blog-post-section section has-profile-image mx-auto">
                    <div class="profile-holder text-center">
                        <img class="profile-pic rounded-circle" src="assets/images/profile.png" alt="image">
                    </div><!--//profile-holder-->

                    <div class="blog-breadcrumb">
                        <a class="blog-home-link" href="blog-home.html">
                            <i class="bi bi-arrow-left"></i> Back To Blog Home
                        </a>
                    </div>

                    <div class="blog-entry">
                        <article class="post">
                            <h2 class="post-title text-center py-2">Blog Post Heading Lorem Ipsum</h2>
                            <div class="post-author text-center mb-3">By <a href="index.html">Daniel Lopez</a></div>
                            <div class="post-meta">
                                <ul class="meta-list list-inline d-flex justify-content-center">
                                    <li class="list-inline-item post-time">Apr 19</li>
                                    <li class="list-inline-item post-length">8 min read</li>
                                    <li class="list-inline-item post-comments-link">
                                        <a href="#blog-comment-area">6 comments</a>
                                    </li>

                                </ul><!--//meta-list-->

                            </div><!--post-meta-->

                            <div class="post-content">
                                <p class="post-figure">
                                    <img class="img-fluid rounded" src="assets/images/blog/blog-post-banner.jpg"
                                        alt="image">
                                </p><!--//post-figure-->
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin lobortis mattis erat,
                                    dictum facilisis magna posuere ac. Curabitur consectetur magna mauris, et aliquam lectus
                                    ornare nec. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur
                                    ridiculus mus. Mauris quis tellus magna.</p>

                                <figure class="blog-quote-holder p-4 p-lg-5 my-5 rounded">
                                    <blockquote class="blockquote theme-custom-quote">
                                        <p><i class="quote-icon fa-solid fa-quote-left d-none d-lg-inline-block"></i>You
                                            don't have to be great to start, but you have to start to be great.</p>
                                    </blockquote>
                                    <figcaption class="blockquote-footer">
                                        <cite title="Source Title">Zig Ziglar</cite>
                                    </figcaption>
                                </figure><!--//blog-quote-holder-->

                                <p>Cras adipiscing ipsum vel molestie cursus. In ultrices tristique vestibulum. Aenean ut
                                    dui diam. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere
                                    cubilia Curae; Ut bibendum ipsum nec sagittis ultrices. Vestibulum ante ipsum primis in
                                    faucibus orci luctus et ultrices posuere cubilia Curae; Vivamus id ante diam.
                                    Pellentesque mauris lacus, dictum sodales elit quis, pulvinar tempus leo. <a
                                        class="post-content-link" href="#">This is a link</a> pellentesque sed leo
                                    dignissim, ornare nunc vitae, volutpat quam. Nam pellentesque tortor eu nibh porttitor
                                    congue. Sed at porta lectus.</p>




                                <ul class="post-list ps-5 py-3">
                                    <li>Lorem <strong class="text-highlight">90% increase</strong> dolor sit amet
                                        consectetuer.</li>
                                    <li>Aenean commodo <strong class="text-highlight">$1200</strong> ligula eget dolor.</li>
                                    <li>Aenean massa <strong class="text-highlight">2M views</strong> cum sociis natoque
                                        penatibus.</li>

                                    <li>Aenean ut <strong class="text-highlight">30K downloads</strong> dui diam.</li>
                                </ul>

                                <h3 class="mt-5 mb-3">Code Block Example</h3>
                                <p>You can get more info at <a class="text-link" href="https://highlightjs.org/"
                                        target="_blank">https://highlightjs.org/</a>. Lorem ipsum dolor sit amet,
                                    consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis
                                    natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam
                                    felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis
                                    enim. </p>
                                <pre>
                                        <code>
        @requires_authorization(roles=["ADMIN"])
        def somefunc(param1='', param2=0):
        r'''A docstring'''
        if param1 > param2: # interesting
        print 'Gre\'ater'
        return (param2 - param1 + 1 + 0b10l) or None

        class SomeClass:
        pass

        >>> message = '''interpreter
        ... prompt'''
                                        </code>
                                    </pre>

                                <h3 class="post-content-heading">Blog Post Section Heading Lorem</h3>

                                <p>Pellentesque mattis scelerisque nibh eu tincidunt. Phasellus feugiat arcu eget sem
                                    tincidunt aliquam. Integer eleifend risus quis venenatis scelerisque. Nulla egestas
                                    commodo dignissim. Curabitur vel imperdiet diam. Suspendisse faucibus tincidunt sem,
                                    faucibus dictum eros rutrum sit amet. Nulla volutpat bibendum urna, eu dignissim libero
                                    elementum in.</p>



                                <p>Morbi vulputate bibendum fringilla. Sed fermentum nisi laoreet, porttitor ipsum et,
                                    vehicula diam. Fusce iaculis turpis dolor, et cursus arcu cursus vel. Ut lobortis tellus
                                    ornare ultrices tristique. Praesent cursus, mi ac rutrum ultrices, lectus erat
                                    pellentesque urna, at placerat eros nisi vitae ligula. Fusce eget lacus non ipsum
                                    vestibulum consequat. Nulla eleifend magna et urna vulputate, vitae volutpat magna
                                    varius. </p>

                                <ul class="post-list list-unstyled ps-4 py-3">
                                    <li><i class="bi bi-check me-2"></i>Lorem ipsum dolor sit amet, consectetuer adipiscing
                                        elit.</li>
                                    <li><i class="bi bi-check me-2"></i>Aliquam tincidunt mauris eu risus.</li>
                                    <li><i class="bi bi-check me-2"></i>Vestibulum auctor dapibus neque.</li>
                                    <li><i class="bi bi-check me-2"></i>Sagittis tempus lacus enim ac dui.</li>
                                </ul>

                                <p>Cras pharetra dolor dui, non aliquet diam faucibus sed. Mauris interdum arcu nec rutrum
                                    ornare. Suspendisse pharetra quam eu sapien egestas, a egestas tortor rhoncus. Quisque
                                    adipiscing tincidunt tellus a vehicula. Vestibulum ante ipsum primis in faucibus orci
                                    luctus et ultrices posuere cubilia Curae; Quisque ornare lorem elit, a aliquet nisl
                                    auctor vitae.</p>

                                <h3 class="post-content-heading">Blog Post Section Heading Lorem Ipsum</h3>

                                <p>Phasellus ligula dolor, fringilla at tincidunt non, fringilla eu justo. Sed hendrerit
                                    mauris quis hendrerit mollis. Vivamus vitae ultrices quam. Duis sed mi leo. Curabitur
                                    facilisis, erat vel egestas tincidunt, nisi ipsum ultricies velit, non scelerisque magna
                                    mi non nibh. Etiam blandit odio quis congue feugiat. Vivamus faucibus eu augue et
                                    ultrices. Phasellus nec euismod enim. Proin quis tellus auctor, porta risus vitae,
                                    pharetra sem. Curabitur fringilla tellus justo. Vestibulum scelerisque rhoncus blandit.
                                    Vivamus cursus bibendum suscipit. Ut vel ornare sapien. Mauris sit amet mollis erat.
                                    Phasellus gravida nisi vel consectetur luctus.</p>

                            </div><!--//post-content-->

                            <div class="post-tags py-5">
                                <ul class="list-inline">
                                    <li class="list-inline-item"><strong>Tags:</strong></li>
                                    <li class="list-inline-item"><span class="badge tag-badge">appdev</span></li>
                                    <li class="list-inline-item"><span class="badge tag-badge">tutorial</span></li>
                                    <li class="list-inline-item"><span class="badge tag-badge">react</span></li>
                                    <li class="list-inline-item"><span class="badge tag-badge">javascript</span></li>
                                </ul>
                            </div><!--//post-tags-->

                            <nav class="post-nav d-flex justify-content-between mb-5">
                                <div class="nav-previous"><a href="#" rel="prev"><i
                                            class="bi bi-arrow-left me-2"></i>Previous</a></div>
                                <div class="nav-next"><a href="#" rel="next">Next<i class="bi bi-arrow-right ms-2"></i></a>
                                </div>
                            </nav><!--//post-nav-->

                            <div id="blog-comment-area" class="blog-comment-area">
                                <div class="comment-container">
                                    <div class="comment-list">
                                        <h3 class="title">6 Comments</h3>
                                        <div class="comment-item depth-1 parent">
                                            <div class="comment-item-box d-flex p-0 p-lg-4 mb-5 rounded">
                                                <div class="comment-author col-auto me-2">
                                                    <img class="img-fluid" src="assets/images/blog/user-4.jpg" alt="" />
                                                </div><!--//comment-author-->
                                                <div class="comment-body col">
                                                    <cite class="name">Sarah Doe Says:</cite>
                                                    <p class="time">Apr 23 at 3:16pm</p>
                                                    <div class="content">
                                                        <p>You can click the reply button of this comment to see an example
                                                            of the reply form. 👇😊 </p>
                                                    </div><!--//content-->
                                                    <a class="comment-reply-link btn btn-secondary" href="#respond-1"
                                                        data-bs-toggle="collapse" role="button"
                                                        aria-expanded="false">Reply</a>
                                                    <div id="respond-1" class="collapse">
                                                        <div class="comment-reply-holder p-0 p-lg-5 my-3 rounded">
                                                            <h4 id="reply-title" class="reply-title mb-3" aria-level="1">
                                                                Reply to Sarah Doe</h4>
                                                            <form id="reply-form" class="reply-form form" method="post"
                                                                action="#">
                                                                <div class="row g-3">
                                                                    <div class="col-12 ">
                                                                        <label class="sr-only" for="ccomment">Leave a
                                                                            Comment</label>
                                                                        <textarea class="form-control" id="reply-comment"
                                                                            name="reply-comment"
                                                                            placeholder="Leave your reply" rows="12"
                                                                            required></textarea>
                                                                    </div>
                                                                    <div class="col-md-6 col-12">
                                                                        <label class="sr-only" for="rname">Name</label>
                                                                        <input type="text" class="form-control" id="rname"
                                                                            name="name" placeholder="Name" minlength="2"
                                                                            required>
                                                                    </div>
                                                                    <div class="col-md-6 col-12 ">
                                                                        <label class="sr-only" for="remail">Email</label>
                                                                        <input type="email" class="form-control" id="remail"
                                                                            name="email" placeholder="Email" required>
                                                                    </div>
                                                                    <div class="col-12 ">
                                                                        <button type="submit" class="btn btn-secondary">Post
                                                                            Reply</button>
                                                                    </div>
                                                                </div><!--//row-->
                                                            </form><!--//reply-form-->
                                                        </div><!--//comment-reply-holder-->
                                                    </div><!--//respond-1-->

                                                </div><!--//comment-body-->
                                            </div><!--//comment-box-->
                                            <div class="children">
                                                <div class="comment-item depth-2 child">
                                                    <div class="comment-item-box d-flex p-0 p-lg-4 mb-5 rounded">
                                                        <div class="comment-author col-auto me-2">
                                                            <img class="img-fluid" src="assets/images/blog/user-2.jpg"
                                                                alt="" />
                                                        </div><!--//comment-author-->
                                                        <div class="comment-body col">
                                                            <cite class="name">Sam Oliver Says:</cite>
                                                            <p class="time">Apr 23 at 4:23pm</p>
                                                            <div class="content">
                                                                <p>Proin ut condimentum ante. Donec in urna dapibus massa
                                                                    sodales varius et eu eros. Integer ac turpis sed dui
                                                                    pulvinar consectetur. Interdum et malesuada fames ac
                                                                    ante ipsum primis in faucibus. Sed pellentesque eu lorem
                                                                    sit amet elementum. Cras et mauris ac turpis maximus
                                                                    tempor vitae a lectus. </p>
                                                            </div><!--//content-->
                                                            <a class="comment-reply-link btn btn-secondary"
                                                                href="#">Reply</a>
                                                        </div><!--//comment-body-->
                                                    </div><!--//comment-box-->
                                                    <div class="children">
                                                        <div class="comment-item depth-3 child">
                                                            <div class="comment-item-box d-flex p-0 p-lg-4 mb-5 rounded">
                                                                <div class="comment-author col-auto me-2">
                                                                    <img class="img-fluid"
                                                                        src="assets/images/blog/user-4.jpg" alt="" />
                                                                </div><!--//comment-author-->
                                                                <div class="comment-body col">
                                                                    <cite class="name">Sarah DoeSays:</cite>
                                                                    <p class="time">Apr 23 at 8:16pm</p>
                                                                    <div class="content">
                                                                        <p>Interdum et malesuada fames ac ante ipsum primis
                                                                            in faucibus. Aenean finibus risus id elit
                                                                            tempor, id blandit sapien accumsan.</p>
                                                                    </div><!--//content-->
                                                                    <a class="comment-reply-link btn btn-secondary"
                                                                        href="#">Reply</a>
                                                                </div><!--//comment-body-->
                                                            </div><!--//comment-box-->
                                                        </div><!--//comment-item depth-3-->
                                                    </div><!--//children-->
                                                </div><!--//comment-item depth-2-->
                                            </div><!--//children-->
                                        </div><!--//comment-item depth-1-->

                                        <div class="comment-item depth-1 parent">
                                            <div class="comment-item-box d-flex p-0 p-lg-4 mb-5 rounded">
                                                <div class="comment-author col-auto me-2">
                                                    <img class="img-fluid" src="assets/images/blog/user-1.jpg" alt="" />
                                                </div><!--//comment-author-->
                                                <div class="comment-body col">
                                                    <cite class="name">Tom Wang Says:</cite>
                                                    <p class="time">May 08 at 13:10pm</p>
                                                    <div class="content">
                                                        <p>Sed condimentum vel quam ut sagittis. Aliquam erat enim, lobortis
                                                            sit amet tellus accumsan, scelerisque porttitor sem. Suspendisse
                                                            dictum risus id iaculis sodales phasellus id ex aliquam.</p>
                                                    </div><!--//content-->
                                                    <a class="comment-reply-link btn btn-secondary" href="#">Reply</a>
                                                </div><!--//comment-body-->
                                            </div><!--//comment-box-->
                                        </div><!--//comment-item depth-1-->

                                        <div class="comment-item depth-1 parent">
                                            <div class="comment-item-box d-flex p-0 p-lg-4 mb-5 rounded">
                                                <div class="comment-author col-auto me-2">
                                                    <img class="img-fluid" src="assets/images/blog/user-0.jpg" alt="" />
                                                </div><!--//comment-author-->
                                                <div class="comment-body col">
                                                    <cite class="name">Anonymous Says:</cite>
                                                    <p class="time">May 09 at 13:12pm</p>
                                                    <div class="content">
                                                        <p>Sed condimentum?</p>
                                                    </div><!--//content-->
                                                    <a class="comment-reply-link btn btn-secondary" href="#">Reply</a>
                                                </div><!--//comment-body-->
                                            </div><!--//comment-box-->
                                        </div><!--//comment-item depth-1-->

                                        <div class="comment-item depth-1 parent">
                                            <div class="comment-item-box d-flex p-0 p-lg-4 mb-5 rounded">
                                                <div class="comment-author col-auto me-2">
                                                    <img class="img-fluid" src="assets/images/blog/user-3.jpg" alt="" />
                                                </div><!--//comment-author-->
                                                <div class="comment-body col">
                                                    <cite class="name">Dave Morgan Says:</cite>
                                                    <p class="time">May 12 at 9:35am</p>
                                                    <div class="content">
                                                        <p>Nunc in urna eu lorem accumsan placerat vel eu turpis. Etiam
                                                            laoreet posuere mauris, id pharetra orci molestie sit amet. Duis
                                                            pretium diam ex, vitae eleifend diam ornare sit amet. </p>
                                                    </div><!--//content-->
                                                    <a class="comment-reply-link btn btn-secondary" href="#">Reply</a>
                                                </div><!--//comment-body-->
                                            </div><!--//comment-box-->
                                            <div class="children">
                                                <div class="comment-item depth-2 child">
                                                    <div class="comment-item-box d-flex p-0 p-lg-4 mb-5 rounded">
                                                        <div class="comment-author col-auto me-2">
                                                            <img class="img-fluid" src="assets/images/blog/user-4.jpg"
                                                                alt="" />
                                                        </div><!--//comment-author-->
                                                        <div class="comment-body col">
                                                            <cite class="name">Sam Oliver Says:</cite>
                                                            <p class="time">May 12 at 4:23pm</p>
                                                            <div class="content">
                                                                <p>Thanks!</p>
                                                            </div><!--//content-->
                                                            <a class="comment-reply-link btn btn-secondary"
                                                                href="#">Reply</a>
                                                        </div><!--//comment-body-->
                                                    </div><!--//comment-box-->
                                                </div><!--//comment-item depth-2-->
                                            </div><!--//children-->
                                        </div><!--//comment-item depth-1-->

                                    </div><!--comment-list-->
                                </div><!--//comments-container-->

                                <div class="comment-form-holder">
                                    <h4 class="title mb-3">Leave a comment</h4>
                                    <form id="comment-form" class="comment-form form" method="post" action="#">
                                        <div class="row g-3">
                                            <div class="col-12 col-md-6">
                                                <label class="sr-only" for="cname">Name</label>
                                                <input type="text" class="form-control" id="cname" name="name"
                                                    placeholder="Name" minlength="2" required>
                                            </div>
                                            <div class="col-md-6 col-12 ">
                                                <label class="sr-only" for="cemail">Email</label>
                                                <input type="email" class="form-control" id="cemail" name="email"
                                                    placeholder="Email" required>
                                            </div>
                                            <div class="col-12">
                                                <label class="sr-only" for="ccomment">Leave a Comment</label>
                                                <textarea class="form-control" id="ccomment" name="comment"
                                                    placeholder="Leave your comment" rows="12" required></textarea>
                                            </div>
                                            <div class="col-12">
                                                <button type="submit" class="btn btn-secondary">Post Comment</button>
                                            </div>
                                        </div><!--//row-->
                                        <div id="form-messages"></div>
                                    </form><!--//contact-form-->
                                </div><!--//comment-form-holder-->
                            </div><!--//comment-area-->
                        </article>
                    </div>
                </section><!--//blog-post-section-->
            </div>
        </div><!--//main-content-wrapper-->
    </div>
    <!-- Footer Load -->
    <TheFooter></TheFooter>
</template>