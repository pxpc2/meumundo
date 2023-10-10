<script>
  import '$lib/styles/global.css';
</script>

<div class="header">
  <div class="header-content">
    <div class="avatar">
      <img src="https://github.com/pxpc2.png" alt="pedro daia" />
      <a href="/">pedrodaia.me</a>
    </div>
    <a href="/">sobre mim</a>
    <a href="/">portfolio</a>
    <a href="/">contrate meus serviços</a>
  </div>
</div>
<slot />

<style>
  .avatar {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 1rem;
  }
  .avatar img {
    border-radius: 20rem;
    width: 50%;
    height: 50%;
  }
  .header {
    padding: 1rem 10rem 0 10rem;
    background-color: #7656db;
    gap: 3rem;
  }
  .header-content {
    padding: 0 10rem 0 10rem;
    background-color: rgb(122, 90, 228);
    height: 7vh;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    border: 1px solid #1a2900;
    border-radius: 20rem;
  }
  a {
    color: #1a2900;
    text-decoration: none;
    font-size: 1.5rem;
    align-self: center;
  }
  a:hover {
    text-decoration: underline;
    text-decoration-color: #fffdfd;
    text-underline-offset: 0.7rem;
  }
</style>
