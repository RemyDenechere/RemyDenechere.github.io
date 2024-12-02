---
layout: page
title: FEISTY-framework
description: A size- and trait- based model of fish communities
img: assets/img/FEISTY_visuals/orange_day_night_combined_lowres.png
importance: 1
category: work
related_publications: true
---
last update: 11/27/2024

<div class="row">
    <div class="col-sm-9 mt-3 mt-md-0">
        <br />
        <br />
        The FishErIes Size and functional TYpe model (FEISTY) is a mechanistic ecosystem modeling framework designed to explore the dynamics of marine fish communities under varying environmental conditions. It emphasizes simplicity and compatibility with global biogeochemical modeling principles. 

        # Overview
        The FEISTY framework models and predicts fish community biomass based on functional groups (or types) instead of individual species, focusing on their ecological traits such as body size, trophic interactions, and habitat use. This approach allows 
    </div>
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FEISTY_visuals/feisty_logo_orange_border.png" title="FEISTY Logo" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
the model to capture the essence of fish community dynamics in a computationally efficient manner, enabling its application on regional to global scales.

FEISTY uses an individual-based mechanistic, mass-conserving framework based on energy budgets, where energy intake supports growth, reproduction, and survival.
The model connects higher trophic levels (fish) to planktonic food webs and benthic resources, integrating predator-prey interactions, competition, and energy transfer pathways.
Fish and prey interactions are determined by size relationships and in the most advance setups by vertical overlap in the water column, accounting for the varying depth and habitat use of species.

# Global Applications:
The model is designed to work with outputs from Earth system models, such as those providing plankton dynamics and oceanographic conditions, to predict fish biomass and ecosystem functions globally.
Our framework has has various application from estimating estimates of potential fisheries yields, to project the effects of future global warming and ocean productivity on fish distributions, food webs, and carbon cycling.


FEISTY provides a robust, flexible platform for addressing global questions in marine ecosystem management. It bridges the gap between traditional species-specific fisheries models and broader ecosystem-based approaches, making it ideal for studying the complex interactions between fisheries, ecosystems, and environmental change.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FEISTY_visuals/orange_day_night_combined_lowres.png" title="Description of the FEISTY framework" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Visual description of the FEISTY framework. 
</div>


Visit our <a href="https://github.com/Kenhasteandersen/FEISTY">FEISTY github page</a> to dowload the model.

All the visuals have been designed by Jan D. Heuschele. 
