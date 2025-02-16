---
title: "PhD-Thesis: Representativeness of Driving Data"
collection: thesis
permalink: /publication/2024-phd-thesis
excerpt: 'Thesis for acquiring Dr.-Ing. title'
date: 2024-04-07
venue: 'RWTH Aachen University'
paperurl: 'https://publications.rwth-aachen.de/record/988780'
citation: 'Johannes Hiller (2024) &quot;Representativeness of Driving Data&quot; <i>RWTH Aachen University</i>'
---
With the further development of automated vehicles, safety assurance as a step towards the introduction on public roads gains in importance.
Typically, the approach involves the analysis of recorded driving data in specific situations, so-called scenarios.
Scenarios concerning the interaction between traffic participants are often considered the most relevant.
However, with the further maturation of the vehicles, other traffic influencing factors come into focus including environmental factors such as road or weather conditions.
For both interaction and environmental factors, the question of balancing the influences remains.
This thesis aims at answering this question with the calculation of the representativeness of parameter values regarding one or multiple references.

In order to achieve this, a framework is designed that incorporates three major stages: aggregation of reference data to parameter spaces, enrichment of recorded driving data and finally the calculation of the representativeness based on the two previous stages.

As reference data, map data from OpenStreetMap and weather data from Deutscher Wetterdienst are used.
They are aggregated based on distance (only for map data) and by matching them to traffic volume and accident data.
For the second stage, the driving data are provided in a specified common data format, but the environmental data are optional as they are not always needed in today’s safety assurance applications.
Therefore, the enrichment of the driving data plays an important role in the process for the calculation of the representativeness.
Using the same data sources as for the aggregation, the enrichment is done based on map-matching algorithms for the map data and via a lookup scheme for the weather data.
Combined with the subsequent driving scenario detection, the parameter spaces for the calculation of the representativeness are available.

The calculation of the representativeness is the final stage of the proposed framework and uses the two previous steps as input.
A method is applied which allows setting parameters (e.g., speed limit of 100 km/h) or combinations of parameters (e.g., speed limit of 100 km/h on two-lane motorway and rain) into relation.
Based on these relations, the representativeness is calculated.
Utilizing the results, it is possible to state the over- or underrepresentation of parameter values in the driving data.
Formulating an optimization problem, this allows the calculation of the additionally required kilometers to be recorded in order to balance the dataset.
Using the presented modular method, an extension to further data sources and reference is perceivable.

[RWTH Publications server](https://publications.rwth-aachen.de/record/988780)

Recommended citation (also see publications server):
```bibtex
@PHDTHESIS{Hiller:988780,
      author       = {Hiller, Johannes Manuel},
      othercontributors = {Eckstein, Lutz and Moormann, Dieter},
      title        = {Representativeness analysis of driving data},
      school       = {Rheinisch-Westfälische Technische Hochschule Aachen},
      type         = {Dissertation},
      address      = {Aachen},
      publisher    = {ika},
      reportid     = {RWTH-2024-06388},
      series       = {Schriftenreihe Automobiltechnik},
      pages        = {1 Online-Ressource : Illustrationen},
      year         = {2024},
      note         = {Veröffentlicht auf dem Publikationsserver der RWTH Aachen
                      University; Dissertation, Rheinisch-Westfälische Technische
                      Hochschule Aachen, 2024},
      abstract     = {With the further development of automated vehicles, safety
                      assurance as a step towards the introduction on public roads
                      gains in importance. Typically, the approach involves the
                      analysis of recorded driving data in specific situations,
                      so-called scenarios. Scenarios concerning the interaction
                      between traffic participants are often considered the most
                      relevant. However, with the further maturation of the
                      vehicles, other traffic influencing factors come into focus
                      including environmental factors such as road or weather
                      conditions. For both interaction and environmental factors,
                      the question of balancing the influences remains. This
                      thesis aims at answering this question with the calculation
                      of the representativeness of parameter values regarding one
                      or multiple references.In order to achieve this, a framework
                      is designed that incorporates three major stages:
                      aggregation of reference data to parameter spaces,
                      enrichment of recorded driving data and finally the
                      calculation of the representativeness based on the two
                      previous stages.As reference data, map data from
                      OpenStreetMap and weather data from Deutscher Wetterdienst
                      are used. They are aggregated based on distance (only for
                      map data) and by matching them to traffic volume and
                      accident data. For the second stage, the driving data are
                      provided in a specified common data format, but the
                      environmental data are optional as they are not always
                      needed in today’s safety assurance applications.
                      Therefore, the enrichment of the driving data plays an
                      important role in the process for the calculation of the
                      representativeness. Using the same data sources as for the
                      aggregation, the enrichment is done based on map-matching
                      algorithms for the map data and via a lookup scheme for the
                      weather data. Combined with the subsequent driving scenario
                      detection, the parameter spaces for the calculation of the
                      representativeness are available. The calculation of the
                      representativeness is the final stage of the proposed
                      framework and uses the two previous steps as input. A method
                      is applied which allows setting parameters (e.g., speed
                      limit of 100 km/h) or combinations of parameters (e.g.,
                      speed limit of 100 km/h on two-lane motorway and rain) into
                      relation. Based on these relations, the representativeness
                      is calculated. Utilizing the results, it is possible to
                      state the over- or underrepresentation of parameter values
                      in the driving data. Formulating an optimization problem,
                      this allows the calculation of the additionally required
                      kilometers to be recorded in order to balance the dataset.
                      Using the presented modular method, an extension to further
                      data sources and reference is perceivable.},
      cin          = {414110},
      ddc          = {620},
      cid          = {$I:(DE-82)414110_20140620$},
      typ          = {PUB:(DE-HGF)11 / PUB:(DE-HGF)3},
      doi          = {10.18154/RWTH-2024-06388},
      url          = {https://publications.rwth-aachen.de/record/988780},
}
```
