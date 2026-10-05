# interactor-hailo-ugen300

Shelved apparatus for running models on a USB neural accelerator: a runtime shim, compiler probes and small compiled models.

## What it is for

It holds what re-running the accelerator measurements needs: a flat C bridge over the device runtime, the vision-encoder export and compiler scripts, the quantisation probes, and compiled models small enough to keep. What was measured, and the condition for reopening the work, is in the logbook entry `logbook-qwen3vl-vit-translate-walls.md` in `manuals-weftspun`. The large artifacts are in a private model repository, <https://huggingface.co/chibifire/hailo-ugen300-artifacts>.

## Build and run

There is no build file. The shim compiles against the accelerator vendor's runtime SDK, and the Python probes run against the device through it.

## Licence

The licence is not stated.
