<template >
  <div>
    <div class="bg-dark" id="top">
      <b-container>
        <div class="position-relative">
          <nav class="navbar navbar-expand-lg navbar-light bg-dark">
            <a class="navbar-brand" href="#">
              <img
                src="../assets/logo2.png"
                class="img-responsive logo"
                alt=""
              />
            </a>
            <button
              class="navbar-toggler"
              type="button"
              data-toggle="collapse"
              data-target="#navbarNav"
              aria-controls="navbarNav"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
              <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                  <a class="nav-link" href="#"
                    >Home <span class="sr-only">(current)</span></a
                  >
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#max">Features</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#pricing">Pricing</a>
                </li>
              </ul>
              <div class="ml-lg-4 ml-2 d-flex">
                <button class="btn btn-light rounded-pill px-3">Login</button>
                <button class="btn btn-light rounded-pill ml-3 px-3">
                  Sign&nbsp;Up
                </button>
              </div>
            </div>
          </nav>
        </div>
      </b-container>
    </div>
    <section>
      <b-container>
        <div class="row mx-0 mt-4 align-items-center">
          <div class="col-lg-5">
            <h1 data-aos="fade-up" data-aos-duration="3000">
              Find new clients and elevate your sales with verified exceptional
              leads
            </h1>
            <p class="text-muted">
              Our leads come from companies that have recently raised funding or
              have a high revenue, so you can be more confident that they have
              the financial resources to purchase your services.
            </p>
            <p class="text-primary font-weight-normal">
              Exceptional leads lead to exceptional results
            </p>
          </div>
          <div class="col-lg-7" data-aos="fade-up" data-aos-duration="3000" >
            <img src="../assets/manwalking.jpg" class="w-100" alt="" />
          </div>
        </div>
        <div class="row mx-0 my-5" style="gap: 30px 0px">
          <div class="col-lg-6">
            <div class="card d-block p-4 radius">
              <div class="d-flex justify-content-center">
                <img src="../assets/f1.jpg" class="person1" alt="" />
              </div>
              <h4 class="text-center mt-2">Michael Dence</h4>
              <p class="mt-1 mb-2 text-primary text-center font-weight-bold">
                WhatsRockets
              </p>
              <p class="text-center text-muted">
                "Wow, going through beta was an absolute blast! We were so
                impressed that we couldn't help but sign up for a year deal and
                we're already wishing we could extend it even further! This is
                the ultimate tool for us, it's delivering results like we've
                never seen before and bringing in clients we never even knew
                existed. It's simply amazing!"
              </p>
            </div>
          </div>
          <div class="col-lg-6">
            <div class="card d-block p-4 radius">
              <div class="d-flex justify-content-center">
                <img src="../assets/f2.jpg" class="person1" alt="" />
              </div>
              <h4 class="text-center mt-2">Seth P.</h4>
              <p class="mt-1 mb-2 text-primary text-center font-weight-bold">
                Metrodoc
              </p>
              <p class="text-center text-muted">
                "I was skeptical at first but after trying this tool, I'm a
                total convert. It's made a huge difference in our workflow and
                results. Highly recommend!"
              </p>
            </div>
          </div>
        </div>
      </b-container>
    </section>
    <section>
      <div>
        <b-container>
          <div class="mt-5">
            <h1 class="text-center text-uppercase" data-aos="fade-up" data-aos-duration="3000">
              simple <span class="text-primary">workflow</span>
            </h1>
            <p class="text-lg-center fs-5 font-weight-light my-3 mb-4">
              Sign up, get new leads, start reaching them and close more deals
              for your business
            </p>
            <img src="../assets/workflow.png" alt="" class="w-100" />
          </div>
        </b-container>
      </div>
    </section>
    <section>
      <b-container>
        <div class="mt-5" id="max">
          <h1 class="text-center" data-aos="fade-up" data-aos-duration="3000">
            WE FOCUS ON <span class="text-primary">MAXIMIZING</span> <br />
            YOUR CHANCES OF <span class="text-primary">SUCCESS</span>
          </h1>
          <div class="row mx-0 justify-content-center mt-5 pt-5">
            <div class="col-lg-4" data-aos="fade-up" data-aos-duration="3000">
              <div class="card__mine">
                <div class="d-flex justify-content-center">
                  <div class="icon__div h1">
                    <font-awesome-icon icon="fa-solid fa-chart-line" />
                  </div>
                </div>

                <div class="text-center">
                  <p class="font-weight-bold small title__mine">
                    HIGH TICKET COMPANIES
                  </p>
                  <p class="text-center description__mine">
                    Our leads come from companies that have recently raised
                    funding or have a proven track record of a consistently
                    strong revenue so you can be more confident that these
                    companies have the financial resources and budget to invest
                    in your services.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-lg-4">
              <div class="card__mine" data-aos="fade-down" data-aos-duration="3000">
                <div class="d-flex justify-content-center">
                  <div class="icon__div h1">
                    <font-awesome-icon icon="fa-solid fa-check-circle" />
                  </div>
                </div>

                <div class="text-center">
                  <p class="font-weight-bold small title__mine">
                    VERIFIED DATA
                  </p>
                  <p class="text-center description__mine">
                    All of our leads are verified by our team to ensure that the
                    information is up-to-date and accurate. We spend hundreds of
                    hours and thousands of dollars every month to collect the
                    most relevant companies so you don’t have to, saving you
                    time and resources.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-lg-4" data-aos="fade-up" data-aos-duration="3000">
              <div class="card__mine">
                <div class="d-flex justify-content-center">
                  <div class="icon__div h1">
                    <font-awesome-icon icon="fa-solid fa-disease" />
                  </div>
                </div>

                <div class="text-center">
                  <p class="font-weight-bold small title__mine">EASY TO USE</p>
                  <p class="text-center description__mine">
                    Our interface is easy and quick to use, making it simple for
                    you to access and manage your leads. Once you unlock and
                    view the leads, they are saved directly in your account,
                    with no extra cost for saving it. <br />
                    <span class="invisible">
                      with no extra cost for saving it.</span
                    >
                  </p>
                </div>
              </div>
            </div>
            <div class="col-lg-4" data-aos="fade-down" data-aos-duration="3000">
              <div class="card__mine">
                <div class="d-flex justify-content-center">
                  <div class="icon__div h1">
                    <font-awesome-icon icon="fa-solid fa-phone" />
                  </div>
                </div>

                <div class="text-center">
                  <p class="font-weight-bold small title__mine text-uppercase">
                    Contact Information
                  </p>
                  <p class="text-center description__mine">
                    Our platform is designed to provide you with leads that are
                    actionable and have a higher chance of converting into
                    business. Instead of providing leads for large,
                    well-established companies that are likely to already have a
                    service provider or in-house team, we focus on smaller, more
                    approachable companies that are more likely to be in need of
                    your services. While it may be possible to approach larger
                    companies, our platform is geared towards maximizing your
                    chances of success.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-lg-4" data-aos="fade-up" data-aos-duration="3000">
              <div class="card__mine">
                <div class="d-flex justify-content-center">
                  <div class="icon__div h1">
                    <font-awesome-icon icon="fa-solid fa-hand-holding-heart" />
                  </div>
                </div>

                <div class="text-center">
                  <p class="font-weight-bold small title__mine">HANDPICKED</p>
                  <p class="text-center description__mine">
                    Our platform is designed to provide you with leads that are
                    actionable and have a higher chance of converting into
                    business. Instead of providing leads for large,
                    well-established companies that are likely to already have a
                    service provider or in-house team, we focus on smaller, more
                    approachable companies that are more likely to be in need of
                    your services. While it may be possible to approach larger
                    companies, our platform is geared towards maximizing your
                    chances of success.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-lg-4" data-aos="fade-down" data-aos-duration="3000">
              <div class="card__mine">
                <div class="d-flex justify-content-center">
                  <div class="icon__div h1">
                    <font-awesome-icon icon="fa-solid fa-earth-americas" />
                  </div>
                </div>

                <div class="text-center">
                  <p class="font-weight-bold small title__mine text-uppercase">
                    World Wide Coverage
                  </p>
                  <p class="text-center description__mine">
                    Our platform is designed to provide you with leads that are
                    actionable and have a higher chance of converting into
                    business. Instead of providing leads for large,
                    well-established companies that are likely to already have a
                    service provider or in-house team, we focus on smaller, more
                    approachable companies that are more likely to be in need of
                    your services. While it may be possible to approach larger
                    companies, our platform is geared towards maximizing your
                    chances of success.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </b-container>
    </section>
    <section>
      <div class="">
        <b-container>
          <div
            class="row mx-0 justify-lg-content-between justify-content-center align-items-center"
            style="gap: 30px 0px"
          >
            <div class="col-lg-7" data-aos="fade-up" data-aos-duration="3000">
              <img src="../assets/draw.svg" class="w-100" alt="" />
            </div>
            <div class="col-lg-5" data-aos="fade-down" data-aos-duration="3000">
              <h1>One credit is enough</h1>
              <p class="text-muted">
                With one credit you will gain access to all the company
                information, including financial data such as fundings and
                revenue, as well as key people's contact information including
                phone numbers and emails. No matter how many people we have
                information on, whether it be 3 or 10, you can unlock it all
                with just one credit.
              </p>
            </div>
          </div>
        </b-container>
      </div>
    </section>
    <section>
      <div>
        <div class="bg-light py-5">
          <div class="container">
            <h1 class="text-center" data-aos="fade-up" data-aos-duration="3000" >Testimonials</h1>

            <!-- <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
              <ol class="carousel-indicators">
                <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
              </ol>
              <div class="carousel-inner">
                <div class="carousel-item active mb-5 pb-5 pt-5">

                  <div class="">
                    <div class="d-flex justify-content-center">
                      <img src="../assets/person.png" class="rounded-circle img__testi">
                    </div>
                    <blockquote>
                      <p class="text-center font-italic  mt-4">

                        “Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur unde
                        reprehenderit
                        aperiam quaerat fugiat repudiandae explicabo animi minima fuga beatae illum eligendi
                        incidunt consequatur. Amet dolores excepturi earum unde iusto.”
                      </p>
                      <p class="font-weight-bold small text-center">Roberts Sear</p>
                    </blockquote>
                  </div>
                </div>
                <div class="carousel-item mb-5 pb-5 pt-5">
                  <div class="">
                    <div class="d-flex justify-content-center">
                      <img src="../assets/person.png" class="rounded-circle img__testi">
                    </div>
                    <blockquote>
                      <p class="text-center font-italic  mt-4">

                        “Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur unde
                        reprehenderit
                        aperiam quaerat fugiat repudiandae explicabo animi minima fuga beatae illum eligendi
                        incidunt consequatur. Amet dolores excepturi earum unde iusto.”
                      </p>
                      <p class="font-weight-bold small text-center">Roberts Sear</p>
                    </blockquote>
                  </div>
                </div>
                <div class="carousel-item mb-5 pb-5 pt-5">
                  <div class="">
                    <div class="d-flex justify-content-center">
                      <img src="../assets/person.png" class="rounded-circle img__testi">
                    </div>
                    <blockquote>
                      <p class="text-center font-italic  mt-4">

                        “Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur unde
                        reprehenderit
                        aperiam quaerat fugiat repudiandae explicabo animi minima fuga beatae illum eligendi
                        incidunt consequatur. Amet dolores excepturi earum unde iusto.”
                      </p>
                      <p class="font-weight-bold small text-center">Roberts Sear</p>
                    </blockquote>
                  </div>
                </div>
              </div>
              <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
              </a>
              <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
              </a>
            </div> -->
            <b-carousel
              id="carousel-1"
              v-model="slide"
              :interval="4000"
              controls
              indicators
              img-width="1024"
              img-height="480"
              style="text-shadow: 1px 1px 2px #333"
              @sliding-start="onSlideStart"
              @sliding-end="onSlideEnd"
            >
              <!-- Text slides with image -->
              <div class="carousel-item active mb-5 pb-5 pt-5">
                <div class="">
                  <div class="d-flex justify-content-center">
                    <img
                      src="../assets/person.png"
                      class="rounded-circle img__testi"
                    />
                  </div>
                  <blockquote>
                    <p class="text-center font-italic mt-4">
                      “ dolor sit amet consectetur adipisicing elit. Consectetur
                      unde reprehenderit aperiam quaerat fugiat repudiandae
                      explicabo animi minima fuga beatae illum eligendi incidunt
                      consequatur. Amet dolores excepturi earum unde iusto.”
                    </p>
                    <p class="font-weight-bold small text-center">
                      Shawn Micheal
                    </p>
                  </blockquote>
                </div>
              </div>
              <div class="carousel-item mb-5 pb-5 pt-5">
                <div class="">
                  <div class="d-flex justify-content-center">
                    <img
                      src="../assets/person.png"
                      class="rounded-circle img__testi"
                    />
                  </div>
                  <blockquote>
                    <p class="text-center font-italic mt-4">
                      “ ipsum dolor sit amet consectetur adipisicing elit.
                      Consectetur unde reprehenderit aperiam quaerat fugiat
                      repudiandae explicabo animi minima fuga beatae illum
                      eligendi incidunt consequatur. Amet dolores excepturi
                      earum unde iusto.”
                    </p>
                    <p class="font-weight-bold small text-center">
                      David Ludroff
                    </p>
                  </blockquote>
                </div>
              </div>
              <div class="carousel-item mb-5 pb-5 pt-5">
                <div class="">
                  <div class="d-flex justify-content-center">
                    <img
                      src="../assets/person.png"
                      class="rounded-circle img__testi"
                    />
                  </div>
                  <blockquote>
                    <p class="text-center font-italic mt-4">
                      “Lorem ipsum dolor sit amet consectetur adipisicing elit.
                      Consectetur unde reprehenderit aperiam quaerat fugiat
                      repudiandae explicabo animi minima fuga beatae illum
                      eligendi incidunt consequatur. Amet dolores excepturi
                      earum unde iusto.”
                    </p>
                    <p class="font-weight-bold small text-center">
                      Roberts Sear
                    </p>
                  </blockquote>
                </div>
              </div>
            </b-carousel>
          </div>
        </div>
      </div>
    </section>
    <section>
      <div>
        <b-container>
          <div class="my-5">
            <h1 class="text-center" data-aos="fade-up" data-aos-duration="3000">
              THIS IS AN ESSENTIAL TOOLS FOR ALL THE BUSINESSES THAT SELL TO
              BUSINESSES
            </h1>
            <div class="row mx-0 pt-5">
              <div class="col-lg-3" data-aos="fade-down" data-aos-duration="3000">
                <div class="text-center fs-1">
                  <font-awesome-icon icon="fa-solid fa-briefcase fs-1" />
                </div>
                <h6 class="text-center fw-bold">
                  SUIT FOR ALL THE BUSINESSES THAT SELL ONLINE
                </h6>
                <p class="text-center">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Cupiditate temporibus quasi dolore tenetur nesciunt
                  blanditiis?
                </p>
              </div>
              <div class="col-lg-3" data-aos="fade-up" data-aos-duration="3000">
                <div class="text-center fs-1">
                  <font-awesome-icon icon="fa-solid fa-headset fs-1" />
                </div>
                <h6 class="text-center fw-bold">INCREDIBLE SUPPORT</h6>
                <p class="text-center">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Cupiditate temporibus quasi dolore tenetur nesciunt
                  blanditiis?
                </p>
              </div>
              <div class="col-lg-3" data-aos="fade-down" data-aos-duration="3000">
                <div class="text-center fs-1">
                  <font-awesome-icon icon="fa-solid fa-hourglass-start fs-1" />
                </div>
                <h6 class="text-center fw-bold">TIME AND MONEY SAVING TOOL</h6>
                <p class="text-center">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Cupiditate temporibus quasi dolore tenetur nesciunt
                  blanditiis?
                </p>
              </div>
              <div class="col-lg-3" data-aos="fade-up" data-aos-duration="3000"> 
                <div class="text-center fs-1">
                  <font-awesome-icon icon="fa-solid fa-pen-nib fs-1" />
                </div>
                <h6 class="text-center fw-bold">BUSINESS SAVIOR</h6>
                <p class="text-center">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Cupiditate temporibus quasi dolore tenetur nesciunt
                  blanditiis?
                </p>
              </div>
            </div>
          </div>
        </b-container>
      </div>
    </section>
    <section>
      <div>
        <b-container>
          <div class="mt-5 pt-5" id="pricing">
            <h1 class="text-center" data-aos="fade-up" data-aos-duration="3000">Subscription Plans</h1>
            <!-- $599.99/year

