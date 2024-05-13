# My Bachelor Thesis

This Repository is meant to be the central point for managing and linking the currently growing number of repo's, data and other sources of my bachelor thesis.


## Unreal Engine Plugins
- [URoboSim](https://github.com/ManuETR/URoboSim)
- [UROSBridge](https://github.com/ManuETR/UROSBridge)
- [URoboVision](https://github.com/ManuETR/URoboVision)
- [UROSWorldControl](https://github.com/ManuETR/UROSWorldControl)
- [UUtils](https://github.com/ManuETR/UUtils)
- [UTFPublisher](https://github.com/ManuETR/UTFPublisher)

### Links
- [Naming Convention](https://dev.epicgames.com/documentation/en-us/unreal-engine/epic-cplusplus-coding-standard-for-unreal-engine)
## Robotic models
- [robotic-models](https://github.com/ManuETR/robotic-models)
- [cogimon-gazebo-models](https://github.com/corlab/cogimon-gazebo-models/tree/master)


## Testing
The final simulation enviroment should also be able to return the test information / simulation results. For this not only feedback from Unreal Engine is needed but also the data what is published within the topics should be logged.
As datasink seq should be used. This application runs within an docker container.
[docker image](https://hub.docker.com/r/datalust/seq)

### Idea
The idea is, that the different components can send information that should be logged via a websocket to the seq instance.

In the end a service should subscribe to the topics and forward them to seq.
