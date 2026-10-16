# Steel section weights: IS 808, IPE / HEA / HEB / UPN, pipe schedules, rebar, sheet gauges

Weights per metre (and per foot), dimensions and section properties of standard steel sections,
as plain CSV and JSON, checked against the source standards. Use them in spreadsheets, BOQ
(bill of quantities) sheets, estimating tools or structural scripts.

Interactive version with a weight calculator, drawings and printable PDF charts:
**[steelweight-calculator.com](https://steelweight-calculator.com/)**

| File | Rows |
|---|---|
| [`india/ismb.csv`](india/ismb.csv) | 14 |
| [`india/iswb.csv`](india/iswb.csv) | 14 |
| [`india/ismc.csv`](india/ismc.csv) | 20 |
| [`india/isa-equal-angles.csv`](india/isa-equal-angles.csv) | 72 |
| [`europe/ipe.csv`](europe/ipe.csv) | 18 |
| [`europe/hea.csv`](europe/hea.csv) | 24 |
| [`europe/heb.csv`](europe/heb.csv) | 24 |
| [`europe/hem.csv`](europe/hem.csv) | 24 |
| [`europe/upn.csv`](europe/upn.csv) | 18 |
| [`pipe/pipe-schedules.csv`](pipe/pipe-schedules.csv) | 405 |
| [`rebar/us-rebar.csv`](rebar/us-rebar.csv) | 11 |
| [`rebar/metric-rebar.csv`](rebar/metric-rebar.csv) | 12 |
| [`sheet-metal/gauges.csv`](sheet-metal/gauges.csv) | 36 |
| [`steel-sections.json`](steel-sections.json) | all of the above |

## ISMB weight chart (IS 808:2021)

The 1964 handbook values in the last column are still printed in many weight charts. IS 808:1989
changed the flange thickness of several sizes, so those figures no longer match what is rolled.

| Section | kg/m | lb/ft | D × B (mm) | tw / tf (mm) | 1989 kg/m | 1964 kg/m |
|---|---|---|---|---|---|---|
| ISMB 100 | 8.95 | 6.01 | 100 × 50 | 4.7 / 7 | 8.9 | 11.5 |
| ISMB 125 | 13.35 | 8.97 | 125 × 70 | 5 / 8 | 13.3 | 13.0 |
| ISMB 150 | 14.96 | 10.05 | 150 × 75 | 5 / 8 | 15.0 | 14.9 |
| ISMB 175 | 19.50 | 13.10 | 175 × 85 | 5.8 / 9 | 19.6 | 19.3 |
| ISMB 200 | 24.17 | 16.24 | 200 × 100 | 5.7 / 10 | 24.2 | 25.4 |
| ISMB 225 | 31.15 | 20.93 | 225 × 110 | 6.5 / 11.8 | 31.1 | 31.2 |
| ISMB 250 | 37.30 | 25.06 | 250 × 125 | 6.9 / 12.5 | 37.3 | 37.3 |
| ISMB 300 | 46.02 | 30.92 | 300 × 140 | 7.7 / 13.1 | 46.0 | 44.2 |
| ISMB 350 | 52.33 | 35.16 | 350 × 140 | 8.1 / 14.2 | 52.4 | 52.4 |
| ISMB 400 | 61.55 | 41.36 | 400 × 140 | 8.9 / 16 | 61.5 | 61.6 |
| ISMB 450 | 72.38 | 48.64 | 450 × 150 | 9.4 / 17.4 | 72.4 | 72.4 |
| ISMB 500 | 86.88 | 58.38 | 500 × 180 | 10.2 / 17.2 | 86.9 | 86.9 |
| ISMB 550 | 103.64 | 69.64 | 550 × 190 | 11.2 / 19.3 | 104.0 | 103.7 |
| ISMB 600 | 121.00 | 81.31 | 600 × 210 | 12 / 20.3 | 123.0 | 122.6 |

All sizes with properties: [`india/ismb.csv`](india/ismb.csv)

## IPE beam weights

| Section | kg/m | lb/ft | h × b (mm) | tw / tf (mm) | Iy (cm⁴) |
|---|---|---|---|---|---|
| IPE 80 | 6 | 4.03 | 80 × 46 | 3.8 / 5.2 | 80.1 |
| IPE 100 | 8.1 | 5.44 | 100 × 55 | 4.1 / 5.7 | 171 |
| IPE 120 | 10.37 | 6.97 | 120 × 64 | 4.4 / 6.3 | 317.7 |
| IPE 140 | 12.89 | 8.66 | 140 × 73 | 4.7 / 6.9 | 541.2 |
| IPE 160 | 15.77 | 10.60 | 160 × 82 | 5 / 7.4 | 869.3 |
| IPE 180 | 18.8 | 12.63 | 180 × 91 | 5.3 / 8 | 1316.9 |
| IPE 200 | 22.36 | 15.03 | 200 × 100 | 5.6 / 8.5 | 1943.1 |
| IPE 220 | 26.2 | 17.61 | 220 × 110 | 5.9 / 9.2 | 2771.8 |
| IPE 240 | 30.71 | 20.64 | 240 × 120 | 6.2 / 9.8 | 3891.5 |
| IPE 270 | 36.07 | 24.24 | 270 × 135 | 6.6 / 10.2 | 5789.6 |
| IPE 300 | 42.24 | 28.38 | 300 × 150 | 7.1 / 10.7 | 8356 |
| IPE 330 | 49.15 | 33.03 | 330 × 160 | 7.5 / 11.5 | 11766.6 |
| IPE 360 | 57.09 | 38.36 | 360 × 170 | 8 / 12.7 | 16265.3 |
| IPE 400 | 66.3 | 44.55 | 400 × 180 | 8.6 / 13.5 | 23127.8 |
| IPE 450 | 77.57 | 52.12 | 450 × 190 | 9.4 / 14.6 | 33742.4 |
| IPE 500 | 90.68 | 60.93 | 500 × 200 | 10.2 / 16 | 48197.9 |
| IPE 550 | 105.52 | 70.91 | 550 × 210 | 11.1 / 17.2 | 67115.5 |
| IPE 600 | 122.45 | 82.28 | 600 × 220 | 12 / 19 | 92082.5 |

All sizes: [`europe/ipe.csv`](europe/ipe.csv)

## Units

- Lengths in mm (`_mm`) or inches (`_in`); area in cm²; second moments `ix`, `iy`, `iu`, `iv`, `it`
  in cm⁴; section moduli `z*` in cm³; radii of gyration `r*` in cm; warping constant `iw` in cm⁶.
- `mass_lb_ft` = `mass_kg_m` ÷ 1.48816. Steel density 7850 kg/m³ throughout.
- Indian sections: IS 808 axis names (x-x major, y-y minor; u-u and v-v principal axes of angles).
  European sections: EN axis names (y-y major, z-z minor).

## How the data was checked

- **Indian (IS 808:2021)**: extracted from the standard and checked row by row with
  M = 0.785 A, r = √(I / A) and Zx = Ix / (D / 2). Known misprints in the printed standard are
  corrected; the 1989 and 1964 masses come from IS 808:1989 and the
  SP 6(1):1964 handbook.
- **European**: geometry from the fib-international structuralcodes library
  (Apache-2.0), cross-checked against FreeCAD's profile library; area rebuilt from the dimensions
  including root fillets.
- **Pipe**: wall thicknesses from ASME B36.10M / B36.19M as tabulated on Wikipedia;
  weight = 10.69 × (OD − t) × t lb/ft; STD and XS walls cross-checked against the AISC pipe shapes.
- **Rebar**: checked against area × 7850 kg/m³ and the d² / 162 rule.

American W, S, C, MC, L and HSS shapes are not included here because the AISC Shapes Database has
no redistribution licence; download it from AISC (AISC Shapes Database v16.0).

## Licence and attribution

See [LICENSE.md](LICENSE.md): different folders carry their sources' licences.
If you use the data, please credit steelweight-calculator.com.

Values are provided for estimating and reference. Check them against the current standard or the
mill certificate before design or purchase.
