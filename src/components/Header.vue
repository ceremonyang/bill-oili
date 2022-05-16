<template>
  <nav h-20 flex justify-between>
    <div text-7 mya>Title</div>
    <div mya>
      <RouterLink class="icon-btn mx-2" to="/">
        <div i-carbon-campsite />
      </RouterLink>
    <button class="icon-btn mx-2 !outline-none">
      <div i="carbon-sun dark:carbon-moon" />
    </button>

    <a class="icon-btn mx-2">
      <div i-carbon-language />
    </a>

    <RouterLink class="icon-btn mx-2" to="/about">
      <div i-carbon-dicom-overlay />
    </RouterLink>

    <a class="icon-btn mx-2" rel="noreferrer" href="https://github.com/antfu/vitesse" target="_blank" title="GitHub">
      <div i-carbon-logo-github />
    </a>
    </div>
  </nav>
</template>