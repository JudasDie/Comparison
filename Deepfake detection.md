# Comparision
Compare performances of algorithms on Deepfake Detection.

<!-- #### Contents
- [Deepfake Detection]() -->

<table class="center">
   </font>
<font size="1" face="Courier New" >
    <tr>
        <td rowspan="2";><b>Conf.<b></td>
        <td rowspan="2"><b>Methods<b></td>
        <td><b>FaceForensics++ (raw)<b></td>
        <td><b>FaceForensics++ (c23)<b></td>
        <td><b>FaceForensics++ (c40)<b></td>
        <td><b>UADFV<b></td>
        <td><b>DeepfakeTIMIT-LQ<b></td>
        <td><b>DeepfakeTIMIT-HQ<b></td>
        <td><b>FaceForensic<b></td>
        <td><b>DFFD<b></td>
        <td><b>celeb-DF<b></td>
        <td><b>DFDC<b></td>
    </tr>
    <tr>
        <td><font size="1"> <b><sup>Accuracy<sup><b></td>
        <td><font size="1"> <b><sup>Accuracy/AUC<sup><b></td>
        <td><font size="1"> <b><sup>Accuracy/AUC<sup><b></td>
        <td><font size="1"> <b><sup>AUC<sup><b></td>
        <td><font size="1"> <b><sup>AUC<sup><b></td>
        <td><font size="1"> <b><sup>AUC<sup><b></td>
        <td><font size="1"> <b><sup>Accuracy<sup><b></td>
        <td><font size="1"> <b><sup>AUC/EER<sup><b></td>
        <td><font size="1"> <b><sup>AUC/EER<sup><b></td>
        <td><font size="1"> <b><sup>AUC/EER/logloss<sup><b></td>
    </tr>
    <tr>
        <td><b>CVPR21<b></td>
        <td><b><a href="https://arxiv.org/pdf/2103.02406.pdf">Multi-attentional Deepfake Detection</a><b></td>
        <td><sub>-<sub></td>
        <td><sub>97.60/99.29<sub></td>
        <td><sub>88.69/90.40<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-/-/0.1679<sub></td>
    </tr>
    <tr>
        <td><b>ECCV20<b></td>
        <td><b><a href="https://arxiv.org/pdf/2008.03412.pdf">Two-branch Recurrent Network</a><b></td>
        <td><sub>-<sub></td>
        <td><sub>96.43/99.12<sub></td>
        <td><sub>86.34/91.10<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
    </tr>
    <tr>
        <td rowspan="3"><b>FG20<b></td>
        <td><b><a href="https://hal.inria.fr/hal-02862476/document">3D ResNet</a><b></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>83.86<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
    </tr>
    <tr>
        <td><b><a href="https://hal.inria.fr/hal-02862476/document">3D ResNeXt</a><b></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>85.14<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
    </tr>
    <tr>
        <td><b><a href="https://hal.inria.fr/hal-02862476/document">I3D</a><b></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>87.43<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
    </tr>
    <tr>
        <td rowspan = "2"><b>CVPR20<b></td>
        <td><b><a href="https://arxiv.org/pdf/1910.01717.pdf">VGG16</a><b></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>96.95/8.43<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
    </tr>
    <tr>
        <td><b><a href="https://arxiv.org/pdf/1910.01717.pdf">VGG16+MAM</a><b></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>99.67/2.66<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
    </tr>
    <tr>
        <td><b>ICCV19<b></td>
        <td><b><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Rossler_FaceForensics_Learning_to_Detect_Manipulated_Facial_Images_ICCV_2019_paper.pdf">XceptionNet</a><b></td>
        <td><sub>99.26<sub></td>
        <td><sub>95.73/92.50<sub></td>
        <td><sub>81.00/86.75<sub></td>
        <td><sub>96.8<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>99.61/2.88<sub></td>
        <td><sub>83.60/28.55<sub></td>
        <td><sub>91.17/17.55/-<sub></td>
    </tr>
    <tr>
        <td><b>ICASSP19<b></td>
        <td><b><a href="https://sci-hub.st/https://ieeexplore.ieee.org/abstract/document/8683164">HeadPose</a><b></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>89<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
    </tr>
    <tr>
        <td><b>CVPRW19<b></td>
        <td><b><a href="https://openaccess.thecvf.com/content_CVPRW_2019/papers/Media%20Forensics/Li_Exposing_DeepFake_Videos_By_Detecting_Face_Warping_Artifacts_CVPRW_2019_paper.pdf">ResNet50-finetune</a><b></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>97.4<sub></td>
        <td><sub>99.9<sub></td>
        <td><sub>93.2<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
    </tr>
    <tr>
        <td><b>BTAS19<b></td>
        <td><b><a href="https://arxiv.org/pdf/1906.06876.pdf">Y-shaped Autorncoder</a><b></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>92.77<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
    </tr>
    <tr>
        <td><b>CVPRW19<b></td>
        <td><b><a href="https://openaccess.thecvf.com/content_CVPRW_2019/papers/Media%20Forensics/Li_Exposing_DeepFake_Videos_By_Detecting_Face_Warping_Artifacts_CVPRW_2019_paper.pdf">FWA</a><b></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>97.4<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
    </tr>
    <tr>
        <td><b>ICASSP19<b></td>
        <td><b><a href="https://arxiv.org/pdf/1910.12467.pdf">capsule</a><b></td>
        <td><sub>99.52<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>99.9<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>82.46/24.29<sub></td>
        <td><sub>87.45/21.39/-<sub></td>
    </tr>
    <tr>
        <td><b>WIFS18<b></td>
        <td><b><a href="https://sci-hub.st/https://ieeexplore.ieee.org/abstract/document/8630761">MesoNet</a><b></td>
        <td><sub>95.23<sub></td>
        <td><sub>83.1<sub></td>
        <td><sub>70.47<sub></td>
        <td><sub>84.3<sub></td>
        <td><sub>87.8<sub></td>
        <td><sub>68.4<sub></td>
        <td><sub>93.4<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
    </tr>
    <tr>
        <td>arxiv18</td>
        <td><b><a href="https://arxiv.org/pdf/1812.02510.pdf">ForensicTransfer</a><b></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>92.6<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
    </tr>
    <tr>
        <td><b>CVPRW17<b></td>
        <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2017_workshops/w28/papers/Davis_Two-Stream_Neural_Networks_CVPR_2017_paper.pdf">two-stream NN</a><b></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>85.1<sub></td>
        <td><sub>83.5<sub></td>
        <td><sub>73.5<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
        <td><sub>-<sub></td>
    </tr>
</table>

