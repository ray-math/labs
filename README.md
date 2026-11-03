# RayMath Labs

운동 데이터와 확률을 직접 탐구하는 두 실험실을 한곳에 모았습니다.

**[Labs 열기](https://ray-math.github.io/labs/)**

| 실험실 | 기능 | 바로 가기 |
| --- | --- | --- |
| Motion Lab | 스마트폰 운동 데이터 분석, 진로별 탐구, 보고서 다운로드 | [운동 실험실](https://ray-math.github.io/labs/motion/) |
| Probability Lab | 반복 실험, 확률 추정, 큰수의 법칙 관찰 | [확률 실험실](https://ray-math.github.io/labs/probability/) |

## 구성

```text
index.html             Labs 첫 화면
motion/index.html      운동 실험실
probability/index.html 확률 실험실
```

설치나 빌드 없이 실행하는 정적 사이트입니다. `main` 브랜치 루트를 GitHub Pages로 배포하며, 푸시하면 자동으로 갱신됩니다.

로컬에서는 이 디렉터리에서 `python3 -m http.server 8765`를 실행한 후 `http://localhost:8765/`를 엽니다.

- [Motion Lab 사용 안내](motion/README.md)
- [Probability Lab 사용 안내](probability/README.md)
- [Ray 수학 블로그](https://raymath.pages.dev/)

## 이전 이력

2026-11-03에 `ray-math/motion-lab`과 `ray-math/probability-lab`의 Git 변경 이력을 보존하여 각 하위 디렉터리로 통합했습니다. 기존 주소는 새 실험실로 이동하도록 안내합니다.
