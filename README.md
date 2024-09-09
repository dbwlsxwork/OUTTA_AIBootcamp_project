# OUTTA_AIBootcamp_project

이 프로젝트는 2024 제 3회 OUTTA AI 부트캠프 딥러닝 Basic반의 최종 팀 프로젝트를 위한 스켈레톤 코드입니다.

해당 프로젝트는 총 3개의 세부 프로젝트로 구성되어 있습니다.

## Team
<table>
    <tbody>
        <tr>
            <td align="center">
                <a href="https://github.com/uzlnee">
                    <img src="https://github.com/uzlnee.png" width="100px;" alt=""/><br />
                    <sub><b>dbwlsxwork </b></sub>
                </a><br />
                <sub>정유진</sub>
            </td>
            <td align="center">
                <a href="https://github.com/sunghp">
                    <img src="https://github.com/sunghp.png" width="100px;" alt=""/><br />
                    <sub><b>sunghp </b></sub>
                </a><br />
                <sub>박성호</sub>
            </td>
            <td align="center">
                <a href="https://github.com/OhJin-Soo">
                    <img src="https://github.com/OhJin-Soo.png" width="100px;" alt=""/><br />
                    <sub><b>OhJin-Soo </b></sub>
                </a><br />
                <sub>오진수</sub>
            </td>
            <td align="center">
                <a href="https://github.com/yim3001">
                    <img src="https://github.com/yim3001.png" width="100px;" alt=""/><br />
                    <sub><b>yim3001 </b></sub>
                </a><br />
                <sub>임은석</sub>
            </td>
        </tr>
    </tbody>
</table>

## [P1] Sign Language Classification
Drop-In Replacement for MNIS for Hand Gesture Recognition Tasks

* 본 프로젝트를 위해 사전학습된 VGG16을 사용하여 프로젝트를 수행하세요.
* VGG16을 제외한 타 모델은 사용하지 않는다.

### Sign Language MNIST 데이터셋
Sign Language MNIST는 수화 인식 문제를 다루는 데이터셋입니다. 이 데이터셋은 24가지 클래스로 구성된 28x28 픽셀의 그레이스케일 손 제스처 이미지로 구성되어 있습니다. 각 클래스는 알파벳 A부터 Z까지 나타내지만, 제스처 동작이 필요한 J와 Z는 제외됩니다. 

제공되는 1D data는 (Height, Width) 형태의 data를 1D로 펼친 것입니다.


## [P2] Real and Fake Job Postings
Dataset of real and fake job postings

* 본 프로젝트를 위해 사전학습된 BERT를 사용하여 프로젝트를 수행하세요.
* BERT를 제외한 타 모델은 사용하지 않는다. 
* Tokenizer는 BERT Tokenizer를 사용해야 한다.

### Real or Fake? Fake Job Posting Prediction 데이터셋
이 데이터셋은 실제 또는 가짜 구인 공고를 예측하는 문제를 다룹니다. 다양한 특성을 가진 구인 공고 데이터가 포함되어 있으며, 각 공고가 실제인지 가짜인지 나타내는 라벨이 포함되어 있습니다. 데이터는 구인 정보의 신뢰성을 평가하는 데 사용될 수 있으며, 가짜 구인 공고를 탐지하는 모델을 학습하는 데 유용합니다.

## [P3] Music Genre Classification
Classify music genres using datasets collected from a variety of sources, including personal CDs, radio, microphone recordings, and more.

### GTZAN Dataset - Music Genre Classification 데이터셋
GTZAN 데이터셋은 음악 장르 분류 문제를 다루는 데이터셋입니다. 이 데이터셋은 머신 러닝 및 딥 러닝 알고리즘을 사용하여 음악의 장르를 자동으로 분류하는 모델을 학습하고 평가하는 데 널리 사용됩니다.

이 데이터셋에는 10개의 장르가 포함되어 있으며, 각 장르는 100개의 30초 길이의 오디오 파일로 구성되어 있습니다. 데이터는 원래 Marsyas 소프트웨어 프레임워크의 일부로 제공되었으며, 다양한 연구 및 학습 목적으로 사용됩니다.

## Reference
본 프로젝트는 OUTTA AI Bootcamp에서 제공된 자료입니다.