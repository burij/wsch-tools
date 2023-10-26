# SunVox
[*SunVox* ](https://warmplace.ru/soft/sunvox/)is a small, fast, and powerful modular synthesizer with a pattern-based sequencer (tracker). It is a tool for those people who like to compose music wherever they are, whenever they wish. On any device. On any system. And it's free for most of the systems, except Android and iOS.

# Philosophy

We're trying to create multi-purpose modules, with a consistent controller paradigm, which are easy to use. The usability of our modules is improved by creative decisions, which are reducing controlling options, defining usable parameter ranges, and improving faster workflows.

# General

This repository contains development versions of custom modules, which were developed by techno label from Berlin, *Weddinger Schule*.

You can find additional documentation and release versions of some of them on the [label website](https://label.weddinger-schule.de/category/tools/).

# Content

The root folder of the repository contains module packs: metamodules packed in a metamodule for easy adding to the project.

The file *wsch module development rr.sunvox* is a work-in-progress project, which contains the latest version of all the modules, which are in active development right now.

All the single modules are stored in the following folders:

- *effects*: audio signal manipulation like delays, distortions, etc.
- *instruments*: signal generators
- *tools*: modules, which can't be easily put in one of the above categories, mostly workflow helpers and midi-generators

## Effects

### Architect

This patch is the third official reverb from our label. The Reverb Studio module was initially designed to replicate the functionalities found in commercial DAWs but proved to be resource-intensive on the CPU and challenging to master. In contrast, Space took a simpler and lighter approach, offering user-friendly features with straightforward patching.

Architect, our latest creation, represents a harmonious fusion of these two approaches. It has evolved beyond being a mere clone, shedding some of its features to enhance usability and optimize CPU utilization. However, it undeniably excels in its capability to craft the desired virtual spatial experience.


The fundamental concept revolves around the distinction between the early reflection and diffusion aspects of the reverb, granting you the ability to effortlessly tailor, customize, and blend these elements. Remarkably, both sections can be pushed to their limits, resulting in the generation of artifacts and unconventional spatial effects. This unique quality proves invaluable, particularly for creators within the realm of underground and experimental genres.


## Instruments

### Virgin

This is not a genuine modular pitch, but rather an initialization preset designed for the FMX module. Several compelling reasons support the existence of this module. While the default preset for FMX yields satisfactory results, it may not be the optimal starting point for FM sound design from scratch. Additionally, encapsulating FMX within a metamodule streamlines the complex user interface, rendering it more accessible.

The metamodule controllers at the top level encompass approximately half of all FMX module controls, enhancing user ease of access. Moreover, they have been organized on an oscillator-by-oscillator basis rather than a function-by-function approach, which is more intuitive for sound design in many cases.

The default algorithm for Virgin is 3 -> 4 -> 5 + 1 -> 2. This algorithm is highly versatile, incorporating numerous widely-used algorithms.
