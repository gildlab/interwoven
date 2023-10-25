<script>
    import "../app.css";
    import {images} from '../images/images.js'
</script>

<div class="header">
  <img src={images.hero} alt="interwoven" class="hero"/>

  <div class="info">
    <img src={images.logo} alt="interwoven-logo" class="logo"/>
    <div class="about">
      <span>
        Interwoven solutions
      </span>
      is a technology company specializing in ledger, blockchain and distributed supply chain solutions
    </div>
  </div>
</div>
<div>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</div>


<style>


    .header {
        position: relative;
    }

    .hero {
        width: 100%;
    }

    .info {
        position: absolute;
        top: 218px;
        left: 137px;
        z-index: 1;
        width: calc(100% - 137px);
    }

    .about span {
        color: #EBEBEB;
        font-family: 'Inter', sans-serif;
        font-size: 25px;
        font-style: normal;
        font-weight: 700;
        line-height: 30px; /* 120% */
    }

    .about {
        width: 416px;
        color: #EBEBEB;
        font-family: 'Inter', sans-serif;
        font-size: 25px;
        font-style: normal;
        font-weight: 400;
        line-height: 30px;
        position: absolute;
        right: 217px;
    }

    .logo {
        width: 38%;
        height: auto;

    }
</style>