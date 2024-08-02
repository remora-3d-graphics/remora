# README


## How to use

1. Run a Geant4 server using Docker (instructions [here](https://hub.docker.com/r/remora3d/g4-demo))

2. Install Remora on your computer and open the executable

3. Control the Geant4 server and watch the Remora client respond. The commands to be passed into the Geant4 app are:

```
/remora/sendDetectors
/remora/removeShapeWithName <beginning of shape's name>
/remora/changeColor <r> <g> <b>
```
