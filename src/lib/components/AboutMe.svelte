<script lang="ts">
  import Icon from "@iconify/svelte";
</script>

<div class="relative border-4 border-blueViolet rounded-2xl">
  <div class="p-6 px-8">
    <h1 class="text-3xl text-amaranthPurple leading-10 font-bold">
      <span class="text-alloyOrange font-semibold flex items-center space-x-4"
        >Welcome to this corner made with <Icon
          icon="noto:heart-on-fire"
          class="w-10 h-10 ml-4"
        /></span
      >
      I'm Yeraldi Mujica
    </h1>
    <div class="mt-2 text-lg pr-28">
      <p>
        I'm a fullstack web developer and I always love facing new challenges
        that benefit me from knowledge and experience.
      </p>
    </div>

    <div class="mt-2 flex items-center justify-start space-x-5">
      <Icon
        icon="hugeicons:linkedin-01"
        class="w-10 h-10"
        style="color: white"
      />
      <Icon icon="line-md:github-loop" class="w-10 h-10" style="color: white" />
      <Icon icon="skill-icons:gmail-light" class="w-10 h-10" />
    </div>
  </div>
  <div
    class="absolute w-52 h-52 bg-white rounded-full -right-24 -top-12 border-4 border-blueViolet"
  ></div>
</div>
