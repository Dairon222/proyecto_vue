<template>
    <div class="sidebar">
        <h2>Barra lateral</h2>
        <ul>
            <li>
                <RouterLink to="/Contador">Contador</RouterLink>
            </li>
            <li>
                <RouterLink to="/ListaDeTareas">Lista De Tareas</RouterLink>
            </li>
        </ul>
    </div>
</template>

<script setup></script>

<style>
.sidebar {
    width: 200px;
    background-color: antiquewhite;
    padding: 20px;
}
</style>