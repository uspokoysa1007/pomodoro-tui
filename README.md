# pomodoro-tui

Pomodoro-таймер с TUI и статистикой на Rust (ratatui).

## Возможности (план)

- циклы 25/5 с настраиваемыми интервалами;
- крупный таймер в терминале;
- статистика: помодоров за день/неделю (SQLite);
- уведомление об окончании (desktop notification);
- пауза/пропуск/сброс.

## Стек

- Язык: Rust
- Планируемые библиотеки: `ratatui`, `crossterm`, `rusqlite`, `notify-rust`

## Сборка и запуск

```bash
cargo build --release
cargo run --release
```

## Лицензия

MIT
