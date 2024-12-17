<script setup lang="ts">
import { Button } from "@/components/ui/button";
import { CircleArrowRight, CircleArrowDown } from "lucide-vue-next";
</script>

<template>
  <!-- navbar -->
  <div>
    <div class="flex justify-between bg-headerBackground bg-no-repeat bg-cover">
      <div class="my-20 ml-48 w-1/2">
        <div>
          <h1 class="text-5xl font-semibold text-white">
            Sebuah framework CSS<br >
            untuk developer yang<br >
            memiliki phobia terhadap<br >CSS
          </h1>
          <p class="text-base text-white mt-5">
            Buku ini akan mengajarkan kamu konsep utility-first pada CSS <br >
            dan diakhiri dengan membangun sebuah website yang <br >
            responsive dengan Tailwind CSS.
          </p>
        </div>
        <div class="mt-12" />
        <div class="flex justify-start">
          <div>
            <Button
              class="bg-btn-blue hover:bg-btn-blue rounded-full py-6 px-11 text-base"
            >
              Beli Sekarang <CircleArrowRight
            /></Button>
          </div>
          <div class="flex justify-between ml-10">
            <div class="mr-4 mt-3 text-white">
              <CircleArrowDown />
            </div>
            <div>
              <p class="text-gray-400 text-base font-bold">SUDAH TERJUAL</p>
              <p class="text-white text-2xl font-semibold">501,234+</p>
            </div>
          </div>
        </div>
        <div class="mt-24 text-gray-400">
          <p class="flex items-center font-medium">
            <img
              src="./../assets/img/Rectangle 2.png"
              alt="rectangle 2"
              class="mr-4"
            >TEKNOLOGI YANG DIGUNAKAN
          </p>
          <img src="./../assets/img/icon.png" alt="icon" >
        </div>
      </div>

      <div class="w-1/2 mr-48">
        <img src="./../assets/img/book.png" alt="book" >
      </div>
    </div>

    <div class="flex justify-between mx-48 mt-52">
      <div class="w-1/2">
        <div class="text-gray-400">
          <p class="flex items-center font-medium text-btn-blue">
            <img
              src="./../assets/img/Rectangle 2.png"
              alt="rectangle 2"
              class="mr-4 bg-btn-blue"
            >BUKU INI UNTUK SIAPA
          </p>
        </div>
        <p class="text-3xl">
          Buku yang cocok dibaca untuk<br >
          front-end dan back-end,<br >
          bahkan UI designer!
        </p>
      </div>
      <div class="w-1/2">
        <p class="text-lg mt-4 text-gray-700">
          Buku ini bukan hanya untuk front-end developer yang ingin<br >
          meningkatkan skill, buku ini juga cocok untuk back-end developer<br >
          dan UI designer agar dapat menulis style tanpa harus menulis kode<br >
          CSS dan tanpa mengandalkan front-end developer!
        </p>
      </div>
    </div>
  </div>
</template>
