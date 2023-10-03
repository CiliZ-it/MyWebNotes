<template>
  <div>
    <NuxtLayout>
      <template v-slot:list>
        <ContainerNotesList />
      </template>

      <template v-slot:resizer>
        <ControlsVerticalResizer />
      </template>
      
      <template v-slot:content>
        <ContainerNotePreview />
      </template>
    </NuxtLayout>
  </div>
</template>
