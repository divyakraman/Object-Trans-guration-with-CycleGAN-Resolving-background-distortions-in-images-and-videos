# Object Transfiguration with CycleGAN: Resolving background distortions in images and videos
<br /><br />
Technical Report: resolveBgDistortionsCycleGAN.pdf
<br /><br />
Abstract:
<br /><br />
Object transﬁguration is a problem that has been widely explored in the past. Signiﬁcant progress was made by CycleGAN which trains on a large number of unpaired examples to generate a mapping from one class to another. However, the method faces many problems like background distortion and hue changes. 
<br /><br />
In images, objects can be localized by object detection. Foreground detection can do the same to moving objects in videos. In our proposed method, detection bounding boxes along with cycleGAN transformed images are used to generate the ﬁnal results. Our method performs better than vanilla cycleGAN for images. For videos,the ﬁnal transformation depends heavily on the robustness of the background subtraction algorithm.
<br /><br />
PS: This work was done as a part of course projects for the courses Deep Learning and Digital Video Processing, the reports for the same have also been uploaded to this repository. 
<br /><br />
Contents of the repository: <br /><br />
implementation.ipynb: Implementation of the paper  Friedman, N., Russell, S. (1997, August). Image segmentation in video sequences: A probabilistic approach. In Proceedings of the Thirteenth conference on Uncertainty in artiﬁcial intelligence (pp. 175-181). Morgan Kaufmann Publishers Inc.<br /><br />
DL_ProjectReport: Deep Learning course project report<br /><br />
DVP_ProjectReport: Digital Video Processing course project report<br /><br />
ImageAnalysis.ipynb: Code for object transfiguration in images using object detection bounding boxes <br /><br />
VideoAnalysis.ipynb: Code for object transfiguration in videos using foreground detection (applicable when the object to be transformed is the only moving object in the video)  <br /><br />

