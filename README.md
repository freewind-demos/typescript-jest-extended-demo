TypeScript "jest-extended" Demo
===========================

使用jest-extended可以增加一些有用的expect语句

注意setup:
1. `jest.config.js`中增加：`setupFilesAfterEnv: ["jest-extended"]`
2. `global.d.ts`中`import 'jest-extended';`

```
npm install
npm test
```
