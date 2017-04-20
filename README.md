[![Codacy Badge](https://api.codacy.com/project/badge/Grade/6bfdbda51c0d41b1bf8de81ceeed5ca5)](https://www.codacy.com/app/mirco-nasuti/ehr-to-i2b2?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=LREN-CHUV/ehr-to-i2b2&amp;utm_campaign=Badge_Grade)
[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](https://github.com/LREN-CHUV/ehr-to-i2b2/blob/master/LICENSE)
[![CHUV](https://img.shields.io/badge/CHUV-LREN-AF4C64.svg)](https://www.unil.ch/lren/en/home.html)

# EHR to I2B2

## Introduction

This is a tool to import EHR (electronic health record) data into an I2B2 database.

## Usage

Run:
`docker run --rm -v <ehr_folder>:/input_folder hbpmip/ehr-to-i2b2 <db_url> <dataset>`
