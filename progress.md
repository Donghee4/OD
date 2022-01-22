1-17
everything done in chapter 1. Download TF Models Pretrained Models from Tensorflow Model Zoo and Install TFOD 
newer CUDA already installed -> need to downgrade??
cuDNN downloaded

#NVIDIA Install cannot continue
#you already have a newer version of the nvidia frameview sdk installed   --새 버전때문에 CUDA를 설치 못함
--> setting 에서 nvidia frameview 언인스톨 후 다시 쿠다 인스톨러를 실행

1-21
ch3 done 2:12

1-22
ch6 done, now doing ch7 evaluating 2:29

error log : CPU로 연산 후에 GPU로 연산이 안되는 상황 -> checkpoint 경로의 모든 checkpoint를 삭제해주는 GPU로 연산이 가능해짐
    검색에는 오래된 모델을 참조하기 때문에 문제가 되는 상황이고 오래된 모델의 step 문제와 관련이 있으니 새로운 모델을 참조하라고 함. 하지만 이렇게 하진 않았음

그리고 작업관리자에서 확인해봤을때 내장 GPU 를 사용하는 것처럼 보임. 외장GPU에 할당된 메모리가 커서 상대적으로 그렇게 보이는 것인지는 알 수 없음
항상 내장GPU를 400mb정도 쓰는것으로 보이고, 학습시 확연히 차이가 있는건 CPU가 90% 가까이 올라가는데 이게 GPU 가 아닌 CPU로 학습하는 것인지 검증할 필요가 잇음
