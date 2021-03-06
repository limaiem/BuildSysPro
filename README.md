# BuildSysPro open source
*BuildSysPro open source* is [EDF](http://researchers.edf.com/edf-researchers-209799.html)'s Modelica library for buildings, districts and energy systems modelling. This is BuildSysPro's official repository.

### Release updates
Current release is version 3.1.0.

This release provides :
- improvements in *Systems.DHW.Electric.WaterTank* model to allow a prescribed or fixed cold water temperature
- correction of an error in the *Meteofile* : a one-hour delay was observed between sun height and solar irradiance data for *RT2012* meteo. **Warning :** this error had an impact on simulation results, be careful if you ran simulations with *RT2012* meteo.
- other minor error corrections

EDF is part of [IBPSA Project 1](https://ibpsa.github.io/project1/), and the [IBPSA library](https://github.com/ibpsa/modelica-ibpsa) is now integrated to BuildSysPro open source 3.1.0.

BuildSysPro open source 3.1.0 is compatible with OpenModelica 1.9.3. When working with OpenModelica, specify your initial conditions carefully and use preferably Dassl, Euler or Runge-Kutta solvers.

### License
The BuildSysPro open source library is licensed by EDF under the [Modelica License Version 2](https://www.modelica.org/licenses/ModelicaLicense2).

### References
1. Plessis G., Kaemmerlen A., Lindsay A. (2014) [BuildSysPro: a Modelica library for modelling buildings and energy systems](https://www.modelica.org/events/modelica2014/proceedings/html/submissions/ECP140961161_PlessisKaemmerlenLindsay.pdf). Modelica Conference 2014.
2. Schumann M. (2015) [Vers une plate-forme de modélisation du bâtiment au quartier multiphysique avec Modelica et BuildSysPro](http://ibpsa.fr/jdownloads/Simurex/2015/Presentations/29_01_mathieuschumann.pdf) (*Towards a multiphysics modelling platform for buildings and districts with Modelica and BuildSysPro*), IBPSA France SIMUREX 2015 Conference.
