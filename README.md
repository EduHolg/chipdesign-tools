# Chip Design Tools

[![Docker Image](https://img.shields.io/badge/Docker-eduholweb%2Fchipdesign--tools-blue?style=flat-square&logo=docker)](https://hub.docker.com/r/eduholweb/chipdesign-tools)
[![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey.svg?style=flat-square&logo=opensourceinitiative)](LICENSE)
[![GitHub Issues](https://img.shields.io/github/issues/EduHolg/chipdesign-tools?style=flat-square&label=Issues&logo=github)](https://github.com/EduHolg/chipdesign-tools/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/EduHolg/chipdesign-tools?style=flat-square&label=PRs&logo=github)](https://github.com/EduHolg/chipdesign-tools/pulls)

---

## Overview

**Chip Design Tools** provides a ready-to-use Docker environment for
Integrated Circuit (IC) design, simulation, verification, and physical
design using open-source EDA tools.

The environment is intended primarily for **teaching, student projects,
and academic IC design workflows** at the

**Institute of Micro and Nanoelectronics (IMNE)**  
**Universidad San Francisco de Quito (USFQ)**

The Docker image is available at:

https://hub.docker.com/r/eduholweb/chipdesign-tools

The environment includes **LibreLane** together with a collection of
open-source tools for RTL-to-GDSII design, simulation, schematic capture,
layout, verification, and circuit characterization.

---

## Based on UNIC-CASS IC Design Tools

This repository is an adaptation of the
**UNIC-CASS IC Design Tools** project developed as part of the
Universalization of IC Design from CASS (UNIC-CASS) program.

The original project can be found at:

https://github.com/unic-cass/uniccass-icdesign-tools

The original Docker image is available at:

https://hub.docker.com/r/isaiassh/unic-cass-tools

The structure of the Docker environment, including the Docker launcher,
cross-platform configuration, X-server support, PDK management, and
integration of open-source IC design tools, is based on the original
UNIC-CASS implementation.

This repository adapts that environment including:

- A dedicated Docker image:
  `eduholweb/chipdesign-tools`
- A dedicated GitHub repository.
- A simplified distribution mechanism for students.
- A persistent shared directory for student projects.
- Support for running the environment through Docker Desktop.
- Windows graphical application support through VcXsrv.
- The PDKs required for the course and student projects.
- A stable versioned Docker image for teaching environments.

## Docker Image

The current Docker image is:

```text
eduholweb/chipdesign-tools:1.1.0
