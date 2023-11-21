# liquid-iron

dynamic structure factor (DSF) $S(k,w)$ of liquid iron, calculated with deep potential molecular dynamics (DPMD) simulations under NVT ensemble (isochoric isothermal), more details see [Acta Phys. Sin., 2023, 72(18): 187102](https://doi.org/10.7498/aps.72.20231258)

| directory |lattice constant `a_0` (angstrom) | density (g/cm^3) | pressure (GPa) | temperature (Kelvin) |
| - | - | - | - | - |
| `dsf-3.762472` |3.762472 | 6.964   | 0     | 1837|
| `dsf-3.409823` |3.409823	| 9.356   | 54   | 3300|
| `dsf-3.294457` |3.294457 | 10.374 | 106 | 4250|

in each directory, DSF at each wavenumber `k = nk * delta_k` is provided in the file `dsf_${nk}k_all.txt`

we note that the resolution of reciprocal space `delta_k = 2*pi/ L` is related to the size of simulation cell `L = 20 * a_0 `
