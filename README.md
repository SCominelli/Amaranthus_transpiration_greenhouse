# Transpiration Response of Palmer Amaranth to Drying Soil

This repository contains Python code used to process, analyze, and visualize greenhouse data for the study of Palmer amaranth (*Amaranthus palmeri*) transpiration under well-watered and drying soil conditions. The workflow supports the analysis presented in Cominelli and Patrignani (2022). :contentReference[oaicite:0]{index=0}

## Overview

The code imports load cell, atmospheric, and soil water retention data to quantify plant transpiration dynamics during a greenhouse experiment conducted in Manhattan, Kansas. The experiment included six replications of well-watered plants and six replications of stressed plants grown in packed silt loam soil columns on automated load cells. :contentReference[oaicite:1]{index=1}

## Main components

- Data cleaning and quality control of load cell measurements
- Calculation of hourly and cumulative transpiration
- Estimation of vapor pressure deficit
- Computation of volumetric water content and soil matric potential
- Fitting of the soil water retention curve
- Statistical comparison of well-watered and stressed treatments
- Generation of figures for environmental conditions, transpiration patterns, and soil water dynamics

## Purpose

The goal of this repository is to provide a reproducible Python workflow to identify when Palmer amaranth transpiration begins to decline during soil drying and to relate that decline to soil water status. In the paper, stomatal conductance started to decline at about -120 kPa and plant transpiration started to decline at about -176 kPa. :contentReference[oaicite:2]{index=2}

## Language

- Python

## Reference

Cominelli, S., and Patrignani, A. 2022. *Transpiration response of palmer amaranth (Amaranthus palmeri) to drying soil in greenhouse conditions*. Frontiers in Agronomy, 4, 1018251. :contentReference[oaicite:3]{index=3}
