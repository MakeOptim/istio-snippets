# istio-snippets

Code snippets of istio for visual studio code.

## Features

- [x] DestinationRule
  - [x] Circuit-Breaking: Circuit Breaking DestinationRule
- [x] VirtualService
  - [x] Canary: Canary Deployments VirtualService
  - [x] Mirroring: Mirroring Traffic VirtualService
  - [x] Fault-Injection-HTTPStatus: Fault Injection (HTTPStatus) VirtualService
  - [x] Fault-Injection-Delay: Fault Injection (Delay) VirtualService
- [x] ServiceEntry
- [x] Gateway
- [x] See more comment

## Requirements

- `apiVersion: networking.istio.io/v1alpha3`

## Usage

Enter the CRD name in the yaml file and the corresponding code snippets will appear.

The following uses DestinationRule and VirtualService as examples to show how to use.

### DestinationRule

![DestinationRule](https://raw.githubusercontent.com/MakeOptim/istio-snippets/master/images/DestinationRule.gif)

### VirtualService

![VirtualService](https://raw.githubusercontent.com/MakeOptim/istio-snippets/master/images/VirtualService.gif)