# The WebFX project

## The goal 

The goal of the WebFX project is to build a **JavaFX transpiler**, the last missing piece of the puzzle to offer to Java developers a **fully cross-platform** UI toolkit targeting all major platforms (desktops, mobiles & web) from a single source code. 

<p align="center">
  <img src="https://docs.webfx.dev/webfx-cross-platform.svg" />
</p>

## For what kind of applications?

Although most of the demos made so far are mainly graphical applications, the real target of the project is **Enterprise applications**. We aim to provide a complete **ecosystem** for WebFX, that will allow developing Enterprise level applications such as systems with back-office, front-office & backend. We are clearly heading in that direction, the WebFX project being now closely related to the [Modality project](https://github.com/modalityproject/modality), the first real-world Enterprise application built on WebFX. These 2 points are developed in the next sections below.

## The WebFX ecosystem

Although the WebFX Kit is the very heart of the project, there are other important repositories that all together form the WebFX ecosystem:

<p align="center">
  <img src="https://docs.webfx.dev/webfx-project/webfx-ecosystem.svg" />
</p>

* The [WebFX Kit](webfx) is a patched version of OpenJFX that can be transpiled by GWT together with WebFX applications.
* The [WebFX CLI](webfx-cli) is the tool assisting developers to build WebFX applications.
* The [WebFX Platform](webfx-platform) is our foundation layer & API for cross-platform development.
* [WebFX Libs](https://github.com/webfx-libs) is a space for hosting existing JavaFX libraries ported for WebFX, or brand new WebFX libraries.
* [WebFX Extras](webfx-extras) is a collection of extra JavaFX controls such as data grid, grant view, etc...
* The [WebFX Stack](webfx-stack) is a collection of pieces of framework for enterprise applications.

*Each link above goes to the corresponding GitHub repository which will provide you with more detailed information.*

Typically, a graphical application will use the WebFX Kit (the covered JavaFX API), and eventually some WebFX libraries (like we did with most of the demos). An Enterprise application will in addition use the WebFX Stack and WebFX extras.

## Relation with Modality

The current development of WebFX is now mainly supported by [Modality](https://github.com/modalityproject/modality), another open-source project on GitHub (*click on the link to know more about it*). Modality will be the first Enterprise level application based on WebFX. These 2 projects are supporting each other. WebFX provides the 100% Java full-stack cross-platform solution Modality was looking for, and Modality 
is the main contributor to the WebFX Stack and WebFX Extras repositories. It will also greatly help the WebFX project by demonstrating its capabilities for Enterprise level applications.
