# Dog-Heart-Vertebral-Heart-Size-VHS--Measurement-Software

This software aims to analyze the Vertebral Heart Size (VHS) of dog heart X-ray images and is developed based on MATLAB.



To run the software, 
For Windows user, 

1. Install Matlab MCR [R2021a (9.10))](https://www.mathworks.com/products/compiler/mcr/index.html)

2. Install "Dog_Heart_VHS_Windows.exe"


For Mac user,
1. Unzip Dog_Heart_Analysis_VHS_Mac.zip
2. Install R2022a (9.12) MCR [here](https://www.mathworks.com/products/compiler/matlab-runtime.html) (Mac version). 
3. Install Dog_Heart_Analysis_VHS.app.







### Reference

If you find it helpful, please cite it as:

`
Li, Jialu, and Youshan Zhang. "Regressive vision transformer for dog cardiomegaly assessment." Scientific Reports 14, no. 1 (2024): 1539.
`


Or in bibtex style:

```

@article{li2024regressive,
  title={Regressive vision transformer for dog cardiomegaly assessment},
  author={Li, Jialu and Zhang, Youshan},
  journal={Scientific Reports},
  volume={14},
  number={1},
  pages={1539},
  year={2024},
  publisher={Nature Publishing Group UK London}
}

```

![UFSKFE_GH060066 results](Sample_Labeling_video.gif)
<p align="center">Sample Labeling Process of the Dog_Heart_Analysis_VHS Software </p>


"Dog Hip Norberg Angle Measurement Software.pdf" is a short explanation of the software functions.

### Steps
1. Open a dog X-ray image;
2. Click on the "Long" button to draw a line from the ventral margin of the Corina to the apex (the bottom part of the heart). This line is named "L";
3. Click on the "Short" button to draw a line from the left part of the heart to the ventral margin of the caudal vena cava (the right of the heart ). This line is named "S", which should be perpendicular to L. Once you click on the "Calculate" button, the line S will automatically be adjusted to be perpendicular to L; 
4. Click on the "Verte" button to draw a line from the fourth vertebral body on the spine (T4) to the ninth vertebral body (T9), which has six lengths of the vertebral body, and this line is named "T".
5. Click on the "Calculate" button to calculate the VHS score, which is VHS = 6 *(L + S)/T. The line S will also automatically be adjusted to be perpendicular to L; 

