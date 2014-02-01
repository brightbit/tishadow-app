# Brightbit's TiShadow App

The TiShadow app we deploy to our devices. It has TestFlight and ti.map modules included.

Based on software versions:

```
TiShadow: 2.5.1
Titanium: 3.2.0.GA
TestFlight: 2.2.0
```

## Installation

Install Titanium, Titanium SDK and TiShadow:

```sh
npm install -g titanium tishadow
ti sdk install -d 3.2.0.GA
```

Build and install on your device (this will install it on all connected devices):

```sh
ti build -p ios -T device -C all
```
