<template>
    <div>
        <h1>{{ message }}</h1>
        <p>
            This is a fresh component.
        </p>
    </div>
</template>

<script>
export default {
    name: 'FreshComponent',
    data() {
        return {
            message: 'Hello from FreshComponent'
        }
    }
}
</script>