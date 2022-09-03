<template>
  <q-page>
    <q-carousel
      style="height: 100vh"
      animated
      v-model="slide"
      infinite
      autoplay
      arrows
    >
      <q-carousel-slide :name="1" img-src="~assets/slide3.jpg">
        <div class="absolute-center">
          <div class="text-center">
            <div
              class="text-h2 text-weight-light"
              data-aos="fade-right"
              data-aos-duration="1000"
            >
              The Most Trusted
            </div>
            <div
              class="text-h2 text-weight-bold q-my-md"
              data-aos="fade-right"
              data-aos-duration="1800"
            >
              Digital Money Exchange
            </div>
            <q-btn
              data-aos="fade-right"
              data-aos-duration="2500"
              class="button q-px-lg text-black text-h6 text-weight-light"
              no-caps
              color="warning"
              label="Read More"
            />
          </div>
        </div>
      </q-carousel-slide>
      <q-carousel-slide :name="2" img-src="~assets/slide2.jpg">
        <div class="text-white" style="margin-left: 130px; margin-top: 200px">
          <div class="text-h2" data-aos="fade-right" data-aos-duration="1000">
            <span class="text-weight-bold">Secure</span> and
            <span class="text-weight-bold">Easy</span> Way <br />
            to <span class="text-weight-bold">Trade</span>
          </div>
          <div
            class="text-h6 q-my-md text-white"
            data-aos="fade-right"
            data-aos-duration="1900"
          >
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab tempora
            <br />
            corporis voluptas nam odio quam iste animi ullam dignissimos ipsam!
          </div>
          <q-btn
            data-aos="fade-right"
            data-aos-duration="2500"
            class="q-px-lg text-black text-h6 text-weight-light"
            no-caps
            color="warning"
            label="Read More"
          />
        </div>
      </q-carousel-slide>
      <q-carousel-slide :name="3" img-src="~assets/slide1.jpg">
        <div class="text-white" style="margin-left: 130px; margin-top: 200px">
          <div
            class="text-h2 text-weight-light"
            data-aos="fade-right"
            data-aos-duration="2000"
          >
            is an innovative
          </div>
          <div
            class="text-h2 q-my-md text-weight-bold"
            data-aos="fade-left"
            data-aos-duration="2000"
          >
            Payment network
          </div>
          <div
            class="text-h2 text-weight-light"
            data-aos="fade-right"
            data-aos-duration="2000"
          >
            and a new kind of money
          </div>
          <q-btn
            data-aos="fade-left"
            data-aos-duration="2000"
            class="q-px-lg q-mt-md text-black text-h6 text-weight-light"
            no-caps
            color="warning"
            label="Read More"
          />
        </div>
      </q-carousel-slide>
    </q-carousel>
    <div class="bg-primary q-pb-xl">
      <div class="text-center">
        <div class="q-pt-xl">
          <div class="text-h3 text-weight-light">
            The Next-Generation Digital
          </div>
          <div class="text-h3 q-mt-sm text-weight-bold">Currency Exchange</div>
          <div class="text-subtitle1 q-mt-md text-weight-light text-grey-6">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nihil
            nulla mollitia<br />
            incidunt est, corporis provident temporibus, necessit
          </div>
        </div>
      </div>
      <div class="Sidewidth">
        <div class="row q-col-gutter-lg">
          <div
            class="col-3"
            data-aos="fade-right"
            data-aos-duration="1000"
            v-for="item in card"
            :key="item"
          >
            <q-card class="my-card q-pa-md text-center q-mt-lg hover-color">
              <div class="text-center">
                <img style="width: 150px" :src="item.src" />
              </div>
              <q-card-section>
                <div class="text-h5 text-weight-bold">{{ item.title }}</div>
                <div class="text-h6 text-weight-light">{{ item.name }}</div>
              </q-card-section>
              <q-card-section class="text-black">
                {{ item.lorem }}
              </q-card-section>
              <q-card-section>
                <q-btn
                  class="q-px-lg text-black text-h6 text-weight-light"
                  no-caps
                  color="warning"
                  label="Read More"
                />
              </q-card-section>
            </q-card>
          </div>
        </div>
      </div>
    </div>
    <div class="Sidewidth" style="margin-top: 100px; margin-bottom: 100px">
      <div class="row">
        <div class="col-6" data-aos="fade-right" data-aos-duration="1000">
          <q-img width="600px" src="~assets/team.png" />
        </div>
        <div
          class="col-6"
          data-aos="fade-left"
          data-aos-duration="1000"
          style="margin-top: 70px"
        >
          <div class="text-h3 text-weight-light">
            Innovative Payment Network
          </div>
          <div class="text-h3 q-mt-sm text-weight-bold">NEW KIND OF MONEY</div>
          <div class="text-h4 q-mt-md text-weight-light">
            Simple & secure access to buy, sell<br />and use Bitcoin
          </div>
          <div class="text-subtitle2 q-my-md text-grey-6 text-weight-light">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ex,
            temporibus error repudiandae obcaecati veniam delectus quisquam eos
            corrupti tempore alias nobis, consequatur nisi aliquid quibusdam
            quod. Excepturi aliquid repellendus quo et dolore eligendi
          </div>
          <q-btn
            class="q-px-lg text-black text-h6 text-weight-light"
            no-caps
            color="warning"
            label="Read More"
          />
        </div>
      </div>
    </div>
    <div class="bg-warning q-pb-xl">
      <div class="Sidewidth" style="margin-top: 100px">
        <div
          class="text-h3 text-weight-light"
          data-aos="fade-right"
          data-aos-duration="1000"
          style="padding-top: 90px"
        >
          Why BitCoin?
        </div>
        <div
          class="text-h3 text-weight-medium q-mt-sm"
          data-aos="fade-right"
          data-aos-duration="2000"
        >
          SECURE TRANSACTIONS PLATFORM
        </div>
        <div class="row q-mt-xl q-col-gutter-md">
          <div
            class="col-3"
            data-aos="flip-right"
            data-aos-duration="1000"
            v-for="item in coin"
            :key="item"
          >
            <q-icon size="50px" :name="item.icon" />
            <div class="text-h6 q-my-sm text-weight-medium">
              {{ item.name }}
            </div>
            <div class="text-body1 text-weight-light text-grey-7">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa
              nulla officiis quasi hic harum accusamus.
            </div>
          </div>
        </div>
      </div>
    </div>
    <q-card class="q-my-xl q-py-lg shadow-0">
      <q-tabs
        style="font-size: 2rem"
        v-model="tab"
        inline-label
        class="text-black q-pa-md q-mt-xl"
        active-bg-color="primary"
        indicator-color="black"
        no-caps
      >
        <q-tab name="Liquidity" label="Liquidity" />
        <q-tab name="Reliability" label="Reliability" />
        <q-tab name="Security" label="Security" />
        <q-tab name="Trading" label="Trading" />
      </q-tabs>

      <q-tab-panels v-model="tab" animated>
        <q-tab-panel name="Liquidity">
          <div class="row q-col-gutter-md Sidewidth">
            <div class="col-6" data-aos="fade-right" data-aos-duration="1000">
              <div class="text-h3 text-weight-light">Supported</div>
              <div class="text-h3 q-my-md text-weight-medium">
                PAYMENT METHODS
              </div>
              <div class="text-h4 text-weight-light">
                Simple & Secure access to buy, sell<br />and use Bitcoin
              </div>
              <div
                class="row q-mt-sm q-col-gutter-lg"
                data-aos="fade-right"
                data-aos-duration="1000"
              >
                <div
                  class="col-6 text-body1 text-weight-light text-grey-6"
                  v-for="item in payment"
                  :key="item"
                >
                  <q-icon
                    color="black"
                    size="15px"
                    name="fas fa-arrow-circle-right"
                  />
                  {{ item.name }}<q-separator />
                </div>
              </div>
            </div>
            <div class="col-6" data-aos="fade-left" data-aos-duration="1000">
              <q-img src="~assets/vid.jpg" style="border-radius: 50px" />
            </div>
          </div>
        </q-tab-panel>

        <q-tab-panel name="Reliability">
          <div
            class="row q-col-gutter-md"
            style="margin-left: 130px; margin-right: 130px"
          >
            <div class="col-6" data-aos="fade-right" data-aos-duration="1000">
              <q-img src="~assets/vid1.jpg" style="border-radius: 50px" />
            </div>
            <div class="col-6" data-aos="fade-left" data-aos-duration="1000">
              <div class="text-h3 text-weight-light">Supported</div>
              <div class="text-h3 q-my-md text-weight-medium">
                PAYMENT METHODS
              </div>
              <div class="text-h4 text-weight-light">
                Simple & Secure access to buy, sell<br />and use Bitcoin
              </div>
              <div
                class="row q-mt-sm q-col-gutter-lg"
                data-aos="fade-right"
                data-aos-duration="1000"
              >
                <div
                  class="col-6 text-body1 text-weight-light text-grey-6"
                  data-aos="fade-left"
                  data-aos-duration="1000"
                  v-for="item in payments"
                  :key="item"
                >
                  <q-icon
                    color="black"
                    size="15px"
                    name="fas fa-arrow-circle-right"
                  />
                  {{ item.name }}<q-separator />
                </div>
              </div>
            </div>
          </div>
        </q-tab-panel>

        <q-tab-panel name="Security">
          <div
            class="row q-col-gutter-md"
            style="margin-left: 130px; margin-right: 130px"
          >
            <div class="col-6" data-aos="fade-right" data-aos-duration="1000">
              <div class="text-h3 text-weight-light">Supported</div>
              <div class="text-h3 q-my-md text-weight-medium">
                PAYMENT METHODS
              </div>
              <div class="text-h4 text-weight-light">
                Simple & Secure access to buy, sell<br />and use Bitcoin
              </div>
              <div
                class="row q-mt-sm q-col-gutter-lg"
                data-aos="fade-right"
                data-aos-duration="1000"
              >
                <div
                  class="col-6 text-body1 text-weight-light text-grey-6"
                  v-for="item in payment"
                  :key="item"
                >
                  <q-icon
                    color="black"
                    size="15px"
                    name="fas fa-arrow-circle-right"
                  />
                  {{ item.name }}<q-separator />
                </div>
              </div>
            </div>
            <div class="col-6" data-aos="fade-left" data-aos-duration="1000">
              <q-img src="~assets/vid2.jpg" style="border-radius: 50px" />
            </div>
          </div>
        </q-tab-panel>

        <q-tab-panel name="Trading">
          <div
            class="row q-col-gutter-md"
            style="margin-left: 130px; margin-right: 130px"
          >
            <div class="col-6" data-aos="fade-right" data-aos-duration="1000">
              <q-img src="~assets/vid3.jpg" style="border-radius: 50px" />
            </div>
            <div class="col-6" data-aos="fade-left" data-aos-duration="1000">
              <div class="text-h3 text-weight-light">Supported</div>
              <div class="text-h3 q-my-md text-weight-medium">
                PAYMENT METHODS
              </div>
              <div class="text-h4 text-weight-light">
                Simple & Secure access to buy, sell<br />and use Bitcoin
              </div>
              <div
                class="row q-mt-sm q-col-gutter-lg"
                data-aos="fade-left"
                data-aos-duration="1000"
              >
                <div
                  class="col-6 text-body1 text-weight-light text-grey-6"
                  v-for="item in payments"
                  :key="item"
                >
                  <q-icon
                    color="black"
                    size="15px"
                    name="fas fa-arrow-circle-right"
                  />
                  {{ item.name }}<q-separator />
                </div>
              </div>
            </div>
          </div>
        </q-tab-panel>
      </q-tab-panels>
      <div
        class="row q-mb-lg q-col-gutter-md"
        style="margin-left: 130px; margin-right: 130px"
      >
        <div class="col-6" data-aos="fade-right" data-aos-duration="1000">
          <q-card class="my-card bg-warning q-pa-md">
            <q-item>
              <q-avatar class="q-mr-md" size="130px">
                <img src="~assets/tab1.png" />
              </q-avatar>
              <q-item-section>
                <div class="text-h3 text-weight-light">Buy & Sell BitCoin</div>
                <div class="text-subtitle2 text-weight-light">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Minima ullam assumenda qui rerum consequatur deleniti
                  cupiditate repudiandae aspernatur! Veritatis, nemo.
                </div>
              </q-item-section>
            </q-item>
          </q-card>
        </div>
        <div class="col-6" data-aos="fade-left" data-aos-duration="1000">
          <q-card class="my-card bg-warning q-pa-md">
            <q-item>
              <q-avatar class="q-mr-md" size="130px">
                <img src="~assets/tab2.png" />
              </q-avatar>
              <q-item-section>
                <div class="text-h3 text-weight-light">Acquire BitCoins</div>
                <div class="text-subtitle2 text-weight-light">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Minima ullam assumenda qui rerum consequatur deleniti
                  cupiditate repudiandae aspernatur! Veritatis, nemo.
                </div>
              </q-item-section>
            </q-item>
          </q-card>
        </div>
      </div>
    </q-card>
    <q-img height="500px" src="~assets/rate.jpg">
      <div class="absolute-center bg-transparent">
        <div class="text-center">
          <div
            class="text-h4 text-weight-light"
            data-aos="fade-right"
            data-aos-duration="500"
          >
            Innovations present an opportunity...
          </div>
          <div
            class="text-h3 text-weight-medium"
            data-aos="fade-right"
            data-aos-duration="1000"
          >
            NOT A THREAT!
          </div>
          <div class="row q-mt-md q-col-gutter-xl">
            <div
              class="col-3"
              data-aos="flip-up"
              data-aos-duration="1000"
              v-for="item in present"
              :key="item"
            >
              <q-icon color="warning" size="40px" :name="item.icon" />
              <div class="text-h3 text-weight-light">{{ item.name }}</div>
              <div class="text-h6 text-weight-medium">{{ item.title }}</div>
            </div>
          </div>
        </div>
      </div>
    </q-img>
    <div class="text-center q-py-xl">
      <div
        class="text-h3 text-weight-light"
        data-aos="fade-right"
        data-aos-duration="1000"
      >
        BitCoin and CryptoCurrency
      </div>
      <div
        class="text-h3 text-weight-medium"
        data-aos="fade-right"
        data-aos-duration="2000"
      >
        LATEST NEWS
      </div>
    </div>
    <div class="row q-my-xl q-col-gutter-md Sidewidth">
      <div
        class="col-4"
        data-aos="flip-right"
        data-aos-duration="1000"
        v-for="item in cards"
        :key="item"
      >
        <q-card class="my-card shadow-0">
          <img :src="item.img" />
          <q-card-section>
            <div class="text-h5 text-weight-medium">{{ item.name }}}</div>
            <div class="text-h6">
              {{ item.title }} <q-icon size="15px" name="fas fa-comment-alt" />0
              <q-icon size="15px" name="fas fa-user" />ram
            </div>
            <div class="text-subtitle2 text-grey-6">
              In: {{ item.new }} tags: {{ item.tag }}
            </div>
          </q-card-section>
          <q-card-section>
            <q-btn
              class="q-px-ld text-black text-weight-light"
              no-caps
              color="warning"
              icon-right="fas fa-arrow-right"
              label="Read More"
            />
          </q-card-section>
        </q-card>
      </div>
    </div>
    <q-img src="~assets/inp.png">
      <div class="text-center full-width full-height q-pt-xl text-white">
        <div class="text-h3 text-weight-light" style="margin-top: 100px">
          BitCoin
        </div>
        <div class="text-h3 text-weight-medium">Calculator</div>
        <div
          class="row q-col-gutter-md Sidewidth q-mt-lg"
          style="margin-top: 100px"
        >
          <div
            class="col-6 text-left"
            data-aos="fade-right"
            data-aos-duration="1000"
          >
            <div class="q-my-lg"></div>
            <div class="text-h4 text-weight-light">
              Minimum purchase is 60 Coins tokens.
            </div>
            <div class="text-h4 text-weight-light">
              Get a bonus from 6% to 35%
            </div>
            <div class="text-h4 text-weight-light">on every token purchase</div>
            <div class="row q-mt-lg q-col-gutter-md">
              <div class="col-3">
                <q-input
                  outlined
                  dark
                  color="black"
                  v-model="text"
                  type="text"
                />
              </div>
              <div class="col-1 text-weight-bold text-white text-h5 q-mt-sm">
                BTC
              </div>
              <div class="col-5">
                <q-input
                  outlined
                  dark
                  color="black"
                  v-model="text"
                  type="text"
                />
              </div>
              <div class="col-3">
                <q-input
                  outlined
                  dark
                  color="black"
                  v-model="text"
                  type="text"
                  placeholder="USD"
                />
              </div>
            </div>
          </div>
          <div class="col-6" data-aos="fade-left" data-aos-duration="1000">
            <q-img src="~assets/inplaptop.png" />
          </div>
        </div>
      </div>
    </q-img>
    <div class="text-center q-py-xl">
      <div
        class="text-h3 text-weight-light"
        data-aos="fade-right"
        data-aos-duration="1000"
      >
        Meet OUR
      </div>
      <div
        class="text-h3 text-weight-medium"
        data-aos="fade-right"
        data-aos-duration="2000"
      >
        Team Member
      </div>
    </div>
    <ul
      class="cards Sidewidth"
      data-aos="flip-down"
      data-aos-duration="1000"
      data-aos-once="true"
    >
      <li>
        <a href="" class="card">
          <q-img src="~assets/team1.jpg" class="card__image" alt="" />
          <div class="card__overlay bg-white">
            <div class="card__header">
              <div class="card__header-text">
                <h3 class="card__title text-weight-bold text-black text-h4">
                  Sam Schwartz
                </h3>
                <span class="text-h6">Cryptocurrency Developer</span>
              </div>
            </div>
            <div class="row text-center q-col-gutter-md">
              <div class="col-2 q-ml-md">
                <q-icon size="30px" color="blue-9" name="fab fa-facebook" />
              </div>
              <div class="col-2">
                <q-icon size="30px" color="red" name="fab fa-youtube" />
              </div>
              <div class="col-2">
                <q-icon size="30px" color="blue" name="fab fa-twitter" />
              </div>
              <div class="col-2">
                <q-icon size="30px" color="blue-8" name="fab fa-linkedin" />
              </div>
            </div>
          </div>
        </a>
      </li>
      <li>
        <a href="" class="card">
          <q-img src="~assets/team3.jpg" class="card__image" alt="" />
          <div class="card__overlay bg-white">
            <div class="card__header">
              <div class="card__header-text">
                <h3 class="card__title text-weight-bold text-black text-h4">
                  Bobby Lawson
                </h3>
                <span class="text-h6">Cryptocurrency Analyst</span>
              </div>
            </div>
            <div class="row text-center q-col-gutter-md">
              <div class="col-2 q-ml-md">
                <q-icon size="30px" color="blue-9" name="fab fa-facebook" />
              </div>
              <div class="col-2">
                <q-icon size="30px" color="red" name="fab fa-youtube" />
              </div>
              <div class="col-2">
                <q-icon size="30px" color="blue" name="fab fa-twitter" />
              </div>
              <div class="col-2">
                <q-icon size="30px" color="blue-8" name="fab fa-linkedin" />
              </div>
            </div>
          </div>
        </a>
      </li>
      <li>
        <a href="" class="card">
          <q-img src="~assets/team2.jpg" class="card__image" alt="" />
          <div class="card__overlay bg-white">
            <div class="card__header">
              <div class="card__header-text">
                <h3 class="card__title text-weight-bold text-black text-h4">
                  Ronnie Patton
                </h3>
                <span class="text-h6">Cryptocurrency Mining Lead</span>
              </div>
            </div>
            <div class="row text-center q-col-gutter-md">
              <div class="col-2 q-ml-md">
                <q-icon size="30px" color="blue-9" name="fab fa-facebook" />
              </div>
              <div class="col-2">
                <q-icon size="30px" color="red" name="fab fa-youtube" />
              </div>
              <div class="col-2">
                <q-icon size="30px" color="blue" name="fab fa-twitter" />
              </div>
              <div class="col-2">
                <q-icon size="30px" color="blue-8" name="fab fa-linkedin" />
              </div>
            </div>
          </div>
        </a>
      </li>
    </ul>
    <div class="bg-warning q-py-lg q-mt-xl">
      <div class="row q-pa-lg Sidewidth q-col-gutter-lg">
        <div
          class="col-6"
          data-aos="fade-right"
          data-aos-duration="1000"
          data-aos-once="true"
        >
          <div class="text-h4 text-weight-light">
            Subscribe to our <span class="text-weight-bold">NEWSLETTER</span>
          </div>
        </div>
        <div
          class="col-6"
          data-aos="fade-left"
          data-aos-duration="1000"
          data-aos-once="true"
        >
          <div class="row q-col-gutter-xs">
            <div class="col-10">
              <q-input
                outlined
                color="black"
                v-model="text"
                type="email"
                placeholder="Enter Your Email Address"
              />
            </div>
            <div class="col-2">
              <q-btn
                no-caps
                class="text-white bg-black q-pa-md"
                label="Subscribe"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="text-center q-py-xl">
      <div
        class="text-h3 text-weight-light"
        data-aos="fade-right"
        data-aos-duration="1000"
      >
        CONTACT <span class="text-weight-medium">US</span>
      </div>
    </div>
    <div class="row q-py-lg Sidewidth q-col-gutter-xl">
      <div class="col-4" data-aos="fade-right" data-aos-duration="1000">
        <div class="text-h4 text-weight-bold q-mb-md">TolFree Numbers</div>
        <div class="text-h6 q-mb-md" v-for="item in items" :key="item">
          <q-icon name="fas fa-globe-asia" /> {{ item.name }}
          <span class="text-h6 text-grey-6">{{ item.title }}</span>
          <q-separator />
        </div>
      </div>
      <div class="col-8" data-aos="fade-left" data-aos-duration="1000">
        <div class="text-h4 text-weight-bold q-mb-md">Enquiry Form</div>
        <div class="row q-col-gutter-lg">
          <q-input
            class="col-6 q-mb-md"
            v-model="text"
            type="text"
            label="First Name"
          />
          <q-input class="col-6" v-model="text" type="text" label="Last Name" />
          <q-input
            class="col-6 q-mb-md"
            v-model="text"
            type="email"
            label="Email"
          />
          <q-input class="col-6" v-model="text" type="phone" label="Phone" />
          <q-input class="col" v-model="text" type="textarea" label="Message" />
        </div>
      </div>
    </div>
    <div class="text-center">
      <q-btn
        no-caps
        class="q-my-lg q-px-lg text-black bg-warning"
        label="Send Message"
      />
    </div>
    <q-toolbar class="bg-black text-warning">
      <q-img class="q-ml-sm" width="150px" src="~assets/logo.png" />
      <q-space />
      <div class="text-subtitle1 q-mr-sm text-weight-medium">
        © 2020 DigiBit
      </div>
    </q-toolbar>
  </q-page>
