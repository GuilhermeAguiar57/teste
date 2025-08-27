<template>
  <section class="w-full flex justify-center">
    <div
      class="flex flex-col items-center w-full rounded-[0.375rem]
             se:px-[0.9375rem] md:px-[3.4375rem] lg:px-[3.4375rem]
             pt-[4.875rem] pb-[10.625rem] gap-[2.3125rem]
             md:max-w-[113.5625rem]"
    >
      <!-- Header Section -->
      <div class="flex flex-col items-center w-full gap-[2.625rem] md:gap-[4.625rem]">
        <!-- Logo -->
        <div class="flex flex-col items-start gap-[0.625rem] md:w-[16.385rem]">
          <img
            :src="brand"
            alt="Eu Quero Consultar"
            class="object-contain h-[5.625rem] s8:h-[7.5rem] lg:h-[10.86rem] w-auto"
            decoding="async"
          />
        </div>

        <!-- Title and Subtitle -->
        <div class="flex flex-col items-center text-center gap-[0.625rem] w-full md:max-w-[67.6875rem]">
          <h2
            class="font-[700] text-[#3D3D3D] w-full
                   se:text-[1.75rem] se:leading-[2.125rem]
                   su:text-[3rem] su:leading-[3.75rem]
                   md:text-[3rem] md:leading-[3.75rem]
                   lg:text-[4rem] lg:leading-[4.875rem]
                   xl:text-[5rem] xl:leading-[6.125rem]"
          >
            Ainda ficou com dúvidas?
          </h2>
          <p
            class="font-[500] text-[#606060] w-full md:max-w-[43.6875rem]
                   se:text-[0.875rem] se:leading-[1.0625rem]
                   su:text-[1.25rem] su:leading-[1.625rem]
                   md:text-[1.5rem] md:leading-[1.875rem]
                   lg:text-[1.75rem] lg:leading-[2.125rem]
                   xl:text-[1.875rem] xl:leading-[2.3125rem]"
          >
            Contate um de nossos canais de atendimento
          </p>
        </div>
      </div>

      <!-- Content Section -->
      <div
        class="w-full
               se:flex se:flex-col
               md:grid md:grid-cols-12
               items-center md:items-stretch justify-center
               px-0 md:px-[3.4375rem]
               gap-y-[1rem]
               md:gap-y-[2rem]
               md:gap-x-[2rem]
               lg:gap-x-[3rem]
               xl:gap-x-[9.75rem]"
      >
        <!-- Image Section -->
        <div class="col-span-12 md:col-span-5 lg:col-span-5 min-w-0 flex justify-center md:items-stretch">
          <div
            class="relative
                   se:w-[18.75rem] se:h-[21.875rem]
                   xs:w-[21.25rem] xs:h-[24.375rem]
                   su:w-[24rem] su:h-[27.5rem]
                   md:w-[26rem] md:h-[30rem]
                   lg:w-[32rem] lg:h-[36rem]
                   xl:w-[38.5625rem] xl:h-[43.75rem]"
          >
            <img
              :src="banner"
              alt="Atendimento Eu Quero Consultar"
              class="absolute bottom-0 left-1/2 -translate-x-1/2
                     w-auto max-w-full
                     h-[90%] md:h-full
                     object-contain"
              decoding="async"
            />
          </div>
        </div>

        <!-- Text and CTA Section -->
        <div
          class="col-span-12 md:col-span-7 lg:col-span-7 min-w-0 w-full
                 flex flex-col items-center md:items-start
                 gap-[1.25rem] md:gap-[2rem] lg:gap-[3.25rem]
                 se:max-w-[18.75rem] md:max-w-none"
        >
          <!-- Schedule Info -->
          <div class="w-full min-w-0 flex flex-col items-center md:items-start gap-[1.75rem]">
            <h3
              class="font-[700] text-[#3D3D3D] text-center md:text-left w-full
                     se:text-[1.25rem] se:leading-[1.5625rem]
                     md:text-[1.875rem] md:leading-[2.25rem]
                     lg:text-[2.25rem] lg:leading-[2.75rem]
                     xl:text-[2.375rem] xl:leading-[2.875rem]"
            >
              Horário de atendimento
            </h3>
            <p
              class="font-[500] text-[#606060] text-center md:text-left w-full
                     se:text-[0.9375rem] se:leading-[1.25rem]
                     md:text-[1.375rem] md:leading-[1.75rem]
                     lg:text-[1.75rem] lg:leading-[2.125rem]
                     xl:text-[2.0625rem] xl:leading-[2.5rem]"
            >
              De segunda a sexta-feira de 09h às 18h. Exceto feriados.
            </p>
          </div>

          <!-- Contact Button -->
          <div class="w-full flex flex-col gap-[1rem] md:gap-[1.5rem]">
            <a
              href="mailto:suporte@euqueroconsultar.com.br"
              aria-label="Enviar e-mail para suporte@euqueroconsultar.com.br"
              class="flex flex-col items-center justify-center
                     gap-[0.75rem] md:gap-[1rem] lg:gap-[1.5625rem]
                     bg-white rounded-[0.75rem]
                     shadow-[0_0_0.4375rem_rgba(0,0,0,0.12)]
                     px-[1.25rem]
                     w-full
                     md:max-w-[32rem]
                     lg:max-w-[40rem]
                     xl:max-w-[44.1875rem]
                     h-[8.75rem]
                     md:h-[9.5rem]
                     lg:h-[10.5rem]
                     xl:h-[11.4375rem]
                     py-[1rem] md:py-[1.5rem] lg:py-[2rem] xl:py-[2.1875rem]
                     focus-visible:outline-none focus-visible:ring-2
                     focus-visible:ring-[#2DD4BF]
                     focus-visible:ring-offset-2 focus-visible:ring-offset-white
                     transition-all duration-200 hover:shadow-lg"
            >
              <img
                :src="emailIcon"
                alt="Email"
                class="object-contain w-auto
                       se:h-[3.375rem]
                       md:h-[3rem]
                       lg:h-[3.75rem]
                       xl:h-[5.625rem]"
                decoding="async"
              />
              <span
                class="font-[600] text-[#606060] text-center
                       se:text-[1rem] se:leading-[1.25rem]
                       md:text-[1.125rem] md:leading-[1.375rem]
                       lg:text-[1.25rem] lg:leading-[1.5rem]
                       xl:text-[1.375rem] xl:leading-[1.75rem]"
              >
                Email
              </span>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import brand from "@/assets/doubts/EQC-logo-client.png"
import banner from "@/assets/doubts/EQC-doubtbanner.png"
import emailIcon from "@/assets/doubts/EQC-email.png"
</script>