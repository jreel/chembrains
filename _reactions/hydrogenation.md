---
layout: reaction
title: "Hydrogenation"
summary: "Adds H<sub>2</sub> across a pi bond"
scheme: "hydrogenation.png"
---
{% assign url = site.data.links %}

Hydrogenation typically constitutes the addition of a pair of hydrogen atoms to a molecule containing a double or triple bond, most often an [alkene]({{ url.alkene }}). The process utilizes [molecular hydrogen]({{ url.H2 }}) ([H<sub>2</sub>]({{ url.H2 }})) in the presence of a metal catalyst such as nickel, palladium or [platinum]({{ url.Pt }}). A catalyst is required for the reaction to be usable; non-catalytic hydrogenation takes place only at very high temperatures.

Source: [Hydrogenation](https://en.wikipedia.org/wiki/Hydrogenation) (Wikipedia)

fgi:
  - substrate: alkenes
    product: alkanes
  - substrate: alkynes
    product: alkanes
  - substrate: aldehydes
    product: alcohols
  - substrate: ketones
    product: alcohols
  - substrate: nitros
    product: amines
  - substrate: aromatics
    product: cycloalkanes
reagents:
  - hydrogen
  - catalyst:
    - platinum
    - palladium
    - rhodium
    - ruthenium
    - Raney-nickel
addition-type: syn