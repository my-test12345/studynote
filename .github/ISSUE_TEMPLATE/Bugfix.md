name: 버그 리포트
about: 프로젝트 내에서 발생한 오류 및 해결 필요 사항을 기록
title: "[버그] 버그 설명 작성"
labels: ["Bugfix"]
assignees: ''

body:
  - type: textarea
    id: bug_description
    attributes:
      label: 🐛 버그 설명
      description: 발견한 버그에 대해 설명해주세요.
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: ✅ 기대한 동작
      description: 원래 어떻게 동작해야 하는지 작성해주세요.
    validations:
      required: true

  - type: textarea
    id: actual
    attributes:
      label: ❌ 실제 동작
      description: 현재 어떻게 동작하고 있는지 작성해주세요.
    validations:
      required: true

  - type: textarea
    id: reproduction
    attributes:
      label: 🔄 재현 방법
      description: 버그를 재현하는 방법을 단계별로 설명해주세요.
    validations:
      required: true

  - type: textarea
    id: environment
    attributes:
      label: 💻 실행 환경
      description: OS, Python 버전, 실행 환경 등의 정보를 입력해주세요.
    validations:
      required: false