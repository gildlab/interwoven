<script>
    import "../app.css";
    import {images} from '../images/images.js'
</script>

<div class="header">
  <img src={images.hero} alt="interwoven" class="hero" loading="lazy"/>

  <div class="info">
    <img src={images.logo} alt="interwoven-logo" class="logo" loading="lazy"/>
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
      chain finance and trade finance solutions.
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