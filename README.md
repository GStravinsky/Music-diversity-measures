# Music-diversity-measures
Spotify project to create and test various diversity measures to estimate how diverse a user playlist is.

Statistical as well as geometrical diversity measures are analysed and the analysis is available under `Writeup` folder. `Notebooks` contain all the code used in the analysis:

- `NonHierachicalEntropies` - implements Shannone entropy, Kullback-Leibler divergence, Gini-Simpson index and Hill number to estimate the diversity and analyses the features of these measures.
- `NonHierarchicalEntropies` - implements the same statistical measures on the artist level data.
- `GeometricalMeasures` - examines Generalist-Specialist score as well as TS-SS and the features they posses in examining the diversity of the playlist
- `RecommenderAlgorithm` - Shows the chosen measures in action by trying to estimate how well the measures predict the songs in the user's playlist in the out-of-sample manner.

Thai main `triplets_train.txt` data is available [here](http://millionsongdataset.com/tasteprofile/). The vectorised version of songs is attached [here](https://drive.google.com/file/d/1IYkgPZpxgGeazeUoNQDje58MTMkLazsr/view?usp=sharing).