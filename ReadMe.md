# px & em & rem

- px(절대 길이 단위) : 어떤 상황에서도 동일한 값을 유지하므로, 가변성이 없다.

- em(박스에서 텍스트 크기를 조정할 때 사용하는 상대 단위): 부모 요소의 글꼴 크기

  - ❗️ em으로 padding과 margin을 정할때는 자기 자신의 글자 크기를 기준으로 한다.

- rem(박스에서 텍스트 크기를 조정할 때 사용하는 상대 단위) : 루트 요소의 글꼴 크기

# vw, vh, vmin, vmax

뷰포트 크기를 기반으로 값을 계산하여 크기를 결정하는 가변 단위

- vw : 뷰포트 너비의 100분의 1

- vh : 뷰포트 높이의 100분의 1

- vmin : 뷰포트 높이와 너비 중 작은 쪽의 100분의 1

- vmax : 뷰포트 높이와 너비 중 큰 쪽의 100분의 1

# media query

조건을 만족했을 경우 덮어씌울 스타일 선언문

- @media 미디어타입 and (조건) {}
  - ex) @media screen and (max-width: 720px) {} -> 스크린이 720px 이하일 경우 추가 적용
