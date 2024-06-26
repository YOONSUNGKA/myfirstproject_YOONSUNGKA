# 프로젝트 개요

이 프로젝트는 여러 주피터 노트북을 사용하여 다양한 데이터 처리 및 분석 작업을 수행합니다. 각 노트북의 주요 내용과 목적은 다음과 같습니다.

## 01_API_Request_n_refine_conf_list_df.ipynb

**설명:** 이 노트북은 API 요청을 통해 데이터를 수집하고, 수집된 데이터를 정제하여 데이터프레임 형식으로 변환하는 과정을 다룹니다.

## 02_hwp_file_crawling.ipynb

**주의사항(한글파일명 관련)**
- hwp파일 크롤링 하게 되면 '국회회의록_21대_379회_1차_국회본회의.hwp' 와 같은 파일명으로 저장될 것입니다.
- 다운로드가 완료된 후 파일명을 다시 지정해야 합니다.
- 예를 들어, 첫 번째 파일은 '000. 국회회의록_21대_379회_1차_국회본회의.hwp' -> '000'으로 시작합니다.
- 끝 파일은 맨 마지막 번호로 지정합니다(예: 176번째 파일이면 “175. {*file_name}.hwp”).
- 주피터 노트북에서 숫자 정렬이 일반적인 방식과 다르므로, 회의명과 순서에 맞춰 파일명을 수작업으로 변경해야 합니다.

## 03_making_conf_speaking_DF_pt1.ipynb

**설명:** 이 노트북은 특정 회의의 발언 내용을 데이터프레임으로 만드는 첫 번째 단계를 다룹니다. 데이터 전처리 및 초기 분석이 포함됩니다.

## 03_making_conf_speaking_DF_pt2(Windows11).ipynb

**설명:** 이 노트북은 특정 회의의 발언 내용을 데이터프레임으로 만드는 두 번째 단계를 다룹니다. 윈도우 11 환경에서 실행됩니다.

## 04_join__dept_cd.ipynb

**설명:** 이 노트북은 부서 코드와 데이터를 조인하여 하나의 데이터프레임으로 결합하는 과정을 다룹니다.

## 05_produce_wordcloud.ipynb

**설명:** 이 노트북은 텍스트 데이터를 기반으로 워드클라우드를 생성하는 과정을 다룹니다. 데이터 시각화를 통해 텍스트의 주요 키워드를 쉽게 파악할 수 있습니다.
![9771032](https://github.com/YOONSUNGKA/myfirstproject_YOONSUNGKA/assets/105855568/7c90ecd1-e70c-4522-a000-4d512dc79ea0)


주피터 노트북 파일들을 기반으로 한 이 프로젝트에서 사용된 주요 기술 스택은 다음과 같습니다:

1. **Python**: 주된 프로그래밍 언어로, 데이터 처리와 분석에 사용되었습니다.
2. **Jupyter Notebook**: 데이터 과학 작업을 위한 대화형 환경으로 사용되었습니다.
3. **Pandas**: 데이터프레임을 사용하여 데이터 조작 및 분석을 수행하기 위해 사용되었습니다.
4. **NumPy**: 효율적인 수치 연산을 위해 사용되었습니다.
5. **Matplotlib**: 데이터 시각화를 위해 사용되었습니다.
6. **Requests**: API 요청을 통해 데이터를 수집하기 위해 사용되었습니다.
7. **BeautifulSoup**: HTML 및 XML 파일을 파싱하여 데이터를 크롤링하기 위해 사용되었습니다.
8. **KoNLPy**: 한국어 자연어 처리를 위해 사용되었습니다.
9. **WordCloud**: 텍스트 데이터를 시각화하기 위해 사용되었습니다.

### 각 노트북에서 사용된 주요 기술

- **01_API_Request_n_refine_conf_list_df.ipynb**
  - Python, Requests, Pandas

- **02_hwp_file_crawling.ipynb**
  - Python, BeautifulSoup, Pandas

- **03_making_conf_speaking_DF_pt1.ipynb**
  - Python, Pandas, NumPy

- **03_making_conf_speaking_DF_pt2(Windows11).ipynb**
  - Python, Pandas, NumPy

- **04_join__dept_cd.ipynb**
  - Python, Pandas

- **05_produce_wordcloud.ipynb**
  - Python, Pandas, Matplotlib, WordCloud, KoNLPy

이와 같은 기술 스택을 통해 데이터 수집, 전처리, 분석 및 시각화 작업을 수행하였습니다. 추가적인 라이브러리나 툴이 사용되었다면, 각 주피터 노트북 파일의 상단에 해당 라이브러리의 임포트 구문을 참고하여 포함할 수 있습니다.

---

각 노트북의 자세한 내용과 실행 방법은 각 파일의 주석과 설명을 참조하십시오. 이 프로젝트는 데이터 수집, 정제, 분석 및 시각화의 전체 과정을 포함하며, 각 단계는 독립적으로 또는 연속적으로 실행할 수 있습니다.
