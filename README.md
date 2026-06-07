# Nanopore Assembly QC & Evaluation

Tento miniprojekt se zabývá hodnocením vlivu QC metod (`fastplong` vs. `porechop` + `filtlong`) a consensus polishingu (`Medaka`) na kvalitu *de novo* genomové assembly vytvořené nástrojem `Flye`.

## Klíčové závěry
* Pro moderní nanoporová data (verze **R10.4.1**) jsou obě QC metody rovnocenné a dodatečný polishing nemá zásadní vliv na kompletnost.
* U starší chemie (**R9.4.1**) vykazuje nástroj `fastplong` mírně lepší výsledky než kombinace `porechop+filtlong`.
