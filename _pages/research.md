---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.research-layout {
  display: grid !important;
  grid-template-columns: minmax(260px, 0.9fr) minmax(520px, 1.6fr) !important;
  gap: 2rem !important;
  margin-top: 2rem !important;
  align-items: start !important;
}

.research-tabs {
  display: grid !important;
  grid-template-columns: 1fr !important;
  gap: 1rem !important;
}

.research-radio {
  display: none !important;
}

.research-tab {
  border: 1px solid #e5e5e5 !important;
  border-radius: 18px !important;
  background: #fff !important;
  box-shadow: 0 4px 14px rgba(0,0,0,0.05) !important;
  padding: 1rem !important;
  text-align: center !important;
  cursor: pointer !important;
  transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease !important;
}

.research-tab:hover {
  transform: translateY(-2px) !important;
  box-shadow: 0 6px 18px rgba(0,0,0,0.08) !important;
}

.research-tab h2 {
  font-size: 1.05rem !important;
  line-height: 1.15 !important;
  margin: 0 0 0.6rem 0 !important;
  text-align: center !important;
}

.research-tab img {
  width: 145px !important;
  height: 145px !important;
  border-radius: 50% !important;
  object-fit: cover !important;
  display: block !important;
  margin: 0 auto !important;
}

.research-panel {
  border: 1px solid #e5e5e5 !important;
  border-radius: 18px !important;
  background: #fff !important;
  box-shadow: 0 4px 14px rgba(0,0,0,0.06) !important;
  padding: 2rem 2.4rem !important;
  min-height: 720px !important;
}

.research-content {
  display: none !important;
}

.research-content h2 {
  font-size: 1.65rem !important;
  line-height: 1.15 !important;
  margin: 0 0 1rem 0 !important;
  text-align: center !important;
}

.research-content img {
  width: 260px !important;
  height: 260px !important;
  border-radius: 50% !important;
  object-fit: cover !important;
  display: block !important;
  margin: 0 auto 1.5rem auto !important;
}

.research-content p {
  font-size: 0.98rem !important;
  line-height: 1.6 !important;
  margin-bottom: 1rem !important;
  text-align: left !important;
}

#research-transgen:checked ~ .research-layout .tab-transgen,
#research-epigenetics:checked ~ .research-layout .tab-epigenetics,
#research-chemical:checked ~ .research-layout .tab-chemical,
#research-popgen:checked ~ .research-layout .tab-popgen {
  border-color: #bfbfbf !important;
  box-shadow: 0 6px 18px rgba(0,0,0,0.10) !important;
  transform: translateY(-2px) !important;
}

#research-transgen:checked ~ .research-layout .content-transgen,
#research-epigenetics:checked ~ .research-layout .content-epigenetics,
#research-chemical:checked ~ .research-layout .content-chemical,
#research-popgen:checked ~ .research-layout .content-popgen {
  display: block !important;
}

@media (max-width: 1000px) {
  .research-layout {
    grid-template-columns: 1fr !important;
  }

  .research-tabs {
    grid-template-columns: repeat(2, 1fr) !important;
  }

  .research-panel {
    min-height: auto !important;
  }
}

@media (max-width: 700px) {
  .research-tabs {
    grid-template-columns: 1fr !important;
  }

  .research-tab img {
    width: 130px !important;
    height: 130px !important;
  }

  .research-content img {
    width: 220px !important;
    height: 220px !important;
  }
}
</style>

My research explores how organisms respond to environmental variation across generations, with emphasis on plasticity, epigenetic mechanisms, chemical ecology, and population genetics.

<input class="research-radio" type="radio" name="research-topic" id="research-transgen" checked>
<input class="research-radio" type="radio" name="research-topic" id="research-epigenetics">
<input class="research-radio" type="radio" name="research-topic" id="research-chemical">
<input class="research-radio" type="radio" name="research-topic" id="research-popgen">

<div class="research-layout">

  <div class="research-tabs">

    <label for="research-transgen" class="research-tab tab-transgen">
      <h2>Transgenerational Plasticity</h2>
      <img src="/assets/images/transgenerational-plasticity.jpg" alt="Transgenerational plasticity">
    </label>

    <label for="research-epigenetics" class="research-tab tab-epigenetics">
      <h2>Epigenetics</h2>
      <img src="/assets/images/epigenetics.jpg" alt="Epigenetics">
    </label>

    <label for="research-chemical" class="research-tab tab-chemical">
      <h2>Chemical Ecology</h2>
      <img src="/assets/images/chemical-ecology.jpg" alt="Chemical ecology">
    </label>

    <label for="research-popgen" class="research-tab tab-popgen">
      <h2>Population Genetics</h2>
      <img src="/assets/images/population-genetics.jpg" alt="Population genetics">
    </label>

  </div>

  <div class="research-panel">

    <div class="research-content content-transgen">
      <h2>Transgenerational Plasticity</h2>
      <img src="/assets/images/transgenerational-plasticity.jpg" alt="Transgenerational plasticity">

      <p>
        To adapt to changing environments, organisms must cope with stress not only within their own lifetime, but also across generations. The conditions experienced by parents or ancestors may influence how descendants grow, survive, and respond to similar stress later in life, even in the absence of genetic change. This controversial process is known as transgenerational plasticity.
      </p>

      <p>
        Transgenerational plasticity may be especially important in clonal organisms, where adaptation through genetic recombination is limited. Yet we still know little about whether transgenerational plasticity can help descendants when stress returns, how long these effects last, and whether some lineages are more likely than others to show these responses.
      </p>

      <p>
        I study these questions by following single descendant lines across multiple generations. First, I expose individuals to stress for five generations. This pre-treatment phase allows stress-related changes to arise. Then, I grow the next five generations without stress to erase all directly induced changes. Finally, I expose the eleventh generation to either control conditions or recurrent stress for three to five generations. This final treatment phase shows whether ancestral stress changes offspring fitness and phenotype. Ancestral stress may have no detectable effects. It may lead to the transgenerational retention of stress-related traits across generations, or it may transgenerationally prime descendants, making them better or worse prepared for recurrent stress.
      </p>

      <p>
        This experimental design has shown that transgenerational plasticity is relevant for clonal organisms. It can modify fitness, such as reproduction rates, morphology, and organismal physiology, likely through inherited non-genetic marks.
      </p>
    </div>

    <div class="research-content content-epigenetics">
      <h2>Epigenetics</h2>
      <img src="/assets/images/epigenetics.jpg" alt="Epigenetics">
      <p>Text coming soon.</p>
    </div>

    <div class="research-content content-chemical">
      <h2>Chemical Ecology</h2>
      <img src="/assets/images/chemical-ecology.jpg" alt="Chemical ecology">
      <p>Text coming soon.</p>
    </div>

    <div class="research-content content-popgen">
      <h2>Population Genetics</h2>
      <img src="/assets/images/population-genetics.jpg" alt="Population genetics">
      <p>Text coming soon.</p>
    </div>

  </div>

</div>
