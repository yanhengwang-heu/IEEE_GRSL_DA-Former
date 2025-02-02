# A Semi-Supervised Domain Alignment Transformer for Hyperspectral Images Change Detection
The code in this toolbox implements the ["A Semi-Supervised Domain Alignment Transformer for Hyperspectral Images Change Detection"](https://ieeexplore.ieee.org/document/10260309). 

![DA-Former](https://github.com/yanhengwang-heu/IEEE_TGRS_DA-Former/assets/39912855/da918565-214e-4b7e-83c6-160c0300ba27)

Citation
---------------------

**Please kindly cite the papers if this code is useful and helpful for your research.**

    @article{10260309,
      title={A Semi-Supervised Domain Alignment Transformer for Hyperspectral Images Change Detection},
      author={Wang, Yanheng and Sha, Jianjun and Gao, Lianru and Zhang, Yonggang and Rong, Xianhui and Zhang, Ce},
      journal={IEEE Trans. Geosci. Remote Sens.},
      year={2023},
      volume={},
      number={},
      pages={1-11},
      note = {DOI: 10.1109/TGRS.2023.3317919}
    }
    
    
How to use it?
---------------------
This code requires a Python Package:torch 1.8.1+cu111, numpy 1.22.4+mkl, scikit-learn 0.23.2, scipy 1.5.2, matplotlib 3.3.2
Here an example experiment is given by using Farmland Dateset. Directly run train.py functions with different network parameter settings to produce the results.
`python train.py --dataset='farmland' --ae_number=2000 --cd_number=100`

Licensing
---------
MIT License

Copyright (c) 2023 yanhengwang-heu

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


