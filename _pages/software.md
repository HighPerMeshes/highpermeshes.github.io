---
title: "Software"
permalink: /software/
---
## HighPerMeshes-DSL ##
#### Domain-specific language for matrix-free, unstructured grid algorithms ####

**Einsatz:** Spezifikation von unstrukturierten Gitteralgorithmen und Generierung einer Einzelknoten Implementierung (Shared Memory System). Code-Generierung für CPU und generisches OpenCL Backend.

## HighPerMeshes-DRTS-GASPI ##
#### Distributed runtime system (DRTS) for HighPerMeshes DSL based on GASPI ####

**Einsatz:** Parallele Ausführung einer mit der HighPerMeshes DSL erzeugten Implementierung auf einem Distributed Memory HPC-System. Unterstützt automatische Problem-Partitionierung und Lastbalancierung.

## Proxy-Type-Generator and Source-to-Source Codetransforation Tool ##
#### A standalone tool that draws on (Clang) LibTooling for source code analysis and proxy-type generation for structured data types. ####

**Einsatz:** Automatische codespezifische Erzeugung von Datenschnittstellen für die transparente Nutzung unterschiedlicher Daten-Layouts.

## KASKADE 7 ##

<picture>
<img src="/assets/images/Logo-Kaskade7.png" width="200" style="float:right;" title="KASKADE 7 Logo">
</picture>

[Kaskade 7](http://www.zib.de/projects/kaskade7-finite-element-toolbox) is a finite element toolbox for the solution of stationary and transient systems of partial differential equations. The library is written in C++ and utilizes template meta-programming to achieve flexibility and efficiency. It is based to a large extent on the DUNE (Distributed and Unified Numerics Environment) core modules. The Kaskade 7 code is under active development by the "Computational Medicine" research group at ZIB.

Two application examples implemented with Kaskade 7, modeling cardiac electrophysiology and elastomechanics, serve as case studies in the HighPerMeshes project.