1680 credits/year

1 credit can unlock all company and key contact people information

Prices for additional credits will vary.

Access to all features
Access to all search filters
Free updates
Email support
Access to handpicked and properly qualified companies
Access to the company's full details, including geographical information, financial information, key people information, and contact
Access to companies that have demonstrated financial strength through funding or high revenues
Access a comprehensive view of a company's technology usage and capabilities through technographic data -->
            <div class="row mx-0 mt-4" style="gap: 30px 0px">
              <div class="col-lg-4">
                <div class="card__subscription px-4 pt-4 pb-lg-4">
                  <h4 class="text-center text-primary">Free Plan</h4>
                  <div class="d-flex justify-content-between my-2 mt-4">
                    <div>$0.00</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>10 credits to test</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      1 credit can unlock all company and key contact people
                      information
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>Access to limited features</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>Email support</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      Access to handpicked and properly qualified companies
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      Access to the company's full details, including
                      geographical information, financial information, key
                      people information, and contact
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      Access to companies that have demonstrated financial
                      strength through funding or high revenues
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      Access a comprehensive view of a company's technology
                      usage and capabilities through technographic data
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>

                  <div class="d-flex justify-content-center mt-5 position__btn">
                    <button class="btn-primary btn text-capitalize w-100">
                      signup
                    </button>
                  </div>
                </div>
              </div>
              <div class="col-lg-4">
                <div class="card__subscription px-4 pt-4 pb-lg-4">
                  <h4 class="text-center text-primary">Monthly Plan</h4>
                  <div class="d-flex justify-content-between my-2 mt-4">
                    <div>$59.99/month</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>140 credits/month</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      1 credit can unlock all company and key contact people
                      information (Prices for additional credits will vary. )
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>Access to all features</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>Access to all search filters</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>Free updates</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>Email support</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      Access to handpicked and properly qualified companies
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      Access to the company's full details, including
                      geographical information, financial information, key
                      people information, and contact
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      Access to companies that have demonstrated financial
                      strength through funding or high revenues
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      Access a comprehensive view of a company's technology
                      usage and capabilities through technographic data
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>

                  <div class="d-flex justify-content-center mt-5 position__btn">
                    <button class="btn-primary btn text-capitalize w-100">
                      signup
                    </button>
                  </div>
                </div>
              </div>
              <div class="col-lg-4">
                <div class="card__subscription px-4 pt-4 pb-lg-4">
                  <h4 class="text-center text-primary">Yearly Plan</h4>
                  <div class="d-flex justify-content-between my-2 mt-4">
                    <div>$599.99/year</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>1680 credits/year</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      1 credit can unlock all company and key contact people
                      information (Prices for additional credits will vary. )
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>Access to all features</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>Access to all search filters</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>Free updates</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>Email support</div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      Access to handpicked and properly qualified companies
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      Access to the company's full details, including
                      geographical information, financial information, key
                      people information, and contact
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      Access to companies that have demonstrated financial
                      strength through funding or high revenues
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>
                  <div class="d-flex justify-content-between my-2">
                    <div>
                      Access a comprehensive view of a company's technology
                      usage and capabilities through technographic data
                    </div>

                    <div class="text-primary">
                      <font-awesome-icon icon="fa-solid fa-check" />
                    </div>
                  </div>

                  <div class="d-flex justify-content-center mt-5 position__btn">
                    <button class="btn-primary btn text-capitalize w-100">
                      signup
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </b-container>
      </div>
    </section>
    <section>
      <div>
        <div class="bg-primary mt-5">
          <b-container>
            <div class="py-5">
              <h4 class="text-center text-white" data-aos="fade-up" data-aos-duration="3000">
                <span class="text-white font-weight-bold">"</span> Stop wasting
                your time chasing dead-end leads. Our platform provides you with
                a carefully curated selection of high-performing,
                under-the-radar companies that are ready for partnership and
                investment opportunities. Sign up and start closing deals today.
                <span class="text-white font-weight-bold">"</span>
              </h4>
            </div>
          </b-container>
        </div>
      </div>
    </section>
    <section>
      <div class="bg-dark">
        <b-container>
          <div class="py-4">
            <!-- <div class="d-flex justify-content-center flex-wrap">
                <div class="mx-2 mx-lg-4 my-2 text-primary">
                    <font-awesome-icon icon="fa-brands fa-facebook-f" />

                </div>
                <div class="mx-2 mx-lg-4 my-2 text-primary">
                    <font-awesome-icon icon="fa-brands fa-twitter" />

                </div>
                <div class="mx-2 mx-lg-4 my-2 text-primary">
                    <font-awesome-icon icon="fa-brands fa-instagram" />

                </div>
                <div class="mx-2 mx-lg-4 my-2 text-primary">
                    <font-awesome-icon icon="fa-brands fa-linkedin-in" />

                </div>
                <div class="mx-2 mx-lg-4 my-2 text-primary">
                    <font-awesome-icon icon="fa-brands fa-pinterest" />

                </div>

            </div> -->
            <div
              class="d-flex justify-content-center flex-wrap"
              style="gap: 0px 25px"
            >
              <a href="#" class="text-white text-decoration-none">About Us</a>
              <a href="#" class="text-white text-decoration-none"
                >Terms Of Service</a
              >
              <a href="#" class="text-white text-decoration-none"
                >Privacy Policy</a
              >
            </div>
            <div class="mt-3 text-center text-white">
              Copyright ©2023 All rights reserved
            </div>
          </div>
        </b-container>
      </div>
    </section>
  </div>
