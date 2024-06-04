# prokaryo

I've always been mesmerized by those animations of [DNA Transcription](https://www.youtube.com/watch?v=-AnsJILjbz8),
and have dreamed of building my own "simulation models" to help me understand complex biology processes.
I did some research to see if anyone has worked on something like this before, and found this paper from 2015:
[PROKARYO an illustrative and interactive computational model of the lactose operon in the bacterium *Escherichia coli*](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-015-0720-z).
It looks like they released some visualization software, and the paper has a lot of good biology background and
details to reference. In the **Methods** section, they mention some other familiar projects to look into.
The goal here isn't to accurately simulate real processes that would require super quantum computers, but to
try and simulate models that can be tweaked to mimic and appear like real processes. I think there's a lot of
value in turning a text wall of biology jargon into a 3d animation that a lay person can start visualizing
and reasoning about.

Just some napkin paper math, wikipedia says an *E. coli* cell is about 0.7 micrometers cubed; wolfram alpha
tells me that `2.333e10` water molecules would fit in that at standard temperature and pressure. Multiply that
by 12 for 3 32-bit positional vectors, a single frame of a molecular dynamics simulation would only take up
exactly 280 GB! That could fit on most consumer computing devices and is smaller than the bitcoin blockchain!
Although simulating an entire cell would be a bit more complicated than just water molecules browning around,
but these are just some numbers to give some sort of sense of scale. Not to mention that accomplishing any
meaningful biological processes would require many magnitudes of molecular dynamic frames, and would quickly
get out of hand. Hence the goal of building models and abstractions to help comprehend these massively complex
processes!
