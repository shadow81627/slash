<template>
  <div class="flex items-center justify-center py-8 lg:py-16">
    <UCard class="w-full max-w-sm">
      <template #header>
        <h1 class="text-2xl font-bold text-center">
          Request an Invite
        </h1>
      </template>

      <UForm
        :state="state"
        :schema="schema"
        class="flex flex-col gap-5"
        disabled
        @submit="submit"
      >
        <UFormField
          label="Email"
          name="email"
          class=""
        >
          <UInput
            v-model="state.email"
            placeholder="you@example.com"
            icon="i-lucide-mail"
            class="w-full"
          />
        </UFormField>

        <UButton
          type="submit"
          block
        >
          Request Invite
        </UButton>
      </UForm>

      <template #footer>
        <p class="text-sm text-center text-muted">
          Already have an invite? <NuxtLink
            to="/login"
            class="text-primary"
          >Log in</NuxtLink>.
        </p>
      </template>
    </UCard>
  </div>
</template>

<script setup>
import { z } from 'zod'

const state = reactive({ email: '' })

const schema = z.object({
  email: z.string().email('Invalid email')
})

async function submit(event) { console.log(event.data) }
</script>
