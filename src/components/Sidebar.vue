<template>
  <aside class="fixed top-0 left-0 h-screen w-64 bg-gray-900 text-white flex flex-col items-center py-6 shadow-lg z-50">
    <div class="mb-8">
      <img src="./assets/logo.svg" alt="Logo Funeraria" class="w-24 h-24 object-contain" />
    </div>
    <nav class="w-full">
      <ul class="flex flex-col gap-2 px-6">
        <li>
          <a
            href="#departamentos"
            class="block py-3 px-4 rounded-lg text-lg hover:bg-gray-700 hover:text-white transition-colors"
          >
            Departamentos
          </a>
        </li>
        <li>
          <a
            href="#servicios"
            class="block py-3 px-4 rounded-lg text-lg hover:bg-gray-700 hover:text-white transition-colors"
          >
            Servicios
          </a>
        </li>
        <li>
          <a
            href="#login"
            class="block py-3 px-4 rounded-lg text-lg hover:bg-gray-700 hover:text-white transition-colors"
          >
            Login
          </a>
        </li>
      </ul>
    </nav>
  </aside>
</template>

<script setup>
// No hay lógica necesaria por ahora
</script>

<style scoped>
/* Tailwind cubre todo, no se requieren estilos adicionales */
</style>
