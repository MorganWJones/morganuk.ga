<script lang="ts">
  import "../global.scss"
</script>

<header class="topBar">
  <div class="logo">MORGAN JONES</div>
  <div class="search">
    <input type="text" placeholder="Search" />
  </div>
  <div class="socialIcons">[SOCIAL ICONS]</div>
</header>

<style lang="scss">
  .topBar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 2rem;
    height: 70px;
    background: #121212;
    font-weight: 700;
  }

  .logo, .socialIcons {
    font-size: 19px;
  }

  .search {
    width: 50%;
    max-width: 630px;
  }

  .search input {
    display: inline-block;
    height: 37px;
    font-size: 16px;
    padding: 0 0.75rem;
    border-radius: 10px;
    border: none;
    background-color: rgba(255, 255, 255, 0.10);
    width: 100%;
  }
</style>
