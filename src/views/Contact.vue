<template>
  <section class="page-section">
    <div class="container mb-5">
      <div class="row">
        <div class="col-xl-9 col-lg-10 mx-auto">
          <div class="bg-faded rounded p-5">

            <h1><span class="section-heading mb-4">Contact</span></h1>
            <hr/>

            <div class="row text-center p-3">
              <div class="col-md-4 text-center">
                <font-awesome-icon icon="envelope-open" size="3x"/>
                <a class="d-block m-2" href="mailto:">youemail@email.com</a>
              </div>
              <div class="col-md-4 text-center">
                <font-awesome-icon :icon="['fab', 'facebook-square']" size="3x"/>
                <a class="d-block m-2" href="https://facebook.com">facebook.com/UserName</a>
              </div>
              <div class="col-md-4 text-center">
                <font-awesome-icon :icon="['fab', 'instagram']" size="3x"/>
                <a class="d-block m-2" href="https://instagram.com">@UserName</a>
              </div>
            </div>

            <div class="container cta bg-transparent p-3">
              <div class="row">
                <form method="GET" class="cta-inner m-auto">
                  <div class="form-group">
                    <label for="email">Deja tu email y nos pondremos en contacto</label>
                    <input class="form-control" type="email" placeholder="E-mail" id="email">
                  </div>
                  <button class="btn btn-primary col" type="submit">Enviar</button>
                </form>
              </div>
            </div>

          </div>
        </div>
      </div>
    </div>
  </section>
</template>