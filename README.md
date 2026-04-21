# GitHub Pages 설정 가이드

> **목표**: TikTok API 신청에 필요한 서비스 약관 & 개인정보 처리방침 URL 생성
> **소요 시간**: 5분
> **비용**: 무료 (평생)

---

## 📦 준비된 파일

1. ✅ **index.html** - 메인 페이지 (소개)
2. ✅ **terms.html** - 서비스 이용약관 (법적 요구사항 충족)
3. ✅ **privacy.html** - 개인정보 처리방침 (한국 개인정보보호법 준수)

---

## 🚀 설치 방법 (진이 따라하기)

### Step 1: GitHub 계정 준비 (1분)

**이미 GitHub 계정이 있다면 Skip!**

없다면:
```
1. https://github.com 접속
2. "Sign up" 클릭
3. 이메일, 비밀번호 입력
4. 계정 생성 완료
```

---

### Step 2: 저장소(Repository) 만들기 (1분)

```
1. GitHub 로그인 후 오른쪽 상단 "+" 클릭
2. "New repository" 선택
3. 아래와 같이 입력:

   Repository name: 진이이름.github.io
   (예: jin-lee.github.io, hermes-ai.github.io 등)
   
   Description: Hermes AI Publisher - Legal Documents
   
   Public 체크 (✓)
   
   "Add a README file" 체크 안 함 (X)

4. "Create repository" 클릭
```

**중요**: 저장소 이름은 반드시 `이름.github.io` 형식이어야 함!

---

### Step 3: 파일 업로드 (2분)

**방법 1: 웹에서 직접 업로드 (추천)**

```
1. 방금 만든 저장소 페이지에서
2. "uploading an existing file" 클릭
3. 아래 3개 파일을 드래그 앤 드롭:
   - index.html
   - terms.html
   - privacy.html

4. 하단에 "Commit changes" 클릭
```

**방법 2: Git 사용 (진이 Git 설치되어 있다면)**

```bash
cd /Users/leejin/SHARED_WORKSPACE/outputs/hermes/github_pages/
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/진이아이디/진이이름.github.io.git
git push -u origin main
```

---

### Step 4: GitHub Pages 활성화 (1분)

```
1. 저장소 페이지에서 "Settings" 클릭
2. 왼쪽 메뉴에서 "Pages" 클릭
3. Source 섹션에서:
   - Branch: main 선택
   - Folder: / (root) 선택
4. "Save" 클릭
```

**1-2분 기다리면 자동으로 배포됨!**

---

## ✅ 완성된 URL

배포가 완료되면 다음 URL로 접속 가능:

```
메인 페이지:
https://진이이름.github.io/

서비스 약관:
https://진이이름.github.io/terms.html

개인정보 처리방침:
https://진이이름.github.io/privacy.html
```

---

## 🎯 TikTok 신청서에 입력할 URL

**Step 2 화면에서:**

1. **서비스 약관 URL** 필드에 입력:
   ```
   https://진이이름.github.io/terms.html
   ```

2. **개인정보 보호정책 URL** 필드에 입력:
   ```
   https://진이이름.github.io/privacy.html
   ```

---

## 🔍 확인 방법

배포 완료 후:
```
1. https://진이이름.github.io/ 접속
2. "서비스 이용약관" 버튼 클릭 → 약관 페이지 확인
3. "개인정보 처리방침" 버튼 클릭 → 개인정보 페이지 확인
```

모두 정상적으로 보이면 성공!

---

## ⚠️ 주의사항

1. **저장소 이름**: 반드시 `이름.github.io` 형식
2. **Public 저장소**: Private으로 하면 접근 불가
3. **배포 시간**: 첫 배포는 1-5분 소요
4. **HTTPS**: 자동으로 HTTPS 적용됨 (보안 인증서 무료)

---

## 🆘 문제 해결

### "404 Not Found" 뜨는 경우:
- 1-2분 더 기다리기 (배포 진행 중)
- Settings → Pages에서 배포 상태 확인
- 파일명 확인 (index.html, terms.html, privacy.html 정확히)

### URL 접속 안 되는 경우:
- 저장소 이름 확인 (`이름.github.io` 형식)
- Public 저장소인지 확인
- 브라우저 캐시 삭제 후 재접속

---

## 📝 다음 단계

URL 생성 완료 후:
1. TikTok 신청서로 돌아가기
2. 2개 URL 입력
3. 나머지 필드 작성
4. 제출!

---

## 💡 팁

- 한 번 만들어두면 **Instagram, Facebook, 다른 API 신청**할 때도 재사용 가능
- 내용 수정하고 싶으면 GitHub에서 파일 직접 편집 가능
- 완전 무료, 평생 사용 가능

---

**문제 생기면 헤르메스한테 스크린샷 보내줘!**
