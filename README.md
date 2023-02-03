# SIADS 694 & 695 - Milestone II

Supervised and unsupervised machine learning using asteroid data (close-approaches of small bodies) from the Jet Propulsion Laboratory.

## Project Summary
Asteroids are small, metallic or rocky bodies without atmospheres that orbit the sun and come in various sizes and shapes. They formed from collisions of proto-planets in the early solar system and contain valuable information about our solar system's origins and the evolution of life on Earth. Over 1 million asteroids have been identified, but many more remain undiscovered, and they may contain rare minerals and organic compounds. Asteroids are also of interest because of the potential danger they pose if they collide with Earth, and their study using machine learning models can help predict their trajectories and better prepare us for future encounters.

The project on predicting potentially hazardous asteroids (PHAs) using supervised learning methods produced models that can predict PHAs significantly better than a dummy classifier. The models' accuracy suggests that the likelihood of an asteroid coming close to Earth may be a function of its characteristics, such as diameter and velocity, contradicting initial intuition. The importance of properly cleaning, pre-processing, and splitting the data for training the models was emphasized, as human discretion and the possibility of error in these processes can affect the validity of the models. Using undersampling instead of oversampling was also crucial in avoiding data contamination. The results of the project are limited by knowledge and experience and would benefit from external perspectives.

## Data source (API)
https://ssd-api.jpl.nasa.gov/doc/cad.html
