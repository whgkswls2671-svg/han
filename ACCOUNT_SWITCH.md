정리하면, 작업 내용은 거의 다 이 맥에 파일로 있어서 Claude 계정을 바꿔도 그대로 보여. 계정에 묶여 있는 건 웹 문서(아티팩트) 편집 권한하고 대화 목록, 두 가지뿐이야.

1. 같은 맥에서 계정만 바꾸기 (제일 쉬워)

* Claude 앱에서 로그아웃하고 다른 계정으로 로그인하면 돼.
* 그대로 따라오는 것:
   * 작업 폴더 `~/mosen-succession`
   * 내 기억 파일(`~/.claude/projects/-/memory`)
   * 지침 파일 `~/.claude/CLAUDE.md`
   * 스킬·플러그인
* 지금 대화 목록은 새 계정에선 안 보일 수 있어. 그래도 새 대화에서 이 한 줄이면 이어서 할 수 있어: `~/mosen-succession/RESUME.md 읽고 이어서 해`

2. 웹 문서는 편집 권한을 줘야 해

* 지금 계정이 소유자라서, 새 계정은 권한이 없으면 보기만 돼. 그 상태로 고치면 새 링크로 따로 생겨.
* 지금 계정으로 claude.ai에서 각 문서를 열고, 공유 메뉴에서 새 계정 이메일에 편집 권한을 줘:
   * 회사 사이트 https://claude.ai/artifact/KhpdyKfX5oQ398jb1Jk2XY
   * 회사소개서 덱 https://claude.ai/artifact/W3YE9ijrryv95kFmZCYvpa
   * 승계 판단 정리 https://claude.ai/artifact/FT58oge3QNYpSkGAzqMbov
   * 체크리스트 https://claude.ai/artifact/7Eq823u8tRebeNGTUMijnb
   * 합의서 https://claude.ai/artifact/Gsbws86iukUqcq4k3WKgir

3. 두 계정을 동시에 쓰고 싶으면

* 앱은 한 번에 한 계정만 돼. 터미널 Claude Code는 설정 폴더를 따로 지정하면(`CLAUDE_CONFIG_DIR`) 다른 계정으로 동시에 띄울 수 있어.
* 다만 기억·지침 폴더가 따로 생겨서 링크를 걸어 줘야 해. 원하면 내가 세팅해 줄게.
* 두 세션이 같은 파일을 동시에 고치면 서로 덮어써. 그래서 일은 나눠서 시켜.

4. 다른 컴퓨터에서 하려면

* 작업 폴더하고 기억 폴더(`~/.claude/projects/-/memory`, `~/.claude/CLAUDE.md`)를 옮겨야 해.
* 아빠 견적서·재무 자료가 들어 있어서 구글드라이브·깃허브 같은 클라우드로는 옮기지 마. 견적 폴더 README에 쓴 약속대로 암호 걸린 외장 드라이브로 옮겨.

참고

* 장기 기억용 NotebookLM 노트북은 Claude 계정이 아니라 구글 계정 기준이라 계정을 바꿔도 그대로야. 지금은 로그인이 풀려 있어.
* 그 다른 계정이 네 것이 아니라 다른 사람 거면, 아빠 견적·가족 재무 자료는 빼고 공유해야 해. 아빠한테 한 약속 범위 밖이야.

같은 맥에서 번갈아 쓸 거야, 아니면 동시에 띄울 거야? 동시에면 3번 세팅을 바로 해 줄게.
