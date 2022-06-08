# Inference steps
1. Open [Inference Code](https://colab.research.google.com/drive/1P2INtZlFJt7JKKztyXqigqL6NCNEWOox#scrollTo=qbrelPu4hd-z)
2. Download Testing Source from [here](https://drive.google.com/drive/folders/1k0VvfMVO3JIihstZkf0p0WWeydl_p1uC) and upload it to Colab
![](https://i.imgur.com/chtpaWZ.png)

4. Run all cell and you can choose source and devices on Inference cell![](https://i.imgur.com/CqPhF1H.png)

### Result
1. For image you can see inference image directly.
2. For video you will get output.mp4, you can uncomment at last cell to see result online![](https://i.imgur.com/hPTP4gc.png)


### p.s.
1. You can upload your own image or video to test,but you need to change this two variable at Testing Source setting cell
```
test_image_path = "test.jpg" #change your image name here
input_video_path = "demo.mp4" #change your video name here
```
2. Every time you upload new source, run Testing Source setting and Inference cell again.
3. When running Inference cell get this message, enter "y" to continue. ![](https://i.imgur.com/yjb1nW5.png)




# Document
* https://hackmd.io/@ArthurLee/Arthur0419
# Cite YOLOX
```
 @article{yolox2021,
  title={YOLOX: Exceeding YOLO Series in 2021},
  author={Ge, Zheng and Liu, Songtao and Wang, Feng and Li, Zeming and Sun, Jian},
  journal={arXiv preprint arXiv:2107.08430},
  year={2021}
  }
```