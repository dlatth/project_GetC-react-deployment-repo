# 🍽️ 한 끼 식단 카드 프로젝트 플로우 차트

## 1️⃣ 시작: 로그인

- 👉 **Google 로그인**
  - 사용자가 구글 계정으로 로그인합니다.

---

## 2️⃣ 메인 페이지: 식단 카드 캐러셀

- 👉 **메인 페이지에 진입하면** 캐러셀 형식으로 식단 카드들이 나열됩니다.
  - 🃏 **카드 내용물은 보이지 않는 상태**로, 랜덤 선택을 강조합니다.
  - 👉 **카드를 클릭 시** 랜덤으로 한 끼 식단의 내용이 표시됩니다.

---

## 3️⃣ 수정 및 삭제 버튼 (우측 상단 고정)

- 🛠️ **웹 페이지 우측 상단에 고정된 수정, 삭제 버튼** 표시.
- 👉 **버튼 클릭 시** 전체 카드의 내용물이 보이는 페이지로 이동합니다.
  - 이 페이지에서는 모든 카드를 **나열된 목록 형식으로 표시**합니다.
  - 📋 각 카드는 사용자가 **수정** 또는 **삭제**할 수 있도록 구성됩니다.

---

## 4️⃣ 한 끼 식단 상세 페이지

- 🍽️ **카드 목록에서 특정 카드를 선택하면** 해당 카드의 메뉴 및 상세 정보를 표시합니다.

  - **필요 재료 목록**
  - **레시피 단계**

- 🔍 **레시피는 모달 창**으로 따로 표시됩니다.
  - 모달 창에는 **사진/영상과 레시피 단계**를 나열합니다.
  - ❌ **닫기 버튼을 클릭**하면 모달 창이 닫힙니다.

---

## 5️⃣ 카드 생성 페이지

- 📝 **카드 생성 폼**을 통해 새로운 식단 카드를 만듭니다.

  - 메뉴 이름 입력
  - 필요 재료 추가
  - 레시피 단계 입력
  - (선택) 사진/영상 업로드

- 💾 **저장 버튼 클릭 시** 캐러셀 페이지로 돌아가 새 카드가 추가됩니다.

---

## 6️⃣ 카드 수정 및 삭제 플로우

- 🛠️ **카드 목록 페이지에서 카드 선택 시:**
  - ✏️ **수정 버튼 클릭** → [카드 수정 페이지]로 이동하여 내용 수정
  - 🗑️ **삭제 버튼 클릭** → 카드 삭제 후 [캐러셀 페이지]로 돌아감

---

## 💡 기타 기능

- 🎲 **랜덤 뽑기 기능**: 캐러셀에서 랜덤으로 선택된 카드의 내용 표시
- 📦 **모달 창 사용**: 레시피와 미디어는 모달 창으로 별도 표시
- 🔐 **로그아웃 기능**: Google 로그아웃 버튼 제공 (옵션)