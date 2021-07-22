# cplusplus-workspace
M1Mac+VSCodeのC++開発環境

## Install
gccをbrewでインストールする(ここではg++-11をインストールするものとする)

```
brew install gcc
```

VSCodeのCodeRunnerをインストールする

```
code --install-extension formulahendry.code-runner
```

VSCodeのC/C++をインストールする

```
code --install-extension ms-vscode.cpptools
```

## How To Use
本リポジトリ内に配置した`.cpp`を開き、かつターミナルにフォーカスした状態で`command + alt + n`を入力すると、コンパイル+実行される

## Reference
- [Visual studio codeで競プロ環境構築[mac OS]](https://qiita.com/EngTks/items/ffa2a7b4d264e7a052c6)
