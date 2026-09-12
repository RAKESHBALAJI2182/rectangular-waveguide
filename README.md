# Rectangular waveguide

Rectangular waveguide designed and simulated in CST Studio Suite.

## Dimensions

- Broad wall (a): 30.083 mm
- Narrow wall (b): 15.5415 mm
- Length: 50 mm

## Mode

TE10. Theoretical cutoff frequency: fc = c / (2a) ≈ 4.99 GHz.

## Simulation

S-parameters and VSWR simulated across 2-6 GHz. The deepest S11 null in the sweep sits near 4.9 GHz, close to the calculated TE10 cutoff, which is worth rechecking against the port mode setup before treating it as a final result. VSWR stays close to 1.0 across most of the band and rises near the low end of the sweep.

## Files

- s11.s1p - exported S-parameter data (Touchstone format)
- s11_plot.png - S11 magnitude vs frequency
- vswr_plot.png - VSWR vs frequency
- geometry.png - model view from CST

Tool: CST Studio Suite.
