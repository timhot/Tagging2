<template>
    <div id="app">
        <navbar-component></navbar-component>
        <section class="container">
            <page-heading-component></page-heading-component>
            <staff-list-component></staff-list-component>
        </section>
    </div>
</template>

<script>
    import PageHeadingComponent from './components/PageHeadingComponent.vue'
    import StaffListComponent from './components/StaffListComponent.vue'
    import NavbarComponent from './components/NavbarComponent.vue'
    export default {
        name: 'app',
        components: {NavbarComponent, PageHeadingComponent, StaffListComponent}
    }
</script>

<style>
</style>
