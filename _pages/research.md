---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.research-grid {
  display: grid !important;
  grid-template-columns: repeat(2, minmax(420px, 1fr)) !important;
  gap: 2.5rem !important;
  margin-top: 2rem !important;
}

.research-flip-card {
  background: transparent !important;
  width: 100% !important;
  min-height: 560px !important;
  perspective: 1200px !important;
}

.research-flip-card input {
  display: none !important;
}

.research-flip-inner {
  position: relative !important;
  width: 100% !important;
  min-height: 560px !important;
  transition: transform 0.7s !important;
  transform-style: preserve-3d !important;
}

.research-flip-card input:checked + .research-flip-inner {
  transform: rotateY(180deg) !important;
}

.research-flip-front,
.research-flip-back {
  position: absolute !important;
  width: 100% !important;
  min-height: 560px !important;
  backface-visibility: hidden !important;
  border: 1px solid #e5e5e5 !important;
  border-radius: 18px !important;
  background: #fff !important;
  box-shadow: 0 4px 14px rgba(0,0,0,0.06) !important;
  padding: 1.4rem !important;
  cursor: pointer !important;
}

.research-flip-front {
  text-align: center !important;
}

.research-flip-back {
  transform: rotateY(180deg) !important;
  overflow-y: auto !important;
  text-align: left !important;
  font-size: 0.88rem !important;
  line-height: 1.5 !important;
  padding: 1.8rem 2rem !important;
}

.research-flip-front h2,
.research-flip-back h2 {
  font-size: 1.45rem !important;
  margin: 0 0 0.7rem 0 !important;
  text-align: center !important;
  line-height: 1.15 !important;
}

.research-flip-front img {
  width: 300px !important;
  height: 300px !important;
  object-fit: cover !important;
  border-radius: 50% !important;
  display: block !important;
  margin: 0.5rem auto 0 auto !important;
}

.research-flip-back p {
  margin-bottom: 1rem !important;
}

.flip-hint {
  margin-top: 1rem !important;
  font-size: 0.8rem !important;
  color: #777 !important;
  text-align: center !important;
}

@media (max-width: 1000px) {
  .research-grid {
    grid-template-columns: 1fr !important;
  }
}

@media (max-width: 700px) {
  .research-flip-front img {
    width: 240px !important;
    height: 240px !important;
  }
}
</style>
My research explores how organisms respond to environmental variation across generations, with emphasis on plasticity, epigenetic mechanisms, chemical ecology, and population genetics.

<label class="research-flip-card">
  <input type="checkbox">

  <div class="research-flip-inner">

  <div class="research-flip-front">
      <h2>Transgenerational Plasticity</h2>
      <img src="/assets/images/transgenerational-plasticity.jpg" alt="Transgenerational plasticity">
      <div class="flip-hint">Click to read more</div>
    </div>

  <div class="research-flip-back">
      <h2>Transgenerational Plasticity</h2>
    
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

  <div class="flip-hint">Click to return</div>
    </div>

  </div>
</label>

  <div class="research-card">
    <details>
      <summary>
        <h2>Epigenetics</h2>
        <img src="/assets/images/epigenetics.jpg" alt="Epigenetics">
      </summary>
      <div class="research-card-text">
        <p>Text coming soon.</p>
      </div>
    </details>
  </div>

  <div class="research-card">
    <details>
      <summary>
        <h2>Chemical Ecology</h2>
        <img src="/assets/images/chemical-ecology.jpg" alt="Chemical ecology">
      </summary>
      <div class="research-card-text">
        <p>Text coming soon.</p>
      </div>
    </details>
  </div>

  <div class="research-card">
    <details>
      <summary>
        <h2>Population Genetics</h2>
        <img src="/assets/images/population-genetics.jpg" alt="Population genetics">
      </summary>
      <div class="research-card-text">
        <p>Text coming soon.</p>
      </div>
    </details>
  </div>

</div>
