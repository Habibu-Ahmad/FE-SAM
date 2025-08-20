# **Free-Energy Sharpness-Aware Minimization (FE-SAM)** 
<div style="display: flex; gap: 20px;">

<table>
<thead>
<tr><th colspan="2">Standard Methods<br>(CIFAR-100, ResNet-18)</th></tr>
<tr><th>Method</th><th>Accuracy (%)</th></tr>
</thead>
<tbody>
<tr><td>SGD</td><td>77.90 ± 0.07</td></tr>
<tr><td>SAM</td><td>80.88 ± 0.10</td></tr>
<tr><td>FriendlySAM</td><td>81.29 ± 0.12</td></tr>
<tr><td>FisherSAM</td><td>80.99 ± 0.13</td></tr>
<tr><td><b>FE-SAM (ours)</b></td><td><b>81.33 ± 0.12</b></td></tr>
</tbody>
</table>

<table>
<thead>
<tr><th colspan="2">Adaptive Variants</th></tr>
<tr><th>Method</th><th>Accuracy (%)</th></tr>
</thead>
<tbody>
<tr><td>ASAM</td><td>81.68 ± 0.10</td></tr>
<tr><td><b>FE-ASAM (ours)</b></td><td><b>81.75 ± 0.05</b></td></tr>
</tbody>
</table>

</div>
