# Operation Whitechapel - Digital Forensic Case

## Overview

A comprehensive digital forensic investigation into a high-profile burglary case involving the theft of a valuable item from a celebrity's residence. The project entails detailed analysis of digital artefacts, utilization of advanced forensic tools, and meticulous documentation of the investigation process to uncover and present key evidence.

## Table of Contents

- [Project Structure](#project-structure)
- [Case Narrative](#case-narrative)
- [Artefacts](#artefacts)
- [Tools and Techniques](#tools-and-techniques)
- [Installation](#installation)
- [Running the Analysis](#running-the-analysis)
- [References](#references)
- [License](#license)

## Project Structure

- `OP_WC_0037.E01` - `OP_WC_0037.E11`: Segments of the evidence image file.
- `OP_WC_0037.E01.txt`: Metadata and verification results of the image file.
- `Digital Forensic Case - Operation Whitechapel.pdf`: Detailed report on the case, artefacts, and analysis.

## Case Narrative

On the evening of October 21, 2023, Kirai Tsuyoshi, a 29-year-old celebrity, became the victim of a burglary at his residence in Whitechapel, London. The investigation led to the identification of suspects Ken Shima and his associate Shiro Aizen. The stolen item, referred to as the "Dragon Balls," is of significant value. The police's investigation focuses on recovering the stolen item and apprehending the suspects.

## Artefacts

The investigation identified various artefacts crucial to understanding the case. These artefacts include chat logs, documents with hidden text, manipulated image files, encrypted containers, and more. The detailed report in the provided PDF file elaborates on each artefact and its significance to the case.

## Tools and Techniques

The investigation utilized several forensic tools and techniques, including:
- **FTK Imager**: For acquiring and verifying the image file.
- **Autopsy**: For analysing the file system and recovering artefacts.
- **HxD**: For hex editing and recovering manipulated file headers.
- **VeraCrypt**: For accessing encrypted containers.
- **OpenPuff**: For uncovering steganographic content.

## Installation

### Clone the Repository

   ```bash
   git clone https://github.com/dhiiiinnn7/operation-whitechapel.git
   cd operation-whitechapel
```

### Set Up a Virtual Environment

Use this link to download the image file and set up the virtual environment: `(https://drive.google.com/drive/folders/1V5icotc6gn85o4jJd333uXo5uiILjfh3?usp=sharing)`

### Install Dependencies

This project primarily uses forensic tools that are not Python libraries. Ensure the following tools are installed on your system:

- FTK Imager
- Autopsy
- HxD
- VeraCrypt
- OpenPuff

## Running the Analysis

To run the forensic analysis, follow the procedures outlined in the detailed report. This involves mounting the image file, extracting artefacts, and using the specified tools to analyze and decode the evidence.

## References

Refer to the detailed reports provided in Digital Forensic Case - Operation Whitechapel.pdf for an in-depth analysis, including:

- Legislation relevant to the case
- Timeline of artefacts
- Detailed artefact analysis

## License
This project is licensed under the Apache License 2.0 - see the LICENSE file for details.
