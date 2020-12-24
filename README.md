# Self-paced-Learning-Project-Sobel-Filter


<br />
<p align="center">

  <h3 align="center">MSOC-HLS Self-paced Learning Project_1 - Sobel Filter</h3>
  
</p>


<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Usage](#usage)
* [Algorithm](#Algorithm)
* [References](#References)
* [Contact](#contact)


<!-- ABOUT THE PROJECT -->
## About The Project
The github repository for hls projects - Sobel Filter

**Directory structure**
* **README.md** - introduce the project, algorithm, usage, reference and contact information
* **code/**
  * original - The original code from Xilinx application note open source 
  * final - The optimized kernel code is in this directory, also including Python host code 

* **testdata/** - include input test data, and output result data
* **impl/** - result of the implementation, e.g. HLS csynth report
     
<!-- USAGE EXAMPLES -->
## Usage
1. Open Vivado HLS
    * We use **Xilinx ZedBoard Evaluation and Development Kit** to evaulate this project 
    * Add sobel.cpp, sobel.h, ap_bmp.cpp, ap_bmp.h, ap_video.h into **Source file**
    * Add sobel_test.cpp, test_1080p.bmp, result_1080p_golden.bmp into **Test Bench**

2. Run C Simulation, Run Synthesis, Run Cosimulation, Export IP
3. Open Vivado 2019.2
4. Import IP and create Block design
5. Generate Bitstream
6.Using PYNQ to control Zedboard


## Algorithm
Sobel edge detection is a classical algorithm in the field of image and video processing for the
extraction of object edges.  
Edge detection using Sobel operators works on the premise of computing an estimate of the first derivative of an image to extract edge information.  
By computing the x and y direction derivatives of a specific pixel against a neighborhood of
surrounding pixels, it is possible to extract the boundary between two distinct elements in an
image.  
Due to the computational load of calculating derivatives using squaring and square root
operators, fixed coefficient masks have been adopted as a suitable approximation in computing
the derivative at a specific point.  

## References
* [Xilinx Support documentation](https://www.xilinx.com/support.html#documentation)
* [[xapp] XAPP890 - Sobel Filter](https://www.xilinx.com/support/documentation/application_notes/xapp890-zynq-sobel-vivado-hls.pdf)

<!-- CONTACT -->
## Contact
* F07943023@ntu.edu.tw
