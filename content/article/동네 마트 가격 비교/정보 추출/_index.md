---
date: "2026-02-01T09:11:43+09:00"
draft: true
title: "정보 추출"
---

## 정보 추출

전단지에서 행사 상품, 가격 정보 등 정보를 추출하기 위한 방법들을 기록한다.

### OCR

솔직히 전단지 같은 비정형 문서의 정보 추출률은 기대하기 어려울 것 같음.
또는 추가적인 학습이 필요할듯함.

#### Paddle OCR

[PaddleOCR 한국어 성능 비교](https://github.com/yunwoong7/paddleocr-3.0-korean-test?tab=readme-ov-file)

중국 AI프레임워크 PaddlePaddle에서 만든 모델들로써 OCR, 문서 구조 추출, VL기반 OCR 모델을 비교한 레포이다.

- 속도면에서는 기본 OCR이 우위이고
- 정확도와 활용도 측면에서는 GPU가 필요한 VL이 우위인듯

온프레미스 GPU를 활용할 때 쓰면 될듯

### Google vision api
