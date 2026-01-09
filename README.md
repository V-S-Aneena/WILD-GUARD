# WILD-GUARD

WildGuard is a **web-based wildlife monitoring and alert application** designed to support structured reporting, verification, and monitoring of wildlife sightings near human-inhabited areas. The system focuses on improving reliability in wildlife reporting and assisting authorities with better situational awareness.

---

## Overview

Wildlife sightings near residential areas are often reported informally and verified manually, which can result in delayed responses or false alerts. WildGuard provides a centralized platform where sightings can be reported with supporting evidence and location data, verified using automated analysis, and managed through a dedicated authority interface.

The system is built as a **decision-support application**, where automated analysis assists verification, while final alert decisions are handled through backend logic.

---

## Key Features

* User-based wildlife sighting reporting with image and location data
* Automated image verification using AI models
* Rule-based alert generation to reduce false positives
* Automatic hotspot detection based on recurring nearby sightings
* Interactive map visualization for monitoring wildlife activity
* Emergency reporting and status tracking
* Role-based access for users and authorities

---

## How the System Works

Users submit wildlife sightings by uploading an image and sharing their location. The backend processes the report and performs image analysis to detect and identify the animal. The result is validated through backend decision rules to determine whether the sighting should be marked as an alert.

When multiple alerts occur within close geographic proximity, the system identifies the area as a hotspot. All verified data is stored and made available to authorities through dashboards and map views for monitoring and response planning.

---

## User Roles

### Users

* Submit wildlife reports
* View alerts and hotspot information
* Send emergency requests

### Authorities

* Monitor verified wildlife alerts
* View hotspots and spatial patterns on the map
* Manage alert status
* Handle emergency requests

---

## Technologies Used

**Frontend**

* HTML, CSS, JavaScript
* Leaflet.js with OpenStreetMap

**Backend**

* Django
* SQLite
* Django media storage

**AI & Processing**

* PyTorch
* YOLOv8 (Ultralytics)
* CNN-based classifier (ResNet)

**Algorithms**

* Rule-based decision logic
* Haversine distance calculation for hotspot detection

---


## Project Scope

This project focuses on:

* System integration
* AI-assisted verification
* Controlled alert generation
* Practical usability

It does not aim to replace human decision-making or provide real-time enforcement.
---

