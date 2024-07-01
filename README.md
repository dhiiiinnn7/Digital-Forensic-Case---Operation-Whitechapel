# Operation Whitechapel - Digital Forensic Case

## Overview

A comprehensive digital forensic investigation into a high-profile burglary case involving the theft of a valuable item from a celebrity's residence. The project entails detailed analysis of digital artefacts, utilization of advanced forensic tools, and meticulous documentation of the investigation process to uncover and present key evidence.

## Table of Contents

- [Project Structure](#project-structure)
- [Case Narrative](#case-narrative)
- [Artefacts](#artefacts)
- [Digital Forensic Individual Evidence Files](#digital-forensic-individual-evidence-files)
- [Tools and Techniques](#tools-and-techniques)
- [Installation](#installation)
- [Running the Analysis](#running-the-analysis)
- [References](#references)
- [License](#license)

## Project Structure

- `Digital Forensic Case - Operation Whitechapel.pdf`: Detailed report on the case, artefacts, and analysis.
- `Digital Forensic Individual Evidence Files`: The individual evidence files can be accessed from the following Google Drive folder: https://drive.google.com/drive/folders/1C8KteCi0cdZAKLrNEox4Fo2Ttk1zywD2?usp=sharing
- `OP_WC_0037.E01` - `OP_WC_0037.E11`: Segments of the evidence image file. These files can be accessed from the Google Drive Folder - https://drive.google.com/drive/folders/1Hk4ALCoHmTKdd6-ZNbmKmcrvpPvoBD3I?usp=sharing
- `OP_WC_0037.E01.txt`: Metadata and verification results of the image file. This file can be accessed from the Google Drive Folder - https://drive.google.com/drive/folders/1Hk4ALCoHmTKdd6-ZNbmKmcrvpPvoBD3I?usp=sharing

## Case Narrative

On the evening of October 21, 2023, Kirai Tsuyoshi, a 29-year-old celebrity, became the victim of a burglary at his residence in Whitechapel, London. The investigation led to the identification of suspects Ken Shima and his associate Shiro Aizen. The stolen item, referred to as the "Dragon Balls," is of significant value. The police's investigation focuses on recovering the stolen item and apprehending the suspects.

## Artefacts

The investigation identified various artefacts crucial to understanding the case. These artefacts include chat logs, documents with hidden text, manipulated image files, encrypted containers, and more. The detailed report in the provided PDF file elaborates on each artefact and its significance to the case.

## Digital Forensic Individual Evidence Files

The folder contains the following artefacts:
1. **Artefact 1 - Chat Artefact**: Contains chat logs recovered from the suspect's device.
2. **Artefact 2 - A document containing important information**: A document with hidden text.
3. **Artefact 3 - A picture**: An image file with potential hidden data.
4. **Artefact 4 & 5 - Hiding text or pictures within pictures**: Files demonstrating steganographic techniques.
5. **Artefact 6 - Manipulating file extensions**: Examples of files with manipulated extensions to conceal their true nature.
6. **Artefact 7 - Manipulating file headers**: Files with modified headers to mislead investigators.
7. **Artefact 8 - Email Artefact**: Emails relevant to the investigation.
8. **Artefact 9 - Registry Information - Installation artefacts**: Information extracted from the Windows registry.
9. **Artefact 10 - The 'hidden' flag within an image**: An image file with a hidden flag.
10. **Artefact 11 - Encrypted password protected document**: A document that is password protected.
11. **Artefact 12 - Encoded or encrypted text**: Text files containing encoded or encrypted information.
12. **Artefact 13 - Steg of pictures**: Images used for steganography.
13. **Artefact 14 - Deleted files (recycle bin)**: Files recovered from the recycle bin.
14. **Artefact 15 - Obfuscation of file and/or paths**: Examples of obfuscated file paths and names.
15. **Artefact 16 - A Video**: A video file with potential evidence.
16. **Artefact 17 - Splicing - using software to manipulate video**: Evidence of video manipulation.
17. **Artefact 18 - Internet history records showing browser history**: Browser history records.
18. **Artefact 19 - Registry Information - user activity**: User activity logs extracted from the registry.
19. **Artefact 20 - Most Recently Used (MRU)**: List of recently accessed files and applications.

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

Use this link to download the image file and set up the virtual environment: https://drive.google.com/drive/folders/1Hk4ALCoHmTKdd6-ZNbmKmcrvpPvoBD3I?usp=sharing

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
