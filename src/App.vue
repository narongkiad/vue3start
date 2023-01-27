<script setup>
import LikeSad from "./components/LikeSad.vue";
</script>

<style>
table,
th,
td {
  border: 1px;
}
</style>

<template>
  <table style="width: 100%">
    <tr>
      <th>
        <div class="Picture">
          <img src="/img/blue.jpg" alt="" width="250" />
        </div>
        Blue
        <LikeSad></LikeSad>
      </th>
      <th>
        <div class="Picture">
          <img src="/img/green.jpg" alt="" width="250" />
        </div>
        Green
        <LikeSad></LikeSad>
      </th>
      <th>
        <div class="Picture">
          <img src="/img/pink.jpg" alt="" width="250" />
        </div>
        Pink
        <LikeSad></LikeSad>
      </th>
    </tr>
    <tr>
      <th>
        <div class="Picture">
          <img src="/img/red.png" alt="" width="250" />
        </div>
        Red
        <LikeSad></LikeSad>
      </th>
      <th>
        <div class="Picture">
          <img src="/img/yellow.jpg" alt="" width="250" />
        </div>
        Yellow
        <LikeSad></LikeSad>
      </th>
      <th>
        <div class="Picture">
          <img src="/img/black.png" alt="" width="250" />
        </div>
        Black
        <LikeSad></LikeSad>
      </th>
    </tr>
  </table>
</template>
