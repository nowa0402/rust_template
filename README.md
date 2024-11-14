# rust_template

Rust用開発テンプレート

## VsCode Setting

- [settings.json](./.vscode/settings.json)

### extensions

- [vadimcn.vscode-lldb](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb)
- [rust-lang.rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
- [fill-labs.dependi](https://marketplace.visualstudio.com/items?itemName=fill-labs.dependi)

## cargo

```bash
# 新しいプロジェクトを作る
cargo new <project_name>
# ライブラリのとき
cargo new <project_name> --lib

# 実行する
cd <project_name>
cargo run
```

ビルド関係

```bash
# コンパイルチェック
cargo check

# ビルドのみ
cargo build

# ビルドと実行
cargo run
```

テスト

```bash
cargo test
```

バージョンアップ

```bash
rustup update
```
