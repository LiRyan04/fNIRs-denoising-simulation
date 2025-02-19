# fNIRS-signal-denoising-methods-simulation
__Different fNIRS signal denoising techniques simulation__  
We applied different methods to the examples code using the tool, in order to compare the simulation efficiency and effectiveness.

## Data:
- [mne.fnirs.data](https://mne.tools/stable/generated/mne.datasets.fnirs_motor.data_path.html)
- [mne.nirs.examples](https://mne.tools/mne-nirs/stable/auto_examples/general/index.html)

## Tools:
- [MNE](https://mne.tools/)
- [MNE-NIRS](https://mne.tools/mne-nirs/stable/index.html)
- [Matplotlib](https://matplotlib.org)

## Environment:
- Python 3.12 (anaconda)
- MNE 1.80
- Matplotlib 3.10.0

## Results:
<table>
  <thead>
    <tr>
      <th>Ref.</th>
      <th>Meth.</th>
      <th>SNR</th>
      <th>CNR</th>
      <th>MSE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="#fang2024motion">Fang et al., 2024</a></td>
      <td>Spline Interpolation</td>
      <td>26.94</td>
      <td>5.19</td>
      <td>5.17e-5</td>
    </tr>
    <tr>
      <td><a href="#yoo2024multivariate">Yoo et al., 2024</a></td>
      <td>Multivariate Disturbance</td>
      <td>19.28</td>
      <td>15.23</td>
      <td>1.6e-4</td>
    </tr>
    <tr>
      <td><a href="#hui2024exploring">Hui et al., 2024</a></td>
      <td>Digital Filter</td>
      <td>17.29</td>
      <td>15.12</td>
      <td>1.6e-4</td>
    </tr>
    <tr>
      <td><a href="#hui2024exploring">Hui et al., 2024</a></td>
      <td>Savitzky-Golay Filter</td>
      <td>27.66</td>
      <td>1.0935</td>
      <td>3.4e-5</td>
    </tr>
    <tr>
      <td><a href="#abdi2010coefficient">Abdi, 2010</a></td>
      <td>Coefficient Variation</td>
      <td>12.32</td>
      <td>19.41</td>
      <td>6e-4</td>
    </tr>
    <tr>
      <td><a href="#huang2022motion">Huang et al., 2022</a></td>
      <td>TDDR</td>
      <td>17.42</td>
      <td>0.15</td>
      <td>3.2e-5</td>
    </tr>
    <tr>
      <td><a href="#ali2023correlation">Ali et al., 2023</a></td>
      <td>CBSI</td>
      <td>15.65</td>
      <td>0.34</td>
      <td>2.928e-5</td>
    </tr>
  </tbody>
</table>
