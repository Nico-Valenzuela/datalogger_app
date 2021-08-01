<template>
  <footer class="footer">
    <div class="container-fluid">
      <ul class="nav">
        <li class="nav-item">
          <a
            href="https://dataloggerservices.online"
            target="_blank"
            rel="noopener"
            class="nav-link"
          >
            Proyecto Final 2021
          </a>
        </li>
        <li class="nav-item">
          <a
            href="https://dataloggerservices.online"
            target="_blank"
            rel="noopener"
            class="nav-link"
          >
          </a>
        </li>
        <li class="nav-item">
          <a
            href="https://dataloggerservices.online"
            target="_blank"
            rel="noopener"
            class="nav-link"
          >
          </a>
        </li>
      </ul>
      <div class="copyright">
        &copy; {{ year }}, made with <i class="tim-icons icon-heart-2"></i> by

        <a
          href="https://dataloggerservices.online"
          target="_blank"
          rel="noopener"
          >Cippitelli - Martino - Valenzuela</a
        >
        for everyone present.
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style></style>
