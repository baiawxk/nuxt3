<template>
  <div>
    <Suspense>
      <NuxtChild />
      <template #fallback>
        <div op50 italic>
          <span animate-pulse>Loading...</span>
        </div>
      </template>
    </Suspense>
    <Footer />
  </div>
</template>
