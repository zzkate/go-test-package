# go-test-package

Пример Go-модуля: структура пакета `zaytseva_module` с вложенным подпакетом `calc`.

## Содержимое

- `zaytseva_module/go.mod` — модуль `zaytseva_module` (Go 1.27).
- `zaytseva_module/calc/math.go` — пакет `calc` с функцией `AddInts`.

## Пример

```go
package calc

func AddInts(a, b int) int {
	return a + b
}
```
