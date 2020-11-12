# Jetson_nano

Nvidia Jetson Nano로 TensorRT와 Yolo를 구동할 수 있도록 쉽게 적용시키는 쉘 스크립트.


1. git clone https://github.com/AwesomeTech-Inc/Jetson_nano
2. cd Jetson_nano
3. ./install_basics.sh
해당 작업을 진행한 이후에 자동으로 기기가 재부팅한다. 만약 자동으로 되지 않으면 직접 재부팅해주세요.
4. ./install_pycuda.sh
5. ./install_protobuf-3.8.0.sh
6. sudo pip3 install onnx==1.4.1


위의 과정이 끝나면 홈 디렉터리에 tensorRT라는 이름의 폴더가 생성된다. 

이후 과정은 
https://github.com/jkjung-avt/tensorrt_demos#demo-5-yolov4
의 3번부터 따라하자. 
