# Textual-Noise-effect-on-sentiment-Detection-Project
Analysis Impact of textual Noise on sentiment Detection Using LLMs
<p></p>
<p></p>
<p><strong>Original Text: Example text to be modified. </strong></p>
<p></p>
Noisy Text with Random Characters: Vxample tTxt to be modified. 
<p></p>
Noisy Text with Special Characters: EвĤxample text to be ŧmΐodiĆfied. 
<p></p>
Noisy Text with Homoglyphs: ᴇхạмpӏe text тo be mɵdifіeԁ.
<p></p>

<div align="left"> 
  <p><strong> Bertweet Accuracy with different noise rate and types of noise : </strong></p> 
  <img src="images/bertbase-effect.png" alt="bertbase-effect" style="max-width: 100%; height: auto;" /> 
</div>

<div align="left"> 
  <p><strong>Distilled Bert without fine-tune Accuracy with different noise rate  : </strong></p> 
  <img src="images/plot3types.png" alt="plot3types" style="max-width: 100%; height: auto;" /> 
</div>

The project investigates the impact of various types of textual noise on sentiment detection using bertbase pre-trained model and The three types of noise considered are: 1-Adding special characters to the text. 2 - Randomly changing characters in the text. 3-Replacing characters with similar-looking characters (homoglyphs). Adding special characters to text has the least impact on model accuracy. The model can recover the meaning of the words to a good extent, depending on the noise level. Replacing characters with similar-looking ones falls between the other two types in terms of impact on accuracy. While the meaning of words can often be recovered, it is less effective than dealing with special characters noise but more effective than random characters noise.