</template>

<script>
import { ref } from "vue";

export default {
  setup() {
    return {
      slide: ref(1),
      tab: ref("Liquidity"),
      items: [
        {
          name: "United States:",
          title: "+91 1234 567 890",
        },
        {
          name: "China:",
          title: "+91 1234 567 890",
        },
        {
          name: "Germany:",
          title: "+91 1234 567 890",
        },
        {
          name: "United Kingdom:",
          title: "+91 1234 567 890",
        },
        {
          name: "France:",
          title: "+91 1234 567 890",
        },
        {
          name: "India:",
          title: "+91 1234 567 890",
        },
        {
          name: "Brazil:",
          title: "+91 1234 567 890",
        },
      ],
      cards: [
        {
          img: require("assets/Blog1.jpg"),
          name: "Exchange rate of bitcoin",
          title: "January 17, 2018",
          new: "Exchange",
          tag: "foreign currency, rates",
        },
        {
          img: require("assets/Blog2.jpg"),
          name: "Fluctuating fortunes of Bitcoin",
          title: "January 10, 2018",
          new: "Finance, News",
          tag: "New Category, Test Category",
        },
        {
          img: require("assets/blog3.jpg"),
          name: "New world wide payment system",
          title: "June 18, 2015",
          new: "Currency, News",
          tag: "cryptocurrency, innovation",
        },
      ],
      card: [
        {
          src: require("assets/card2.png"),
          title: "Easy To Transact",
          name: "Peer To Peer Transactions",
          lorem:
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation",
        },
        {
          src: require("assets/card4.png"),
          title: "Foolproof Security",
          name: "Borderless Paymentss",
          lorem:
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation",
        },
        {
          src: require("assets/card3.png"),
          title: "No Fear Of Loss",
          name: "Fraud Protection",
          lorem:
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation",
        },
        {
          src: require("assets/card1.png"),
          title: "No Expensive Softwares",
          name: "Open Source Software",
          lorem:
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation",
        },
      ],
      coin: [
        {
          icon: "fas fa-user",
          name: "BitCoin for Individuals",
        },
        {
          icon: "fas fa-briefcase",
          name: "BitCoin for Business",
        },
        {
          icon: "fas fa-coins",
          name: "BitCoin for Developers",
        },
        {
          icon: "fab fa-bitcoin",
          name: "BitCoin for Investors",
        },
      ],
      payment: [
        { name: "PayPal" },
        { name: "BitCoin Exchange" },
        { name: "Bank Account" },
        { name: "From Someone Near" },
        { name: "Deposit" },
        { name: "Competitive Mining" },
        { name: "Credit/Debit Card" },
        { name: "Payment for goods/services" },
      ],
      payments: [
        { name: "PayPal" },
        { name: "Competitive Mining" },
        { name: "Payment for goods" },
        { name: "Bank Account" },
        { name: "Credit/Debit Card" },
        { name: "Deposit" },
        { name: "From Someone Near" },
        { name: "Payment for goods/services" },
      ],
      present: [
        {
          icon: "fab fa-bitcoin",
          name: "45B+",
          title: "Currency Exchange",
        },
        {
          icon: "fas fa-clock",
          name: "5B+",
          title: "24-Hour Volume Record",
        },
        {
          icon: "fas fa-map-marker-alt",
          name: "34",
          title: "Countries Supported",
        },
        {
          icon: "fas fa-user-friends",
          name: "10M+",
          title: "Customers Served",
        },
      ],
    };
  },
};
</script>

