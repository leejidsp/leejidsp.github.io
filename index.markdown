---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


# Adversarial Audio Synthesis using a Harmonic-Percussive Discriminator

Submitted to ICASSP 2022 (Paper ID: 5617)

<br />
### Authors
Jihyun Lee, Hyeongsub Lim, Chanwoo Lee, Inseon Jang, Hong-Goo Kang

<br />



### Proposed Method

<br />
<img src="./assets/proposed.png"> 





### Samples
<br />

**Baseline**: ParallelWaveGAN trained with MAESTRO dataset (down-sampled to 16 kHz)

**Ablation 1**: Proposed method without a harmonic-percussive separator module

**Ablation 2**: Proposed method switching the roles of the harmonic and percussive discriminators



<br />

<table style="width: auto; table-layout: fixed; word-wrap: normal;" borded="1" border-collapse="collapse">

<tr>
<td style="column-width: auto; padding-left: 10px; padding-right: 10px"><strong></strong></td>
<td style="column-width: auto; padding-left: 10px; padding-right: 10px"><strong>Reference</strong></td>
<td style="column-width: auto; padding-left: 10px; padding-right: 10px"><strong>Proposed</strong></td>
<td style="column-width: auto; padding-left: 10px; padding-right: 10px"><strong>Baseline</strong></td>
<td style="column-width: auto; padding-left: 10px; padding-right: 10px"><strong>Abalation 1</strong></td>
<td style="column-width: auto; padding-left: 10px; padding-right: 10px"><strong>Ablation 2</strong></td>
</tr>

<!--Sample 1-->
<tr>
<td style="column-width: auto; padding-left: 10px; padding-right: 10px"><strong>Sample 1</strong></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/032_reference.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/032_proposed.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/032_baseline.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/032_wo_hpss.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/032_reverse.wav'></audio></td>
</tr>

<!--Sample 2-->
<tr>
<td style="column-width: auto; padding-left: 10px; padding-right: 10px"><strong>Sample 2</strong></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/108_reference.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/108_proposed.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/108_baseline.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/108_wo_hpss.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/108_reverse.wav'></audio></td>
</tr>

<!--Sample 2-->
<tr>
<td style="column-width: auto; padding-left: 10px; padding-right: 10px"><strong>Sample 3</strong></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/074_reference.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/074_proposed.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/074_baseline.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/074_wo_hpss.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/074_reverse.wav'></audio></td>
</tr>

<!--Sample 2-->
<tr>
<td style="column-width: auto; padding-left: 10px; padding-right: 10px"><strong>Sample 4</strong></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/097_reference.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/097_proposed.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/097_baseline.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/097_wo_hpss.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/097_reverse.wav'></audio></td>
</tr>

<!--Sample 2-->
<tr>
<td style="column-width: auto; padding-left: 10px; padding-right: 10px"><strong>Sample 5</strong></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/083_reference.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/083_proposed.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/083_baseline.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/083_wo_hpss.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/083_reverse.wav'></audio></td>
</tr>

<tr>
<td style="column-width: auto; padding-left: 10px; padding-right: 10px"><strong>Sample 6</strong></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/066_reference.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/066_proposed.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/066_baseline.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/066_wo_hpss.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/066_reverse.wav'></audio></td>
</tr>

<tr>
<td style="column-width: auto; padding-left: 10px; padding-right: 10px"><strong>Sample 7</strong></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/027_reference.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/027_proposed.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/027_baseline.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/027_wo_hpss.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/027_reverse.wav'></audio></td>
</tr>

<tr>
<td style="column-width: auto; padding-left: 10px; padding-right: 10px"><strong>Sample 8</strong></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/052_reference.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/052_proposed.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/052_baseline.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/052_wo_hpss.wav'></audio></td>
<td><audio controls style="width: 150px;"><source src='./assets/demo_samples/052_reverse.wav'></audio></td>
</tr>
</table>


​	


