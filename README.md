Problem Statement I

Problem Statement:
Estimate the occurrence of a supermoon using the ephemeris data for the moon.
Input:
Ephemeris data for the moon, including the moon's distance from Earth (perigee distance) and its phase age.
Output:
A prediction of the occurrence of a supermoon, based on the following criteria:
• A supermoon occurs when the full moon is at or within 90% of its perigee distance.
• The moon should also be the brightest at that point in time.
Evaluation:
The performance of the code would be evaluated by comparing its predictions to the actual occurrences of
supermoons.
Potential Applications: 
This model could be used to help astronomers and photographers predict the occurrence of supermoons, so
that they can plan their sessions accordingly.

Problem Statement II

Problem Statement: 
Use machine learning to classify galaxies into three types (ellipticals, spirals, or galactic mergers) based on their
observed properties: color index, adaptive moments, eccentricities, and concentrations.
Evaluation:
Use held-out validation to evaluate the performance of the model. Split the data into a training set and a test set. Train the model on the training set and predict the galaxy type for each galaxy in the test set. Compare the
predicted galaxy types to the actual galaxy types in the test set to calculate the accuracy of the model.
Constraints: 
The model must be able to generalize to new data, meaning that it should be able to predict the type of a
galaxy accurately even if it has not seen the data for that galaxy before.
Potential Applications:
• This model could be used to help astronomers classify galaxies in large datasets of astronomical
images.
• It could also be used to study the evolution of galaxies by tracking their type over time.

Problem Statement III

Problem Statement:
Predict whether an object is a star or not, and if it is a star, classify its type, using a CSV file obtained from
Sloan Digital Sky Survey (SDSS) photometric data.
Objective:
To develop a machine learning model that can accurately predict whether an object is a star or not, and if it is
a star, classify its type, using only its photometric data.
Input:
A CSV file containing the spectra of objects, along with their labels (star or not).
Output: 
A prediction for each object in the 80:20 split input file, indicating whether it is a star or not, and if it is a star,
its type. (Split the given dataset and use 80% of it for training and 20% of it for testing)
Potential Applications:
• This model could be used to help astronomers identify stars in large datasets of astronomical images.
• It could also be used to study the evolution of stars by tracking their type over time.
