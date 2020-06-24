# certificate_creator

A Certificate creator that uses Pillow(PIL) library of Python to write the names of the candidates in the Predefined Certficate format.

The code is quite simple. The names are given in a .xlsx file, which is read by panda's read_excel functiona and is converted to a python list. Then using Image the certificate format image (.jpg or .png etc) are brought, on which the names are written using ImageDraw with font taken using ImageFont.truetype(). Since the font was not available in Colab, hence I downloaded it manually and put it externally through drive.


Packages Required: 
      1. pandas:https://pandas.pydata.org/
      2. Pillow(PIL): https://pypi.org/project/Pillow/
                    
Fonts: https://www.1001fonts.com/cursive-fonts.html

A great help was taken from Rahul Sinha (https://dev.to/rahulsinha036/generate-certificate-using-python-43fa) ..... A BIG Shoutout to him!!!!
