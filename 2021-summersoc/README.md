# SummerSOC 2021 Prototype

This use case shows how to specify Quantum4BPMN workflow models independent of a quantum computer by using a *QuantumHardwareSelectionSubprocess*.
The quantum computer is then automatically selected during workflow runtime, and the QuantME modeling constructs within the QuantumHardwareSelectionSubprocess are dynamically replaced by suitable workflow fragments based on the selected quantum computer.

The following figure shows a workflow model implementing Simon's algorithm:

TODO

## Setting up the Environment

Next, we will discuss the steps required to set-up the environment to model and execute the workflow model.

### Running the QuantME Transformation Framework

First, build and run the [QuantME Transformation Framework](https://github.com/UST-QuAntiL/QuantME-TransformationFramework):

1. Clone the repository using release v1.2.0: 
```
git clone  git@github.com:mygitname/theproject.git --branch v1.2.0
```
2. Change to the cloned folder and build the modeler:
```
npm install
npm run build
```
3. The build product can be found in the ``dist`` folder and started depending on the operating system, e.g., using the ``.exe`` for Windows

The QuantME Transformation Framework can be configured on start-up by passing in corresponding environment variables. 
However, we will update the configuration using the graphical user interface:

TODO

### Running the OpenTOSCA and QuAntiL Components

TODO