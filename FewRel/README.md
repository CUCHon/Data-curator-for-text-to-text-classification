

```bash
sh scripts/run_sen_gen.sh 4 48 t5-small
sh scripts/run_sen_gen.sh 4 24 t5-base
sh scripts/run_sen_gen.sh 4 12 t5-large
sh scripts/run_sen_gen.sh 5 6 t5-3b
```


```bash
sh scripts/run_sen_cls.sh 2 64 t5-small 5e-4
sh scripts/run_sen_cls.sh 2 32 t5-base 5e-4
sh scripts/run_sen_cls.sh 2 16 t5-large 5e-4
sh scripts/run_sen_cls.sh ​7​ ​8​ t5-​3b ​1​e-4
```


<table style="height: 108px; width: 673px;" width="599">
<tbody>
<tr style="height: 18px;">
<td style="height: 36px; width: 107.969px;" rowspan="2"><strong>Model</strong></td>
<td style="text-align: center; height: 18px; width: 124.57px;"><strong>Text-to-Indices</strong></td>
<td style="text-align: center; height: 18px; width: 418.461px;" colspan="3"><strong>Text-to-Text</strong></td>
</tr>
<tr style="height: 18px;">
<td style="text-align: center; height: 18px; width: 124.57px;"><strong>accuracy</strong></td>
<td style="text-align: center; height: 18px; width: 112.734px;"><strong>accuracy</strong></td>
<td style="text-align: center; height: 18px; width: 146.453px;"><strong>In-test ratio</strong></td>
<td style="text-align: center; height: 18px; width: 147.273px;"><strong>In-train ratio</strong></td>
</tr>
<tr style="height: 18px;">
<td style="height: 18px; width: 107.969px;">T5-small</td>
<td style="text-align: center; height: 18px; width: 124.57px;">
<div>
<div>37.1250</div>
</div>
</td>
<td style="text-align: center; height: 18px; width: 112.734px;">
<div>
<div>8.1875</div>
</div>
</td>
<td style="text-align: center; height: 18px; width: 146.453px;">
<div>
<div>9.5625</div>
</div>
</td>
<td style="text-align: center; height: 18px; width: 147.273px;">
<div>
<div>48.0000</div>
</div>
</td>
</tr>
<tr style="height: 18px;">
<td style="height: 18px; width: 107.969px;">T5-base&nbsp;</td>
<td style="text-align: center; height: 18px; width: 124.57px;">
<div>
<div>53.6875</div>
</div>
</td>
<td style="text-align: center; height: 18px; width: 112.734px;">
<div>
<div>0.3125</div>
</div>
</td>
<td style="text-align: center; height: 18px; width: 146.453px;">
<div>
<div>1.3750</div>
</div>
</td>
<td style="text-align: center; height: 18px; width: 147.273px;">
<div>
<div>97.8125</div>
</div>
</td>
</tr>
<tr style="height: 18px;">
<td style="height: 18px; width: 107.969px;">T5-large&nbsp;</td>
<td style="text-align: center; height: 18px; width: 124.57px;">
<div>
<div>57.1250</div>
</div>
</td>
<td style="text-align: center; height: 18px; width: 112.734px;">
<div>
<div>0.0000</div>
</div>
</td>
<td style="text-align: center; height: 18px; width: 146.453px;">
<div>
<div>0.0000</div>
</div>
</td>
<td style="text-align: center; height: 18px; width: 147.273px;">
<div>
<div>99.8750</div>
</div>
</td>
</tr>
<tr style="height: 18px;">
<td style="height: 18px; width: 107.969px;">T5-3B</td>
<td style="text-align: center; width: 124.57px; height: 18px;">
<div>
<div>
<div>
<div>67.2500</div>
</div>
</div>
</div>
</td>
<td style="text-align: center; width: 112.734px; height: 18px;">
<div>
<div>
<div>
<div>0.0000</div>
</div>
</div>
</div>
</td>
<td style="text-align: center; width: 146.453px; height: 18px;">
<div>
<div>
<div>
<div>0.0000</div>
</div>
</div>
</div>
</td>
<td style="text-align: center; width: 147.273px; height: 18px;">
<div>
<div>100.000</div>
</div>
</td>
</tr>
</tbody>
</table>