# React + Vite サンプル
Viteを用いてReactの必要最低限の構成を作成した  
またDocker上で動作させるための設定も行った  
TypeScriptは採用していない

## 経緯
Reactアプリケーションを作るにあたって、create-react-appが公式に非推奨であるため、Viteを用いることとした  
他にもcompose.yamlを用いるなど最新の推奨設定とすることを心がけた

## 作成した手順
```
npm create vite@latest react_vite_sample
cd react_vite_sample
npm install
```
npm create viteにおける選択は  
React -> JavaScript + SWC

## 起動方法
```
docker compose up --build
```
http://localhost:5173 にアクセス
