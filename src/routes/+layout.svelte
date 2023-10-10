<div class="header">
  <a href="/">pedrodaia.me</a>
  <a href="/">sobre mim</a>
  <a href="/">projetos</a>
  <a href="/">contato</a>
</div>
<slot />

<style>
  .header {
    background-color: #c0c9ef;
    height: 10vh;
    margin-bottom: 10vh;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    gap: 3rem;
    border: 1px solid #423913;
  }
  a {
    color: #423913;
    text-decoration: none;
    font-size: 1.5rem;
    align-self: center;
  }
</style>
