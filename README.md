# Deep Learning Ventilation Magnetic Resonance Imaging

This repository is an implementation of "[Pulmonary Ventilation Maps Generated with Free-breathing Proton MRI and a Deep Convolutional Neural Network.](https://doi.org/10.1148/radiol.2020202861)" in _Radiology_ 2020 by Dante Capaldi and colleagues.

![DL-Vent MRI](https://github.com/capaldid/DLMRI/blob/master/DLVentFigure.png)

## Requirements

- Python 3.7.2
- Tensorflow 1.13.1

### Implementation of DL-Vent MRI was performed using code from the following library
- [MRI-to-CT-DCNN-TensorFlow](https://github.com/ChengBinJin/MRI-to-CT-DCNN-TensorFlow)

## Files and Documentation

The DL-Vent code to run test image and model are provided.

```
src\DLMRI_DCNN.zip     - main code
```

### Running the Code

1. Please contact us to download the VGG16 weights (previously downloadable from [here](https://github.com/ChengBinJin/MRI-to-CT-DCNN-TensorFlow)).

2. Download trained model from [here](https://gitlab.com/fumin.guo/dante_capaldi_DLMRI).

3. Save the VGG16 weights file (caffe_layers_value.pickle) to ./Models_zoo/

4. Save the contents from the trained model to ./model/DLVentMRI/20200815-2145/model4/

5. We provided an example image for test: 014.png (left and right panels: specific ventilation map and mask)

6. Run >> python run_prediction.py --load_model=20200815-2145 --dataset=DLVentMRI --test_filename=./input/014.png

7. The results are save as ./test/DLVentMRI/20200815-2145/model4/000.png

## Citation

```
@article{capaldi2020DLVentMRI,
  title={Pulmonary Ventilation Maps Generated with Free-breathing Proton MRI and a Deep Convolutional Neural Network},
  author={Capaldi, Dante PI and Guo, Fumin and Xing, Lei and Parraga, Grace},
  journal={Radiology},
  year={2020},
  publisher={Radiological Society of North America}
}
```

## License

MIT License

Copyright 2020 Dante Capaldi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
