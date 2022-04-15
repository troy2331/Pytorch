# Pytorch

## albumentation library[ data augmentation 정리

albumentation library 소개 
https://hoya012.github.io/blog/albumentation_tutorial/

자주 쓰이는 메소드들 
- RandomResizedCrop(height, width, scale(자른 원본 크기의 크기 범위) ratio(자른 원본 종횡비의 종횡비 범위, p=default 1) 
- RandomRotate90(무작위로 0번이상 90도 회전 )
- ColorJitte이미지의 밝기,대비,채도 변경 
- GaussNoise 입력이미지에 가우스 노이즈를 적용 
- ISONoise 카메라 센서 노이즈를 적용 
- GaussianBlur 임의의 커널 크기를 갖는 가우스 필터를 사용하여 이미지를 흐리게 처리함 
- MotionBlur 임의 크기의 커널을 사용하여 입력 이미지에 모션 블러를 적용 
- ImageCompression 이미지의 jpeg webp압축을 줄임 
- RandomFog 이미지의 안개를 씌움 
- RandomGamma
- RandomRain
- RandomShadow
- RandomSnow
- RandomSunFlare
- Flip
- GridDistortion
- Perspective
