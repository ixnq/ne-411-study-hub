# NE-411 Study Site Quality Check

## Uploaded Materials Covered

- `Reactivity_Lecture_Notes.docx`
  - Introduction to reactivity
  - Units: delta-k/k, pcm, dollars, cents, inhour
  - Small-reactivity approximations and prompt/delayed regimes
  - Control rods, differential/integral worth, rod shadowing, shutdown margin
  - Chemical shim and boron worth
  - Reactivity coefficients overview
  - Fuel temperature/Doppler coefficient and Doppler defect
  - Moderator temperature coefficient
  - Void coefficient
  - Summary comparison tables
  - Practice problems

- `Point Kinetics Analytical_lecture Note.docx`
  - Delayed neutron motivation
  - One-group approximation
  - U-235 delayed neutron data
  - One-group point kinetics equations
  - Matrix/eigenvalue method
  - One-group inhour equation
  - General analytical solution
  - Prompt jump/drop approximation
  - Zero reactivity and prompt critical cases
  - Worked numerical examples
  - Six-group extension
  - Summary formulas
  - Practice problems

## Figures Covered

All embedded figures were extracted and included:

- Doppler effect on resonance escape probability and reactivity
- Doppler broadening of the U-238 capture cross section
- One-group inhour roots and reactivity regimes
- Prompt jump/drop behavior
- Six-group inhour equation

## Formula and Definition Coverage

Included formulas were cross-checked against paragraph text, tables, and Word equation objects, including:

- Reactivity: `rho = (k_eff - 1) / k_eff`
- pcm, dollars, cents
- Small-reactivity period approximation
- Inhour relation
- DRW, IRW, shutdown margin
- Reactivity coefficients
- Doppler, MTC, void feedback
- One-group PKE equations
- Steady-state precursor concentration
- One-group inhour quadratic
- Eigenvalue roots
- General two-mode solution
- Prompt jump/drop
- Six-group inhour equation

## Improvement Pass

- Added a stronger overview dashboard with readiness scoring.
- Added study path cards with timing, aim, and progress.
- Added recommended next topic logic based on the selected path and completed topics.
- Added quick jump actions for detailed notes, formulas, MCQs, and cheat sheet.
- Improved progress bars, topic cards, focus states, and mobile layout behavior.
- Regenerated `single-file.html` so the shareable version matches the upgraded site.

## Content Cleanup

- Removed document headers, separators, and author/date footer text from the learning flow.
- Corrected the likely duplicated exponent typo in the extracted general solution so the second neutron term uses `e^(omega_2 t)`.
- Preserved important numbers and table ranges from the notes.
- Added explanations for common mistakes that follow directly from the lecture content.

## Checks Run

- Parsed HTML structure.
- Checked inline JavaScript syntax with Node.
- Verified extracted image references resolve.
- Verified study-path topic IDs resolve.
- Regenerated the embedded single-file HTML version.

## Browser QA Note

The user has the site open in the in-app browser at:

`file:///C:/Users/PC/Documents/NE-411/Final%20Exam/index.html`

In this sandbox, direct browser-control tools were not exposed through tool discovery, and local headless Chrome/Edge previously failed because crashpad could not start under Windows sandbox permissions. Static and syntax checks passed, but visual review should be done in the open in-app browser.
