# Zeta Zeros (Critical Line Mix)

What the Riemann zeta function sounds like as techno. Live at https://heheok.github.io/the-riemann-zeros/

## What is this?

The zeta function has special inputs where its answer is exactly zero. This page finds those zeros one at a time, in your browser, and plays a note for each. It never loops, because there are infinitely many of them.

- **The swirl** is the function's answer drawn as a moving dot. Each time it crosses the middle, that's a zero and you hear a note.
- **The melody** comes from the spacing. A longer wait than usual for the next zero makes the tune step up and hold. A shorter wait makes it step down and hurry.
- **The drops** happen when the curve swings unusually far out between two zeros (bigger than 92% of the last 250 loops).

## For the nerds

Zeros are found from sign changes of the Hardy Z-function: Euler–Maclaurin summation below t = 200, Riemann–Siegel above. The melody step is round(4(δ − 1)) clamped to ±3, where δ = Δγ · ln(γ/2π) / 2π is the normalized gap. The first 10,000 zeros match published tables.

## Small print

The zeros are real maths. The drums, scale, tempo and the gap-to-note rule are choices made so it sounds good. It doesn't prove anything and isn't connected to anyone's proof.

## Run it

Open `index.html`. One file, no dependencies, all sound made with the Web Audio API.
