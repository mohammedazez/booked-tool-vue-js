<template>
    <div>
        <section class="touch-area" id="touch">
            <div>
                <img class="touch-img" src="https://res.cloudinary.com/dulqd0xea/image/upload/v1609294371/Customer%202/002-insurance_l8ei8i.png"/>
                <h1 class="text-touch-one">Get in Touch</h1>
                <p class="text-touch-two">Want to get in touch? We'd love to her from you. Here's how you can reach us..</p>
            </div>
            <div>
                <div >
                    <input class="input-touch-area" type="text" name="" placeholder="Search..." >
                </div>
            </div>
            <div>
                <div class="row-touch">
                    <div class="column-touch" style="background-color: #f6f8f8;">
                       <div class="responsive-map">
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2822.7806761080233!2d-93.29138368446431!3d44.96844997909819!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x52b32b6ee2c87c91%3A0xc20dff2748d2bd92!2sWalker+Art+Center!5e0!3m2!1sen!2sus!4v1514524647889" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
</div>
                    </div>
                <div class="column-touch" style="background-color:#ffffff;">
                    <div class="container-touch-form">
                        <h1>Feedback</h1>
                        <form>
                            <input class="input-touch" type="text" id="fname" name="firstname" placeholder="First">
                            <input class="input-touch" type="text" id="lname" name="lastname" placeholder="Last">
                            <input class="input-touch" type="text" id="femail" name="email" placeholder="Email">
                        <textarea class="textarea-touch" id="subject" name="subject" placeholder="Message" style="height:80px"></textarea>
                         <button class="button-touch">Send</button>
                        </form>
                    </div>
                </div>    
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