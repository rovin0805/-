## 웹 성능 최적화 - Part. 1

- Light House를 이용한 페이지 검사
- 이미지 사이즈 최적화
- Bottleneck 코드 최적화
- Bundle 파일 탐색
- Code splitting
- 텍스트 압축

## 적용

### Bundle 파일 탐색 : `@next/bundle-analyzer`

- Before  
  ![before-bundle](assets/lecture1/before-bundle.png)
- Vscode
  ![vscode](assets/lecture1/vscode-bundle.png)
- After
  ![after-bundle](assets/lecture1/after-bundle.png)

### 폰트

> Ensure text remains visible during webfont load

- Before  
  ![before-font](assets/lecture1/before-font.png)  
  <img src="assets/lecture1/before-perf1.png" width="40%" height="30%" title="before-perf1" alt="before-perf1"></img>
  ![before-perf2](assets/lecture1/before-perf2.png)
- Vscode
  ![vscode-font1](assets/lecture1/vscode-font1.png)
  ![vscode-font2](assets/lecture1/vscode-font2.png)
- After  
  ![after-font](assets/lecture1/after-font.png)  
  <img src="assets/lecture1/after-perf1.png" width="40%" height="30%" title="after-perf1" alt="after-perf1"></img>
  ![after-perf2](assets/lecture1/after-perf2.png)

### 이미지 사이즈 최적화

> Properly size images

- Before  
  <img src="assets/lecture1/before-perf3.png" width="40%" height="30%" title="before-perf1" alt="before-perf1"></img>
  ![before-perf4](assets/lecture1/before-perf4.png)
  ![before-perf5](assets/lecture1/before-perf5.png)
