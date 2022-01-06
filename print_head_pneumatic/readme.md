# Microfluidic printing using pneumatic extrusion
This folder contains design files for SLA/DLP manufactured microfluidic print heads, allowing 3 inputs (2 mixed for (bio)ink, 1 for cross-linking solution) and two nozzles (1 standard long-tipped, 1 co-axial for core-shell printing) compatible with pneumatic Vitaprint extruders.

## File descriptions
- 3-ch-coax-short-nomix.stl (microfluidic head without spiral mixer, suitable for laminar flow applications with lower viscosity inks)
- 3-ch-coax-short.stl (microfluidic head with spiral mixer compartment, suitable for multicomponent printing with low and high viscosity inks)
- coax-head.stl (co-axial nozzle component connecting to the mixing compartment, useful for direct deposition of material)
- fresh-head.stl (nozzle suitable for support bath printing, which requires further modification by inserting hollow blunt end needle, sealed with epoxy resin)

## Required components list
- 3-ch-coax-short-nomix.stl
- 3-ch-coax-short.stl
- coax-head.stl
- fresh-head.stl
- 2x o-ring seal, 5x0.5mm
- 3x M3 threaded bolt
- 3x M3 threaded nut
- 3x M5 to luer-lock fittings
- 3x one-way valve with luer-lock connectivity (e.g., 
- 1x spiral mixer (optional - 2.36mm diameter, 15mm in length, e.g., [Nordson EFD 7700465](https://www.nordson.com/en/divisions/efd/products/mixers/disposable-spiral-mixers)
- hollow blunt end needle G27 (optional)

## Assembly and usage
the attached stl files can be manufactured by SLA/DLP resin printing. For biomedical research applications the used resin should be non-toxic. Cleaning and sterilisation of the filter should be performed according to resin specifications.

Material inputs need to be modified by cutting an M5 thread to fit the M5-to-luer-lock connectors. The components can be assembled in vayring combinations with the nozzle as shown in the figure below and fastened using M3 screws. By rotating the co-axial nozzle, the core and shell compartments can be reversed.

![explode-diagram](https://github.com/Institute-of-Biomedical-Sciences/vitaprint-microfluidic-printing/blob/master/print_head_pneumatic/uf_print_set-up.jpg)

