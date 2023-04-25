# dataset
사용한 데이터셋에 대한 정보가 담겨있는 디렉토리입니다.


### 사용한 데이터
[1] Person
* 그대로 사용
  * https://universe.roboflow.com/human-v2/human-dataset-v2/browse?queryText=&pageSize=50&startingIndex=0&browseQuery=true

[2] Helmet
* 헬멧 착용, 미착용이라는 두 개의 class로 나눠지므로, 헬멧 착용에 대해서만 분석하기 위해 착용 내용만 프로세싱함
  * https://universe.roboflow.com/bike-helmets/bike-helmet-detection-2vdjo/dataset/2/download/yolov8
  * 해당 폴더 내에 있는 re-helmet-roboflow 폴더 내부에 존재함
* XML 파일로 되어있어 YOLOv8 format으로 변경
  * https://www.kaggle.com/datasets/andrewmvd/helmet-detection
  * 해당 폴더 내에 있는 re-helmet-kaggle 폴더 내부에 존재함
* 기존 제공 틀에서 YOLOv8 format으로 변경
  * https://www.aicitychallenge.org/
  * 공개 데이터가 아니므로 전처리 이후 정보는 제공하지 않을 예정

[3] Scooter
* Web-crawling을 통해 데이터셋 수집

[4] Load(Segmentation)
* XML 파일로 되어있어 YOLOv8 format으로 변경함
  * AI-hub 제공 데이터셋 활용
