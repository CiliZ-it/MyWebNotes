<template v-slot:list>
    notes list
    <div v-for="item in 5" :key="item">
        <ContainerNotesListItem/>
    </div>
</template>