</template> 

<script>
export default {
  name: "Landing",
  data() {
    return {
      msg: "Welcome to Your Vue.js App",
      showDiv: false,
      slide: 0,
      sliding: null,
    };
  },
  methods: {
    handleScroll() {
      const scrollPosition = window.scrollY;
      if (scrollPosition >= 50) {
        this.showDiv = true;
        console.log("hi");
      } else {
        this.showDiv = false;
        console.log("bye");
        console.log(scrollPosition);
      }
    },
    onSlideStart(slide) {
      this.sliding = true;
    },
    onSlideEnd(slide) {
      this.sliding = false;
    },
  },
  mounted() {
    window.addEventListener("scroll", this.handleScroll);
  },
  beforeDestroy() {
    window.removeEventListener("scroll", this.handleScroll);
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth; 
}*/

* {
  box-sizing: border-box;
  scroll-behavior: smooth;
}
.nav-link {
  margin: 0px 8px;
  color: #fff !important;
}
.logo {
  width: 40px;
  height: 40px;
}
.navbar-toggler:focus {
  outline: none !important;
}
.radius {
  border-radius: 50px !important;
  background: #ffffff;
  box-shadow: 20px 20px 60px #bebebe45, -20px -20px 60px #ffffff40;
  height: 400px !important;
}
.scrollbtn {
  width: 50px;
  height: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #4285f4;
  color: #fff !important;
  cursor: pointer;
  border-radius: 50%;
  position: fixed;
  right: 5%;
  bottom: 5%;
  font-size: 30px !important;
}
.radius img {
  border-radius: 50% !important;
  width: 100px;
  margin: auto;
}
.card__mine {
  padding: 30px;
  background: #f1f1f1;
  border-radius: 5px;
  -webkit-transition: 0.3s all ease;
  -o-transition: 0.3s all ease;
  transition: 0.3s all ease;
  position: relative;
  top: 0;
  margin-bottom: 4em;
  text-align: center;
  padding-top: 50px;
}
.title__mine {
  color: #000 !important;
}
.description__mine {
  color: #00000083 !important;
}
.icon__div {
  width: 80px;
  height: 80px;
  color: #fff !important;
  position: absolute;
  top: -50px;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #4285f4;
  -webkit-box-shadow: 0 4px 20px -5px rgba(66, 133, 244, 0.4);
  box-shadow: 0 4px 20px -5px rgba(66, 133, 244, 0.4);
}
.card__mine:hover .title__mine {
  color: #fff !important;
}
.card__mine:hover .description__mine {
  color: #fff !important;
}
.card__mine:hover {
  color: #fff !important;

  background-color: #4285f4 !important;
}
.card__mine:hover .icon__div {
  background-color: #fff;
  color: #4285f4 !important;
}
.card__subscription {
  background-color: #fff;
  border: 1px solid #ccc;
  border-radius: 12px;
  height: 770px;
  position: relative;
}
.position__btn {
  position: absolute;
  bottom: 3%;
  display: flex;
  justify-content: center;
  margin: auto;
  width: 85%;
}
.position__btn button {
  width: 290px !important;
  margin: auto !important;
}
.fs-1 {
  font-size: 3.5rem;
}
.fs-2 {
  font-size: 2.5rem;
}
.fs-3 {
  font-size: 2rem;
}
.fs-4 {
  font-size: 1.5rem;
}
.fs-5 {
  font-size: 1rem;
}
.fs-6 {
  font-size: 0.75rem;
}

.carousel-indicators li {
  /* background: rgba(255, 255, 255, 0.4); */
  background-color: #000 !important;
  /* border-top: 20px solid; */
  height: 20px !important;
  width: 20px !important;
  border-radius: 50%;
  z-index: 15;
}
.carousel-indicators .active {
  background-color: #000 !important;
}
.img__testi {
  width: 90px;
}
@media (max-width: 423px) {
  .radius {
    border-radius: 50px !important;
    background: #ffffff;
    box-shadow: 20px 20px 60px #bebebe45, -20px -20px 60px #ffffff40;
    height: max-content !important;
  }
  .card__subscription {
    height: max-content !important;
    padding-bottom: 58px !important;
  }
  .position__btn {
    position: absolute;
    bottom: 1%;
    display: flex;
    justify-content: center;
    margin: auto;
    width: 85%;
  }
}
</style>
