# python_da_source

삼양미디어 처음 시작하는 파이썬 데이터분석 책 소스
# A. 소스코드 복제 및 다운로드
1. 소스코드 파일: 완성 소스코드파일- python_da_ml.ipynb, 실습 직접하기파일- python_da_ml_s.ipynb
- python_da_ml.ipynb,
  - https://colab.research.google.com/drive/12qzhlSlcVBHAsbq3Lsv25U9QYI7vypbz?usp=sharing
- python_da_ml_s.ipynb,
  - https://colab.research.google.com/drive/1plm21lRnjS0icUKGMNOaZTK6LVA81vBd?usp=sharing

2. 소스코드 포함 전체 실습파일: source.zip
- https://github.com/keobooks/python_da_source/blob/main/source.zip
- [Download Raw file]아이콘 버튼 클릭

# B. 실습에 필요한 추가데이터 다운로드
1. 행정구획데이터 geojson:  행정구획 사용버전, HangJeongDong_ver20241001
- 행정구획 데이터 다운로드 위치: 
  - 원본, https://github.com/vuski/admdongkor/blob/master/ver20241001/HangJeongDong_ver20241001.geojson
  - 책제공, https://drive.google.com/uc?id=14tVmVvUufsoFaCjlvuyUZYC33G0rkkev&export=download

2. 상권정보데이터, https://www.data.go.kr/data/15083033/fileData.do

# C. 각장 요약 파일: 
1. Google NotebookLM을 사용한 각 장 요약 동영상파일
- 다운로드 링크: https://drive.google.com/file/d/1IH-0WYBR0trKbhF3nExZXi8rzo9Cpitw/view?usp=drive_link

2. Google NotebookLM을 사용한 각 장 요약 슬라이드pdf파일
- 다운로드 링크: https://drive.google.com/file/d/1Aj6e85qmS1bdoL1S6PkQwnJyRIY3HIZC/view?usp=drive_link

# D. 책소스 변경사항 및 주의사항
1. 2026.4.19
   - 7장 2절 folium라이브러리 사용 지도 시각화에서 "403 Forbidden error in folium.Map" 발생시 대처방법
   - 발생이유: User-Agent/Referer변경 또는 트래픽초과로 인한 block 등의 사유 
   - 대처방법:
   - 방법1: tiles를 'CartoDB positron'로 사용: 예) folium.Map(tiles='CartoDB positron')
   - 방법2: zoom 레벨을 18미만으로 사용



