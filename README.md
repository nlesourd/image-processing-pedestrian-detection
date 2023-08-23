# Image processing

## Pedestrian detection thanks to Hitogram of Oriented Gradients

As part of an image processing course, the rules were as follows:
- Download image 0006 from the road scenes 1 file on Moodle
- Isolate the pedestrian of your choice in a 64x64 image.
- Divide this image into 8x8 squares, calculate the histograms of gradients
oriented on each block (choose 8 orientations as in HOG)
- Concatenate these histograms to obtain a single final histogram. This
final histogram is your car's signature.
- Using a 64x64 sliding window, use the metric of your choice to detect the presence of
presence of cars in the image 0009.jpg
- Check the stability of your method against different Gaussian noises of 5
different scales (std)

## Work

The work was carried out using a python notebook available under the name "notebook.ipynb".

## Conclusion

The conclusions drawn from this work are available in the "Rapport.pdf".