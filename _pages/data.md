---
layout: archive
title: "Original Data"
permalink: /data/
author_profile: true
---
<p align="center">
  <img src="../images/cca_banner.jpg" alt="Emerging Military Technologies" style="display: block; margin: 0 auto; border-radius: 15px; padding: 5px; border: 1px solid #f2f3f3">
</p>

**Battles in Armed Conflict**
Unit of analysis: battle. Coverage: global, 1998-2024 (1,285 battles across 53 armed conflicts, including 14 interstate and 39 intrastate).

Records battle outcomes based on overt territorial control, geocoded location, start and end dates, involved actors, initiator, battle type (attack, engagement, offensive), duration, use of airpower and air defenses, access to heavy weapons, presence of fortifications, and battle environment (urban, rural, or mixed). Data collection combines human identification of battles and sources with LLM-assisted variable measurement: source text is scraped and parsed, then coded via API calls using a structured JSON schema derived from a detailed codebook, with instructions to extract information only from provided source text.

**Armed and Reconnaissance Military UAV (ARM-UAV)**
Unit of analysis: country-year. Coverage: 196 countries, 1992-2024.

Records state pursuit of and access to reconnaissance, combat, and one-way attack drones; whether initial access was indigenous or imported; first known combat use; platform group (3, 4, or 5, based on US classification); date confidence flags; and annual inventory counts by model. Inclusion requires minimum endurance (6 hours), range (200 km), and weight (100 kg for reconnaissance and combat drones; 50 kg for one-way attack drones). Constructed through cross-referencing multiple sources including the New America Foundation, Drone Databook, RUSI, SIPRI, and Drone Wars. Inventory counts were machine-coded from all years of the IISS Military Balance, double-coded for selected years, and validated through a hand-coded audit of 2014 and 2016.

**Rebel Sanctuary**
Unit of analysis: state-rebel dyad-year. Coverage: global, 1975-2016 (360 dyads; 2,016 observations).

Records the type of sanctuary rebels used each year, classified along two dimensions: overtness (overt vs. covert) and defense construction (purpose-built vs. ad hoc). Rebel sanctuary is the discrete location where rebels house military support and non-combat infrastructure and differs from areas of territorial control and coercive influence. The resulting typology produces four categories: Fortified, Unhardened, Hidden, and Makeshift. Coding is hierarchical and exclusive, based on keyword searches of news databases and triangulation with secondary sources. The universe of cases corresponds to UCDP intrastate armed conflicts excluding coups.

**Rebel and State Armed Force Size**
Unit of analysis: state-rebel dyad-year (rebel forces) and conflict-year (state forces). Coverage: global, 1975-2014 (1,927 observations).

Provides annual point estimates of the number of armed militants commanded by each rebel group and the number of state military and paramilitary forces committed to each conflict. Estimates are derived from triangulation across UCDP, IISS Military Balance, SIPRI, news sources, and case-study research, with linear interpolation for years lacking direct estimates. All dyad start and end years as well as inflection points are identified. An inflection point is determined by conflict narratives describing changes in rebel capabiltiy or strength. The universe of cases corresponds to the UCDP Armed Conflict Dataset.
