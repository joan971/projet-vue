<template>
    <section>

 <div class="contact1">
    <div class="container-contact1">

<div class="im">
      <img src="img/brand/unnamed.jpg" width="300px" height="300px" alt="IMG">

    </div>


      <form class="contact1-form validate-form">
        <span class="contact1-form-title">
          Keep in touch
        </span>

        <div class="wrap-input1 validate-input" data-validate="Name is required">
          <input class="input1" type="text" name="name" placeholder="First Name">

        </div>

        <div class="wrap-input1 validate-input" data-validate="Name is required">
          <input class="input1" type="text" name="name" placeholder="Last Name">

        </div>

        <div class="wrap-input1 validate-input" data-validate="Valid email is required: ex@abc.xyz">
          <input class="input1" type="text" name="email" placeholder="Email">

        </div>

        <div class="wrap-input1 validate-input" data-validate="Subject is required">
          <input class="input1" type="text" name="subject" placeholder="Subject">

        </div>

        <div class="wrap-input1 validate-input" data-validate="Message is required">
          <textarea class="input1" name="message" placeholder="Message"></textarea>

        </div>

        <div class="container-contact1-form-btn">
          <button class="contact1-form-btn">
            <span>
              Submit
              <i class="fa fa-long-arrow-right" aria-hidden="true"></i>
            </span>
          </button>
        </div>
      </form>

    </div>
  </div>
        
    </section>

</template>
<script>
export default {};
</script>
