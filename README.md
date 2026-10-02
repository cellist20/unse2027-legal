# legal/ — 개인정보처리방침·이용약관

GitHub Pages(공개 저장소 `cellist20/unse2027-legal`)로 서빙한다. 이 폴더가 원본이고, 배포는 subtree push.

- https://cellist20.github.io/unse2027-legal/privacy.html
- https://cellist20.github.io/unse2027-legal/terms.html

```bash
# 최초 1회: 원격 추가
git remote add legal-pages https://github.com/cellist20/unse2027-legal.git
# 수정 후 메인 저장소에 커밋하고 나서
git subtree push --prefix=legal legal-pages main
```

Play Console의 "개인정보처리방침 URL"과 앱의 `TERMS_URL` / `PRIVACY_URL`(dart_define.json)에 위 주소를 쓴다.
`[운영자명 …]` 자리는 사업자등록 후 상호·대표자·사업자등록번호·통신판매업 신고번호로 채운다.
