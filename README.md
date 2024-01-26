# maximumdiversityindex

The notebook `index_diversity.ipynb`contains R code to get the *n* most dissimilar sequences of a concrete length for a given set of sequences.

## Usage

The user can go to **Google Colab** and open a notebook in the File section, click the **GitHub** option, paste the URL of this repository and click in the search button followed by clicking `index_diversity.ipynb`. Then, the user just have to upload a `.csv` file with at least two columns containing (i) the ID of each sequence and (ii) the sequences themselves. An already-computed demostration can be visualized just by clicking in the notebook file on this repository.

## Limitations

Computational efficiency of the `maximumdiversityindex()` function could be improved. Also, the algorithm is properly an approximation to solve the problem, but not a perfect solution. Even though the algorithm is built for evaluting the global diversity between combinations of sequences, the maximization of the total dissimilaty should tend towards the maximization of the local diversity, i.e. the diversity of nucleotides in each position.

## Contributors

- **Pedro Sánchez-Sánchez** is currently (January 2024) a PhD student in the Quantitative Stem Cell Dynamics laboratory led by Alejo Rodríguez-Fraticelli (ICREA - IRB Barcelona).
- **Freddy Monteiro** is manager of the Functional Genomics Core Facility (IRB Barcelona).

Freddy posed the question that Pedro later tried to solve with the algorithm within the `maximumdiversityindex()` function. Pedro also developed the rest of the code and created the Jupyter notebook to be easily accessible to the user by running it on Google Colab.

