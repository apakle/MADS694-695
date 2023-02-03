# SIADS 694 & 695 - Milestone II 
# Close Encounters: A Study of Small Body Trajectories in Our Solar System

Supervised and unsupervised machine learning using asteroid data (close-approaches of small bodies) from the Jet Propulsion Laboratory.

By Andre Kleber, Trevor McCalmont, & Julien Weinstein

## Project Summary
Asteroids are small, metallic or rocky bodies without atmospheres that orbit the sun and come in various sizes and shapes. They formed from collisions of proto-planets in the early solar system and contain valuable information about our solar system's origins and the evolution of life on Earth. Over 1 million asteroids have been identified, but many more remain undiscovered, and they may contain rare minerals and organic compounds. Asteroids are also of interest because of the potential danger they pose if they collide with Earth, and their study using machine learning models can help predict their trajectories and better prepare us for future encounters.

Using supervised learning methods we produced models that can predict potentially hazardous asteroids (PHAs) significantly better than a dummy classifier. The models' accuracy suggests that the likelihood of an asteroid coming close to Earth may be a function of its characteristics, such as diameter and velocity, contradicting initial intuition. A key learning from creating the supervised models was the importance of appropriately cleaning, pre-processing, and splitting the data for training the models, as human discretion and the possibility of error in these processes can affect the validity of the models. Using undersampling instead of oversampling was also crucial in avoiding data contamination. The results of the project are limited by our knowledge and experience and would benefit from external perspectives.

The primary outcome of using unsupervised learning methods on the asteroid data set was disappointing, as clustering did not provide valuable insights. The variables in the original data set were mainly size and velocity, which made it challenging to find unique insights about the asteroids. In a more ideal scenario with more time and resources, additional data points or data sets with more information about the asteroids would be sought, but collecting such data would be nearly impossible.

## Data source (API)
https://ssd-api.jpl.nasa.gov/doc/cad.html
