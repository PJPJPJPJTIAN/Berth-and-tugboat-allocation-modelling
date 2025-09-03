# Berth and Tugboat Allocation Modelling

## Overview

This repository contains supplementary materials for the research project **"LLM-Driven Automated Algorithm Design Framework for the Just-In-Time System at the Port of Singapore: From Design to Case Validation"**.

## Purpose

This work specifically addresses **Aim 1** of the main project, focusing on berth and tugboat allocation optimization for Just-In-Time (JIT) maritime operations. The repository provides baseline implementations that demonstrate the limitations of traditional manual algorithmic approaches, highlighting the need for the proposed LLM-driven automated algorithm design framework.

## Contents

- **Mixed-Integer Linear Programming Model**: Formalizes berth and tugboat allocation with JIT arrival time (JIT-AT) generation
- **Manual Algorithm Implementation**: Uses commercial solver Gurobi for optimization
- **Constraint Integration**: Incorporates vessel-berth compatibility and tugboat horsepower sufficiency requirements
- **Performance Analysis**: Demonstrates limitations in adaptability and efficiency of traditional approaches

## Key Findings

The manual algorithms exhibit several limitations:
- Heavy reliance on expert parameter tuning
- Slow response to operational disruptions
- Limited adaptability to dynamic maritime environments

These findings provide critical baseline evidence supporting the advantages of the proposed LLM-AADF framework for solving JIT optimization challenges.

## Context

This work forms part of the preliminary studies conducted by the research team at NTU's School of Civil and Environmental Engineering, serving as foundational research for developing next-generation autonomous port operations at the Port of Singapore.

## Related Work

For the complete research framework and methodology, please refer to the main project proposal focusing on LLM-driven automated algorithm design for maritime JIT systems.
