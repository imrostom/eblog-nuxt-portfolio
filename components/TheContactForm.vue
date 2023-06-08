<template>
    <div class="contact-form-wrapper pt-3">
        <form id="contact-form" class="contact-form p-md-4 px-lg-5">
            <h4 class="text-center mb-4">Contact Form</h4>

            <div class="row g-3">
                <div class="col-md-6">
                    <label class="sr-only" for="cname">Name</label>
                    <input type="text" class="form-control" id="cname" name="name" placeholder="Name" minlength="2">
                </div>
                <div class="col-md-6">
                    <label class="sr-only" for="cemail">Email</label>
                    <input type="email" class="form-control" id="cemail" name="email" placeholder="Email">
                </div>

                <div class="col-12">
                    <label class="sr-only" for="cmessage">Your message</label>
                    <textarea class="form-control" id="cmessage" name="message" placeholder="Enter your message"
                        rows="10"></textarea>
                </div>
                <div class="col-12">
                    <button type="submit" class="btn w-100 btn-secondary py-2">Submit</button>
                </div>
            </div><!--//form-row-->
        </form>
    </div><!--//contact-form-wrapper-->
</template>