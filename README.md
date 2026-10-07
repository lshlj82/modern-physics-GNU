# Modern Physics (현대물리학): Interactive Lecture Notes

Interactive web companion to the undergraduate course Modern Physics (현대물리학) in the Department of Physics, Gyeongsang National University, following S. T. Thornton, A. Rex, and C. E. Hood, *Modern Physics for Scientists and Engineers*, 5th ed. (Cengage Learning). The pages were created by Claude Opus 5.5 (Anthropic) based on Sang Hoon Lee's lecture notes.

Each chapter is a single, self-contained HTML page that pairs the lecture notes with simulations and calculations computed live in the browser. Key terms are given in English with the Korean term in parentheses, as in the lecture notes.

## Chapters

Live pages (GitHub Pages). Start from the [course home page](https://YOUR-USERNAME.github.io/YOUR-REPO/).

| Chapter | Demo page | Source |
|---|---|---|
| 2. Special theory of relativity, Part 1 (§2.1–2.5) | [Open demo](https://YOUR-USERNAME.github.io/YOUR-REPO/ch02a-special-relativity.html) | [`ch02a-special-relativity.html`](ch02a-special-relativity.html) |
| 2. Special theory of relativity, Part 2 (§2.6–2.14) | [Open demo](https://YOUR-USERNAME.github.io/YOUR-REPO/ch02b-spacetime-and-relativistic-dynamics.html) | [`ch02b-spacetime-and-relativistic-dynamics.html`](ch02b-spacetime-and-relativistic-dynamics.html) |
| 3. The experimental basis of quantum physics (§3.1–3.9) | [Open demo](https://YOUR-USERNAME.github.io/YOUR-REPO/ch03-experimental-basis-of-quantum-physics.html) | [`ch03-experimental-basis-of-quantum-physics.html`](ch03-experimental-basis-of-quantum-physics.html) |
| 4. Structure of the atom (§4.1–4.7) | [Open demo](https://YOUR-USERNAME.github.io/YOUR-REPO/ch04-structure-of-the-atom.html) | [`ch04-structure-of-the-atom.html`](ch04-structure-of-the-atom.html) |
| 5. Wave properties of matter and quantum mechanics I (§5.1–5.8) | [Open demo](https://YOUR-USERNAME.github.io/YOUR-REPO/ch05-wave-properties-of-matter.html) | [`ch05-wave-properties-of-matter.html`](ch05-wave-properties-of-matter.html) |
| 6. Quantum mechanics II (§6.1–6.7) | [Open demo](https://YOUR-USERNAME.github.io/YOUR-REPO/ch06-quantum-mechanics-II.html) | [`ch06-quantum-mechanics-II.html`](ch06-quantum-mechanics-II.html) |
| 7. The hydrogen atom (§7.1–7.6) | [Open demo](https://YOUR-USERNAME.github.io/YOUR-REPO/ch07-hydrogen-atom.html) | [`ch07-hydrogen-atom.html`](ch07-hydrogen-atom.html) |
| 8. Atomic physics (§8.1–8.3) | [Open demo](https://YOUR-USERNAME.github.io/YOUR-REPO/ch08-atomic-physics.html) | [`ch08-atomic-physics.html`](ch08-atomic-physics.html) |
| 9. Statistical physics (§9.1–9.7) | [Open demo](https://YOUR-USERNAME.github.io/YOUR-REPO/ch09-statistical-physics.html) | [`ch09-statistical-physics.html`](ch09-statistical-physics.html) |

The demo links assume the site is published with GitHub Pages; replace `YOUR-USERNAME` and `YOUR-REPO` throughout this file with your GitHub user name and repository name.

## Chapter 2, Part 1: what's inside

The page covers inertial frames and Galilean invariance, the ether, the Michelson–Morley experiment, Einstein's postulates, the Lorentz transformation, time dilation, and length contraction.

- *The Michelson–Morley interferometer (§2.2).* A slowly rotating interferometer with live fringes. The ether theory predicts a shift $N(\theta) = v^2(\ell_1+\ell_2)\sin^2\theta/c^2\lambda$, about 0.04 fringe for Michelson's 1881 apparatus and 0.4 for the 1887 one; the observed shift was zero. A toggle adds the Lorentz–FitzGerald contraction, which removes the predicted shift.
- *Two flashes, two observers (§2.3).* Flashes at ±1 m seen by Frank at rest and Mary moving: simultaneous for Frank, right flash first for Mary, with arrival times and the time difference in K′.
- *Galilean or Lorentz? (§2.4).* The light wavefront in K′: a circle centered on K′'s origin under the Lorentz transformation, off-center under the Galilean one. Also a plot of $\gamma(\beta)$ and an event calculator that checks the invariant $x^2 - c^2t^2$.
- *Two light clocks on one spaceship (§2.5).* A vertical and a horizontal light clock of the same proper length, seen from K. They tick together only if the horizontal arm is contracted to $L_0/\gamma$; without contraction, Mary could detect her own motion.
- *Plan your own trip (§2.5, Example 2.2).* Required speed and Earth time for a round trip of given distance and ship time; the default reproduces $v = 0.473c$ and 18.2 years for Alpha Centauri.
- *Contracted vs photographed (§2.5).* Wireframe boxes moving at up to $0.95c$: at rest, at one instant in K (contracted), and as recorded by a camera (light-travel delays), in the spirit of Scott and Viner (1965).

The page header shows a spaceship passing a row of synchronized clocks: the station clocks read $t$, the ship's clock reads $t/\gamma$, and the ship is drawn length-contracted.

## Chapter 2, Part 2: what's inside

The page covers velocity addition, experimental verification, the twin paradox, spacetime, the Doppler effect, relativistic momentum and energy, and electromagnetism and relativity.

- *Galileo vs Einstein (§2.6).* Velocity vectors in two dimensions with presets for Examples 2.3 (0.99c fired from a ship at 0.6c gives 0.997c) and 2.4 (perpendicular firing gives 0.994c), and a light pulse that stays at exactly $c$.
- *Muons reaching the ground (§2.7).* Survivors out of 1000 versus altitude with and without time dilation; the default reproduces 45 vs about 538 for the textbook's mountain (542 measured).
- *Two events, any frame (§2.9).* A Minkowski diagram with tilted primed axes and the light cone. The interval $\Delta s^2$ stays fixed as the boost changes, with buttons that find the frame where a spacelike pair is simultaneous or a timelike pair is at one place.
- *The twin paradox in spacetime (§2.8–2.10).* Worldlines and annual light signals for any speed and distance, with a live version of French's signal-counting table; the default reproduces Examples 2.7 and 2.8 (20 vs 12 years; 6 + 6 and 2 + 18 signals).
- *The Doppler effect for light (§2.10).* Longitudinal shift compared with the two sound formulas, the angular dependence $f/f_0 = 1/[\gamma(1-\beta\cos\theta)]$ including the transverse effect, and the emitted and received colors.
- *Momentum bookkeeping (§2.11).* The two-ball collision of Figure 2.29: the classical momentum changes do not cancel, the relativistic ones do, for any speeds.
- *Accelerating electrons (§2.12).* Speed versus kinetic energy, classical and relativistic, and the energy–momentum hyperbola; Example 2.11 (25 kV) gives $0.302c$ with a 3.6% classical error.
- *A wire seen from two frames (§2.14).* Ions and electrons in a current-carrying wire; in the frame of a moving test charge, length contraction leaves a net positive charge density $\gamma\beta^2\lambda_0$, turning a magnetic force into an electric one.

The page header is a Minkowski diagram whose primed axes slowly scissor as the relative speed changes, with an event riding the invariant hyperbola $c^2t^2 - x^2 = 1$.

## Chapter 3: what's inside

The prologue to quantum mechanics: the experiments around 1900 that classical physics could not explain.

- *Thomson's e/m experiment (§3.1).* An electron beam between charged plates, drawn to scale, with electric and magnetic fields; Example 3.1 gives a 30° deflection, $v_0 = E/B = 1.4\times10^7$ m/s, and $q/m = 1.8\times10^{11}$ C/kg.
- *A simulated oil-drop experiment (§3.2).* Synthetic drops carrying whole numbers of charges, with adjustable measurement error; the histogram peaks at multiples of $e$ and the data give an estimate of $e$.
- *The hydrogen series (§3.3).* Lyman through Pfund from the Rydberg equation, in color where visible, with an overview of all five series.
- *Planck vs Rayleigh–Jeans (§3.5).* The two spectra at any temperature, the visible band, $\lambda_{\max}$, and the numerically integrated total power against $\sigma T^4$; presets include the Sun.
- *The photoelectric experiment (§3.6).* Photons striking a chosen metal and photoelectrons crossing to the collector, with the current–voltage curve and $eV_0 = hf - \phi$ for three metals.
- *The x-ray continuum (§3.7).* Bremsstrahlung spectra in Kramers' approximation and the Duane–Hunt limit $\lambda_{\min} = hc/eV_0$ (Example 3.15: $3.54\times10^{-11}$ m at 35 kV).
- *Compton scattering (§3.8).* The collision geometry with the electron's recoil angle, and $\Delta\lambda = \lambda_C(1-\cos\theta)$; the default is Compton's molybdenum $K_\alpha$ x rays at 135°.
- *Pair production (§3.9).* A photon converting into an electron and a positron that curve oppositely in a magnetic field, with the 1.022 MeV threshold and 0.511 MeV annihilation photons.

The page header is a blackbody slowly heated and cooled, with its color and Planck spectrum.

## Chapter 4: what's inside

From plum pudding to Bohr's quantized orbits.

- *α particles meeting a nucleus (§4.2).* Trajectories integrated numerically in the Coulomb field for impact parameters from 2 to 150 fm, labeled with their scattering angles, with the distance of closest approach and the tiny deflection a Thomson atom could give.
- *A Geiger–Marsden experiment by Monte Carlo (§4.2).* Simulated α particles with random impact parameters; counts per unit solid angle follow the Rutherford $1/\sin^4(\theta/2)$ law over orders of magnitude.
- *The death spiral of a classical atom (§4.3).* The Larmor-radiation collapse $r^3 = r_0^3 - 4r_e^2ct$, which takes about $1.6\times10^{-11}$ s from $r_0 = a_0$.
- *Energy levels and transitions (§4.4–4.5).* Hydrogen, deuterium, tritium, He⁺, and Li²⁺: level diagram, orbits to scale, and the photon's wavelength and color; reproduces Example 4.8 (656.47, 656.29, 656.23 nm).
- *Quantum jumps approach classical orbits (§4.4).* The correspondence principle as the ratio $f_{\rm Bohr}/f_{\rm classical}\to1$.
- *Moseley's law (§4.6).* $\sqrt f$ against $Z$ for K$_\alpha$ and L$_\alpha$ lines, compared with well-known measured K$_\alpha$ wavelengths.
- *The Franck–Hertz experiment (§4.7).* A simple model of an electron's energy between cathode and grid, and the collector current with drops every 4.88 V.

The page header is a Bohr hydrogen atom whose electron jumps between orbits drawn to scale, emitting and absorbing photons in their real colors.

## Chapter 5: what's inside

Matter waves and the first steps of quantum mechanics.

- *Bragg reflection (§5.1).* Rays reflected from adjacent planes with the extra path $2d\sin\theta$, and the 20-plane intensity peaked at $n\lambda = 2d\sin\theta$; Example 5.1 (NaCl, 0.098 nm at 10°).
- *A standing wave around the orbit (§5.2).* A whole number of de Broglie wavelengths closes on itself, giving $L = n\hbar$.
- *De Broglie wavelength calculator (§5.2–5.5).* Electrons, protons, neutrons, α particles, and a tennis ball, computed relativistically, with presets for Examples 5.2, 5.3, 5.4, and 5.7.
- *The Davisson–Germer peak (§5.3).* A schematic polar plot whose diffraction peak sits at $\sin\phi = \lambda/D$, about 51° at 54 eV.
- *Building a wave packet (§5.4, Problem 69).* Seven cosines with $n = 9$–15 forming a packet that repeats at every integer $x$, and a Gaussian spectrum showing $\Delta k\Delta x\sim1$.
- *Phase and group velocity (§5.4).* Two-wave beats for light in vacuum, deep-water waves, and a free particle, with dots riding a crest and the envelope.
- *The double slit (§5.5).* Probability on the screen with and without a which-slit detector; Example 5.7 gives fringes 938 nm apart.
- *Narrow in position, wide in momentum (§5.6).* A Gaussian packet and its spectrum with $\Delta x\Delta k = 1/2$, plus the confinement energy of an electron in an atom (3.4 eV) or a nucleus (15.9 MeV).
- *Standing waves in a box (§5.8).* The first five levels and probability densities, with the uncertainty bound; Example 5.13.

The page header builds up a double-slit interference pattern one electron at a time.

## Chapter 6: what's inside

The Schrödinger equation and its first solutions.

- *Probability as area (§6.1, Example 6.4).* The normalized $\sqrt\alpha\,e^{-\alpha|x|}$ with a shaded interval whose area is the probability (0.432 for 0 to $1/\alpha$).
- *The infinite square well (§6.3).* Stationary states up to $n = 20$ with $\langle x\rangle$, $\langle x^2\rangle$, $\langle p\rangle$, $\langle p^2\rangle$ by numerical integration (Example 6.8), and a superposition of $n = 1$ and 2 whose probability sloshes back and forth.
- *Bound states of a finite well (§6.4).* Exact energies for an electron from the transcendental matching conditions, shown graphically, with wave functions leaking into the walls and the penetration depth.
- *Degeneracy in a box (§6.5).* Energy levels of a three-dimensional box labeled by $(n_1,n_2,n_3)$; stretching a side of the cube removes the degeneracy.
- *The quantum harmonic oscillator (§6.6).* The lowest states at equally spaced energies, and $|\psi_n|^2$ against the classical probability up to $n = 30$.
- *Transmission through a barrier (§6.7).* The exact $T(E)$ with resonances above the barrier and the thick-barrier approximation, plus $|\psi|^2$ from matching at both edges; Example 6.14.
- *Why an STM is so sensitive (§6.7).* The exponential dependence of tunneling current on the gap.

The page header solves the time-dependent Schrödinger equation live (split-step Fourier method) for a wave packet striking a barrier, reporting the reflected and transmitted probability.

## Chapter 7: what's inside

The Schrödinger equation applied to hydrogen.

- *Space quantization of $\vec L$ (§7.3).* The $2\ell+1$ allowed $L_z$ values with vectors of length $\sqrt{\ell(\ell+1)}\hbar$, drawn flat and on precession cones, with Feynman's check $3\langle L_z^2\rangle = \ell(\ell+1)\hbar^2$.
- *Counting the states of level $n$ (§7.3, Example 7.4).* Subshells, $m_\ell$ values, and the $n^2$ (or $2n^2$ with spin) degeneracy.
- *The normal Zeeman effect (§7.4).* The 2p level split by $\mu_BB$ and the Lyman-α line split into three; Example 7.7.
- *The Stern–Gerlach experiment (§7.4–7.5).* Atoms deflected in an inhomogeneous field: a continuous band classically, three spots for $\ell = 1$, two for silver (spin ½).
- *Allowed and forbidden transitions (§7.6).* A level diagram by $\ell$ with the $\Delta\ell = \pm1$ rule; Example 7.10.
- *Orbital explorer (§7.6).* Any $(n,\ell,m_\ell)$ up to $n = 6$, computed from associated Laguerre functions and spherical harmonics: the density in the $xz$ plane, $R_{n\ell}$, and $P_{n\ell}$, with the most probable radius, $\langle r\rangle$, and the probabilities of Examples 7.11–7.14.

The page header cycles through hydrogen probability densities.

## Chapter 8: what's inside

Many-electron atoms, the periodic table, and fine structure.

- *The periodic table (§8.1).* All 118 elements, colored by block; selecting one shows its ground-state configuration, generated from the $n+\ell$ filling order with the known exceptions (Cr, Cu, Pd, Ag, Au, La, Gd, …) and matching the textbook's Figure 8.2, plus its place on a plot of first ionization energies (NIST values, $Z = 1$–88).
- *How big is a Rydberg atom? (§8.1).* Size, binding energy, and $n\to n-1$ photon wavelength; $n = 400$ gives about 17 µm and a 2.9 m radio line.
- *Adding $\vec L$ and $\vec S$ (§8.2).* Vector triangles for $j = \ell\pm\tfrac12$ drawn to scale and the resulting spin-orbit doublet.
- *Term symbols for two electrons (§8.2).* Microstates counted by $M_L$ and $M_S$ with the Pauli principle for equivalent electrons, terms extracted from the table, and the ground level by Hund's rules; carbon 2p² gives $^1S$, $^1D$, $^3P$ with $^3P_0$ lowest (Example 8.9).
- *Zeeman patterns (§8.3).* Landé $g$ factors and all allowed $\Delta m_J = 0,\pm1$ transitions: 4 lines for sodium D₁, 6 for D₂, and the normal 3-line pattern for $^1D_2\to{}^1P_1$ (Example 8.10).

The page header fills the subshells of the first 36 elements one electron at a time, following the Pauli principle and Hund's rule.

## Chapter 9: what's inside

From Maxwell's molecules to Fermi and Bose gases.

- *Degrees of freedom switching on (§9.3).* The textbook's Table 9.1 against the equipartition values, and a quantum model of $c_V$ for H₂ (translation + rigid rotor + oscillator) showing why rotation and vibration switch on only at higher temperatures.
- *The Maxwell speed distribution (§9.4).* $F(v)$ for several gases with $v^*$, $\bar v$, $v_{\rm rms}$; Example 9.3, and Example 9.4's ±1% probability by numerical integration (0.0166).
- *Counting configurations (§9.5).* Two particles in up to five states, listed for distinguishable particles, bosons, and fermions.
- *Three distribution functions (§9.5).* Fermi–Dirac, Bose–Einstein, and Maxwell–Boltzmann with an adjustable chemical potential; Example 9.6.
- *Counting states in number space (§9.6).* The exact lattice count against $\tfrac13\pi r^3$.
- *The Fermi gas at finite temperature (§9.6).* $\mu(T)$ solved numerically, $F_{\rm FD}$ and $n(E)$, and $C_V$ against Sommerfeld's result; Examples 9.7 and 9.8.
- *When does a Bose gas condense? (§9.7).* $T_c$ for ⁴He (3.06 K vs the observed 2.17 K), the condensate fraction, and the degeneracy parameter of Example 9.9.
- *Two particles in a box (§9.7).* Densities for distinguishable particles, bosons, and fermions: bunching, antibunching, and the Pauli principle.

The page header is a gas of colliding disks whose speed histogram relaxes to the Maxwell distribution.

## Running locally

No build step and no dependencies. Clone the repository and open any HTML file in a modern browser:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

An internet connection is needed the first time for the web fonts and for [KaTeX](https://katex.org/) (loaded from jsDelivr), which typesets the equations. All simulations run offline in plain JavaScript.

## Publishing with GitHub Pages

1. Push the repository to GitHub.
2. Go to **Settings → Pages**, choose **Deploy from a branch**, and select `main` with the `/ (root)` folder.
3. The course home page will be served at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

## Repository layout

```
.
├── README.md
├── index.html                    # Landing page linking every chapter
├── ch02a-special-relativity.html                     # Chapter 2, Part 1 (§2.1–2.5)
├── ch02b-spacetime-and-relativistic-dynamics.html     # Chapter 2, Part 2 (§2.6–2.14)
├── ch03-experimental-basis-of-quantum-physics.html    # Chapter 3 (§3.1–3.9)
├── ch04-structure-of-the-atom.html                    # Chapter 4 (§4.1–4.7)
├── ch05-wave-properties-of-matter.html                # Chapter 5 (§5.1–5.8)
├── ch06-quantum-mechanics-II.html                     # Chapter 6 (§6.1–6.7)
├── ch07-hydrogen-atom.html                            # Chapter 7 (§7.1–7.6)
├── ch08-atomic-physics.html                           # Chapter 8 (§8.1–8.3)
└── ch09-statistical-physics.html                      # Chapter 9 (§9.1–9.7)
```

## Technical notes

- **Schrödinger solvers (Ch. 6):** split-step Fourier time evolution with radix-2 FFTs on a 1024-point grid with absorbing edges; finite-well energies by bisection on the even and odd matching conditions; oscillator states from the normalized Hermite recursion; barrier wave functions by matching $\psi$ and $d\psi/dx$ with complex arithmetic.
- **Hydrogen wave functions (Ch. 7):** radial functions from the generalized Laguerre recurrence and angular functions from the associated Legendre recurrence, each normalized numerically.
- **Rendering:** HTML5 canvas for every plot and animation, with a small built-in plotting helper; no charting library. Diagrams and simulations are original and do not reproduce textbook figures.
- **Animations:** time-based (not frame-based), deliberately slow, paused when off screen, and paused at start for visitors who prefer reduced motion.
- **Appearance of moving objects:** each point of a wireframe is placed at its retarded position, solving $c^2t_e^2 = x(t_e)^2 + y^2 + z^2$ for the emission time $t_e<0$, then projected through a pinhole camera.
- **Accessibility:** light and dark color schemes follow the operating-system setting; layouts reflow down to phone widths.

## References

- S. T. Thornton, A. Rex, and C. E. Hood, *Modern Physics for Scientists and Engineers*, 5th ed. (Cengage Learning).
- A. A. Michelson and E. W. Morley, "On the relative motion of the Earth and the luminiferous ether," *Am. J. Sci.* **34**, 333 (1887).
- A. Einstein, "Zur Elektrodynamik bewegter Körper," *Ann. Phys.* **17**, 891 (1905).
- A. P. French, *Special Relativity* (Norton, 1968).
- J. C. Hafele and R. E. Keating, "Around-the-world atomic clocks," *Science* **177**, 166 and 168 (1972).
- T. Alväger, F. J. M. Farley, J. Kjellman, and I. Wallin, "Test of the second postulate of special relativity in the GeV region," *Phys. Lett.* **12**, 260 (1964).
- W. Bertozzi, "Speed and kinetic energy of relativistic electrons," *Am. J. Phys.* **32**, 551 (1964).
- A. H. Compton, "A quantum theory of the scattering of x-rays by light elements," *Phys. Rev.* **21**, 483 (1923).
- R. A. Millikan, "A direct photoelectric determination of Planck's h," *Phys. Rev.* **7**, 355 (1916).
- E. Rutherford, "The scattering of α and β particles by matter and the structure of the atom," *Phil. Mag.* **21**, 669 (1911).
- N. Bohr, "On the constitution of atoms and molecules," *Phil. Mag.* **26**, 1 (1913).
- H. G. J. Moseley, "The high-frequency spectra of the elements," *Phil. Mag.* **26**, 1024 (1913).
- C. Davisson and L. H. Germer, "Diffraction of electrons by a crystal of nickel," *Phys. Rev.* **30**, 705 (1927).
- A. Tonomura, J. Endo, T. Matsuda, T. Kawasaki, and H. Ezawa, "Demonstration of single-electron buildup of an interference pattern," *Am. J. Phys.* **57**, 117 (1989).
- A. Kramida, Yu. Ralchenko, J. Reader, and NIST ASD Team, *NIST Atomic Spectra Database* (first ionization energies used in Chapter 8).
- J. Terrell, "Invisibility of the Lorentz contraction," *Phys. Rev.* **116**, 1041 (1959).
- G. D. Scott and M. R. Viner, "The geometrical appearance of large objects moving at relativistic speeds," *Am. J. Phys.* **33**, 534 (1965).

## Acknowledgments and disclaimer

These pages were created by Claude Opus 5.5 (Anthropic) based on Sang Hoon Lee's lecture notes on the textbook by Thornton, Rex, and Hood, for the undergraduate course Modern Physics (현대물리학) of the Department of Physics, Gyeongsang National University. The text is a paraphrase written for teaching; it does not reproduce the book, and this project is not affiliated with or endorsed by the authors or publisher.

## License

Choose a license before publishing; for course material a common pairing is [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) for the text and [MIT](https://opensource.org/license/mit) for the code.
