# Pure Data Modules

This repo hosts modules (abstractions) developed using Pure Data. The modules are organized into three categories:

* Audio: modules that alter audio in the signal chain and I/O. Some examples are effects, mixer utilities, or channel strips.
* Control: modules that alter or control parameters of other modules, like an envelope generator, or an amplifier.
* Synth: modules that make sound or are closley related to modules that make sound. Examples would be a noise generator, oscillator, sampler, etc.

## Installation

1. Clone this repo into your root Pd folder

```shell
cd ~/Documents/Pd
git clone [this repo] modules
```

2. Add the newly-cloned modules to your path settings in Pure Data

## Usage

Each module can be targetted by it's namespace and filename. Example, if there is a module in the `audio` folder called `reverb~.pd`, you should create an object with the name `[audio/reverb~]`.
