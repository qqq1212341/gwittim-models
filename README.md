# gwittim-models

귀띔(Gwittim) 앱이 내려받는 받아 적기(Whisper small) NPU 모델입니다. 퀄컴 칩별로 변환된 파일이며, 앱이 압축을 풀 수 없어 sherpa-onnx 릴리스의 `sherpa-onnx-qnn-<칩>-binary-whisper-small.tar.bz2` 를 풀어 그대로 올렸습니다. 퀄컴 QAIRT 2.40.0.251030 전용입니다.

출처: https://github.com/k2-fsa/sherpa-onnx/releases/tag/asr-models-qnn-binary-2 (k2-fsa/sherpa-onnx, Apache License 2.0 — 이 저장소의 LICENSE). 모델 원본은 OpenAI Whisper(MIT)입니다.

파일은 릴리스 `whisper-small-qnn2.40` 에 있습니다: `<칩>-encoder.bin`, `<칩>-decoder.bin`, `tokens.txt`(전 칩 공통).
