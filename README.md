# Linseis LSR-3 Data Tool
Data extraction and evaluation tool for Linseis LSR-3 800 Seebeck coefficient &amp; electric conductivity measurement. Taking below measured data as an input:

* Time (min)
* Temperature (C)
* Temperature Gradient (C)
* Resistivity (uOhm * m)
* Relative Seebeck Coefficient (uV/K)

and the tool plots:

* Seebeck Coefficient vs. Temperature
* Resistivity vs. Temperature
* Conductivity vs. Temperature
* Power Factor vs. Temperature

## Getting Started

MATLAB_R2017a was used to develop this tool. Older version of MATLAB and [Octave](https://www.gnu.org/software/octave/) can also run the tool.

### Prerequisites

#### Exporting ACSII From Linseis Data Software

1. Click 'ACSII-Export' on the top function bar in the Linseis Data Evaluation Program

2. Click 'Other traces' and then OK

3. Locate the raw data file (.LSR file) that you want to export

4. Select ANSI format

5. Converting *.ACS to *.xlsx on spreadsheet software like Microsoft Excel  

#### Installing

1. Place this file and converted file on the same folder

## Running the Example Files

Explain how to run the automated tests for this system

## Authors

* [**Sunhwi Bang**](https://github.com/SunhwiBang) 

## Acknowledgments

* Unknown author's LSR Data Handler v.0.9.3.xlsm
