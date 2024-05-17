<script lang="ts">
  import Icon from "@iconify/svelte";
</script>

<div class="box fixed bottom-0 left-1/2 min-h-5">
  <nav class=" px-3 relative z-40">
    <ul class="flex items-center justify-center space-x-4">
      <li
        class="h-12 flex items-center justify-center"
        style=" box-shadow: 0 4px 2px -2px rgba(0, 0, 0, 0.3); "
      >
        <Icon icon="cib:about-me" style="color: white" class="w-10 h-10" />
      </li>
      <li
        class="h-12 flex items-center justify-center"
        style=" box-shadow: 0 4px 2px -2px rgba(0, 0, 0, 0.3); "
      >
        <Icon icon="carbon:skill-level" style="color: white" class="w-10 h-10" />
      </li>
      <li
        class="h-12 flex items-center justify-center"
        style=" box-shadow: 0 4px 2px -2px rgba(0, 0, 0, 0.3); "
      >
        <Icon
          icon="fluent:time-picker-24-filled"
          style="color: white"
          class="w-10 h-10"
        />
      </li>
      <li
        class="h-12 flex items-center justify-center"
        style=" box-shadow: 0 4px 2px -2px rgba(0, 0, 0, 0.3); "
      >
        <Icon
          icon="grommet-icons:projects"
          style="color: white"
          class="w-10 h-10"
        />
      </li>
    </ul>
  </nav>
  <div class="cube-wrap">
    <div class="cube m-auto relative h-6 w-[250px]">
      <div
        class="face front absolute box-border h-full w-full bg-alloyOrange border-2 border-antiflashWhite"
      ></div>
      <div
        class="face top absolute box-border h-full w-full bg-alloyOrange border-2 border-t-0 border-antiflashWhite"
      ></div>
      <div
        class="face back absolute box-border h-full w-full bg-alloyOrange border-2 border-antiflashWhite"
      ></div>
    </div>
  </div>
</div>

<style>
  .box {
    transform: translateX(-50%);
  }

  .cube {
    transform-style: preserve-3d;
    transform: scale3d(1, 1, 1) rotateX(-25deg) rotateY(0deg) rotateZ(0deg)
      translate3d(0px, 0px, 0px) skew(0deg, 0deg);
  }

  .top {
    transform: rotateX(-90deg) translateY(-50%);
    transform-origin: top center;
  }

  .front {
    transform: translateZ(12px);
  }

  .back {
    transform: rotateY(180deg) translateZ(12px);
  }

  .cube-wrap {
    perspective: 2000px;
    perspective-origin: 50% 50%;
  }
</style>
