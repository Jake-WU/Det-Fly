# Det-Fly

## Introduction
The problem of air-to-air visual detection of micro unmanned aerial vehicles (UAVs) by monocular cameras is important for many tasks such as vision-based swarming of UAVs, malicious UAV detection, and see-and-avoid systems for UAVs. 
We present a new dataset, named Det-Fly, which consists of more than 13,000 images of a flying target UAV acquired by another flying UAV (DJI Mavic2). 
Compared to the existing datasets, the proposed one is systematically designed and more comprehensive in the sense that it covers a wide range of practical scenarios with different background scenes, viewing angles, relative distance, flying altitude, and lightning conditions. 

Det-Fly involves four types of environmental background: sky, urban, field, and mountain. Each type of environmental background occupies nearly the same proportion in the entire dataset (about 20\%-30\%).
In terms of relative viewing angles, Det-Fly can be split into three categories: front view, top view, bottom view. The data proportion of the three viewing angles are, respectively, 36.4\% (front view), 32.5\% (top view), and 31.1\% (bottom view).
In terms of the sizes of the target UAV in the images, a large portion of the target UAV images in the dataset are very small. In particular, nearly half of them are smaller than 5\% of the entire image area. When the height and width of a target UAV image are smaller than 10\% of the entire image, it could be regarded as a small object, whose detection is a well-known challenging task.

## Samples show
<img src="https://github.com/Jake-WU/Det-Fly/blob/main/Images/Det-Fly.jpg" width="700" height="600" align="middle" />


# Download
We put the images and annotation files in onedrive. If you are interested in Det-Fly, you can download this dataset by the links show in below.

Annotations: https://westlakeu-my.sharepoint.com/:f:/g/personal/zhengye_westlake_edu_cn/Em9kWPCMYm1KpFHnhVOTn9UBQfQ25m0lH67xIcULuYXYHw?e=AWZfiw

JPEGImages: https://westlakeu-my.sharepoint.com/:f:/g/personal/zhengye_westlake_edu_cn/EqFYguroD9lEnVDTRkyoOJQBrHvndTQGa5f8EQurGRFUqQ?e=DXPQxN

If you have any problem about Det-Fly, please contact us. (Email: zhengye@westlake.edu.cn)


# Citation
If you use Det-Fly in an academic context, please cite the following publication:

```
@article{Det-Fly,
  author={Zheng, Ye and Chen, Zhang and Lv, Dailin and Li, Zhixing and Lan, Zhenzhong and Zhao, Shiyu},
  journal={IEEE Robotics and Automation Letters}, 
  title={Air-to-Air Visual Detection of Micro-UAVs: An Experimental Evaluation of Deep Learning}, 
  year={2021},
  volume={6},
  number={2},
  pages={1020-1027}}
```
