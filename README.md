# malvernoutlines
Type1 font file for the Malvern font by Damian Cugley (ctan.org/tex-archive/fonts/malvern). Most of the work is due to Damian Cugley, I have just made the outline font files and added some support files.

In order to keep things simple, I have used only one optical size per style and have put all encoding-variants in a singe font file. The malvern.map can map the missing font files. The unification to a single optical size will cause a very slight optical offset for different optical sizes (like for 48pt). The PDF maman-comparison will show you, that the offset is indeed very slight (the bitmapped version is blue, the Type1 version is overlayed in a transparent orange, most of the area will appear gray). (Remember, that only the pictures are offset, the metrics are identical. Therefore, line breaks and page breaks will not change). Thus, I ended up with these files:
ma55a10.pfb 
ma56a10.pfb 
ma75a10.pfb 
ma76a10.pfb
ma53a12.pfb 
ma57a12.pfb
Unfortunately, some tfm files are missing, if one wants to typeset Greek or Cyrillic. I have added them. 
