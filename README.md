# shopping-mall-cli

Using Java in 2024  
📌: KOSA 전자정부 표준 프레임워크 기반 공공프로젝트 개발 전문가 양성과정 - 콘솔 기반 쇼핑몰 프로그램

[![Last Commit](https://img.shields.io/github/last-commit/FlounderAround/shopping-mall-cli)](https://github.com/FlounderAround/shopping-mall-cli/commits/main)

## 🚀 Introduction
KOSA 과정 중 팀원과 함께 진행한 콘솔(CLI) 기반 쇼핑몰 시스템 팀 프로젝트입니다. 관리자(Admin)와 고객(Customer) 역할을 분리하여 회원가입/로그인, 카테고리 및 상품 관리, 주문 등록/수정/취소 등 쇼핑몰의 핵심 기능을 객체지향 설계로 구현했습니다. 브랜치 분리 및 병합, 코드 컨플릭트 해결까지 실제 협업 프로세스를 경험한 프로젝트입니다.

---

## ✨ Features

* 👥 **역할 기반 사용자 관리**
  `User`를 상속받는 `Admin`, `Customer`로 역할을 분리하여 각 역할에 맞는 기능 제공, 회원가입/로그인 처리

* 🗂️ **카테고리 관리**
  상품 카테고리 등록 및 삭제 (`addCategory`, `deleteCategory`)

* 📦 **상품 관리**
  상품 등록/수정/삭제 및 전체/카테고리별 상품 목록 조회 (`addItem`, `updateItem`, `deleteItem`, `showItemList`, `showItemListByCategory`)

* 🧾 **주문 관리**
  고객의 주문 등록, 수정, 취소 및 전체/개인별 주문 목록 조회 (`addCustomerOrder`, `updateCustomerOrder`, `cancelCustomerOrder`, `showOrderList`)

* 🤝 **협업 개발 프로세스**
  기능별 브랜치 분리 개발 후 병합, 코드 컨플릭트 해결 등 실제 팀 개발 워크플로우 경험

---

## 📂 Folder Structure

```plaintext
shopping-mall-cli/
└── ShoppingMission/
    └── src/
        └── shop/
            ├── Main.java           # 프로그램 진입점
            ├── ShoppingMall.java   # 핵심 비즈니스 로직 (카테고리/상품/주문 처리)
            ├── User.java           # 사용자 공통 속성 (email, password, nickname)
            ├── Admin.java          # 관리자 (User 상속)
            ├── Customer.java       # 고객 (User 상속)
            ├── Category.java       # 상품 카테고리
            ├── Item.java           # 상품
            ├── Order.java          # 주문
            └── DataInput.java      # 사용자 입력 처리
```

---

## 🛠️ Built With

* **Programming Language**: Java
* **IDE**: IntelliJ IDEA / Eclipse
* **Collaboration**: Git branch 전략 및 merge/conflict 해결

---

## 👥 Team

* [221B0825](https://github.com/221B0825)
* [gkfktkrh153](https://github.com/gkfktkrh153)

---

## 📧 Contact

* **Name**: Eunseo Yu
* **E-mail**: [eunseoyu0825@gmail.com](mailto:eunseoyu0825@gmail.com)
* **GitHub**: [221B0825](https://github.com/221B0825)
