# Diff-SVC-Tools

## 음원 자르기 툴
#### ffmpeg 필요

> sep_wav.py

  1. 음원 노멀라이징
  2. 음원을 지정된 시간으로 슬라이스
  3. 자동 무음제거 (파일단위 무음제거 또는 파일내부 샘플 단위 무음제거 가능)

## 모델 사용(infer) 도움 스크립트

> infer_mod.py

  1. 모델 리스트 작성 (여러 모델 연속해서 출력 가능)
  2. raw 내부의 wav 파일을 모두 가져옴
  3. wav 파일 마다 각각의 옵션 생성 (global key 조절 가능)
  4. results 폴더에 결과 저장
