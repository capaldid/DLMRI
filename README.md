# Deep Learning Ventilation Magnetic Resonance Imaging

This repository is an implementation of "[Deep Convolutional Neural Network Pulmonary Ventilation Maps Trained using Free breathing Proton and Hyperpolarized Helium-3 MR Ventilation Imaging.](https://github.com/capaldid/DLMRI/)" accepted with revisions to  the _Radiology_ 2020 by Dante Capaldi and colleagues.

![DL-Vent MRI](https://github.com/capaldid/DLMRI/blob/master/DLVentFigure.png)

## Requirements

- Python 3.7.2
- Tensorflow 1.13.1

### Implementation of DL-Vent MRI was performed using code from the following library
- [MRI-to-CT-DCNN-TensorFlow](https://github.com/ChengBinJin/MRI-to-CT-DCNN-TensorFlow)

## Files and Documentation

The DL-Vent code to run test image and model are provided.

```
src\code     - main code
```

The trained model can be downloaded from [here](https://github.com/capaldid/DLMRI/).

## Citation

```
@article{capaldi2020DLVentMRI,
  title={Technical Note: Evaluation of Audiovisual Biofeedback Smartphone Application for Respiratory Monitoring in Radiation Oncology},
  author={Capaldi, Dante PI and Guo, Fumin and Xing, Lei and Parraga, Grace},
  journal={Radiology},
  year={Accepted with Revisions},
  publisher={Radiological Society of North America}
}
```

## License

MIT License

Copyright 2020 Dante Capaldi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
