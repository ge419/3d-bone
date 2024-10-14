# React + TypeScript + Vite

This is a new project.

TO DO (2024/10/14) Alpha Version
1) E-mail service
2) Skeleton 마무리
3) Newsletter 수동 Component 만들기
4) 디자인 마무리 후 alpha 배포
5) blog, oncology, for professional, login 임시 삭제

Beta version
1) Newsletter editing tool
2) Database
3) Login tool

Archive--------------------
1. 이메일 (파일 첨부 가능), 선택 등등
2. 언론, 사진, 논문, 동영상 업로드와 show
3. 데이터베이스
4. 네비게이션 설정
5. 결제 paypal?
6. 영어 한글 페이지
7.
---------------------------
Main branch에서 개인 branch로 merge 및 실행 순서

1. `cd` into project directory.
2. Commit/push any changes in current branch, and `git checkout main` --> `git pull`
3. `git checkout {back to personal branch}`, `git merge main`, resolve merge conflict.
4. `npm install` to install any additional packages.
5. `npm run dev` to run the website.

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: "latest",
    sourceType: "module",
    project: ["./tsconfig.json", "./tsconfig.node.json"],
    tsconfigRootDir: __dirname,
  },
};
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
