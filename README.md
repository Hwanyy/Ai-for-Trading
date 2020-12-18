# AI-For-Trading Project 1. Trading with Momentum

**Implementing a momentum trading strategy and testing to see if it has the potential to be profitable.**

이 프로젝트는 Udacity의 [AI For Trading](https://www.udacity.com/course/ai-for-trading--nd880)의 Project1 내용입니다.

## 개요
* 모멘텀 지표를 활용하여 Trading Signal을 만들고, 생성된 Signal을 주어진 time range에서 계산한 뒤, 수익률을 예상하기 위해 데이터셋에 적용한다.

* signal에 대해 Alpha가 있는지 수익률의 평균에 대해 통계적 검정을 수행한다.

* 데이터셋은 Quotemedia에서 주식 종가를 set을 활용했다.

## 내용
* Pandas 라이브러리를 활용하여 일별 종가를 월별 종가로 resampling 한다.

* 다음과 같은 Python 작업을 수행:
  - 주어진 기간에서 Best performer와 Worst Performer 종목을 추려낸다.
  - 주어진 기간에서 Best 종목을 매수하고 Worst 종목을 공매도한 샘플 포트폴리오의 수익률을 계산한다.

* T-test 검정과 p-value를 계산하여, 샘플 포트폴리오 수익률이 알파인지 아니면 단순한 무작위 기회에 따른 수익률인지 검정한다.

## Project1 - Jupyter Notebook
* [Project 1. Trading with Momentum](https://nbviewer.jupyter.org/gist/Hwanyy/e822c9d2d22c8be64e24b9ca8a4b6e27)

## 사용된 라이브러리들과 version (Dependencies)
* [requirements.txt](https://github.com/Hwanyy/Ai-for-Trading-Project-1-Trading-with-Momentum/blob/main/requirements.txt)
