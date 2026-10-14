# HANDOVER.md (AI A -> AI B 인수인계 문서)

## 1. 목표 (Goal)
- T04 정보판 커스텀 테마/글자 크기 기능 완성 및 고정 검사 10개(TC-01~10) 통과

## 2. 현재 상태 (Current Status)
- TC-01 ~ TC-05 (다크/라이트 테마, 글자 크기 10/14/20px) 구현 완료
- Commit ID: v1.1.0-ai-a-done

## 3. 실행 명령 (Execution Commands)
- t04.html 브라우저로 열기 또는 npx serve . 실행

## 4. 통과 검사 (Passed Tests)
- TC-01, TC-02, TC-03, TC-04, TC-05 (5개 통과)

## 5. 남은 문제 (Remaining Issues)
- TC-06 ~ TC-10 미구현 (테마 색상 셀렉터, 초기화 버튼, 입력 예외 처리 등)

## 6. 다음 행동 (Next Steps)
1. t04.html 파일 열기
2. 테마 색상(#ffc107, #0d6efd) 선택 컨트롤 구현
3. 초기화 버튼 기능 구현
4. 폰트 크기 직접 입력창 및 예외 처리(10~30px) 구현

## 7. 건드리지 말 것 (Do Not Touch)
- 기존 T04 API 연동 및 Fixture 시험 로직
- 고정 검사 10개 스펙 조건