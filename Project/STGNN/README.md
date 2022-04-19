<table>
  <tr>
      <td colspan="6"><p align="center">STGNN</p></td>
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
     <td rowspan="6">Traffic </td>
     <td >2018.2 ICLR</td>
     <td >Li, USC, "1225"</td>
     <td ><a href="https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Diffusion+convolutional+recurrent+neural+network%3A+Data-driven+traffic+forecasting&btnG=">DCRNN(GCGRU)</a></td>
     <td >Diffusion Conv + GRU</td>
     <td > Traffic Forecasting (T'→T) - Traffic Speed(LA&BAY)<a href="https://github.com/liyaguang/DCRNN"> - tf(802*)</a> <a href="https://github.com/chnsh/DCRNN_PyTorch">torch(232*)</a></td>
  </tr>
  <tr>
     <td >2018.3</td>
     <td >Zhang,CUHK, "358"</td>
     <td ><a href="https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&as_vis=1&q=Gaan%3A+Gated+attention+networks+for+learning+on+large+and+spatiotemporal+graphs&btnG=">GaAN/GGRU</a>   vs DCRNN</td>
     <td >Attention+RNN</td>
     <td >Traffic Speed Forecaseting (J→K)- LA </td>
  </tr>
  <tr>
     <td >2018.7</td>
     <td >Yu,PKU,"1251"</td>
     <td ><a href="https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&as_vis=1&q=Spatio-temporal+graph+convolutional+networks%3A+A+deep+learning+framework+for+traffic+forecasting&btnG=">STGCN</a> vs DCRNN</td>
     <td > ChebNet/GCN+Gated 1D-Conv(GLU)</td>
     <td >Traffic forecast (M→H)-BJ&PeMS- <a href="https://github.com/VeritasYin/STGCN_IJCAI-18" >tf(613*)</a> <a href="https://github.com/FelixOpolka/STGCN-PyTorch" >torch(212*)</a></td>
  </tr>
  <tr>
     <td >2019 AAAI</td>
     <td >Geng,HKUST,"353"</td>
     <td ><a href="https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&as_vis=1&q=Spatiotemporal+multi-graph+convolution+network+for+ride-hailing+demand+forecasting&btnG=">ST-MGCN</a> vs DCRNN&STGCN</td>
     <td >Multi-graph Conv+CGRNN</td>
     <td >Ride-hailing Demand Forecasting(T→1)-BJ&SH</td>
  </tr>
  <tr>
     <td >2019.3</td>
     <td >Wu,UTC,"393"</td>
     <td ><a href="https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&as_vis=1&q=Graph+wavenet+for+deep+spatial-temporal+graph+modeling&btnG=">Graph WaveNet</a> vs DCRNN&GGRU&STGCN</td>
     <td >GCN+TCN+self-adaptive adjacency</td>
     <td >Traffic Forecasting (S→T)-LA&BAY</td>
  </tr>
   <tr>
     <td >2019 AAAI</td>
     <td >Guo,BJTU,"539"</td>
     <td ><a href="https://scholar.google.com/scholar?q=Attention+based+spatialtemporal+graph+convolutional+networks+for+traffic+flow+forecasting&inst=1597255436240989024">ASTGCN</a> vs STGCN</td>
     <td >GCN+CNN+spatial&temporal attention</td>
     <td >Traffic Flow Forecast (N→T) - PeMS</td>
  </tr>
  
  <tr>
     <td rowspan="4">Action Recog </td>
     <td >2018.1 AAAI</td>
     <td >Yan, CUHK,"1833"</td>
     <td ><a href="https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&as_vis=1&q=Spatial+temporal+graph+convolutional+networks+for+skeleton-based+action+recognition&btnG=">ST-GCN</a></td>
     <td >GCN+1D-Conv</td>
     <td >Skeleton Action Recognition (Classification)-Kinetics&NTU-RGBD<a href="https://github.com/yysijie/st-gcn?git" > torch(924*)</a></td>
  </tr>
     <tr>
     <td >2018 ECCV</td>
     <td >Wang, CMU,"530"</td>
     <td ><a href="https://openaccess.thecvf.com/content_CVPR_2019/html/Shi_Two-Stream_Adaptive_Graph_Convolutional_Networks_for_Skeleton-Based_Action_Recognition_CVPR_2019_paper.html">I3D+Joint GCN</a> vs ST-GCN</td>
     <td >Similarity GCN + ST-GCN</td>
     <td >Skeleton Action Recognition -Charades&Something-Something</a></td>
  </tr>
  
  <tr>
     <td >2019 CVPR</td>
     <td >Shi, CAS,"568"</td>
     <td ><a href="https://openaccess.thecvf.com/content_CVPR_2019/html/Shi_Two-Stream_Adaptive_Graph_Convolutional_Networks_for_Skeleton-Based_Action_Recognition_CVPR_2019_paper.html">2s-AGCN</a> vs ST-GCN</td>
     <td >Adaptive GCN(2nd info) + CNN</td>
     <td >Skeleton Action Recognition (Classification)-Kinetics&NTU-RGBD</a></td>
  </tr>
  
   <tr>
     <td >2019 CVPR</td>
     <td >Li, SJTU,"464"</td>
     <td ><a href="https://openaccess.thecvf.com/content_CVPR_2019/html/Li_Actional-Structural_Graph_Convolutional_Networks_for_Skeleton-Based_Action_Recognition_CVPR_2019_paper.html">AS-GCN</a> vs ST-GCN</td>
     <td >Adaptive GCN(2nd info) + CNN</td>
     <td >Skeleton Action Recognition (Classification)-Kinetics&NTU-RGBD</a></td>
  </tr>
  
  

  
 

  
  <tr>
     <td rowspan="1">Others </td>
     <td >2017 ICLR</td>
     <td >Seo, EPFL, "342"</td>
     <td ><a href="https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&as_vis=1&q=Structured+sequence+modeling+with+graph+convolutional+recurrent+networks&btnG=">GCRN</td>
     <td >LSTM+ChebNet</td>
     <td >Sequencing Modeling (J→K) -  moving MNIST/NLP </td>
  </tr>
  
  
   <tr>
     <td rowspan="1">Theory </td>
     <td >2021</td>
     <td >Hadou, UPenn, "1"</td>
     <td ><a href="https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&inst=1597255436240989024&q=SPACE-TIME+GRAPH+NEURAL+NETWORKS&btnG=">ST-GNN</a></td>
     <td >Diffusion Equation</td>
     <td > decentralized flocking &
unlabeled motion planning</td>
  </tr>
  
</table>
