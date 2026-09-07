# Blind Comparator

Two blind listening tests for electric guitars, built on the sound samples Thomann
publishes on its product pages. Audio is streamed from Thomann's servers and is their
copyright; nothing is redistributed here. Needs an internet connection.

## The five-way test — `/`

Ten instruments drawn at random from 275, all their factory clips, five candidates each
round — always from the same maker, with Epiphone counted as Gibson and Squier as Fender,
and each Harley Benton or Larry Carlton grouped with whatever its model copies, so the
badge gives nothing away.

Scored against chance with an exact binomial test: guessing averages 2/10, and 5/10 is
where the result stops being explainable by luck. The report also totals how far your
picks sat above or below the price of the guitars actually playing.

## The A/B test — `/price/`

Twelve rounds. Each puts the same riff through an expensive guitar and a cheap equivalent
of the same body style, and asks which clip is which. Prices are shown; a coin flip
averages 6/12 and 10/12 clears significance.

## A caveat worth knowing

Thomann's clips are **not** reamped — their own per-clip flag says so on 1519 of 1522
clips — and each product was recorded on its own rig, with 17 different amplifiers across
the set. Two clips sharing a riff name are not automatically a fair comparison: only about
45% of same-riff pairs share an amplifier.

The A/B test therefore pairs a guitar only with one that played the same riff through the
same amp, and within 10 seconds of the same length — a wider gap than that means it is not
really the same performance (the worst was 60 seconds apart). That leaves 771 usable pairs.
Both pages show each clip's full recording chain
— effects, amp, cab, mic, preamp, interface, software — behind the info button on the clip
row, so you can check for yourself.
