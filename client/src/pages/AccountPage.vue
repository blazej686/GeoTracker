<script setup>
import { computed } from 'vue';
import { AppState } from '../AppState.js';

const account = computed(() => AppState.account)

</script>

<template>
  <div class="about text-center">
    <div v-if="account">
      <h1>Welcome {{ account.name }}</h1>
      <img class="rounded" :src="account.picture" alt="" />
      <p>{{ account.email }}</p>

      <h3>United States</h3>
      <p>Total States You Have Been : {{ }}</p>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Alabama</label> <br>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Alaska</label> <br>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Arizona</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Arkansas</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">California</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Colorado</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Connecticut</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Delaware</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Florida</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Georgia</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Hawaii</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Idaho</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Illinois</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Indiana</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Iowa</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Kansas</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Kentucky</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Louisiana</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Maine</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Maryland</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Massachusetts</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Michigan</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Minnesota</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Mississippi</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Missouri</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Montana</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Nebraska</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Nevada</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">New Hampshire</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">New Jersey</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">New Mexico</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">New York</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">North Carolina</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">North Dakota</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Ohio</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Oklahoma</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Oregon</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Pennsylvania</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Rhode Island</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">South Carolina</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">South Dakota</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Tennessee</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Texas</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Utah</label>
      <input type="checkbox" id="AK"> <span> </span>
      <label for="AK">Vermont</label>
      <input type="checkbox" id="VA"> <span> </span>
      <label for="VA">Virginia</label>
      <input type="checkbox" id="WA"> <span> </span>
      <label for="WA">Washington</label>
      <input type="checkbox" id="WV"> <span> </span>
      <label for="WV">West Virginia</label>
      <input type="checkbox" id="WI"> <span> </span>
      <label for="WI">Wisconsin</label>
      <input type="checkbox" id="WY"> <span> </span>
      <label for="WY">Wyoming</label>


    </div>
    <div v-else>
      <h1>Loading... <i class="mdi mdi-loading mdi-spin"></i></h1>
    </div>
  </div>
</template>

<style scoped lang="scss">
img {
  max-width: 100px;
}
</style>
