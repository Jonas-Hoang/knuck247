<template>
  <div>
    <div class="p-10 page bg-white overflow-hidden">
      <section class="homepage-section h-[200px] d-xl-flex position-relative bg-red-300 home-section homepage-hero-section">
      
      </section>
      <div class="synchronized-scroll horizontal">
        <i class="navigation-links align-items-center justify-content-between py-0-5 py-sm-1 px-0-625 px-sm-1-25 px-xl-2 py-xl-1 disabled d-none d-xl-flex">
          <NuxtLink to="/">Home </NuxtLink>
        </i>
        <i class="navigation-links align-items-center justify-content-between py-0-5 py-sm-1 px-0-625 px-sm-1-25 px-xl-2 py-xl-1 disabled d-none d-xl-flex">
          <NuxtLink to="/working">Working page</NuxtLink>
        </i>
      </div>
    </div>
    <slot />
  </div>

</template>

