<script lang="ts">
  import Icon from "@iconify/svelte";
</script>

<div class="mx-6 lg:mx-0">
  <h1
    class="mb-2 md:mb-4 text-3xl md:text-4xl font-semibold text-alloyOrange text-center font-merienda"
  >
    Skills
  </h1>
  <div class="w-full border-4 min-h-[22rem] border-blueViolet rounded-2xl">
    <ul
      class="w-full mx-auto my-8 max-w-lg grid grid-cols-3 md:grid-cols-4 gap-2 md:gap-4 px-2 md:px-0"
    >
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="skill-icons:javascript" class="w-10 md:w-14 h-10 md:h-14" />
        <h3 class="text-center">Javascript</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="skill-icons:typescript" class="w-10 md:w-14 h-10 md:h-14" />
        <h3>Typescript</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="logos:php" class="w-10 md:w-14 h-10 md:h-14" />
        <h3>Php</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="logos:nodejs-icon" class="w-10 md:w-14 h-10 md:h-14" />
        <h3 class="text-center">Node.js</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="skill-icons:svelte" class="w-10 md:w-14 h-10 md:h-14" />
        <h3>Svelte</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="devicon:react" class="w-10 md:w-14 h-10 md:h-14" />
        <h3>React</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon
          icon="vscode-icons:file-type-svelte"
          class="w-10 md:w-14 h-10 md:h-14"
        />
        <h3>Sveltekit</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon
          icon="tabler:brand-nextjs"
          class="w-10 md:w-14 h-10 md:h-14"
          style="color: white"
        />
        <h3>Next.js</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon
          icon="skill-icons:tailwindcss-dark"
          class="w-10 md:w-14 h-10 md:h-14"
        />
        <h3>Tailwindcss</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="logos:laravel" class="w-10 md:w-14 h-10 md:h-14" />
        <h3>Laravel</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon
          icon="hugeicons:sql"
          class="w-10 md:w-14 h-10 md:h-14"
          style="color: white"
        />
        <h3>Sql</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon
          icon="skill-icons:supabase-dark"
          class="w-10 md:w-14 h-10 md:h-14"
        />
        <h3>Supabase</h3>
      </li>
    </ul>
  </div>
</div>
