# selenium-docker

### Description
This repository provides a Dockerfile for building a Python Selenium image on a Linux platform.

### Note
1. Please ensure that chrome and chromedriver have the same version.
    - For example: Stable Version 125.0.6422.141
2. If you encounter the error "Error sending stats to Plausible: error sending request for url (https://plausible.io/api/event)", it may be due to a delay in Chrome initialization. If this happens, simply try running it again. Don't use "--rm" flag for execution.

### Source
- [Chrome & Chromedriver Download](https://googlechromelabs.github.io/chrome-for-testing/#stable)
- [Tutorial Video](https://www.youtube.com/watch?v=M02_z-w2AFw)