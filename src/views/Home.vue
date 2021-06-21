<template>
  <v-container class="">
    <div>
      <div>
        <div class="py-10">
          <div>
            <h1 class="saira-semibold text-center text-primary">
              Leonardo Antonio
              <span class="text-secundary">
                Nolasco Leyva
              </span>
            </h1>
            <span class="text-center subtitle">
              <h4>DESARROLLADOR DE SOFTWARE</h4>
            </span>
          </div>
        </div>

        <v-row>
          <v-col align="end">
            <div>
              <img src="../assets/img__main__home.svg" width="420px" alt="" />
            </div>
          </v-col>
          <v-col align="start">
            <div class="w50">
              <div class="text-md text-white pb-5 pt-10">
                Desarrollador Backend con concimientos en el Frontend
              </div>
              <div>
                <button class="text-white btn">
                  Contáctame
                </button>
              </div>
            </div>
          </v-col>
        </v-row>
      </div>
    </div>
  </v-container>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Saira:wght@600&display=swap");

.text-secundary {
  color: #00aae4;
}
.text-primary {
  color: #fff;
}
.saira-semibold {
  font-family: Saira;
  font-style: normal;
  font-weight: 600;
  font-size: 70px;
  line-height: 52px;
}

.subtitle {
  font-family: Saira;
  font-style: normal;
  font-weight: 600;
  font-size: 25px;
  line-height: 55px;

  color: #ffffff;
}

.btn {
  background: #00aae4;
  border-radius: 50px;
  width: 100%;
  padding: 0.5rem;
}
</style>
