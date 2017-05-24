# ImageProcessing
Making Brightnessfunction with CxImage<br/>
2016. 2nd semester Practice (Image Processing)<br/>
Making Image brighter or darker<br/>

Color Data Structure<br/>
public:<br/>
nbsp; RGBQUAD m_color;<br/>
typedef struct tagRGBQUAD {<br/>
nbsp; BYTE rgbBlue;<br/>
nbsp; BYTE rgbGreen;<br/>
nbsp; BYTE rgbRed;<br/>
nbsp; BYTE rgbReserved;<br/>
} RGBQUAD;<br/>

Exception Handling<br/>
 - Range of RGB value : 0~255 (each value)<br/>
 - avoid overflow & underflow<br/>
 
How to run<br/>

1. Open Solution File<br/>
Path : Template\cximage\CxImgLib.sln<br/>
- Build Library solution<br/>

2. Open Solution File<br/>
Path : Brightness\SRC\ImageProcessing.sln<br/>
- Build template solution<br/>
