# Avatars 마크업 과제

## 10~49행 까지는 'flex' 속성을 사용하기 위한 구조로 마크업 진행

> ### 진행사항

1. image를 4개씩 묶는 컨테이너 생성
2. flex 속성과 justify-content, align-items 속성을 통해 가로, 세로 중앙정렬
3. figure 요소안에 img 요소를 삽입하여 alt 속성은 공라으로 두는 대신
   figcaption 요소에 대체 텍스트 삽입 후 sr-only 클래스를 추가하여 스크린 리더에서만 보일 수 있도록 하였음.
4. 이미지 로딩 최적화를 위해 이미지 포맷을 jpg -> webp로 변경 후 assets/images 폴더에 저장
5. figure 요소에 가상요소(::after)를 생성하여 '상태 정보' 표시
6. 가상요소 색깔 별로 클래스 설정을 다르게하여 구분하였음.
7. 가상요소에 absolute 속성을 추가하여 right, bottom 속성으로 위치 조정
8. img 요소에 border 옵션을 주어 원 모양으로 변경

## 53~91행 까지는 'float' 속성을 사용하기 위한 구조로 마크업 진행

> ### 진행사항

1. div 요소를 사용해 전체 컨테이너 선언
2. div 요소를 사용해 image를 4개씩 묶는 컨테이너 생성
3. text-align: center 속성을 사용해 중앙 정렬
4. 각각의 img 요소를 담고 있는 div 태그에 inline-block 속성을 부여하여 횡방향 정렬 5.이미지 로딩 최적화를 위해 이미지 포맷을 jpg -> webp로 변경 후 assets/images 폴더에 저장
5. img 요소와 형제 요소로 '상태 정보'를 담고 있는 div 요소 선언
6. div 요소에 float: right 옵션 선언 후 margin-top, margin-left 속성을 통해 위치 조정
7. '상태 정보'를 나타내는 div 요소에 색깔별 클래스 (state-green, state-gray)를 부여하여 색깔 구분
8. img 요소에 border 속성을 부여하여 원 모양으로 변경

> ### 과제 링크
>
> 1. [Avatars 마크업 페이지](https://llhyeon.github.io/homework/avatars/avatars.html)
> 2. [homework 저장소](https://github.com/llhyeon/homework)
