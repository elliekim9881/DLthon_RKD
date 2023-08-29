# DLthon_RKD
repository for the DLthon project.

Objective : 성능향상과정 과 test&train결과에서 각 모델의 특징을 찾고 향후 해당 모델들이 application과정에서 얻을 수 있는 선호척도를 알아보자

1. Organize Data and Data Augmentation
   - Random Crop (무작위 자르기): 이미지의 일부를 무작위로 잘라내어 사용
     이를 통해 모델이 객체의 위치 변화에 덜 민감하게 됨
   - Random Flip (무작위 뒤집기): 이미지를 수평으로 무작위로 뒤집음
     객체가 뒤집혀 있는 경우에도 인식할 수 있도록 도와 줌
   - Random Rotation (무작위 회전): 이미지를 무작위 각도로 회전
     모델이 회전된 객체를 인식하는 능력을 향상 시킴
   - Color Jitter (색상 변화): 이미지의 밝기, 대비, 채도를 무작위로 변경
     다양한 조명 조건 하에서도 모델이 잘 동작하도록 도와 줌
   - Random Grayscale (무작위 흑백 변환): 이미지를 흑백으로 무작위로 변환
     모델이 색상이 아닌 다른 특성에 더 집중하도록 도와 줌
   - Gaussian Noise (가우시안 노이즈 추가): 이미지에 무작위 노이즈를 추가
     모델이 노이즈에 강인하게 만듬
3. Model Selection
4. Perform Error Analysis
5. Wrap-up
