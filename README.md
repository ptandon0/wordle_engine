# wordle_engine
A simple wordle solving engine based on entropy and word frequency, inspired by a popular [3b1b video](https://www.youtube.com/watch?v=v68zYyaEmEA), and made for fun.
Currently written as an interactive jupyter notebook you can run on colab.

To use open the notebook, run all the cells, and in the last cell enter your guesses as directed in the comments.

The wordle color checking algorithm currently doesn't perfectly handle cases when two or three of the same letter appear, which is why the calcualted entropies don't exactly match those in the video, but it seems to work well enough in a relative sense to rank the guesses.

Currently to generate a score combining entropy and word frequency we just add the two. While I'm suprised how well it works, maybe one day a more sophisticated strategy will be implemented.
