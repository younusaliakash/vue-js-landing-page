<script setup>
const heading = "Our News";
const subHeading = "Far from the countries Vokalia and Consonantia";
const blogItems = [
  {
    title: "Far far away behind the word mountains far from the countries",
    name: "James",
    date: "Jun 14, 2020",
    category: "Digital Service",
    photo: "images/person_1.jpg",
  },
  {
    title: "Far far away behind the word mountains far from the countries",
    name: "James",
    date: "Jun 14, 2020",
    category: "Digital Service",
    photo: "images/person_2.jpg",
  },
  {
    title: "Far far away behind the word mountains far from the countries",
    name: "James",
    date: "Jun 14, 2020",
    category: "Digital Service",
    photo: "images/person_3.jpg",
  },
];
</script>

<template>
  <div class="untree_co-section bg-light">
    <div class="container">
      <div class="row mb-4">
        <div class="col-12 text-center" data-aos="fade-up" data-aos-delay="0">
          <h2 class="heading">{{ heading }}</h2>
          <p>{{ subHeading }}</p>
        </div>
      </div>
      <div class="row">
        <div
          class="col-md-6 mb-4 mb-lg-0 col-lg-4"
          data-aos="fade-up"
          data-aos-delay="0"
        >
          <div class="news-item">
            <div class="vcard d-flex align-items-center mb-4">
              <div class="img-wrap">
                <img :src="blogItems[0].photo" alt="Image" class="img-fluid" />
              </div>
              <div class="post-meta">
                <strong>Posted by {{ blogItems[0].name }}</strong>
                <span>{{ blogItems[0].date }}</span>
              </div>
            </div>
            <div class="news-contents mb-4">
              <span class="post-meta-2"
                >{{ blogItems[0].category }}, 4 min read</span
              >
              <h3>
                <a href="#">{{ blogItems[0].title }}</a>
              </h3>
            </div>
            <p class="mb-0">
              <a href="#" class="read-more-arrow">
                <svg
                  class="bi bi-arrow-right"
                  width="1em"
                  height="1em"
                  viewBox="0 0 16 16"
                  fill="currentColor"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M10.146 4.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L12.793 8l-2.647-2.646a.5.5 0 0 1 0-.708z"
                  />
                  <path
                    fill-rule="evenodd"
                    d="M2 8a.5.5 0 0 1 .5-.5H13a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 8z"
                  />
                </svg>
              </a>
            </p>
          </div>
        </div>
        <div
          class="col-md-6 mb-4 mb-lg-0 col-lg-4"
          data-aos="fade-up"
          data-aos-delay="100"
        >
          <div class="news-item">
            <div class="vcard d-flex align-items-center mb-4">
              <div class="img-wrap">
                <img :src="blogItems[1].photo" alt="Image" class="img-fluid" />
              </div>
              <div class="post-meta">
                <strong>Posted by {{ blogItems[1].name }}</strong>
                <span>{{ blogItems[1].date }}</span>
              </div>
            </div>
            <div class="news-contents mb-4">
              <span class="post-meta-2"
                >{{ blogItems[1].category }}, 4 min read</span
              >
              <h3>
                <a href="#">{{ blogItems[1].title }}</a>
              </h3>
            </div>
            <p class="mb-0">
              <a href="#" class="read-more-arrow">
                <svg
                  class="bi bi-arrow-right"
                  width="1em"
                  height="1em"
                  viewBox="0 0 16 16"
                  fill="currentColor"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M10.146 4.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L12.793 8l-2.647-2.646a.5.5 0 0 1 0-.708z"
                  />
                  <path
                    fill-rule="evenodd"
                    d="M2 8a.5.5 0 0 1 .5-.5H13a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 8z"
                  />
                </svg>
              </a>
            </p>
          </div>
        </div>
        <div class="col-md-12 col-lg-4" data-aos="fade-up" data-aos-delay="300">
          <div class="news-item">
            <div class="vcard d-flex align-items-center mb-4">
              <div class="img-wrap">
                <img :src="blogItems[2].photo" alt="Image" class="img-fluid" />
              </div>
              <div class="post-meta">
                <strong>Posted by {{ blogItems[2].name }}</strong>
                <span>{{ blogItems[2].date }}</span>
              </div>
            </div>
            <div class="news-contents mb-4">
              <span class="post-meta-2"
                >{{ blogItems[2].category }}, 4 min read</span
              >
              <h3>
                <a href="#">{{ blogItems[2].title }}</a>
              </h3>
            </div>
            <p class="mb-0">
              <a href="#" class="read-more-arrow">
                <svg
                  class="bi bi-arrow-right"
                  width="1em"
                  height="1em"
                  viewBox="0 0 16 16"
                  fill="currentColor"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M10.146 4.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L12.793 8l-2.647-2.646a.5.5 0 0 1 0-.708z"
                  />
                  <path
                    fill-rule="evenodd"
                    d="M2 8a.5.5 0 0 1 .5-.5H13a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 8z"
                  />
                </svg>
              </a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
