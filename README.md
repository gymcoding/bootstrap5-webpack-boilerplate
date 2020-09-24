# Bootstrap5 + WebPack4 = Boilerplate
Bootstrap5 기반 새로운 프로젝트를 시작할 때마다 기본 설정을 직접 만들지 않고도 웹 앱과 사이트를 더 빠르게 구축 할 수있는 전문적인 프런트 엔드 템플릿입니다.

이 템플릿은 Bootstrap Framework 버전 5를 기반으로 하며, 유연하고 현대적인 모듈 번들러인 Webpack을 사용합니다. 프런트 엔드 프로젝트에 대한 모든 공통 기능 (SCSS 컴파일, 자산 축소 등)이 포함되어 있습니다.

# Quick Start
1. 새 프로젝트의 새 폴더에 저장소를 복제합니다.
```sh
git clone git@github.com:gymcoding/bootstrap5-webpack-boilerplate.git my-project
```
2. 나만의 git저장소를 갖기위해 .git을 제거합니다.
```sh
cd my-project
rm -rf .git
```

3. 새 프로젝트에 맞게 package.json을 업데이트 하십시오.
```sh
{
  "name": "my-project",
  "description": "A description of my new project",
  "author": "Your Name",
  "license": "MIT"
}
```

4. 의존 모듈 설치
```sh
npm install
```

5. dev 명령 실행
```sh
npm run dev
```

# Build for production
```sh
npm run build
```