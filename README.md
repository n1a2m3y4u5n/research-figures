# research-figures

독도 지역 조사와 에너지·모니터링 연구 발표에 쓴 인포그래픽 모음입니다.

## 소개

독도 조사 체계의 한계, 전력 구성, 환경 DNA(eDNA) 분석 과정, 개체 재식별 흐름을 그림으로 정리한 HTML/SVG 파일입니다. 각 파일은 독립 실행형이라 브라우저로 바로 열 수 있습니다.

## 파일

| 파일 | 내용 |
|---|---|
| `fig1_monitoring_limits.html` | 독도 조사 체계의 한계 (조사 빈도, 접근 가능일, 모니터링 공백) |
| `fig2_power_comparison.html` | 독도 전력 구성 비교 (현재와 파력 발전을 추가한 경우) |
| `fig3_edna_pipeline.html` | eDNA 분석 파이프라인 (해수 채취, 현장 여과, DNA 추출, NGS 시퀀싱, 종 동정) |
| `fig4_reid_flowchart.svg` | 개체 재식별 흐름도 (최초 탐지, AI 학습, DB 저장, 재식별, 재탐지, 알림) |

## 기술

- 순수 HTML, CSS, SVG
- fig2는 Chart.js 4.4.1을 CDN에서 불러옵니다 (인터넷 연결 필요)

## 실행 방법

빌드는 필요 없습니다. HTML 파일을 브라우저에서 열면 됩니다.

```bash
open fig1_monitoring_limits.html   # macOS. 다른 환경에서는 파일을 더블클릭
```
