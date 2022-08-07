# The WebFX project

## The goal 

The goal of the WebFX project is to build a **JavaFX transpiler**, the final missing piece of the puzzle to offer Java developers a **fully cross-platform** UI toolkit targeting all major platforms natively (desktops, mobiles & web) from a single codebase, with [Gluon](https://gluonhq.com/) already providing solutions for platforms other than the web. 

<p align="center">
  <img src="https://docs.webfx.dev/webfx-cross-platform.svg" />
</p>

## For what kind of application?

Although most of the demos made so far are graphical applications, the actual goal is to support **Enterprise applications**, for which we aim to provide a complete WebFX **ecosystem**. We are rapidly heading in that direction, and WebFX is now closely tied to the [Modality project](https://github.com/modalityproject/modality), the first real-world Enterprise application built on WebFX!

## The WebFX ecosystem

Although the WebFX Kit is the very heart of the project, there are other important repositories that together comprise the WebFX ecosystem:

<div align="center">
  <img src="https://docs.webfx.dev/webfx-project/webfx-ecosystem.svg" />

  <p></p>

| Repository *                                                      | Description                                                                                   |
|-------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| [WebFX Kit](https://github.com/webfx-project/webfx)               | A patched version of OpenJFX that can be transpiled by GWT.                                   |
| [WebFX Platform](https://github.com/webfx-project/webfx-platform) | Our foundation layer & API for cross-platform development.                                    |
| [WebFX CLI](https://github.com/webfx-project/webfx-cli)           | A tool to assist developers to build WebFX applications.                                      |
| [WebFX Libs](https://github.com/webfx-libs)                       | A space for hosting existing JavaFX libraries ported for WebFX, or brand new WebFX libraries. |
| [WebFX Stack](https://github.com/webfx-project/webfx-stack)       | A collection of framework pieces for enterprise applications.                                 |
| [WebFX Extras](https://github.com/webfx-project/webfx-extras)     | A collection of extra JavaFX controls such as data grid, Gantt view, etc...                   |

*\* Each link goes to the corresponding GitHub repository whose README provides more detailed information.*

</div>

Typically, a graphical application will use the WebFX Kit (with its covered JavaFX API), and eventually some other WebFX libraries (like we did in most of the [demos](https://github.com/webfx-demos)). An Enterprise application will, in addition, use the WebFX Stack and WebFX extras.

## Relation to the Modality project

The WebFX project is now supported by the [Modality project](https://github.com/modalityproject/modality), another open-source project on GitHub (*click on the link for a description of the project*). Modality will be the first Enterprise-level application based on WebFX. These two projects are supporting each other. WebFX provides the 100% Java full-stack cross-platform solution Modality was looking for, and Modality is the main contributor to the WebFX Stack and WebFX Extras repositories. Modality also benefits the WebFX project by demonstrating its capabilities for Enterprise-level applications.
