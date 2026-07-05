---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.research-layout {
  display: grid !important;
  grid-template-columns: minmax(280px, 0.8fr) minmax(620px, 1.7fr) !important;
  gap: 2rem !important;
  margin-top: 2rem !important;
  align-items: start !important;
}

.research-cards {
  display: grid !important;
  grid-template-columns: 1fr !important;
  gap: 1rem !important;
}

.research-card {
  border: 1px solid #e5e5e5 !important;
  border-radius: 18px !important;
  background: #fff !important;
  box-shadow: 0 4px 14px rgba(0,0,0,0.05) !important;
  padding: 1rem !important;
  text-align: center !important;
  cursor: pointer !important;
  transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease !important;
}

.research-card:hover {
  transform: translateY(-2px) !important;
  box-shadow: 0 6px 18px rgba(0,0,0,0.08) !important;
}

.research-card.active {
  display: none !important;
}

.research-card h2 {
  font-size: 1.05rem !important;
  line-height: 1.15 !important;
  margin: 0 0 0.6rem 0 !important;
  text-align: center !important;
}

.research-card img {
  width: 150px !important;
  height: 150px !important;
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
  padding: 2rem 2.6rem !important;
  min-height: 720px !important;
}

.research-content {
  display: none !important;
}

.research-content.active {
  display: block !important;
}

.research-content h2 {
  font-size: 1.75rem !important;
  line-height: 1.15 !important;
  margin: 0 0 1rem 0 !important;
  text-align: center !important;
}

