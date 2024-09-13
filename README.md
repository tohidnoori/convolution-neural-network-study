# Convolution neural network study
A **convolutional neural network (CNN)** is a regularized type of feed-forward neural network that learns features by itself via filter (or kernel) optimization. This type of deep learning network has been applied to process and make predictions from many different types of data including text, images and audio.
<br/>
- - - -
#### These statistics are being examined right now: ####
 * <a  href="https://www.kaggle.com/datasets/alirezaatashnejad/sad-and-happy-face-detection">Happy sad face recognition<a/>
 * ...

#### These features of CNN studied here: ####
  * MaxPooling (pool_size)
  * Kernels (also known as filters in cnn)
  * Strides (determines how many squares or pixels our filters skip when they move across the image)
  * Padding (the technique of adding extra pixels around the input image or feature map to maintain spatial dimensions during the convolution operation)
- - - -
### Images from this expirement
#### Kernel and sobel learned here
<img src="https://github.com/tohidnoori/convolution-neural-network-study/blob/main/images/kernel-applied.png" width="800" height="400">
<img src="https://github.com/tohidnoori/convolution-neural-network-study/blob/main/images/convolve-applied.png" width="800" height="400">

#### MaxPooling leaned here
<img src="https://github.com/tohidnoori/convolution-neural-network-study/blob/main/images/max_pooled_image.png" width="800" height="400">
<br/>

#### My system and colab trained model
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/tohidnoori/convolution-neural-network-study/blob/main/images/happy-sad conv colab model.png" width="500" height="400" alt="Hidden layer weight's backpropagation">
      <h3>Colab trained model</h3>
     <p>Total params: 15,767,313 <br/>
      <p>Precision: 0.9563
       <br/>
       Accuracy: 0.9548
       <br/>
       Sensitivity (Recall): 0.9459</p>
    </td>
    <td align="center">
      <img src="https://github.com/tohidnoori/convolution-neural-network-study/blob/main/images/Tensor flow model confusion matrix.png" width="500" height="400" alt="Output layer bias backpropagation">
      <h3>My system trained model</h3>
      <p>Total params: 7,886,481 <br/>
      <p>Precision: 0.6039
       <br/>
       Accuracy: 0.6482
       <br/>
       Sensitivity (Recall): 0.6831</p>
    </td>
  </tr>
</table>
