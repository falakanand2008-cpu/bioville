# Bioville

**Live demo:** https://falakanand2008-cpu.github.io/bioville/

A city-builder simulation about the bioeconomy. Bioville runs on a coal plant, sends its food waste to a landfill and runs its buses on diesel. The player turns the city's waste into energy by building biogas digesters, biomass power plants, biofuel refineries, compost sites and elephant grass farms.

**Goal:** shut down the coal plant and run every bus on biofuel.

## Features
- Tile-based city map with homes, markets, farms, roads, a coal plant and a landfill
- Monthly simulation of electricity demand, bus fuel, budget and CO₂, with a growing population
- Waste-routing logic: waste is assigned to the nearest plant with spare capacity, shown as animated trucks
- AI advisor: a search-based planner that simulates every possible build on every empty tile and recommends the best one
- Live charts of CO₂ by source and clean energy share

## Built with
HTML, CSS and JavaScript (Canvas), no libraries. Built with AI-assisted development.

## Inspiration
University of Bath International Summer School, Chemical Engineering stream (2025): bioeconomy and waste-to-energy topics.

## Data
Coal and biomass life-cycle emissions from IPCC AR5 (2014). Other yields are typical published values, simplified for gameplay.
