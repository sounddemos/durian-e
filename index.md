# <center> DurIAN-E: </center>
<br>
## Abstract
<div style="text-align: justify"> This paper introduces an improved  duration informed attention neural network (DurIAN-E) for expressive and high-fidelity  text-to-speech  (TTS) synthesis.  Inherited from the original DurIAN model, an auto-regressive model structure in which the alignments between the input linguistic information and the output acoustic features are inferred from a duration model is adopted. Meanwhile the proposed DurIAN-E utilizes multiple stacked SwishRNN-based Transformer blocks as linguistic encoders.
Style-Adaptive Instance Normalization (SAIN) layers are exploited into 
frame-level encoders to improve the modeling ability of expressiveness.
A  denoiser incorporating both  denoising diffusion probabilistic model (DDPM) for mel-spectrograms and SAIN modules is conducted to further improve the synthetic  speech quality and expressiveness.
Experimental results prove that the proposed expressive TTS model in this paper can achieve better performance than the state-of-the-art approaches  in both subjective mean opinion score (MOS) and preference tests. </div> 
