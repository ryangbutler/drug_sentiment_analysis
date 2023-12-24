# drug_sentiment_analysis

This project utilizes several well-known sentiment analysis tools:

<b>NLTK VADER</b><br>
<b>huggingface (RoBERTa)</b><br>
<b>spaCY</b><br><br>

We compare the sentiment analysis tools based on how well they align with the 1-10 rating scores, select the best model, and answer questions about the dataset based on our findings.<br><br>

### Data Schema Documentation <br>

 <table>
  <tr>
    <td><b>Field Name</b></td>
    <td><b>Type</b></td>
    <td><b>Description</b></td>
    <td><b>Example</b></td>
  </tr>
  <tr>
    <td><b>uniqueID</b></td>
    <td>int</td>
    <td>Unique Identifier for each data object</td>
    <td>163740</td>
  </tr>
  <tr>
    <td><b>drugName</b></td>
    <td>str</td>
    <td>Name of drug</td>
    <td>Mirtazapine</td>
  </tr>
  <tr>
    <td><b>condition</b></td>
    <td>str</td>
    <td>Name of patient condition</td>
    <td>Depression</td>
  </tr>
  <tr>
    <td><b>review</b></td>
    <td>str</td>
    <td>Patient review of the drug</td>
    <td>"Quick reduction of symptoms"</td>
  </tr>
  <tr>
    <td><b>rating</b></td>
    <td>int</td>
    <td>Patient rating of the drug out of 10</td>
    <td>8</td>
  </tr>
  <tr>
    <td><b>date</b></td>
    <td>datetime</td>
    <td>Date review was submitted</td>
    <td>28-Feb-12</td>
  </tr>
  <tr>
    <td><b>usefulCount</b></td>
    <td>int</td>
    <td>Number of other users who found the review helpful</td>
    <td>22</td>
  </tr>
</table> 
<br>

To set up the environment necessary to run this project (using the requirements.txt or spec-file.txt file), please refer to the Anaconda documentation here: <a href= "https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment">Conda Documentation</a><br><br>

Enjoy!<br>

-Ryan