<style lang="sass" scoped>
.Sidewidth
  margin-right: 130px
  margin-left: 130px
:root
  --surface-color: #ffffff
  --curve: 40

*
  box-sizing: border-box

body
  font-family: 'Noto Sans JP', sans-serif
  background-color: #fef8f8

.cards
  display: grid
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))
  gap: 2rem
  padding: 0
  list-style-type: none

.card
  position: relative
  display: block
  height: 100%
  border-radius: calc(var(--curve) * 1px)
  overflow: hidden
  text-decoration: none

.card__image
  width: 100%
  height: auto

.card__overlay
  position: absolute
  bottom: 0
  left: 0
  right: 0
  z-index: 1
  border-radius: calc(var(--curve) * 1px)
  background-color: var(--surface-color)
  transform: translateY(100%)
  transition: .2s ease-in-out

.card:hover .card__overlay
  transform: translateY(0)

.card__header
  position: relative
  display: flex
  align-items: center
  gap: 2em
  padding: 2em
  border-radius: calc(var(--curve) * 1px) 0 0 0
  background-color: var(--surface-color)
  transform: translateY(-100%)
  transition: .2s ease-in-out

.card__arc
  width: 80px
  height: 80px
  position: absolute
  bottom: 100%
  right: 0
  z-index: 1

.card__arc path
  fill: var(--surface-color)
  d: path("M 40 80 c 22 0 40 -22 40 -40 v 40 Z")

.card:hover .card__header
  transform: translateY(0)

.card__thumb
  flex-shrink: 0
  width: 50px
  height: 50px
  border-radius: 50%

.card__title
  margin: 0 0 .3em

.card__tagline
  display: block
  margin: 1em 0
  font-family: "MockFlowFont"
  font-size: .8em
  color: #D7BDCA

.card__description
  padding: 0 2em 2em
  margin: 0
  color: #D7BDCA
  font-family: "MockFlowFont"
  display: -webkit-box
  -webkit-box-orient: vertical
  -webkit-line-clamp: 3
  overflow: hidden
  .hover-color:hover
    background-color: black
    color: white
</style>
<style lang="scss">
  .hover-color{
  background:linear-gradient(to bottom, #fffc00, #ffffff);
  color: black;
}
</style>
