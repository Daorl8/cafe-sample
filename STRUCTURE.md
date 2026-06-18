# STRUCTURE — cafe-sample (HARUCHI)

```
cafe-sample/
├── index.html        # 단일 파일(인라인 CSS/JS)
├── .assetsignore     # .git 등 공개 서빙 차단
├── README.md
├── STRUCTURE.md
└── CHANGELOG.md
```

## index.html 섹션 순서
1. `#popup` 입장 이벤트 팝업(닫기 가능, 1회성)
2. `.topnav` 스티키 앵커 내비(한·영 병기)
3. `#home` 히어로 — **좌우 분할**(좌 카피+CTA / 우 이미지)
4. `#menu` **메뉴-퍼스트** — 좌우 분할(좌 카테고리 / 우 시그니처 카드+가격)
5. `#about` 소개 — 좌우 분할(이미지+롱카피)
6. `#feed` 인스타 피드 그리드(6컷)
7. `#visit` 오시는 길 — 컬러 OSM 지도 + 영업시간/주소
8. `#contact` 대관·단체 **문의하기** 폼(Formspree)
9. `footer` + `.mbar` 모바일 하단바(전화/네이버예약/인스타)
10. `<script>` 팝업 닫기, 스티키 내비 솔리드, 모바일 메뉴, 스크롤 리빌(데스크탑 한정)

## 팔레트/토큰
`--green:#1E3A2B; --green-d:#15291E; --cream:#F4EFE3; --paper:#FBF8F1; --mustard:#E0A52E; --ink:#20281F; --line:#E2DBC8`
