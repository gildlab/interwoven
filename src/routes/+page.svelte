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
        Interwoven Solutions
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
      across the organization and subsidiaries
    </div>
  </div>

</div>
.
<div class="leverage-container">

  <div class="leverage">
    <div class="header-title">
      Leverage value across the portfolio
    </div>
    <div class="paragraph">
      To align technology deployment and implementation to avoid mass fragmentation of approach and solutions and
      leverage value created across the portfolio:
    </div>
    <ul class="points">
      <li>Blockchain network strategy by portfolio company and parent company</li>
      <li>Identify base contracts that cover scope of parent co and subsidiary activity</li>
      <li> Identify range of calculations required to apply business logic to these contracts to make them fit for
        purpose
      </li>
    </ul>

    <div class="paragraph">
      Spin up a customised environment for the customer and subsidiaries to create, share and deploy the onchain
      business logic in a single environment.
    </div>

    <ul class="points">
      <li>Underlying set of core contracts across portfolio</li>
      <li>Deployment environment for contracts and expressions</li>
      <li>Custom wordpacks or expressions to extend business use</li>
      <li>Deployment chains maintaining integrity across chains</li>
      <li>Support for QA of expressions Integration with specific applications</li>
      <li>Decentralized infrastructure and hosting</li>
    </ul>
  </div>
</div>

<div class="footer">
  <img src={images.logo} alt="interwoven-logo" class="logo"/>
  <span class="copyright">Copyright © {new Date().getFullYear()} Interwoven Solutions. All Rights Reserved.</span>
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

    .leverage-container {
        width: 100%;

        background: #B8B8B8;
    }

    .leverage {
        margin: auto;
        width: 66.6%;
        padding: 150px 0;
        display: flex;
        flex-direction: column;
        gap: 40px;
    }

    .header-title {
        color: #000;
        font-family: 'Inter', sans-serif;
        font-size: 40px;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
    }

    .paragraph {
        color: #000;
        font-family: 'Inter', sans-serif;
        font-size: 20px;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
    }

    .points {
        color: #000;
        font-family: 'Inter', sans-serif;
        font-size: 20px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        margin-left: 30px;
    }

    .footer {
        background: #010322;
        padding: 25px 46px;
        width: calc(100% - 92px);
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .footer .logo {
        width: 181px;
        height: auto;
    }

    .copyright {
        color: #979797;
        font-family: 'Inter', sans-serif;
        font-size: 12px;
        font-style: normal;
        font-weight: 700;
        line-height: normal;
    }
</style>