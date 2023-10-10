<div class="hero-div">
  <div class="content">
    <div class="text">
      <h1 class="title">Sejam bem vindos ao meu mundo.</h1>
      <p>
        Sou Pedro Daia Cardoso, entusiasta por programação desde os 13 anos, e
        hoje com 23 anos, sou engenheiro de software especialista em Web Design.
      </p>
    </div>
  </div>
  <div class="decorations">
    <img src="/athos.png" alt="Athos Bulcão" />
    <img src="/athos.png" alt="Athos Bulcão" />
    <img src="/athos.png" alt="Athos Bulcão" />
    <img src="/athos.png" alt="Athos Bulcão" />
    <img src="/athos.png" alt="Athos Bulcão" />
    <img src="/athos.png" alt="Athos Bulcão" />
  </div>
</div>
<div class="about-div" />

<style>
  .hero-div {
    display: flex;
    flex-direction: row;
    width: 100%;
    height: 90vh;
    background-color: #7656db;
    position: relative;
    align-items: center;
  }
  .decorations {
    display: flex;
    flex-direction: row;
    position: absolute;
    width: 100%;
    bottom: 1rem;
    justify-content: space-between;
    padding: 0 10rem 0 10rem;
    margin: 0 auto;
    overflow: hidden;
  }
  .decorations img {
    width: 10rem;
  }
  .content {
    padding: 0rem 10rem 0rem 10rem;
  }
  .text {
    width: 70vw;
    max-width: 1300px;
    margin-top: -10%;
  }
  .title {
    padding-bottom: 1rem;
  }
  .about-div {
    width: 100%;
    height: 90vh;
    background-color: black;
    padding: 0rem 10rem 0rem 10rem;
  }
  h1,
  p {
    color: #1a2900;
  }
  h2 {
    color: #fffdfd;
  }
</style>
