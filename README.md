# JetsonNano
update : sudo apt-get update, sudo apt-get upgrade and sudo apt-get dist-upgrade


#젯슨나노 강의 유튜브 링크
https://www.youtube.com/watch?v=zzVi_26YhwY&list=PLU0UlMBWB-GsFmx8lWXaq9mLm4n9uI1Jn

#젯슨나노 조립 및 이미지 굽
1. 쿨링팬 밑에 wfi 보드 설치
2. wifi 보드에 안테나 선 연결해야함
3. dc 전원 연결시 빼둬야 할 플라스틱 마개가 있음 ac는 그 반대
4. 이미지 굽기 링크 - https://github.com/Qengineering/Jetson-Nano-Ubuntu-20-image

5. jetpack SDK 이미지 - https://developer.nvidia.com/embedded/jetpack

# 쿨링 팬 동작
1. sudo jetson_clocks
2. sudo sh -c 'echo 100 > /sys/devices/pwm-fan/target_pwm'

# 젯슨나노에 vscode 설치하기 (Paul DeCarlo, github, ARM64 (Jetson Nano) 용)
링크 : https://github.com/toolboc/vscode/releases
     #vscode 원격접속 방법 1. ssh 연결  2. jetson@(hostname -I)  3. 비밀번호
     #vscode 원격접속 안될 때 : https://velog.io/@hong_journey/vscode-ssh-%EC%97%B0%EA%B2%B0%EC%9D%B4-%EB%90%98%EB%8B%A4-%EC%95%88-%EB%90%A0%EB%95%8C

#젯슨나노 ubuntu2004 CUDA, cudann 확인방법
1. https://beelinekim.tistory.com/98


#젯슨나노에서 라즈베리카메라 사용하기
링크 : https://jetsonhacks.com/2019/04/02/jetson-nano-raspberry-pi-camera/

# 젯슨나노에서 파이썬 가상환경 만들기 && YOLOv8 사용하기
첫번째 링크 : https://i7y.org/en/yolov8-on-jetson-nano/
두번째 유튜브 링크 : https://www.youtube.com/watch?v=joAZEUbZZy8&list=PL0WeB24qp3wZ9DE5vSIBx_8FutKlyEUs1&index=23&t=1094s 

# 젯슨나노 Coral USB 가속기 설치
- pycoral 설치 :
https://coral.ai/docs/accelerator/get-started/
- 테스트 데이타가 없을경우 :
git clone https://github.com/google-coral/test_data.git


#젯슨나노에 yolo 사용하기 (pytorch, tensorflow 있는 이미지 구워야함 꼭!!)
1. 첫번째 방법 ultralyrics 메뉴얼 따르기 (pytorch 설치 방법 포함) :
https://docs.ultralytics.com/ko/yolov5/tutorials/running_on_jetson_nano/#install-pytorch-and-torchvision
2. 두번째 방법 CSI-Camera와 함께 사용:
https://github.com/amirhosseinh77/JetsonYolo
3. 세 번째 방법  git clone ultralytics해서 yolov8 사용하기
4. 네 번째 방법 https://whiteknight3672.tistory.com/316?category=723167 yolov5 사용하기
   #ROS로 YOLO 켜기
    1. YOLOV5 - https://velog.io/@katinon/ROS-2-Foxy%EC%97%90%EC%84%9C%EC%9D%98-YOLOv5-%EC%8B%A4%ED%96%89-%EA%B0%80%EC%9D%B4%EB%93%9C
    2. YOLOV8 - https://github.com/mgonzs13/yolov8_ros 다음으로 https://developer-lionhong.tistory.com/61
        - 1. yolov8_ros -> 필요 라이브러리 다운
          2. yolov5 requirments.txt -> 필요 라이브러리 다운
             
opencv, torch, torchvision, ultralytics 제외
#젯슨나노에 opencv 설치 (velog)
1. https://velog.io/@tilkoas35/Jetson-Nano-openCV-%EC%84%A4%EC%B9%98

#ros2 패키지에 대하여
1. https://intuitive-robotics.tistory.com/175#recentComments

#Oak_d_lite 스테레오 카메라
1. Oak_d_lite python : git clone https://github.com/iftahnaf/ros2_oak_d_lite.git
2. 번외) depthai 라이브러리 : git clone https://github.com/luxonis/depthai.git
3. dephai 라이브러리 설명 : https://robofoundry.medium.com/oak-d-lite-camera-basic-setup-38a563cd594f
4. deohai AI : https://velog.io/@lcooldong/OpenCV-%EC%B9%B4%EB%A9%94%EB%9D%BC-%EC%97%B0%EA%B2%B0-%EC%9E%91%EC%84%B1-%EC%A4%91
5. .pt to .blob : https://tools.luxonis.com/

#intell realsense 스테레오 카메라
1. https://velog.io/@zzziito/Realsense-%ED%8C%8C%EC%9D%B4%EC%8D%AC%EC%9C%BC%EB%A1%9C-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0
2. https://dev.intelrealsense.com/docs/python2 (공식 사이트)




@@기본 명령어@@
1) nano(code) ~/.bashrc
2) wifi IP 알아내기 = hostname -I


@@ Visual studio code 라이브러리 @@
better comment
c/c++ , c/c++ extension pack , c/c++ themes
cmake
cmake tools
code runner
colcon task
eof mark
error lens
highlight trailing white ~
indent-rainbow
intellicode
intellicdoe api usage ~
markdown all in one
material theme
material theme icons
python, pylance, python debugger, python task provider
ros
urdf
vscode-icons
xml tools
yaml
