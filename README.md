# Object Transfiguration with CycleGAN: Resolving background distortions in images and videos

# Abstract:

Object transﬁguration is a problem that has been widely explored in the past. Signiﬁcant progress was made by CycleGAN which trains on a large number of unpaired examples to generate a mapping from one class to another. However, the method faces many problems like background distortion and hue changes. 
<br />
In images, objects can be localized by object detection. Foreground detection can do the same to moving objects in videos. In our proposed method, detection bounding boxes along with cycleGAN transformed images are used to generate the ﬁnal results. Our method performs better than vanilla cycleGAN for images. For videos,the ﬁnal transformation depends heavily on the robustness of the background subtraction algorithm.
<br />
PS: This work was done as a part of course projects for the courses Deep Learning and Digital Video Processing, the reports for the same have also been uploaded to this repository. 
