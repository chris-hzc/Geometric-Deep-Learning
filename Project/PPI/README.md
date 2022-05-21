<table>
  <tr>
      <td colspan="6"><p align="center">PPI</p></td>
  </tr>
  <tr>
      <td >Type</td>
      <td >Year</td>
      <td >Author</td>
      <td >Model</td>
      <td >Intro</td>
      <td >PS</td>
  </tr>
  <tr>
     <td rowspan="6">Partner </td>
     <td >2017 NIPS</td>
     <td >Fout, Colorado, "484"</td>
     <td ><a href="https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=Protein+interface+prediction+using+graph+convolutional+networks&btnG=">Baseline</a></td>
     <td >GNN</td>
     <td > <a href="https://github.com/fouticus/pipgcn"> tf(80*)</a>-DB5 </td>
  </tr>
  <tr>
     <td >2019 Bio</td>
     <td >Sanchez-Garcia,Spanish, "50"</td>
     <td ><a href="https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=BIPSPI%3A+a+method+for+the+prediction+of+partner-specific+protein-protein+interfaces&btnG=">BIPSPI</a> </td>
     <td >Sep-Only</td>
     <td ><a href="https://github.com/bioinsilico/BIPSPI">code(7*)</a>-DIMS-DB5-DB3 </td>
  </tr>
  <tr>
     <td >2019 NIPS</td>
     <td >Townshend,Stanford,"43"</td>
     <td ><a href="https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=End-to-end+learning+on+3d+protein+structure+for+interface+prediction&btnG=">SASNet</a> vs Baseline & BIPSPI </td>
     <td > 3DCNN</td>
     <td ><a href="https://github.com/drorlab/DIPS" >tf(46*)</a>-DB5-DIPS</td>
  </tr>
  <tr>
     <td >2020 KDD</td>
     <td >Liu,Texas A&M,"15"</td>
     <td ><a href="https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=Deep+learning+of+high-order+interactions+for+protein+interface+prediction&btnG=">high-order</a> vs Baseline & BIPSPI & SASNet   </td>
     <td >GNN+CNN</td>
     <td >DB5-DB4-DB3</td>
  </tr>
  <tr>
     <td >2021 Bio</td>
     <td >Dai,Dartmouth,"22"</td>
     <td ><a href="https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=Protein+interaction+interface+region+prediction+by+geometric+deep+learning&btnG=">Plnet</a> </td>
     <td >Point Cloud + Multiple Feature Extraction + MLP</td>
     <td ><a href="https://github.com/FTD007/PInet">code(13*)</a>-DB5-DB3</td>
  </tr>
   <tr>
     <td >2022 ICLR</td>
     <td >Morehead,Missouri,"0"</td>
     <td ><a href="https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=Geometric+Transformers+for+Protein+Interface+Contact+Prediction&btnG=">Geometric Transformer</a> </td>
     <td >GNN+Transformer</td>
     <td ><a href="https://github.com/BioinfoMachineLearning/DeepInteract">torch(29*)</a>- DIPS</td>
  </tr>
  

  
 
  
</table>
