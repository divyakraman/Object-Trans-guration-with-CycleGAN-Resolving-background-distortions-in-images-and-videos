# Object Transfiguration with CycleGAN: Resolving background distortions in images and videos
<br /><br />
**Technical Report: resolveBgDistortionsCycleGAN.pdf** 
<br /><br />
**Abstract:**
<br /><br />
Object transﬁguration is a problem that has been widely explored in the past. Signiﬁcant progress was made by CycleGAN which trains on a large number of unpaired examples to generate a mapping from one class to another. However, the method faces many problems like background distortion and hue changes. 
<br /><br />
In images, objects can be localized by object detection. Foreground detection can do the same to moving objects in videos. In our proposed method, detection bounding boxes along with cycleGAN transformed images are used to generate the ﬁnal results. Our method performs better than vanilla cycleGAN for images. For videos,the ﬁnal transformation depends heavily on the robustness of the background subtraction algorithm.
<br /><br />
**Contents of the repository:** <br /><br />
implementation.ipynb: Implementation of the paper "Friedman, N., Russell, S. (1997, August). Image segmentation in video sequences: A probabilistic approach. In Proceedings of the Thirteenth conference on Uncertainty in artiﬁcial intelligence (pp. 175-181). Morgan Kaufmann Publishers Inc".<br /><br />
DL_ProjectReport: Literature Survey of various style transfer methods; in-depth analysis of cycleGAN; object detection method to resolve background distortions in images when cycleGAN is applied directly.<br /><br />
DVP_ProjectReport: Literature survey of background subtraction algorithms; implementation and analysis of "Friedman, N., Russell, S. (1997, August). Image segmentation in video sequences: A probabilistic approach. In Proceedings of the Thirteenth conference on Uncertainty in artiﬁcial intelligence (pp. 175-181). Morgan Kaufmann Publishers Inc"; background subtraction to localise only moving object in a video to resolve background distortions in videos when cycleGAN is applied directly.<br /><br />
ImageAnalysis.ipynb: Code for object transfiguration in images using object detection bounding boxes <br /><br />
VideoAnalysis.ipynb: Code for object transfiguration in videos using foreground detection (applicable when the object to be transformed is the only moving object in the video)  <br /><br />

