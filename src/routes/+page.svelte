<div class="frontpage">
  <div class="hero-div">
    <div class="content">
      <div class="text">
        <h1 class="title">Sejam bem vindos<br /> ao meu mundo.</h1>
        <p>
          Sou Pedro Daia Cardoso, entusiasta por programação desde os 13 anos de
          idade,<br /> e hoje com 23 anos, sou Engenheiro de Software especialista
          em Web Design.
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
  <div class="about-div">
    <h2>Olá mundo.</h2>
  </div>
</div>

<style>
  .frontpage {
    overflow-y: hidden;
  }
  .hero-div {
    display: flex;
    flex-direction: row;
    width: 100%;
    height: 93vh;
    background-color: #7656db;
    position: relative;
    align-items: center;
  }
  .decorations {
    display: flex;
    flex-direction: row;
    position: absolute;
    width: 100%;
    bottom: 2rem;
    justify-content: space-between;
    margin: 0 auto;
    overflow: hidden;
  }
  .decorations img {
    width: 11rem;
  }
  .content {
    padding: 0rem 10rem 0rem 10rem;
  }
  .text {
    margin-top: -27%;
  }
  .title {
    padding-bottom: 1rem;
  }
  .about-div {
    width: 100%;
    height: 90vh;
    background-color: #480355;
    padding: 0rem 10rem 0rem 10rem;
    display: flex;
    align-items: center;
  }
  h1,
  p {
    color: #1a2900;
  }
  h2 {
    color: #fffdfd;
  }
</style>
