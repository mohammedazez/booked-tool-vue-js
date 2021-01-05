<template>
    <div>
        <section class="touch-area" id="touch">
            
            <!-- Text -->
            <div>
                <img class="touch-img" src="https://res.cloudinary.com/dulqd0xea/image/upload/v1609294371/Customer%202/002-insurance_l8ei8i.png"/>
                <h1 class="text-touch-one">Get in Touch</h1>
                <p class="text-touch-two">Want to get in touch? We'd love to her from you. Here's how you can reach us..</p>
            </div>

            <!-- Search -->
            <div>
                <div >
                    <input class="input-touch-area" type="text" name="" placeholder="Search..." >
                </div>
            </div>

            <!-- Maps and contact -->
            <div>
                <!-- Row  -->
                <div class="row-touch">

                    <!-- Grid satu -->
                    <div class="column-touch" style="background-color: #f6f8f8;">
                        <h2>Column 1</h2>
                        <p>Some text..</p>
                    </div>
                    <!-- End grid satu -->

                    <!-- Grid dua -->
                <div class="column-touch" style="background-color:#f6f8f8;">
                    <div class="container-touch-form">
                        <h1>Feedback</h1>
                        <form>
                            <input class="input-touch" type="text" id="fname" name="firstname" placeholder="First">
                            <input class="input-touch" type="text" id="lname" name="lastname" placeholder="Last">
                            <input class="input-touch" type="text" id="femail" name="email" placeholder="Email">
                        <textarea class="textarea-touch" id="subject" name="subject" placeholder="Message" style="height:200px"></textarea>
                        </form>
                    </div>
                </div>
                <!-- End grid dua -->

                
            </div>
            </div>
        </section>
    </div>
</template>

<script>
import "../styles/Touch.scss"

export default {
    name: "Touchsection"
}
</script>