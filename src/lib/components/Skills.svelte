<script lang="ts">
  import Icon from "@iconify/svelte";
</script>

<div>
  <h1
    class="mb-4 text-4xl font-semibold text-alloyOrange text-center font-merienda"
  >
    Skills
  </h1>
  <div class="w-full border-4 border-blueViolet rounded-2xl">
    <ul
      class="w-full mx-auto py-10 max-w-sm grid grid-rows-3 grid-flow-col gap-4"
    >
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="skill-icons:javascript" class="w-14 h-14" />
        <h3 class="text-center">Javascript</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="skill-icons:svelte" class="w-14 h-14" />
        <h3>Svelte</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon
          icon="tabler:brand-nextjs"
          class="w-14 h-14"
          style="color: white"
        />
        <h3>Next.js</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="skill-icons:typescript" class="w-14 h-14" />
        <h3>Typescript</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="devicon:react" class="w-14 h-14" />
        <h3>React</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="logos:laravel" class="w-14 h-14" />
        <h3>Laravel</h3>
      </li>

      <li class="flex flex-col items-center space-y-2">
        <Icon icon="logos:php" class="w-14 h-14" />
        <h3>Php</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="skill-icons:tailwindcss-dark" class="w-14 h-14" />
        <h3>Tailwindcss</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="skill-icons:supabase-dark" class="w-14 h-14" />
        <h3>Supabase</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="logos:nodejs-icon" class="w-14 h-14" />
        <h3 class="text-center">Node.js</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="vscode-icons:file-type-svelte" class="w-14 h-14" />
        <h3>Sveltekit</h3>
      </li>
      <li class="flex flex-col items-center space-y-2">
        <Icon icon="hugeicons:sql" class="w-14 h-14" style="color: white" />
        <h3>Sql</h3>
      </li>
    </ul>
  </div>
</div>
