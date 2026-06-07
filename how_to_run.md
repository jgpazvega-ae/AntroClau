# claw-analog — как запускать и как это устроено

Минимальный агент поверх того же стека API, что и основной CLI [`claw`](rust/README.md).

## Требования

- Установленный **Rust** и **cargo**.
- Ключ API для выбранного провайдера.

## Сборка и справка

```powershell
cd D:\path\to\claw-code-main\rust
cargo build -p claw-analog
cargo run -p claw-analog -- --help
```

## Основные команды

```powershell
cargo run -p claw-analog -- -w D:\path\to\repo "Кратко опиши структуру rust/crates"
```

See the full [how_to_run.md](how_to_run.md) for all options.
