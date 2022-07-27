<script setup>

</script>

<template>
    <div>
        <h1>
            <slot name="header">??header??</slot>
        </h1>
        <main>
            <slot name="content">??content??</slot>
        </main>
    </div>
</template>