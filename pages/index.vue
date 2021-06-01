<template>
  <div class="wrapper">
    <v-app-bar color="#101010" absolute relative>
      <v-app-bar-title>Xcelspaces</v-app-bar-title>
    </v-app-bar>
    <div class="grid grid-cols-1 md:grid-cols-2 mt-16">
      <div class="h-full items-center flex" style="height: calc(100vh - 64px)">
        <div class="p-24">
          <span class="text-5xl p-2 block">
            Premium Virtual Spaces. Now free for everyone
          </span>

          <span class="block p-2">
            Connect with different people seamlessly, with no stree, no hastle
            and for FREE.
          </span>

          <div class="my-4 flex flex-col md:flex-row gap-4">
            <wrapper>
              <v-btn rounded x-large color="blue">New Space</v-btn>
            </wrapper>

            <wrapper width="55%">
              <v-text-field
                rounded
                outlined
                label="Enter a code or Space link"
                id="id"
              ></v-text-field>
            </wrapper>
          </div>
          <div>xceldeveloper.com</div>
        </div>
      </div>

      <div class="items-center flex" style="height: calc(100vh - 64px)">
        <div class="block m-auto">
          <v-carousel hide-delimiter-background hide-delimiters height="auto">
            <v-carousel-item>
              <div class="p-5">
                <wrapper height="auto" width="400px">
                  <img
                    class="block m-auto object-cover rounded-full h-72 w-72"
                    src="../static/get-link.svg"
                    alt=""
                  />
                  <div class="mt-3">
                    <span class="block text-center text-2xl">
                      Get a link you can Share
                    </span>
                  </div>
                </wrapper>
              </div>
            </v-carousel-item>
            <v-carousel-item>
              <div class="p-5">
                <wrapper height="auto" width="400px">
                  <img
                    class="block m-auto object-cover rounded-full h-72 w-72"
                    src="../static/group-video.svg"
                    alt=""
                  />
                  <div class="mt-3">
                    <span class="block text-center text-2xl">
                      Get a link you can Share
                    </span>
                  </div>
                </wrapper>
              </div>
            </v-carousel-item>
          </v-carousel>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import wrapper from "~/components/wrapper.vue";
export default {
  components: { wrapper },
};
</script>

<style scoped>
.wrapper {
  width: 100%;
  height: 100%;
}
</style>
