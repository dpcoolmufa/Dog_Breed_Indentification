<h3> Dog Breed Indentification</h3>
A Deep Learning Neural Network model that identifies breed of a dog given an image of a dog. This model uses <a href="https://tfhub.dev/google/imagenet/mobilenet_v2_130_224/classification/4">MobileNet v2</a>.
To know more about the model click on the above link.<br>

<b>Note:</b> this project is done using google colab which provides GPU for fast processing. 
<br>

<h3>Steps to be followed:</h3>
<ol>
  <li>Open the notebook in Google colab.</li>
  <li>Goto Runtime>Change runtime type.</li>
  <li>Click GPU in the Hardware accelerator dropdown and Save the settings.</li>
  <li>To run all cell press ctrl+f9(for more options goto runtime).</li>
</ol>

<b>Note:</b> Before running the notebook download the data(<b>.zip</b>) and mount google drive in colab . Upload the file to google drive and unzip it.
if you wish to unzip the file using command.<b>Follow the below step:</b><br>
  <ul>
    <li>Modify this line of code in colab notebook.<br>
      <b>!unzip "[source file path]"  -d "[target directory]"</b>
      <br>
      ><b>[source file path]</b>-the directory where your .zip file resides<br>
      ><b>[target directory]</b>-the directory where you want to unzip the file
    </li>
  </ul>
<h3>Dataset:</h3>
<ul>
<li><a href="https://www.kaggle.com/c/dog-breed-identification/data">Dog Breed Identification Dataset</a>
</ul>



