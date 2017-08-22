1. Use "make" to compile source code on iMX8DV.

2. Copy kernel(nlmeans.cl) and inpout image(src.tga) to same direction with binary.

3. If want to test different images, please change the name of input image in source code and make sure the input image is "tga" format with R-G-B-A 4 channels.

4. Results: "5-ImageRGB.tga" is noise reduced image. "1-ImageOriginal.tga" is input image saved as "tga" format. "2-ImageY.tga" is Y-channel image saved as "tga" format. "3-ImageBorder.tga" is image added border in Y-channel and saved as "tga" format. "4-ImageDenoise-Y.tga" is noise reduced image in Y-channel and saved as "tga" format.
