<template>
  <section class="ltr py-4 w-full absolute bottom-0 flex justify-around">
    <p class="text-xs text-custom-text-secondary font-thin">
      <a
        href="mailto:shayaulman@gmail.com"
        class="font-thin hover:text-custom-brand transform transition duration-300"
        >Shaya Ulman</a
      >
      &copy; 2020
    </p>
    <a
      href="https://github.com/shayaulman/kosher-code"
      target="_blank"
      class="h-6 w-6"
    >
      <app-icon
        class="fill-current text-custom-text-secondary hover:text-custom-brand transform transition duration-300"
        :icon="'github'"
      />
    </a>
  </section>
</template>

<script>
import AppIcon from "~/components/UI/AppIcon";
export default {
  components: { AppIcon },
};
</script>
