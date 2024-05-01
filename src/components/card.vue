<template>
  <div class="card">
    <div class="card1">
      <b-card no-body class="overflow-hidden" style="max-width: 540px">
        <b-row no-gutters>
          <b-col md="6">
            <b-card-img
              src="https://news-homepage-s3.s3.eu-west-2.amazonaws.com/image-retro-pcs.jpg"
              alt="Image"
              class="rounded-0"
            ></b-card-img>
          </b-col>
          <b-col>
            <b-card-body title="01">
              <b-card-body title="Reviving Retro PCs">
                <b-card-text>
                  What happens whwn old PCs are given modern updrades?
                </b-card-text>
              </b-card-body>
            </b-card-body>
          </b-col>
        </b-row>
      </b-card>
    </div>
    <div class="card2">
      <b-card no-body class="overflow-hidden" style="max-width: 540px">
        <b-row no-gutters>
          <b-col md="6">
            <b-card-img
              src="https://news-homepage-s3.s3.eu-west-2.amazonaws.com/image-top-laptops.jpg"
              alt="Image"
              class="rounded-0"
            ></b-card-img>
          </b-col>
          <b-col md="6">
            <b-card-body title="02">
              <b-card-body title="Top 10 Laptops of 2022">
                <b-card-text>
                  Our best picks for various needs nd budgets.
                </b-card-text>
              </b-card-body>
            </b-card-body>
          </b-col>
        </b-row>
      </b-card>
    </div>
    <div class="card3">
      <b-card no-body class="overflow-hidden" style="max-width: 540px">
        <b-row no-gutters>
          <b-col md="6">
            <b-card-img
              src="https://news-homepage-s3.s3.eu-west-2.amazonaws.com/image-gaming-growth.jpg"
              alt="Image"
              class="rounded-0"
            ></b-card-img>
          </b-col>
          <b-col md="6">
            <b-card-body title="03">
              <b-card-body title="The Growth of Gaming">
                <b-card-text>
                  How the pandemic has sparked fresh opportunities.
                </b-card-text>
              </b-card-body>
            </b-card-body>
          </b-col>
        </b-row>
      </b-card>
    </div>
  </div>
</template>

<style>
.card {
  width: auto;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  gap: 33px;
}
.rounded-0 {
  padding: 50px;
}
</style>
