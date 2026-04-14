# Zmniejszanie błędu pozycji przy pomocy RL na robocie honeybadger

## Opis
Projekt ma na celu wytrenowanie modelu RL do estymacji macierzy kowariancji filtru Kalmana, aby poprawić dokładność estymacji pozycji robota kroczącego hb40 w dłuższym horyzoncie czasowym.

## Narzędzia
- Mujoco
- ROS2
- [SB3](https://stable-baselines3.readthedocs.io/en/master/)

## Cele
 1. Zebranie danych do nauczania modelu.
 2. Zmniejszenie błędu estymacji pozycji względem bazowego filtru Kalmana stosowanego na robocie.

## Bibliografia
 - [Learning robust perceptive locomotion for quadrupedal robots in the wild](https://arxiv.org/pdf/2201.08117)
 - [Robust Legged Robot State Estimation Using Factor Graph Optimization](https://www.robots.ox.ac.uk/~mobile/Papers/2019RAL_wisth.pdf)
 - [Robust Localization, Mapping, and Navigation for Quadruped Robots](https://www.ias.informatik.tu-darmstadt.de/uploads/Team/NicoBohlinger/quadruped_localization1.pdf)
 - [Learning dynamics models for velocity estimation in autonomous racing](https://ieeexplore.ieee.org/document/10802481)
