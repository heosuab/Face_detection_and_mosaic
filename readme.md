# Face_detection_and_mosaic
> SNS나 1인 미디어에서 사진을 업로드할 때, 배경에 의도치 않게 등장한 낯선 사람의 얼굴을 자동으로 식별하고 모자이크해주는 AI 프로그램
> <br>나도 모르게 타인의 초상권을 침해할 수 있는 일을 방지
# Results
<img src="media/results.png"><br>
> 아이유, 김수현, 윤아 3명의 사람을 학습시킨 결과
> <br> 대부분의 얼굴을 잘 식별해서 **"학습되지 않은"** 인물들의 얼굴만 모자이크(블러) 처리
# Process
<img src="media/process.PNG" width="70%" height="70%"><br>
> 각 object에 대한 training data는 한 장씩만 있어도 좋은 성능을 보임
> <br> 많은 반복학습을 필요로 하지 않아서 빠른 속도
# Requirements
~~~
pip install tensorflow face_recognition opencv-python matplotlib scikit-learn
~~~