.research-content img {
  width: 280px !important;
  height: 280px !important;
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

.research-back-hint {
  margin-top: 1.5rem !important;
  font-size: 0.85rem !important;
  color: #777 !important;
  text-align: center !important;
}

@media (max-width: 1000px) {
  .research-layout {
    grid-template-columns: 1fr !important;
  }

  .research-cards {
    grid-template-columns: repeat(2, 1fr) !important;
  }

  .research-panel {
    min-height: auto !important;
  }
}

@media (max-width: 700px) {
  .research-cards {
    grid-template-columns: 1fr !important;
  }

  .research-card img {
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

<div class="research-layout">

  <div class="research-cards">

   <div class="research-card active" data-topic="transgen">
      <h2>Transgenerational Plasticity</h2>
      <img src="/assets/images/transgenerational-plasticity.jpg" alt="Transgenerational plasticity">
    </div>

   <div class="research-card" data-topic="epigenetics">
      <h2>Epigenetics</h2>
      <img src="/assets/images/epigenetics.jpg" alt="Epigenetics">
    </div>

   <div class="research-card" data-topic="chemical">
      <h2>Chemical Ecology</h2>
      <img src="/assets/images/chemical-ecology.jpg" alt="Chemical ecology">
    </div>

   <div class="research-card" data-topic="popgen">
      <h2>Population Genetics</h2>
      <img src="/assets/images/population-genetics.jpg" alt="Population genetics">
    </div>

  </div>

  <div class="research-panel">

   <div class="research-content active" id="content-transgen">
      <h2>Transgenerational Plasticity</h2>
      <img src="/assets/images/transgenerational-plasticity.jpg" alt="Transgenerational plasticity">

   <p>
        To adapt to changing environments, organisms must cope with stress not only within their own lifetime, but also across generations. The conditions experienced by parents or ancestors may influence how descendants grow, survive, and respond to similar stress later in life, even in the absence of genetic change. This controversial process is known as transgenerational plasticity.
      </p>

   <p>
        Transgenerational plasticity may be especially important in clonal organisms, where adaptation through genetic recombination is limited. Yet we still know little about whether transgenerational plasticity can help descendants when stress returns, how long these effects last, and whether some lineages are more likely than others to show these responses.
      </p>

   <p>
        I study these questions by following single descendant lines across multiple generations. First, I expose individuals to stress for five generations. This pre-treatment phase allows stress-related changes to arise. Then, I grow the next five generations without stress to erase all directly induced changes. Finally, I expose the eleventh generation to either control conditions or recurrent stress for three to five generations. This final treatment phase shows whether ancestral stress changes offspring fitness and phenotype. Ancestral stress may have no detectable effects, it may lead to the transgenerational retention of stress-related traits across generations, or it may transgenerationally prime descendants, making them better or worse prepared for recurrent stress.
      </p>

   <div class="research-back-hint">Click another topic to change the panel.</div>
   </div>

   <div class="research-content" id="content-epigenetics">
      <h2>Epigenetics</h2>
      <img src="/assets/images/epigenetics.jpg" alt="Epigenetics">

   <p>
Genetic diversity allows organisms to adapt in changing environments, but it may not be the only mechanism that shapes adaptation. Epigenetic marks, such as DNA methylation, small RNAs, and histone modifications, regulate how genes are expressed without changing the DNA sequence itself. Yet we still know little about whether these marks can influence adaptation in the absence of genetic change, how quickly they change across generations, and whether they can contribute to transgenerational plasticity.
      </p>
    <p>
To study these questions, I use clonally reproducing organisms to assses DNA methylation and its correlation with gene expression. I currently work with <em>Rhopalosiphum nymphaeae</em>, <em>Daphnia magna</em>, <em>Spirodela polyrhiza</em>, <em>Boechera stricta</em> and <em>Marchantia polymorpha</em>.
      </p>

   <div class="research-back-hint">Click another topic to change the panel.</div>
   </div>

   <div class="research-content" id="content-chemical">
      <h2>Chemical Ecology</h2>
      <img src="/assets/images/chemical-ecology.jpg" alt="Chemical ecology">

   <p>
Metabolites are small molecules that take part in metabolism, including growth, development, and energy production. Their biosynthesis often starts from primary metabolites, such as amino acids, and leads to specialized metabolites, such as amines, alkaloids, phenolamides, and phenylpropanoids.
      </p>
    <p>
Amines are well known as neurotransmitters and neuromodulators in animals, but they also occur in plants. In plants, they may influence growth and stress responses. However, their role in plant–herbivore interactions remains poorly characterized.
      </p>
    <p>
Phenylpropanoids, including flavonoids, are another major group of plant specialized metabolites. Flavonoids are often recognized for their antioxidant activity, but whether they are sufficient on their own to protect plants from oxidative stress remains unclear.
      </p>
    <p>
To study these questions, I use genetically engineered <em>Spirodela polyrhiza</em> lines that either over-accumulate or suppress specific amines. I expose these lines to abiotic stress and to two types of herbivory: sap-feeding by <em>Rhopalosiphum nymphaeae</em> and chewing herbivory by <em>Lymnaea stagnalis</em>. This approach shows how changes in amine and flavonoid concentrations affect plant stress responses and plant–herbivore interactions.
      </p>

   <div class="research-back-hint">Click another topic to change the panel.</div>
    </div>

   <div class="research-content" id="content-popgen">
      <h2>Population Genetics</h2>
      <img src="/assets/images/population-genetics.jpg" alt="Population genetics">

   <p>
        While a major question in biology is how organisms adapt to changing environments, it is also important to understand the species current population structure. To assess this, I use genetic and epigenetic markers to characterize genetic diversity, population structure, gene flow, and their associations with environmental and phenotypic variation.
      </p>
    <p>
I work with a variety of organisms, including plants such as <em>Spirodela polyrhiza</em> and <em>Aristotelia chilensis</em>, and mammals such as the southern huemul deer (<em>Hippocamelus bisulcus</em>), the Andean bear (<em>Tremarctos ornatus</em>), and camelids.
      </p>

   <div class="research-back-hint">Click another topic to change the panel.</div>
   </div>

  </div>

</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const cards = document.querySelectorAll(".research-card");
  const contents = document.querySelectorAll(".research-content");

  cards.forEach(function (card) {
    card.addEventListener("click", function () {
      const topic = card.getAttribute("data-topic");

      cards.forEach(function (item) {
        item.classList.remove("active");
      });

      contents.forEach(function (content) {
        content.classList.remove("active");
      });

      card.classList.add("active");

      const selectedContent = document.getElementById("content-" + topic);
      if (selectedContent) {
        selectedContent.classList.add("active");
      }
    });
  });
});
</script>
