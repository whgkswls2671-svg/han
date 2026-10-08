# Claude 계정 바꾸기 안내

작업 내용은 거의 다 이 맥에 파일로 있어서, Claude 계정을 바꿔도 그대로 보인다.
계정에 묶여 있는 건 **웹 문서(아티팩트) 편집 권한**과 **대화 목록**, 두 가지뿐이다.

## 1. 같은 맥에서 계정만 바꾸기 (제일 쉬움)

- Claude 앱에서 로그아웃하고 다른 계정으로 로그인한다.
- 그대로 따라오는 것:
  - 작업 폴더 `~/mosen-succession`
  - 기억 파일 `~/.claude/projects/-/memory`
  - 지침 파일 `~/.claude/CLAUDE.md`
  - 스킬·플러그인
- 지금 대화 목록은 새 계정에선 안 보일 수 있다. 새 대화에서 이 한 줄이면 이어서 할 수 있다:

  ```
  ~/mosen-succession/RESUME.md 읽고 이어서 해
  ```

## 2. 웹 문서는 편집 권한을 줘야 함

- 지금 계정이 소유자라서, 새 계정은 권한이 없으면 보기만 된다.
  그 상태로 고치면 원래 링크가 아니라 새 링크로 따로 생긴다.
- **계정을 바꾸기 전에**, 지금 계정으로 claude.ai에서 각 문서를 열고
  공유 메뉴에서 새 계정 이메일에 편집 권한을 준다.

| 문서 | 링크 |
| --- | --- |
| 회사 사이트 | [설계부터 양산까지](https://claude.ai/artifact/KhpdyKfX5oQ398jb1Jk2XY) |
| 회사소개서 덱 | [몰드센세이션 회사소개서 2026](https://claude.ai/artifact/W3YE9ijrryv95kFmZCYvpa) |
| 승계 판단 정리 | [승계 판단 정리](https://claude.ai/artifact/FT58oge3QNYpSkGAzqMbov) |
| 체크리스트 | [기술영업팀 만들기](https://claude.ai/artifact/7Eq823u8tRebeNGTUMijnb) |
| 합의서 | [기술영업 업무 합의서](https://claude.ai/artifact/Gsbws86iukUqcq4k3WKgir) |

## 순서 요약

1. (지금 계정) 위 문서 5개에 새 계정 이메일로 편집 권한 주기
2. Claude 앱에서 로그아웃 → 새 계정으로 로그인
3. 새 대화에서 `~/mosen-succession/RESUME.md 읽고 이어서 해`
4. 새 계정으로 위 링크를 열어 편집 권한이 보이는지 확인
