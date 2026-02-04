# Homebrew Tap для tg

Этот репозиторий содержит Homebrew formula для установки [tg (Tool Gateway)](https://github.com/seniorGolang/tg).

## Установка

### Рекомендуемый способ (простая команда)

```bash
# Добавить tap (только один раз)
brew tap seniorGolang/cli

# Установить tg (после tap можно использовать короткую команду)
brew install tg
```

### Альтернативный способ (одна команда)

Если не хотите добавлять tap, можно установить напрямую:

```bash
brew install seniorGolang/cli/tg
```

**Примечание:** После добавления tap (`brew tap seniorGolang/cli`) вы можете использовать короткую команду `brew install tg` для всех последующих установок и обновлений.

## Обновление

```bash
brew update
brew upgrade tg
```

## Формула

Формула находится в файле [`Formula/tg.rb`](Formula/tg.rb).

## Лицензия

См. лицензию основного проекта: https://github.com/seniorGolang/tg
