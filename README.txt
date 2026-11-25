호이스트·장비 일정 앱 (PWA) — 설치 안내

1) 이 폴더 전체를 HTTPS 정적 호스팅에 올립니다 (GitHub Pages, Netlify Drop, Cloudflare Pages 등).
   - 파일: index.html, manifest.json, sw.js, icon-192.png, icon-512.png, apple-touch-icon.png
   - 서비스워커(오프라인)는 HTTPS 또는 localhost에서만 동작합니다.
2) 안드로이드(Chrome): 주소 접속 → ⋮ 메뉴 → 앱 설치 / 홈 화면에 추가
3) 아이폰(Safari): 주소 접속 → 공유 버튼 → 홈 화면에 추가
4) 데이터는 각 기기의 브라우저(localStorage)에만 저장됩니다. 설정 > 백업하기로 주기적으로 복사해 두세요.
5) 파일을 수정해 다시 올릴 때는 sw.js 맨 위 VERSION 값을 바꿔야 휴대폰에 새 버전이 반영됩니다.
