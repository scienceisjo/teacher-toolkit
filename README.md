# Teacher Toolkit

승재쌤(중학교 과학교사)이 바이브코딩으로 만든 **교사 업무·수업 준비 도구 모음**입니다.
설치 없이 브라우저에서 바로 쓰는 웹도구들을 subfolder로 모아 GitHub Pages로 배포합니다.

> `class-tools`(학급 운영 도구)와 짝을 이루는, 수업 자료 제작·업무 준비용 도구 허브.

## 도구

| 도구 | 설명 | 링크 |
|---|---|---|
| **학습지 스튜디오** (`worksheet-studio/`) | A4 학습지 전용 블록형 조판기. 교사용 원본 → 학생용·정답지 자동 컴파일, 테마·다페이지·표·이미지·과학 시각화(파동 그래프·입자 모형·힘 화살표) | [열기](https://scienceisjo.github.io/teacher-toolkit/worksheet-studio/) |

## 배포

각 도구는 `<tool>/index.html` 단일 파일(자체 포함 빌드)로 배포됩니다.
GitHub Pages(main 브랜치 루트)가 `https://scienceisjo.github.io/teacher-toolkit/` 로 서빙합니다.

학습지 스튜디오 소스: Vite + React + TypeScript (별도 개발 폴더). `npm run build` → `dist/index.html`(vite-plugin-singlefile) → `worksheet-studio/index.html`로 복사.
