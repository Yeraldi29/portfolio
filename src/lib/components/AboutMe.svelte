<script lang="ts">
  import Icon from "@iconify/svelte";
  import profileImage from "$lib/assets/profile_photo.jpg";
</script>

<div class="relative border-4 border-blueViolet rounded-2xl mx-6 lg:mx-auto">
  <div class="mt-20 md:mt-0 p-6 px-4 text-center md:text-left md:px-6">
    <div
      class=" md:hidden absolute w-40 h-40 bg-white rounded-full left-1/2 -top-16 border-4 border-blueViolet"
      style="transform: translateX(-50%);"
    >
      <img
        class="w-full h-full rounded-full"
        src={profileImage}
        alt="profile"
      />
    </div>
    <h1
      class="text-2xl md:text-3xl text-amaranthPurple leading-10 font-bold font-merienda"
    >
      <span
        class="text-alloyOrange font-semibold md:flex md:items-center md:space-x-2"
      >
        <span> Welcome to this corner, </span>
        <span
          class=" flex justify-center items-center md:justify-start space-x-3"
        >
          <span> made with </span>
          <Icon
            icon="noto:heart-on-fire"
            class=" w-8 h-8 md:w-10 md:h-10 ml-4"
          />
        </span>
      </span>
      I'm Yeraldi Mujica
    </h1>
    <div
      class="mt-2 max-w-sm mx-auto md:mx-0 md:max-w-none md:text-lg md:pr-28"
    >
      <p>
        I'm a fullstack web developer and I always love facing new challenges
        that benefit me from knowledge and experience.
      </p>
    </div>

    <div
      class="mt-2 flex items-center justify-center md:justify-start space-x-5"
    >
      <Icon
        icon="hugeicons:linkedin-01"
        class="w-8 md:w-10 h-8 md:h-10"
        style="color: white"
      />
      <Icon
        icon="line-md:github-loop"
        class="w-8 md:w-10 h-8 md:h-10"
        style="color: white"
      />
      <Icon icon="skill-icons:gmail-light" class="w-8 md:w-10 h-8 md:h-10" />
    </div>
  </div>
  <div
    class="hidden md:block absolute w-40 h-40 lg:w-52 lg:h-52 bg-white rounded-full -right-12 -top-10 lg:-right-24 lg:-top-12 border-4 border-blueViolet"
  >
    <img class="w-full h-full rounded-full" src={profileImage} alt="profile" />
  </div>
</div>
