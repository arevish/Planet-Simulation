# Planet Simulation ![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)

![python License](https://img.shields.io/badge/MADE%20WITH-Pygames-green.svg)

This planet simulation is Made Using Python3 & Pygame Module.
Goal of this is to simulate the orbit of different planets around the sun. we're going to use real astroniomical values like the real mass of the sun and other planets, real distance from Earth to the sun. and we are going to apply the force of gravity between all of the different planets, so we actually get an accurate elliptical orbit.

also we are going to write the distance of the planet to the sun on each planet, so we can see how it's changes as we go around the orbit.

Hope You Will Like The project. also u can use the code to make your own version of simulation by adding other planets

###  DEMO 

<!-- ![PlanetSimulation](https://user-images.githubusercontent.com/91308138/161219844-96994df6-8c76-4c35-9648-c0140b37562c.gif) -->

PLEASE FEEL FREE TO FORK THE PROJECT AND START CONTRIBUTING. :)

### Code Discussion
The system described in the code consists of the Sun, Earth, and Venus, so the main() function creates three Body instances for each body and passed to the loop() function.

The loop() function is the heart of the simulation, taking a list of Body instances and then performing simulation steps forever. The time step chosen is one day, which works well for our Sun/Earth/Venus example. When you run the program, you can see how long it takes for the plot to complete an entire orbit; for Earth it’s the expected 365 days and for Venus it’s 224 days.

## PRE-REQUISITES
Your laptop with python 3.6.x (onwards) installed.

**NOTE:** Those with Linux and MacOSX would have Python installed by default, no action required.

Windows: Download the version for your laptop via https://www.python.org/downloads/

**NOTES**
In your preferred editor, make sure indentation is set to "4 spaces".

* Make sure you have **pygame** installed in python otherwise code may fail, to install pygame in your machine > open python in your terminal then type `pip install pygame` to install. :warning:

---

## Run using Python3.8+
1. Clone or download repositiory: https://github.com/arevish/Planet-Simulation.git
2. In source folder, run `python3 'main.py'` to start program, optionally, run with `--help` argument to see other runtime options.

### ThankYou!