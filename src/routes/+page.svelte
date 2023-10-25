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
<div class="solutions">
  <div class="section">
    <div class="title">Blockchain solutions</div>
    <div class="text">Build scalable ledger based solutions that intersect supply chain and finance including supply
      chain finance and trade finance solutions
    </div>
  </div>
  <div class="section">
    <div class="title">p2p networking & edge computing</div>
    <div class="text">Build networking technology into supply chain scanner, IOT and other hardware devices to creating
      distributed hardware networks.
    </div>
  </div>
  <div class="section">
    <div class="title">Decentralized technology strategies</div>
    <div class="text">Build a group wide blockchain technology strategy.
    </div>
  </div>
  <div class="section">
    <div class="title">Advisory and Blockchain containerisation for group</div>
    <div class="text">Build an overarching blockchain capability within the parent company to coordinate and add value
      across the organization and subsidiaries. 
    </div>
  </div>

</div>


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

    .solutions {
        width: 66.6%;
        display: flex;
        flex-direction: column;
        gap: 100px;
        margin: 150px auto;
    }

    .section {
        display: flex;
        flex-direction: column;
        gap: 15px;
    }

    .title {
        color: #FFF;
        font-family: 'Inter', sans-serif;
        font-size: 40px;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
    }

    .text {
        color: #FFF;
        font-family: 'Inter', sans-serif;
        font-size: 20px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
    }

</style>