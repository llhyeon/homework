# apple 마크업 과제

---

> # 목차
>
> 1. [마크업](#마크업)
> 2. [스타일링](#스타일링)
> 3. [구현결과](#구현결과)

---

> ## 마크업

1. `Card Component` 구성은 아래와 같이 진행하였음.  
   <img src="./images/apple/card-component.png">
2. 총 7개의 `Card Component` 배치를 위해 각 컴포넌트를 감싸는 `grid-wrapper`를 선언하였음.  
   <img src="./images/apple/grid-layout.png">

---

> ## 스타일링

1. `Custom Properties`사용을 위해 `theme.css`파일을 `import`해 진행하였음  
   <img src="./images/apple/import-theme.png">
2. `Card Component`는 `flex`속성을 사용하여 작성 후 전체적인 레이아웃은 `grid`속성을 사용하였음.
3. 미디어 쿼리를 사용하여 `1024px`의 `breakpoint`를 설정하였음.
4. 가로 길이가 `1024px`이 되는 순간 아래 4개의 컴포넌트는 두 줄로 변경되게끔 구성하기 위해 `grid`속성 중
   `grid-template-area`속성을 사용하였음.  
   <img src="./images/apple/template-areas.png" width="270">

---

> ## 구현결과
