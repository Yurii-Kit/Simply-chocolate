# fson-114

**Theoretical and practical classes HTML + CSS course**

[🍫 Посилання на макет Simply Chocolate](https://www.figma.com/file/SHNrA7r9RBXLqDUVYZjL1g/Simply-Chocolate?type=design&node-id=0%3A1&mode=design&t=6aQS0hFd0tLCXP49-1)


 <!-- Example for adaptive images with tag <piture> -->
    <section class="hide">
      <h2>Our Portfolio</h2>
      <li class="item">
        <div class="wrapper">
          <picture>
            <!-- Desktop -->
            <source
              media="(min-width: 1158px)"
              srcset="
                ./images/portfolio/img-1_desk@1x 1x,
                ./images/portfolio/img-1_desk@2x 2x
              "
            />
            <!-- Tablet -->
            <source
              media="(min-width: 768px)"
              srcset="
                ./images/portfolio/img-1_tab@1x 1x,
                ./images/portfolio/img-1_tab@2x 2x
              "
            />
            <!-- Mobile -->
            <source
              media="(max-width: 767px)"
              srcset="
                ./images/portfolio/img-1_mob@1x 1x,
                ./images/portfolio/img-1_mob@2x 2x
              "
            />
            <img
              class="portfolio-ill"
              src="./images/portfolio/img-1_mob@1x"
              alt="image"
              width="360"
              height="300"
            />
          </picture>
          <p class="overlay"></p>
        </div>
        <div class="bottom-box">
          <h3></h3>
          <p></p>
        </div>
      </li>
    </section>