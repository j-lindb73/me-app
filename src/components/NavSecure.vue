<template>
    <div class="w3-content" id="nav">
    <router-link to="/register">Registrera användare</router-link> |
    <router-link to="/login">Logga in</router-link> |
    <router-link to="/reports/week/new">Skapa rapport</router-link> |
    </div>
</template>

<script>

// import Auth from '@/components/Auth'

export default {
    name: 'NavSecure',

}
</script>