# Mosaic_IBM

# Mosaic Guide

## IBM Culture Game을 위해 작성해보는 깃헙!
-------------------------------

### Pillow와 numpy 설치

#### RGB값 및 데이터 분석을 위해 설치가 필요합니다. 
#### data 파일에 모자이크 재료로 사용해줄 타일 (이미지) 들을 넣어주시면 됩니다. 100장 이상의 사진이면 더 좋은 퀄리티의 사진들을 만들 수 있습니다.

``` python
python3 -m pip install --upgrade pip
python3 -m pip install --upgrade Pillow
python3 -m pip install numpy

``` 
``` python

python scripts/Mosaic_creator.py --target scripts/target.jpeg --images scripts/data/ --grid 60 60 --output ./IBM_Sangwon.jpeg

````


####이렇게 활용해주면 됩니다
