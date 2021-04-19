# @developer119/use-title
NPM 배포를 학습하기 위한 간단한 프로젝트입니다
웹 브라우저의 타이틀을 바꿔주는 간단한 기능을 하는 모듈을 배포합니다

Use
```js
import "./styles.css";
import { UseTitle } from "@developer119/use-title";

export default function App() {
  const titleUpdater = UseTitle("Loading...");
  setTimeout(() => titleUpdater("Home"), 5000);
  return (
    <div className="App">
      <h1>Hello CodeSandbox</h1>
      <h2>Start editing to see some magic happen!</h2>
    </div>
  );
}
```