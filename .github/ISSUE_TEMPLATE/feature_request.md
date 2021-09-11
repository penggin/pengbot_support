name: 기능 요청
description: 있었으면 좋겠는 기능들을 추천해보세요!
title: "[요청]: "
labels: [요청]
body:
  - type: markdown
    attributes:
      value: |
        좋은 아이디어를 주셔서 감사합니다. 아래의 빈칸에 해당하는 내용을 채워주세요!
  - type: textarea
    id: des
    attributes:
      label: 기능에 대한 설명
      description: 추가를 원하는 기능에 대해서, 자세히 설명해주세요!
    validations:
      required: true
