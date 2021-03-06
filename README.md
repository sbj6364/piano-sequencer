# Piano-Sequencer
> Program that takes a text sequence and outputs the corresponding piano sequence.





## Introduction

> The source of this repository is [FutureSkill](https://futureskill.io/)의 [Contents](https://futureskill.io/content/e03834be-85b0-45a8-8cf6-f9d997c3e429)입니다.



[피아노 시퀀서 만들기 프로젝트] 를 통해서 오디오 데이터를 처리하는 기초를 공부한다.



#### 학습 목표

- **[최종] 텍스트 시퀀스를 입력받아, 해당하는 피아노 시퀀스를 출력하는 프로그램 만들기.**
- *오디오 파일 불러온 뒤 데이터 형태 파악하기*
- *librosa library를 활용한 spectrogram, chroma 등 음원의 특성 (feature) 이해하기*
- *librosa effect 를 활용한 음원 modify 연습하기.*
- *오디오 데이터 조작하기 (더하기, 붙이기, 자르기 등)*



오디오 데이터를 다룬 콘텐츠는 이미지 또는 텍스트 처럼 눈에 보이는 데이터들에 비해 매우 부족하다. 그만큼 처음 접근하기에 쉽지 않은 것도 맞는 말이다.

항상 특정한 목표를 가지고, 해당 목표를 달성해나가기 위한 Task 들을 해결해나가는 과정을 훈련하는 것이 효과적이다.

이에 '피아노 만들기' 라는 미니 프로젝트를 만들어가는 과정을 통해, 세부 과정에서 오디오 데이터를 처리하는 기초적인 테크닉을 익혀보기로 한다.



## Contents



1. wav 파일 불러오기
2. wav 파일 불러오기 (2)
3. linear spectrogram 확인
4. chroma gram 확인
5. 음원 더하기
6. 음원 붙이기
7. 음원 변형하기 - pitch
8. 음원 변형하기 - time stretch
9. 피아노 시퀀서



---

#### Reference

- [Future Skill](https://futureskill.io/)

#### Editor

- [**Colab**](https://colab.research.google.com/) / PyCharm