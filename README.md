# Zeta Zeros (Critical Line Mix)

The zeros of the Riemann zeta function, played as techno, one after another, forever. Every lead note is a real zero, found in the browser just before it plays. It never loops. The maths decides when the drop hits.

## How it works

- The spiral traces ζ(½ + it) as t climbs. Each pass through the centre is a zero.
- Each lead note is one zero, in order, starting at 14.1347.
- The normalized gap to the next zero, δ = Δγ · ln(γ/2π) / 2π, sets the melody step (wider than average steps up, tighter steps down) and the note length.
- When max |ζ(½ + it)| between two zeros is in the top 8% of the last 250 loops, it arms a build-up and drop.
- The mood buttons change the five-note scale. The zeros, rhythm and drops stay the same.

Zeros are found from sign changes of the Hardy Z-function, using Euler–Maclaurin summation below t = 200 and the Riemann–Siegel formula above.

## Honest label

This is a sonification of the zeros. It is not a proof of anything and is not affiliated with any claimed proof of the Riemann hypothesis. The scale, drums, tempo and the gap-to-note rule are artistic choices.

## Run it

Open `index.html` in a browser. No build step, no dependencies. All sound is synthesized with the Web Audio API.
