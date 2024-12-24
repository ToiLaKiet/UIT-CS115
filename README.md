<!-- Banner -->
<p align="center">
  <a href="https://www.uit.edu.vn/" title="Trường Đại học Công nghệ Thông tin" style="border: none;">
    <img src="https://i.imgur.com/WmMnSRt.png" alt="Trường Đại học Công nghệ Thông tin | University of Information Technology">
  </a>
</p>

<!-- Title -->
<h1 align="center"><b>CS115 - TOÁN CHO KHOA HỌC MÁY TÍNH</b></h1>
<h1 align="center"><b>MATH FOR COMPUTER SCIENCE</b></h1>

[![Status](https://img.shields.io/badge/status-woking-brightgreen?style=flat-square)](https://github.com/ToiLaKiet/UIT-CS115)
[![GitHub contributors](https://img.shields.io/github/contributors/ToiLaKiet/UIT-CS115?style=flat-square)](https://github.com/ToiLaKiet/UIT-CS115/graphs/contributors)
[![Status](https://img.shields.io/badge/language-python-green?style=flat-square)](https://github.com/ToiLaKiet/UIT-CS115)

## BẢNG MỤC LỤC
* [Giới thiệu môn học](#giới-thiệu-môn-học)
* [Giới thiệu nhóm](#giới-thiệu-nhóm)
* [Giới thiệu đề tài](#giới-thiệu-đề-tài)
* [Cài đặt](#cài-đặt)
    - [Requirements](#requirements)
    - [Installation](#installation)
    - [Usage](#usage)
* [Demo](#demo)
* [Tài liệu tham khảo](#tài-liệu-tham-khảo)

## GIỚI THIỆU MÔN HỌC
* **Tên môn học:** TOÁN CHO KHOA HỌC MÁY TÍNH - MATH FOR CS
* **Mã môn học:** CS115
* **Mã lớp:** CS115.P11
* **Năm học:** HK1 (2024 - 2025)
* **Giảng viên:** TS. Dương Việt Hằng - *hangvd@uit.edu.vn*

## GIỚI THIỆU NHÓM
| STT | Họ tên | MSSV | Vai trò | Email | Github | Facebook |
| :---: | --- | --- | --- | --- | --- | --- |
| 1 | Võ Anh Kiệt | 23520825 | Thành viên | 23520825@gm.uit.edu.vn | [toilakiet](https://github.com/ToiLaKiet) | [phuwowngnef](https://www.facebook.com/voanhkiet05) |
| 2 | Lê Phú Quý | 19520214 | Thành viên | 19520214@gm.uit.edu.vn | [caohungphu](https://github.com/caohungphu) | [caohungphuvn](https://www.facebook.com/caohungphuvn) |
| 3 | Trần Tuấn Kiệt | 19520195 | Thành viên | 19520195@gm.uit.edu.vn | [nhalq](https://github.com/nhalq) | [qnhane](https://www.facebook.com/qnhane) |
| 4 | Phạm Tài Lộc | 19520195 | Thành viên | 19520195@gm.uit.edu.vn | [nhalq](https://github.com/nhalq) | [qnhane](https://www.facebook.com/qnhane) |

## GIỚI THIỆU ĐỀ TÀI
* **Tên đề tài:** Policy Gradient For Reinforcement Learning
* **Mô tả đề tài:** Hệ thống phát hiện tiếp xúc gần sử dụng dữ liệu từ các video (video có sẵn được triết xuất từ các camera,...) sau đó dữ liệu sẽ được cắt ra từng frame ảnh để phát hiện tiếp xúc gần thông qua việc xác định các đối tượng là người trong ảnh sau đó sẽ tính khoảng cách giữa các cặp người.

## CÀI ĐẶT
- Mô hình sử dụng pretrain model YoloV5 để phát hiện vật thể (người) [[1]](#tài-liệu-tham-khảo)

### Requirements
* **Language:** Python 3
* **Library:** 
```sh
matplotlib>=3.2.2
numpy>=1.18.5
opencv-python>=4.1.2
Pillow>=8.0.0
PyYAML>=5.3.1
scipy>=1.4.1
torch>=1.7.0
torchvision>=0.8.1
tqdm>=4.41.0
seaborn>=0.11.0
imutils
pandas
thop
```

### Installation
```sh
git clone https://github.com/lphuong304/CS117.L21.git
cd CS117.L21
pip install -r requirements.txt
```

### Usage
- Phát hiện image / video
```sh
python detector.py --type image --input Testcases/image_1.jpg
python detector.py --type video --input Testcases/video_1.mp4
```
- Xuất output image / video
```sh
python output.py --type image --input Testcases/image_1.jpg --output Results/image_1.jpg
python output.py --type video --input Testcases/video_1.mp4 --output Results/video_1.avi
```

## DEMO
Full demo: https://www.youtube.com/playlist?list=PLuIgPZeWJ60_27EQfdfIsNqTEDtN2DMGj

https://user-images.githubusercontent.com/63930670/131475574-32c75d09-e6b1-4f64-9b75-b786141db538.mp4

## TÀI LIỆU THAM KHẢO
- [[1] - Social Distancing Detection with Deep Learning Model](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9243478)
- [[2] - Perspective transformation](https://subscription.packtpub.com/book/web-development/9781838646301/6/ch06lvl1sec94/perspective-transformation)
- [[3] - Real-time and Accurate UAV Pedestrian Detection for Social Distancing](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9417704)
- [[4] - A Vision-based Social Distancing and Critical Density Detection System for COVID-19](https://arxiv.org/abs/2007.03578)
- [[5] - YOLOv5 | PyTorch](https://pytorch.org/hub/ultralytics_yolov5/)
