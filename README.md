# Hemoglobin Scanner

A low-cost, non-invasive device that estimates blood hemoglobin from a fingertip — built to make anemia screening accessible to frontline health workers in India.

## Overview

Anemia is widespread in India, but the standard test needs a blood draw and a lab. This prototype estimates hemoglobin **without a needle** — it shines red and infrared light (660 / 880 nm) into a fingertip and reads the reflected signal. It was built end-to-end using the Stanford Biodesign method, from clinical need to working device.

## What I did

- Executed a clinical immersion at JL Eye and GSVM Hospitals, conducted 17+ stakeholder interviews to identify critical needs.
- Applied Stage 1 of the Biodesign method to screen 30+ needs, formulating a SMART problem statement for an affordable device.
- Defined a non-invasive hemoglobin scanner for India's anemia via needs-filtering, screening 30+ insights from clinicians.
- Built a non-invasive hemoglobin scanner (660/880 nm optical); predicted Hb closely to reference values across tested samples.

## How it works

The MAX30102 sensor shines red (660 nm) and infrared (880 nm) light into the fingertip and measures the reflectance. That signal is converted to absorbance, processed, and mapped to a hemoglobin value using a calibration equation from published research.

## Built with

Nordic nRF54L (microcontroller) · nPM1300 (power management) · MAX30102 (optical sensor) · Zephyr RTOS (firmware)

## Documentation

[Technical Brief (PDF)](Hemoglobin_Scanner_Technical_Brief.pdf) — full system architecture, components, and clinical validation.

## Project details

Course project · BSE668 · Prof. Amitabha Bandyopadhyay · Aug–Nov 2025
