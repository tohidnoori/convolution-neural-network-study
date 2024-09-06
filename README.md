# Convolution neural network study


A **convolutional neural network (CNN)** is a regularized type of feed-forward neural network that learns features by itself via filter (or kernel) optimization. This type of deep learning network has been applied to process and make predictions from many different types of data including text, images and audio.
<br/>
<br/>
- - - -
#### These statistics are being examined right now: ####
 
#### These features of CNN studied here: ####
  * MaxPooling2D (pool_size)
  * Kernels (also known as filters in cnn)
  * Strides (determines how many squares or pixels our filters skip when they move across the image)
  * Padding (the technique of adding extra pixels around the input image or feature map to maintain spatial dimensions during the convolution operation)
- - - -
### Some equations used for the backprop process
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/tohidnoori/Ann-from-scratch/blob/main/images/Hidden%20Layer%20weight's%20backpropagation.png" width="500" height="400" alt="Hidden layer weight's backpropagation">
      <p>Hidden layer weight's backpropagation</p>
    </td>
    <td align="center">
      <img src="https://github.com/tohidnoori/Ann-from-scratch/blob/main/images/Output%20Layer%20bias%20backpropagation.png" width="500" height="400" alt="Output layer bias backpropagation">
      <p>Output layer bias backpropagation</p>
    </td>
  </tr>
</table>
<br/>

### My handwritten model Vs Tensor model
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/tohidnoori/Ann-from-scratch/blob/main/images/My model confusion matrix.png" width="500" height="400" alt="Hidden layer weight's backpropagation">
      <p>My model confusion matrix</p>
      <p>Precision: 0.7168 
       <br/>
       Accuracy: 0.6120   
       <br/>
       Sensitivity (Recall): 0.3333</p>
    </td>
    <td align="center">
      <img src="https://github.com/tohidnoori/Ann-from-scratch/blob/main/images/Tensor flow model confusion matrix.png" width="500" height="400" alt="Output layer bias backpropagation">
      <p>Tensor flow model confusion matrix</p>
      <p>Precision: 0.7171
        <br/>
        Accuracy: 0.6920 
        <br/>
        Sensitivity (Recall): 0.6049</p>
    </td>
  </tr>
</table>
<br/>
<div align="center" style="display:flex;flex-direction:row;align-items: center;">
  <img style="margin:10;" src="https://github.com/tohidnoori/Ann-from-scratch/blob/main/images/Roc-auc.png" width="600" height="500" alt="Image 1">
<div/>
<p>Roc-auc curve</p>
