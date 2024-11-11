# Pick Car Pic 
## SK Encar 중고차 이미지 크롤러 및 이미지 분석 프로그램
이 프로젝트는 파이썬을 독학하며 처음 만들어본 중고차 사이트 이미지 크롤러 겸 인식 프로그램입니다.  
SK엔카 사이트에서 특정 카테고리에 해당하는 차량 이미지를 다운로드한 후,  
이미지에 간단한 필더를 적용할 수 있고 사물 인식을 통해 이미지를 분석할 수 있습니다.  

## 기능
- 중고차 이미지 다운로드: SK엔카 사이트에서 선택한 차량 카테고리에 해당하는 이미지를 선택한 경로에 지정한 개수만큼 다운로드합니다.
- 내장 이미지 뷰어: 프로그램에서 다운로드한 이미지를 바로 확인할 수 있고 색반전 필터, 흑백 필터를 적용할 수 있습니다.
- 사물 감지: MobileNetSSD 모델을 사용하여 `DETECT` 버튼을 클릭하면 이미지 내 사물을 감지하고 표시할 수 있습니다.

## 사용 기술
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white)

## 사용 라이브러리
- PyQt5
- OpenCV
- MobileNetSSD

## 아이콘 디자인
- 직접 Adobe Illustrator를 사용하여 제작했습니다.
