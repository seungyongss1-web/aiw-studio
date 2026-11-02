# aiw-studio — 'AI가 대체하는 세상에서 살아보기' 인스타 예약 게시

- `queue/<날짜-시각-epNN>/` 에 reel.mp4 · cover.jpg · post.json 을 넣고 `올리기.bat` 실행 → GitHub에 올라감
- GitHub Actions가 매시 7분에 예약 시각이 지난 게시물을 1개씩 인스타에 올림
- 시크릿: IG_ACCESS_TOKEN, IG_USER_ID (선택: GH_PAT — 토큰 자동 갱신용)
- 게시가 끝난 항목은 done/ 으로 옮겨지고 영상 파일은 지워짐 (원본은 ai in the world\episodes)
