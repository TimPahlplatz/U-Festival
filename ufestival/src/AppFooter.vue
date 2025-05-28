<template>
  <!-- HOME SVG -->
  <svg
    xmlns="http://www.w3.org/2000/svg"
    height="200px"
    viewBox="0 -960 960 960"
    width="200px"
    fill="#000000"
    class="footer-svg"
    onclick="window.location.href = '/'"
  >
    <path
      d="M240-200h120v-240h240v240h120v-360L480-740 240-560v360Zm-80 80v-480l320-240 320 240v480H520v-240h-80v240H160Zm320-350Z"
    />
  </svg>
  <!-- INFO SVG -->
  <svg
    xmlns="http://www.w3.org/2000/svg"
    height="200px"
    viewBox="0 -960 960 960"
    width="200px"
    fill="#000000"
    class="footer-svg"
    onclick="window.location.href = '/info'"
  >
    <path
      d="M440-280h80v-240h-80v240Zm40-320q17 0 28.5-11.5T520-640q0-17-11.5-28.5T480-680q-17 0-28.5 11.5T440-640q0 17 11.5 28.5T480-600Zm0 520q-83 0-156-31.5T197-197q-54-54-85.5-127T80-480q0-83 31.5-156T197-763q54-54 127-85.5T480-880q83 0 156 31.5T763-763q54 54 85.5 127T880-480q0 83-31.5 156T763-197q-54 54-127 85.5T480-80Zm0-80q134 0 227-93t93-227q0-134-93-227t-227-93q-134 0-227 93t-93 227q0 134 93 227t227 93Zm0-320Z"
    />
  </svg>
  <!-- MUSIC SVG -->
  <svg
    xmlns="http://www.w3.org/2000/svg"
    height="200px"
    viewBox="0 -960 960 960"
    width="200px"
    fill="#000000"
  >
    <path
      d="M400-120q-66 0-113-47t-47-113q0-66 47-113t113-47q23 0 42.5 5.5T480-418v-422h240v160H560v400q0 66-47 113t-113 47Z"
    />
  </svg>
  <!-- LOCATION SVG -->
  <svg
    xmlns="http://www.w3.org/2000/svg"
    height="200px"
    viewBox="0 -960 960 960"
    width="200px"
    fill="#000000"
  >
    <path
      d="M480-301q99-80 149.5-154T680-594q0-90-56-148t-144-58q-88 0-144 58t-56 148q0 65 50.5 139T480-301Zm0 101Q339-304 269.5-402T200-594q0-125 78-205.5T480-880q124 0 202 80.5T760-594q0 94-69.5 192T480-200Zm0-320q33 0 56.5-23.5T560-600q0-33-23.5-56.5T480-680q-33 0-56.5 23.5T400-600q0 33 23.5 56.5T480-520ZM200-80v-80h560v80H200Zm280-520Z"
    />
  </svg>
</template>

<script>
export default {
  name: "AppFooter",
};
</script>
