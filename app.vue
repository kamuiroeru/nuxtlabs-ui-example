<template>
  <UContainer class="mt-4">
    <UCard>
      <template #header>
        <div class="m-0 p-0 flex items-center gap-2">
          This is the header with a
          <UButton icon="i-ic-baseline-alternate-email" variant="outline"
            >button</UButton
          >
        </div>
      </template>

      <p>This is the body with a <UBadge>Badge</UBadge></p>
      <p class="text-teal-500">
        Hogefuga
        <UButton
          :ui="{ rounded: 'rounded-full', size: 'xl' }"
          icon="i-heroicons-pencil-square"
        />
      </p>
    </UCard>
  </UContainer>
</template>
