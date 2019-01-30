<img align="right" src="https://github.com/Errrneist/AIARG-UWKWT-Analyzation-Software/blob/master/IMG/UW-Icon.jpg" alt="University of Washington" width="100">

# AIARG-UWKWT-Acquisition Software
**[University of Washington](http://www.washington.edu/) [Kirsten Wind Tunnel](https://www.aa.washington.edu/AERL/KWT)-[Aircraft Icing and Aerodynamics Research Group](https://www.aa.washington.edu/research/AIARG)**

*[William E. Boeing Department of Aeronautics & Astronautics](https://www.aa.washington.edu/), [Boeing](http://www.boeing.com/), [NASA](https://www.nasa.gov/), [FAA](https://www.faa.gov).*
* The purpose of this project is to collect raw data and prepare for futher mathematical computing.
* It collects data from a NI DAQ board and saves all data into a .csv file.


<img align="right" src="https://github.com/Errrneist/AIARG-UWKWT-Analyzation-Software/blob/master/IMG/UW-AA.jpg" alt="University of Washington" width="350">

## Instructions
* Step 1: Make sure you connected and configured the acquisition device properly in the NI MAX software.
* Step 2: Please specify a file path for the .csv file in the program.
* Step 3: Maintain a test run log is recommended so we all understand what was going on.
* Step 4: For every run, input the load information and click collect when you are ready.
* Step 5: Upload test result to Perforce, Shared Drives, etc.

## About
* We use the following 11 channels for adding load.
* The program outputs voltages from the following 6 channels: L1, L2, SF1, SF2, SF3, D1.
* A useful tool to view the CSV files: [CSVFileView](https://www.nirsoft.net/utils/csv_file_view.html)

## Updates
* [20190126] Released [V2](https://github.com/Errrneist/AIARG-UWKWT-Acquisition-Software/releases/tag/v2.0) to meet most recent demand.
* [20190125] UI changed. Now recording 11 loads at different load locations, not moments.
* [20190114] Code testing successfull.

## Contributor

**Principal Investigator**

* *[Dr. Michael B. Bragg](https://www.aa.washington.edu/people/faculty/bragg)*

**Research Professor**

* *[Dr. Christopher Lum](https://www.aa.washington.edu/people/faculty/lum)*

* *[Dr. Mohamad Reza Soltani](http://ae.sharif.edu/~web/homepage.php?username=msoltani)*

**Software Developer**

* *[Hongjun Wu](https://errrneist.github.io)*

**Lab Manager**

* *Kevin Ho*

**Kirsten Wind Tunnel Support**

* *Hannah Stevens*

**Staff**

* *Rami Slim*

## License
* [Apache License 2.0](https://github.com/Errrneist/AIARG-UWKWT-Analyzation-Software/blob/master/LICENSE.txt)


