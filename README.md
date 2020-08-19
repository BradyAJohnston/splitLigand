# toLigands

Script to take output from gromacs `trjconv` function that spits out
the protein+RNA in the same chain, and split them into multiple chains.

Importantly works on multi-frame files, returning a multi-frame .pdb with correctly split
protein and RNA into different chains (A + B).

Mostly utilises the [`pdb-tools`](http://www.bonvinlab.org/pdb-tools/) set of python tools.
