# Robot2021 Characterization

This repository contains the configuration and generated robot code for [Robot Characterization](https://docs.wpilib.org/en/stable/docs/software/wpilib-tools/robot-characterization/index.html), for our 2020/2021 robot.

## Usage
To generate a new project:
- Delete `characterization-project`
- Follow the instructions in the FRC docs to install the Robot Characterization Toolsuite.
- Run `frc-characterization drive new` to launch the new project GUI.
- Select this repository as the project location.
- Input the information from the comments at the top of [`robotconfig.py`](robotconfig.py) into the GUI. It is ordered from top to bottom, then left to right.
- Click *Read Config*.
- Click *Generate Project*.

For using the project and analyzing the results, please see the FRC docs.

To modify and run the generated code outside of the characterization tools, you must open the [`characterization-project`](characterization-project) subdirectory in VSCode, such that `build.gradle` is on the root, or else WPILib will function correctly.
