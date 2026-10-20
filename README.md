# nextjs-starter

pnpm workspace 기반 Next.js 스타터입니다. 앱은 `apps/matthew/`, 공통 컴포넌트는 `@packages/components/`에 있습니다.

## 개발 환경

- `.nvmrc`: Node.js `v18.16.0`
- 루트 `package.json`: `pnpm@8.3.1`
- 앱: Next.js 13, React 18, TypeScript

위 버전은 저장소에 기록된 개발 환경입니다. 배포 전에는 지원 중인 런타임 및 의존성으로의 업데이트를 별도 검토하세요.

## 설치 및 실행

저장소 루트에서 의존성을 설치하고 앱 디렉터리에서 실행합니다.

```bash
pnpm install
cd apps/matthew
pnpm dev
```

개발 서버: http://localhost:3000

앱 디렉터리에서 사용할 수 있는 명령:

- `pnpm build`: 프로덕션 빌드
- `pnpm start`: 빌드 결과 실행
- `pnpm lint`: 린트 검사

루트에는 `dev` 또는 `build` 스크립트가 없습니다. 앱별 명령은 해당 디렉터리에서 실행하세요. 추가 앱 설명은 [apps/matthew/README.md](apps/matthew/README.md)를 참고하세요.
