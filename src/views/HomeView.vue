<template>
    <div class="flex flex-col gap-5 justify-center items-center h-screen bg-base-200">
  <main>
    <div class="flex flex-col gap-10 justify-center items-center w-1/3">
      <h1 class="text-5xl font-bold">Google</h1>
      <label class="input focus:outline-0 w-full w-full rounded-full flex items-center gap-2">
        <font-awesome-icon :icon="['fas', 'magnifying-glass']" />
        <input
          type="text"
          placeholder="Pesquise ou digite uma url"
          class="grow"
        />
        <font-awesome-icon :icon="['fas', 'camera']" />
        <font-awesome-icon :icon="['fas', 'microphone']" />
      </label>
      <div class="grid grid-cols-4 justify-items-center gap-4 w-full">

        <div class="avatar placeholder flex flex-col items-center gap-4">

          <div class="bg-neutral text-neutral-content rounded-full w-min p-3">
            <font-awesome-icon :icon="['fas', 'earth-oceania']" size="2xl" />
          </div>
          <span>Facebook</span>
        </div>

        <div class="avatar placeholder flex flex-col items-center gap-4">

          <div class="bg-neutral text-neutral-content rounded-full w-min p-3">
            <font-awesome-icon :icon="['fas', 'earth-oceania']" size="2xl" />
          </div>
          <span>Facebook</span>
        </div>

        <div class="avatar placeholder flex flex-col items-center gap-4">

          <div class="bg-neutral text-neutral-content rounded-full w-min p-3">
            <font-awesome-icon :icon="['fas', 'earth-oceania']" size="2xl" />
          </div>
          <span>Facebook</span>
        </div>

        <div class="avatar placeholder flex flex-col items-center gap-4">

          <div class="bg-neutral text-neutral-content rounded-full w-min p-3">
            <font-awesome-icon :icon="['fas', 'earth-oceania']" size="2xl" />
          </div>
          <span>Facebook</span>
        </div>

        <div class="avatar placeholder flex flex-col items-center gap-4">

          <div class="bg-neutral text-neutral-content rounded-full w-min p-3">
            <font-awesome-icon :icon="['fas', 'earth-oceania']" size="2xl" />
          </div>
          <span>Facebook</span>
        </div>

        <div class="avatar placeholder flex flex-col items-center gap-4">

          <div class="bg-neutral text-neutral-content rounded-full w-min p-3">
            <font-awesome-icon :icon="['fas', 'earth-oceania']" size="2xl" />
          </div>
          <span>Facebook</span>
        </div>

        <div class="avatar placeholder flex flex-col items-center gap-4">

          <div class="bg-neutral text-neutral-content rounded-full w-min p-3">
            <font-awesome-icon :icon="['fas', 'earth-oceania']" size="2xl" />
          </div>
          <span>Facebook</span>
        </div>

        <div class="avatar placeholder flex flex-col items-center gap-4">

          <div class="bg-neutral text-neutral-content rounded-full w-min p-3">
            <font-awesome-icon :icon="['fas', 'earth-oceania']" size="2xl" />
          </div>
          <span>Facebook</span>
        </div>


      </div>
    </div>
  </main>
    </div>
</template>
<script setup lang="ts">
</script>
