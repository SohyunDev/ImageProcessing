# ImageProcessing
Making Brightnessfunction with CxImage
2016. 2nd semester Practice (Image Processing)
Making Image brighter or darker

Color Data Structure
public:
  RGBQUAD m_color;
typedef struct tagRGBQUAD {
  BYTE rgbBlue;
  BYTE rgbGreen;
  BYTE rgbRed;
  BYTE rgbReserved;
} RGBQUAD;

Exception Handling
 - Range of RGB value : 0~255 (each value)
 - avoid overflow & underflow
 
How to run

1. Open Solution File
Path : Template\cximage\CxImgLib.sln
- Build Library solution

2. Open Solution File
Path : Brightness\SRC\ImageProcessing.sln
- Build template solution
