<template>
  <footer class="footer">
    <div class="icons">
      <a :href="blogUrl" target="_blank" rel="noopener noreferrer" class="icon-link" title="Blog">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path d="M192 32c0 17.7 14.3 32 32 32c123.7 0 224 100.3 224 224c0 17.7 14.3 32 32 32s32-14.3 32-32C512 128.9 383.1 0 224 0c-17.7 0-32 14.3-32 32zm0 96c0 17.7 14.3 32 32 32c70.7 0 128 57.3 128 128c0 17.7 14.3 32 32 32s32-14.3 32-32c0-106-86-192-192-192c-17.7 0-32 14.3-32 32zM96 144c0-26.5-21.5-48-48-48S0 117.5 0 144L0 368c0 79.5 64.5 144 144 144s144-64.5 144-144s-64.5-144-144-144l-16 0 0 96 16 0c26.5 0 48 21.5 48 48s-21.5 48-48 48s-48-21.5-48-48l0-224z"/></svg>
      </a>
      <a :href="githubUrl" target="_blank" rel="noopener noreferrer" class="icon-link" title="GitHub">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 480 512"><path d="M186.1 328.7c0 20.9-10.9 55.1-36.7 55.1s-36.7-34.2-36.7-55.1 10.9-55.1 36.7-55.1 36.7 34.2 36.7 55.1zM480 278.2c0 31.9-3.2 65.7-17.5 95-37.9 76.6-142.1 74.8-216.7 74.8-75.8 0-186.2 2.7-225.6-74.8-14.6-29-20.2-63.1-20.2-95 0-41.9 13.9-81.5 41.5-113.6-5.2-15.8-7.7-32.4-7.7-48.8 0-21.5 4.9-32.3 14.6-51.8 45.3 0 74.3 9 108.8 36 29-6.9 58.8-10 88.7-10 27 0 54.2 2.9 80.4 9.2 34-26.7 63-35.2 107.8-35.2 9.8 19.5 14.6 30.3 14.6 51.8 0 16.4-2.6 32.7-7.7 48.2 27.5 32.4 39 72.3 39 114.2zm-64.3 50.5c0-43.9-26.7-82.6-73.5-82.6-18.9 0-37 3.4-56 6-14.9 2.3-29.8 3.2-45.1 3.2-15.2 0-30.1-.9-45.1-3.2-18.7-2.6-37-6-56-6-46.8 0-73.5 38.7-73.5 82.6 0 87.8 80.4 101.3 150.4 101.3h48.2c70.3 0 150.6-13.4 150.6-101.3zm-82.6-55.1c-25.8 0-36.7 34.2-36.7 55.1s10.9 55.1 36.7 55.1 36.7-34.2 36.7-55.1-10.9-55.1-36.7-55.1z"></path></svg>
      </a>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  data() {
    return {
      blogUrl: "https://snell.us.kg",
      githubUrl: "https://github.com/emokui",
    };
  }
};
</script>


<style scoped>
.footer {
  margin-top: 30px;
  text-align: center;
  padding: 20px;
  background-color: #ffffff77;
  font-size: 16px;
  border-radius: 50% 50% 0 0;

}

.icons {
  display: flex;
  justify-content: center;
  gap: 16px;
  margin-bottom: 25px;
}

.icon-link {
  width: 28px;
  height: 28px;
  display: inline-block;
  fill: #2c2c2c;
  transition: fill 0.3s;
}

.icon-link:hover {
  fill: #444;
}

</style>
