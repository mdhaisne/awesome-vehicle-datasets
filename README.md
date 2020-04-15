# Awesome Vehicle Datasets

## Datasets


- BoxCars21k - [Website](https://medusa.fit.vutbr.cz/traffic/data/2016-CVPR-BoxCars21k-dataset.zip)
- BoxCars116k - [Website](https://medusa.fit.vutbr.cz/traffic/data/BoxCars116k.zip)
- Car Highway - [Website](http://thefuckingweather.com/)
- CompCars - [Website](http://mmlab.ie.cuhk.edu.hk/datasets/comp_cars/index.html)
- DLR Vehicle Aerial - [Website](https://www.dlr.de/eoc/en/desktopdefault.aspx/tabid-12760/22294_read-52777)
- KITTI - [Website](http://www.cvlibs.net/datasets/kitti/)
- PKU-VD - [Website](https://pkuml.org/resources/pku-vds.html)
- PKU-VehicleID - [Website](https://pkuml.org/resources/pku-vehicleid.html)
- Toy Car ReID - [Website](http://thefuckingweather.com/)
- UA-DETRAC - [Website](http://detrac-db.rit.albany.edu/)
- UTS dataset - [Website](http://thefuckingweather.com/)
- VEDAI - [Website](https://downloads.greyc.fr/vedai/)
- VehicleID - [Website](https://www.pkuml.org/resources/pku-vehicleid.html)
- Vehicle-1M - [Website](http://www.nlpr.ia.ac.cn/iva/homepage/jqwang/Vehicle1M.htm)
- VeRi-776 - [Website](https://vehiclereid.github.io/VeRi/)
- VeRi-Wild - [Website](https://github.com/PKU-IMRE/VERI-Wild)
- Virtual KITTI - [Website](https://europe.naverlabs.com/research/computer-vision/proxy-virtual-worlds-vkitti-1/)
- Virtual KITTI 2 - [Website](https://europe.naverlabs.com/research/computer-vision/proxy-virtual-worlds-vkitti-2/)
- VRIC - [Website](https://qmul-vric.github.io/)


## Details

| Name | What for | Images | Vehicles | Models | Cameras | 
| ---- | -------- | ------ | -------- | ------ | ------- |
| BoxCars21k |Fine-Grained, Classification, Reidentification|63,750|21,250|||
| BoxCars116k |Fine-Grained, Classification, Reidentification|116,826|27,496|||
| Car Highway |Detection|11,290|57,290||23|
| CompCars |Classification|214,345||1,716||
| DLR Vehicle Aerial |Detection|||||
| KITTI | Detection, tracking, Optical Flow | | | | |
| PKU-VD1 |Classification (high-res)|846,358|141,756|1,232||
| PKU-VD2 |Classification (surveillance)|690,518|79,763|1,112||
| PKU-VehicleID | Reidentification | 221,763 | 26,267 | | |
| Toy Car ReID |Reidentification|||||
| UA-DETRAC |Detection|>140,000|8,250||24|
| UTS dataset ||||||
| VEDAI |||||
| VehicleID |model Verification, reidentification|221,763|26,267|||
| Vehicle-1M |Classification|936,051|55,527|400||
| VeRi-776 |Reidentification|50,000|776||20|
| VeRi-Wild |Reidentification|416,314|40,671||174|
| Virtual KITTI (Unity)|Detection, tracking|50 videos (21,260)||||
| Virtual KITTI 2 (Unity)|Detection, tracking|||||
| VRIC |Reidentification|60,430|5,622||60|

## Citations


### BoxCars
```
@article{Sochor2018, 
	author={J. Sochor and J. Špaňhel and A. Herout}, 
	journal={IEEE Transactions on Intelligent Transportation Systems}, 
	title={BoxCars: Improving Fine-Grained Recognition of Vehicles Using 3-D Bounding Boxes in Traffic Surveillance}, 
	year={2018}, 
	volume={PP}, 
	number={99}, 
	pages={1-12}, 
	doi={10.1109/TITS.2018.2799228}, 
	ISSN={1524-9050}
}
```
### Car Highway
```
Song, H., Liang, H., Li, H. et al. Vision-based vehicle detection and counting system using deep learning in highway scenes. Eur. Transp. Res. Rev. 11, 51 (2019). https://doi.org/10.1186/s12544-019-0390-4
```

### CompCars
```
Linjie Yang, Ping Luo, Chen Change Loy, Xiaoou Tang. A Large-Scale Car Dataset for Fine-Grained Categorization and Verification, In Computer Vision and Pattern Recognition (CVPR), 2015.
```
### DLR Vehicle Area
```
```
### PKU-VD
```
@inproceedings{yan2017exploiting,
	title={Exploiting Multi-Grain Ranking Constraints for Precisely Searching Visually-Similar Vehicles},
	author={Yan, Ke and Tian, Yonghong and Wang, Yaowei and Zeng, Wei and Huang, Tiejun},
	booktitle={Proceedings of the IEEE International Conference on Computer Vision},
	pages={562--570},
	year={2017}
}
```
### PKU-VehicleID
```
@inproceedings{liu2016deep,
	title={Deep Relative Distance Learning: Tell the Difference Between Similar Vehicles},
  	author={Liu, Hongye and Tian, Yonghong and Wang, Yaowei and Pang, Lu and Huang, Tiejun},
  	booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  	pages={2167--2175},
	year={2016}
}
```
### KITTI
```
For the stereo 2012, flow 2012, odometry, object detection or tracking benchmarks, please cite:
@INPROCEEDINGS{Geiger2012CVPR,
  	author = {Andreas Geiger and Philip Lenz and Raquel Urtasun},
  	title = {Are we ready for Autonomous Driving? The KITTI Vision Benchmark Suite},
  	booktitle = {Conference on Computer Vision and Pattern Recognition (CVPR)},
  	year = {2012}
}
For the raw dataset, please cite:
@ARTICLE{Geiger2013IJRR,
  	author = {Andreas Geiger and Philip Lenz and Christoph Stiller and Raquel Urtasun},
  	title = {Vision meets Robotics: The KITTI Dataset},
  	journal = {International Journal of Robotics Research (IJRR)},
  	year = {2013}
}
For the road benchmark, please cite:
@INPROCEEDINGS{Fritsch2013ITSC,
  	author = {Jannik Fritsch and Tobias Kuehnl and Andreas Geiger},
  	title = {A New Performance Measure and Evaluation Benchmark for Road Detection Algorithms},
  	booktitle = {International Conference on Intelligent Transportation Systems (ITSC)},
  	year = {2013}
}
For the stereo 2015, flow 2015 and scene flow 2015 benchmarks, please cite:
@INPROCEEDINGS{Menze2015CVPR,
  	author = {Moritz Menze and Andreas Geiger},
  	title = {Object Scene Flow for Autonomous Vehicles},
  	booktitle = {Conference on Computer Vision and Pattern Recognition (CVPR)},
  	year = {2015}
} 
```
### UA-DETRACT
```
@article{CVIU_UA-DETRAC,
	author    = {Longyin Wen and Dawei Du and Zhaowei Cai and Zhen Lei and Ming{-}Ching Chang and
               Honggang Qi and Jongwoo Lim and Ming{-}Hsuan Yang and Siwei Lyu},
        title     = { {UA-DETRAC:} {A} New Benchmark and Protocol for Multi-Object Detection and Tracking},
        journal   = {Computer Vision and Image Understanding},
        year      = {2020}
}          
            
@inproceedings{lyu2018ua,
	title={UA-DETRAC 2018: Report of AVSS2018 \& IWT4S challenge on advanced traffic monitoring},
	author={Lyu, Siwei and Chang, Ming-Ching and Du, Dawei and Li, Wenbo and Wei, Yi and Del Coco, Marco and Carcagn{\`\i}, Pierluigi and Schumann, Arne and Munjal, Bharti and Choi, Doo-Hyun and others},
	booktitle={2018 15th IEEE International Conference on Advanced Video and Signal Based Surveillance (AVSS)},
	pages={1--6},
	year={2018},
	organization={IEEE}
}

@inproceedings{lyu2017ua,
	title={UA-DETRAC 2017: Report of AVSS2017 \& IWT4S Challenge on Advanced Traffic Monitoring},
	author={Lyu, Siwei and Chang, Ming-Ching and Du, Dawei and Wen, Longyin and Qi, Honggang and Li, Yuezun and Wei, Yi and Ke, Lipeng and Hu, Tao and Del Coco, Marco and others},
	booktitle={Advanced Video and Signal Based Surveillance (AVSS), 2017 14th IEEE International Conference on},
	pages={1--7},
	year={2017},
	organization={IEEE}
}
```

### UTS Dataset
```
Zhou, Y., Liu, L., Shao, L. and Mellor, M., 2016, October. DAVE: A Unified Framework for Fast Vehicle Detection and Annotation
```
### VEDAI
```
Vehicle Detection in Aerial Imagery: A small target detection benchmark., Sébastien Razakarivony and Frédéric Jurie, Journal of Visual Communication and Image Representation, 2015
```
### VehicleID
```
@inproceedings{liu2016deep,
	title={Deep Relative Distance Learning: Tell the Difference Between Similar Vehicles},
	author={Liu, Hongye and Tian, Yonghong and Wang, Yaowei and Pang, Lu and Huang, Tiejun},
	booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
	pages={2167--2175},
	year={2016}
}
```
### Vehicle-1M
```
Haiyun Guo, Chaoyang Zhao, Zhiwei Liu, Jinqiao Wang, Hanqing Lu: Learning coarse-to-fine structured feature embedding for vehicle re-identification. AAAI 2018.
```
### VeRi-776
```
	Xinchen Liu, Wu Liu, Huadong Ma, Huiyuan Fu: Large-scale vehicle re-identification in urban surveillance videos. ICME 2016: 1-6 (Best Student Paper Award, Citation=75)
	Xinchen Liu, Wu Liu, Tao Mei, Huadong Ma: A Deep Learning-Based Approach to Progressive Vehicle Re-identification for Urban Surveillance. ECCV (2) 2016: 869-884 (Citation=56)
	Xinchen Liu, Wu Liu, Tao Mei, Huadong Ma: PROVID: Progressive and Multimodal Vehicle Reidentification for Large-Scale Urban Surveillance. IEEE Trans. Multimedia 20(3): 645-658 (2018) (Citation=26)

```
### VeRi-Wild
```
@inproceedings{lou2019large,
	title={A Large-Scale Dataset for Vehicle Re-Identification in the Wild},
	author={Lou, Yihang and Bai, Yan and Liu, Jun and Wang, Shiqi and Duan, Ling-Yu},
	booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
	year={2019}
}
```
### Virtual KITTI 
```
@inproceedings{Gaidon:Virtual:CVPR2016,
	author = {Gaidon, A and Wang, Q and Cabon, Y and Vig, E},
	title = {Virtual Worlds as Proxy for Multi-Object Tracking Analysis},
	booktitle = {CVPR},
	year = {2016}
}
```

### Virtual KITTI 2
```
@misc{cabon2020vkitti2,
	title={Virtual KITTI 2},
	author={Cabon, Yohann and Murray, Naila and Humenberger, Martin},
	year={2020},
	eprint={2001.10773},
	archivePrefix={arXiv},
	primaryClass={cs.CV}
}
<a href="https://europe.naverlabs.com/wp-content/uploads/2020/01/vkitti2.pdf">pdf</a>
<a href="https://arxiv.org/pdf/2001.10773.pdf">arXiv</a>

@inproceedings{gaidon2016virtual,
	title={Virtual worlds as proxy for multi-object tracking analysis},
	author={Gaidon, Adrien and Wang, Qiao and Cabon, Yohann and Vig, Eleonora},
	booktitle={Proceedings of the IEEE conference on Computer Vision and Pattern Recognition},
	pages={4340--4349},
  year={2016}
}
<a href="https://europe.naverlabs.com/wp-content/uploads/ultimatemember/temp/2015-085.pdf">pdf</a>
```
### VRIC
```
@inproceedings{2018gcpr-Kanaci,
	author    = {Aytac Kanaci and Xiatian Zhu and Shaogang Gong},
	title     = {Vehicle Re-Identification in Context},
	booktitle = {Pattern Recognition - 40th German Conference, {GCPR} 2018, Stuttgart,
                         Germany, September 10-12, 2018, Proceedings},
	year      = {2018}
}
            
```