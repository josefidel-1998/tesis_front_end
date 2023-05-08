<template>
  <section class="w-100">
    <Modal />
    <article class="fondoAzul rounded p-3">
      <div class="float-end mb-4">
        <i class="bi bi-x-circle naranja"></i>
      </div>
      <div class="mt-4">
        <h2 class="text-white h6">Jonh Mircha</h2>
      </div>
    </article>
    <article>
      <nav>
        <ul class="list-group">
          <li class="list-group-item p-3">
            <a class="nav-link bold fw-bold" href="#">Notificaciones</a>
          </li>
          <li class="list-group-item p-3">
            <a class="nav-link bold fw-bold" href="#">Privacidad y seguridad</a>
          </li>
          <li class="list-group-item p-3">
            <a class="nav-link bold fw-bold" href="#">Cerrar Sesión</a>
          </li>
        </ul>
      </nav>
    </article>
  </section>
  <Footer />
</template>

<script setup>
import Modal from "../components/Modal.vue";
import Header from "../layout/Header.vue";
import Footer from "../layout/Footer.vue";
</script>

<style scope></style>
