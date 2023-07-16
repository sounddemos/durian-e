# <center> DurIAN-E:  Duration Informed Attention Network For Expressive Text-to-Speech Synthesis
</center>
<br>
## Abstract
<div style="text-align: justify"> This paper introduces an improved  duration informed attention neural network (DurIAN-E) for expressive and high-fidelity  text-to-speech  (TTS) synthesis.  Inherited from the original DurIAN model, an auto-regressive model structure in which the alignments between the input linguistic information and the output acoustic features are inferred from a duration model is adopted. Meanwhile the proposed DurIAN-E utilizes multiple stacked SwishRNN-based Transformer blocks as linguistic encoders.
Style-Adaptive Instance Normalization (SAIN) layers are exploited into 
frame-level encoders to improve the modeling ability of expressiveness.
A  denoiser incorporating both  denoising diffusion probabilistic model (DDPM) for mel-spectrograms and SAIN modules is conducted to further improve the synthetic  speech quality and expressiveness.
Experimental results prove that the proposed expressive TTS model in this paper can achieve better performance than the state-of-the-art approaches  in both subjective mean opinion score (MOS) and preference tests. </div> 

<br>

![arch](images/duriane.png)

<br>

## Sound Samples

\* <sup>Note: All samples are in Mandrin Chinese.</sup>

<br>
## synthesized demos from different systems
<br>

<table align="center">
  <thead>
    <tr>
      <th>GT (vocoder)</th>
      <th>FastSpeech 2</th>
      <th>DurIAN</th>
      <th>DiffSpeech</th>
      <th>DurIAN-E</th>
    </tr>
  </thead>
  <tbody>
    
   <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/gt/test01.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/fs/test01.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/durian/test01.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/ds/test01.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/duriane/test01.wav"></audio></td>
    </tr>
   
  </tbody>
</table>