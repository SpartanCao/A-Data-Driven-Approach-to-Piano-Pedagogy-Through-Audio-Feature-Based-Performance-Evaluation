# A Data-Driven Approach to Piano-Pedagogy Through Audio Feature-Based Performance Evaluation
Official implementation of the piano performance analysis system from "A Data-Driven Approach to Piano Pedagogy Through Audio Feature-Based Performance Evaluation" by Vincent Cao.

## Running the program
To run the program, simply access the provided Jupyter Notebooks and run the cells. It's highly recommended to use the sample files given in the repository for controlled testing purposes, but any given piano recording will work just fine. Do note that the code in the Notebooks assumes the user is importing the file from Google Drive. If you would like to host the files locally, you can modify the code and provide the path to the files in the setup cells.

## Data
The audio files used in the paper are all uploaded into the `sample_audio` directory of this repository. Each piece has its own folder containing the recordings. Each piece also has a file titled `BEATLOC.xlsx`, which contains the manually annotated beat locations for each piece. For the Bach and Chopin, the annotations are based on the files with `OG` in their names. For the Prokofiev, the annotations are based off of the file titled `GAVRILOV.wav`
