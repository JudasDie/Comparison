# Comparision
Compare performances of algorithms on Objcet Tracking Benchmarks (SOT/MOT...)
- **Single Object Tracking (SOT)**

<table class="center">
   </font>
<font size="1" face="Courier New" >
   <tr>
      <td rowspan="2";><b>Conf.<b></td>
      <td rowspan="2"><b>Trackers<b></td>
      <td><b>OTB13/15<b></td>
      <td><b>LASOT<b></td>
      <td><b>GOT10K<b></td>
      <td><b>TrackingNet<b></td>
      <td><b>VOT20<b></td>
      <td><b>VOT19<b></td>
      <td><b>VOT18<b></td>
      <td><b>VOT17<b></td>
      <td><b>VOT16<b></td>
   </tr>
   <tr>
      <td><font size="1"> <b><sup>AUC/Prep.<sup><b></td>
      <td><font size="1"> <b><sup>Succ./Prep.<sup><b></td>
      <td><font size="1"> <b><sup>AO/SR0.5/SR0.75<sup><b></td>
      <td><font size="1"> <b><sup>Succ./Prep.<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
   </tr>
   <tr>
      <td rowspan="3"><b>ECCV20<b></td>
      <td><b><a href="https://arxiv.org/pdf/2006.10721.pdf">Ocean</a><b></td>
      <td><sub>-/(0.684/0.920)<sub></td>
      <td><sub>0.560/0.566<sub></td>
      <td><sub>0.611/0.721/-<sub></td>
      <td>-</td>
      <td><sub>0.470/0.715/0.286<sub></td>
      <td><sub>0.594/0.316/0.350<sub></td>
      <td><sub>0.489/0.592/0.117<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
   </tr>
   <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
   </tr>
   <tr>
      <td rowspan="9"><b>CVPR20<b></td>
      <td><b><a href="https://arxiv.org/pdf/2004.00830v1.pdf">MAML</a><b></td>
      <td><sub>(0.714/-)/(0.712/-)<sub></td>
      <td><sub>0.523/-<sub></td>
      <td>-</td>
      <td><sub>0.757/-<sub></td>
      <td>-</td>
      <td><sub>0.637/0.421/0.295<sub></td>
      <td><sub>0.635/0.220/0.392<sub></td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1911.12836.pdf">Siam R-CNN</a><b></td>
      <td><sub>-/(0.701/0.891)<sub></td>
      <td><sub>0.648/0.722<sub></td>
      <td><sub>0.649/0.728/0.597<sub></td>
      <td><sub>0.812/0.800<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub><sub>0.609/0.220/0.408</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="http://arxiv.org/pdf/1911.08862v2.pdf">D3S</a><b></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.597/0.676/0.462<sub></td>
      <td><sub>0.728/0.664<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.640/0.150/0.489<sub></td>
      <td>-</td>
      <td><sub>0.660/0.131/0.493<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2003.12565v1.pdf">PrDiMP</a><b></td>
      <td><sub>-/(69.6/-)<sub></td>
      <td><sub>0.598/-<sub></td>
      <td><sub>0.634/0.738/0.543<sub></td>
      <td><sub>0.758/0.704<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.618/0.165/0.442<sub></td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1907.12006v3.pdf">ROAM</a><b></td>
      <td><sub>-/(0.681/0.908)<sub></td>
      <td><sub>0.447/0.445<sub></td>
      <td><sub>0.465/0.532/0.236<sub></td>
      <td><sub>0.670/0.623<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.543/0.195/0.380<sub></td>
      <td><sub>0.599/0.174/0.441<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2003.06761.pdf">SiamBAN</a><b></td>
      <td><sub>-/(0.696/0.910)<sub></td>
      <td><sub>0.514/0.598<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.602/0.396/0.327<sub></td>
      <td><sub>0.597/0.178/0.452<sub></td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2004.06711v1.pdf">SiamAttn</a><b></td>
      <td><sub>-/(0.712/0.926)<sub></td>
      <td><sub>0.560/0.648<sub></td>
      <td>-</td>
      <td><sub>0.752/-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.63/0.16/0.470<sub></td>
      <td>-</td>
      <td><sub>0.98/0.14/0.537<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Du_Correlation-Guided_Attention_for_Corner_Detection_Based_Visual_Tracking_CVPR_2020_paper.pdf">CGACD</a><b></td>
      <td><sub>-/(0.713/0.922)<sub></td>
      <td><sub>0.518/0.626<sub></td>
      <td>-</td>
      <td><sub>0.711/0.693<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.615/0.173/0.449<sub></td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1"><b>AAAI20<b></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
   </tr>
</table></font>

