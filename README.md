# JavaScript Self Driving Car 🚗

_A code along from freeCodeCamp's [Self-Driving Car with JavaScript Course – Neural Networks and Machine Learning](https://www.youtube.com/watch?v=Rs_rAxEsAvI&t=8339s) video._

_Many thanks to [Dr. Radu Mariescu-Istodor](https://radufromfinland.com) for creating this course!_

---

## Instructions

-   Visit the [deployed site](https://glowing-gelato-faf834.netlify.app/)
-   100 random cars will begin to move. The goal is to get the car to 'learn' how to navigate past the traffic.
-   The vast majority will initially fail / crash, but if there is a car that does relatively well and makes it past the first car, you can 'Save' to use this car's neural network as a basis for the next set of 100 cars when you refresh the page.
-   'Discard' will start a fresh and will use a random neural network configuration again.

---

## Logic

-   This course creates and visualises a neural network used to direct the car.
-   Sensors from the front of the car work by ray casting and detect the road barriers and the neighbouring cars using a segment intersection formula.
-   We improve the neural network of the car by trial and error with parallelisation added to speed this process up.
-   A basic genetic algorithm is added to optimise faster.
-   The best neural network can be saved and can be mutated and used as a basis for the next iteration.

---

### Future Features

-   Dynamically generate more traffic.
-   Allow users to be able to set the number of car iterations.
-   Allow users to be able to set how much to mutate the neural network.
