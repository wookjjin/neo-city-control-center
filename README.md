# 🏙️ NeoCity Control Center

### <center>React 19 & Vite 8 기반의 차세대 스마트 도시 자원 관리 및 실시간 모니터링 대시보드</center>

NeoCity Control Center는 도시 전역의 에너지 소비, 교통 흐름, 환경 지표를 실시간으로 시각화하고 관리하기 위한 운영자용 플랫폼입니다. 최신 프론트엔드 기술 스택을 활용하여 고성능 데이터 렌더링과 선언적인 상태 관리를 구현하는 데 초점을 맞추었습니다.

## ✨ Key Features
- **Real-time Energy Monitoring:** 구역별 전력 사용량 및 재생 에너지 발전 현황 시각화.

- **Traffic Intelligence:** 주요 교차로 혼잡도 분석 및 긴급 사고 알림 시스템.

- **Environmental Sensors:** 미세먼지(PM2.5), 소음, 온도 데이터의 지형 기반 모니터링.

- **Infrastructure Management:** 도시 시설물(CCTV, 가로등) 상태 추적 및 원격 제어 시뮬레이션.

- **Interactive Widgets** Tailwind 4 컨테이너 쿼리를 활용한 유동적인 대시보드 레이아웃.

## 🛠 Tech Stack
- **Framework:** React 19

- **Build Tool:** Vite 8

- **Language:** TypeScript

- **Routing:** React Router

- **State Management:** TanStack Query (React Query) v5

- ***Styling:*** Tailwind CSS v4 (Engine-based styling)

- **Visualization:** Recharts / Lucide React / Framer Motion / Leaflet


## 🚀 Technical Challenges & Goals
- **React 19 Action & use API:** 비동기 데이터 로딩과 폼 상태 처리를 더 선언적이고 간결하게 구현합니다.

- **Tailwind 4 Optimization:** 새로운 엔진의 성능 이점을 활용하고 CSS 변수 기반의 정교한 테마 시스템을 구축합니다.

- **Advanced Data Fetching:** TanStack Query의 낙관적 업데이트(Optimistic Updates)를 통해 실시간 제어 시 매끄러운 UX를 제공합니다.

- **Responsive Dashboard:** `Container Queries`를 도입하여 위젯의 크기에 따라 내부 차트 요소가 유동적으로 변하는 고도화된 반응형 UI를 설계합니다.

## 📂 Project Structure (Planned)
프로젝트는 도메인 중심의 계층형 구조(Features-based)를 따릅니다.

```text
src/
├── app/              # React Router Routes & Loaders
├── components/       # Shared UI Components (Atomic Design)
│   ├── charts/       # Specialized Chart Components
│   └── dashboard/    # Widget-specific Components
├── hooks/            # Custom Hooks (Logic reuse)
├── services/         # API Fetching & TanStack Query Logic
├── stores/           # Global Client State (if needed)
└── styles/           # Tailwind 4 Global Configurations
```

## 🏁 Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/neocity-control-center.git

# Install dependencies
pnpm install

# Start the development server
pnpm run dev
```
