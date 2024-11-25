# ToyVenture


## 프로젝트 개요
**ToyVenture**는 아이들을 위한 창의적인 3D 모델 장난감을 제작하고 판매하는 온라인 플랫폼입니다. 고객이 3D 모델을 직접 디자인하거나 색칠하는 과정을 통해 상상력을 키울 수 있는 경험을 제공합니다. 주요 서비스는 디지털 패키지와 실물 패키지의 판매, 커스텀 모델 제작 요청, 완성된 모델 구매 및 공유 기능입니다.
### 주요 제공 서비스
1. **디지털 색칠 놀이 패키지**
    - **구성:**
        - 고품질 3D 모델 파일 (형식: `.fbx`, `.gltf`, `.glb`, `.obj`)
        - 색칠 놀이 실습 영상
    - **사용방법:**  
        고객은 태블릿과 스타일러스 팬을 활용해 영상을 보며 3D 모델을 디지털로 색칠한 후, 이를 3D 프린터로 출력 가능합니다.
    - **사용자 친화적인 색칠 툴 추천:**  
        Blender, Substance Painter 등 3D 소프트웨어 사용법 가이드 제공.
2. **실물 색칠 놀이 패키지**
    - **구성:**
        - **KC 인증**을 받은 PVC 재질의 말랑말랑한 3D 아트토이
        - 환경 친화적 물감 세트 (5가지 색상, 기본 제공)
        - 다양한 크기와 용도의 붓 3종
    - **사용방법:**  
        실물을 직접 색칠하고 완성한 아트토이를 장식품으로 사용하거나 선물로 활용 가능.
3. **커스텀 3D 모델 요청 서비스**
    - **요청 방식:**
        - 텍스트 설명(예: "귀여운 고양이 로봇 캐릭터")
        - 스케치나 이미지를 업로드하여 디자이너와 커뮤니케이션
    - **제작 과정 제공:**  
        고객은 진행 상황을 이메일이나 플랫폼 내 알림으로 실시간 확인 가능.
    - **완성 파일 제공:**
        - `.fbx`, `.gltf`, `.glb`, `.obj` 형식으로 다운로드 가능.
4. **완성된 3D 모델 구매**
    - ToyVenture의 전시장에서 제공되는 완성된 3D 모델을 구매 가능.
    - **3D 뷰어 기능:**
        - 웹 기반 3D 뷰어 제공 (360도 회전, 확대/축소, 애니메이션 재생 지원).
    - **형식 지원:**
        - `.fbx`, `.gltf`, `.glb`, `.obj`.


## 유저 플로우
### 네비게이션 구성
1. **색칠 놀이**
    - 디지털 및 실물 패키지 탐색
    - 카테고리별 필터 및 키워드 검색 제공
    - 모델별 세부 설명 및 미리보기 제공
2. **전시장**
    - 커뮤니티의 창작물 감상
    - ToyVenture의 완성 모델 구매
3. **FAQ**
    - 사용 가이드, 환불 정책 등 고객 자주 묻는 질문 제공

### 상세 플로우
#### 1. 색칠 놀이
- **검색 및 탐색 기능**
    - 필터 옵션:
        - 카테고리(동물, 차량, 캐릭터 등)
        - 난이도(초급, 중급, 고급)
        - 모델 형식 (디지털, 실물)
    - 고급 검색: 태그 기반 및 자연어 검색 지원.
- **모델 미리보기**
    - 웹 기반 3D 모델 뷰어로 실시간 확인 가능:
        - 360도 회전, 확대/축소, 재질 미리보기
    - 다운로드 가능한 샘플 파일 제공.
#### 2. 전시장
- **커뮤니티 업로드**
    - 완성된 3D 모델 또는 실제 색칠 결과물 업로드
    - 모델별 '좋아요' 기능 제공 및 순위 표시.
- **공유 기능**
    - SNS(인스타그램, 트위터 등)와 연동하여 창작물 공유.
- **전시장 판매 페이지**
    - ToyVenture 디자이너들의 프리미엄 모델 판매.
    - 구매 고객 리뷰 및 평점 기능 제공.

## 기술 스택
### 필수 기술 스택
- **Next.js App Router**
    - 서버 사이드 렌더링(SSR) 및 동적 라우팅.
    - SEO 최적화를 통해 검색 엔진 노출 강화.
- **ShadCN UI**
    - 일관되고 현대적인 디자인 구성 요소.
    - 커스터마이징 가능한 컴포넌트로 브랜드 아이덴티티 구현.
- **TailwindCSS**
    - 유틸리티 중심의 CSS 프레임워크로 빠른 스타일링.
    - 반응형 디자인을 통한 다양한 디바이스 지원.
### 추가 기술 스택
- **TypeScript**
    - 정적 타입 시스템을 통해 코드 안정성 확보.
    - 코드 자동 완성과 디버깅 속도 향상.
- **React Hooks 및 Context API**
    - 글로벌 상태 관리 및 컴포넌트 간 데이터 공유 용이.
    - 리액티브 UI 구현.
- **로컬 스토리지(Local Storage)**
    - 사용자가 탐색한 3D 모델, 검색 기록 등을 로컬에 저장하여 재방문 시 빠른 접근 제공.
- **Axios 또는 Fetch API**
    - API 통신 안정성을 높이고 데이터 요청 처리.
- **Lucide Icons**
    - ShadCN UI와 자연스럽게 통합되는 경량 아이콘 세트.

### 추가 고려 사항
- **3D 뷰어 기술**
    - Three.js를 활용한 3D 모델 렌더링 및 애니메이션 지원.
    - GPU 최적화를 통한 성능 향상.
- **파일 업로드 및 다운로드**
    - Cloudinary 또는 AWS S3를 사용하여 안정적인 파일 저장.
    - 대용량 파일 다운로드를 위한 CDN 연동.
- **결제 시스템**
    - Stripe 또는 PayPal API 연동.
    - 지역화된 결제 방식 제공(국내 카드 결제, 해외 결제 등).
- **모바일 최적화**
    - PWA(Progressive Web App)로 개발하여 모바일 사용자 경험 개선.

## 고도화된 기능 로드맵
1. **AR(증강현실) 지원**
    - 고객이 디지털 색칠 완료 후 AR로 결과물을 확인 가능.
2. **AI 기반 추천 시스템**
    - 고객 취향에 맞는 3D 모델 및 콘텐츠 추천.
3. **커뮤니티 순위 및 배지 시스템**
    - 창작물 업로드 시 활동에 따라 레벨과 배지를 부여.
4. **플러그인 확장성**
    - Blender, Unity 등 툴과의 호환성 강화.