# JetsonNano
update : sudo apt-get update, sudo apt-get upgrade or sudo apt-get dist-upgrade


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

#젯슨나노 ubuntu2004 CUDA 설정 && YOLOv5 tensorRT 설정
1. https://github.com/mailrocketsystems/CudaSetupUbuntu20
2. 


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


#젯슨나노에 yolo 사용하기
1. 첫번째 방법 ultralyrics 메뉴얼 따르기 (pytorch 설치 방법 포함) :
https://docs.ultralytics.com/ko/yolov5/tutorials/running_on_jetson_nano/#install-pytorch-and-torchvision
2. 두번째 방법 CSI-Camera와 함께 사용:
https://github.com/amirhosseinh77/JetsonYolo
3. 세 번째 방법 youtube 링크:
https://www.youtube.com/watch?v=keuYwbkZz7c
4. 네 번째 방법 git clone ultralytics

#젯슨나노에 opencv 설치 (velog)
1. https://velog.io/@tilkoas35/Jetson-Nano-openCV-%EC%84%A4%EC%B9%98













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
