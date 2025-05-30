# Never Forget To Laugh - Carol Howe

Структура перевода книги для Weblate.

## Структура

Каждая глава - отдельный компонент в Weblate:

- `ch01-introduction/` - Chapter 1: Introduction (1 предложений)
- `ch02-appendix-two/` - Chapter 2: Appendix Two (13 предложений)
- `ch03-foreword/` - Chapter 3: Foreword (32 предложений)
- `ch04-preface/` - Chapter 4: Preface (21 предложений)
- `ch05-introduction/` - Chapter 5: Introduction (55 предложений)
- `ch06-part-i/` - Chapter 6: Part I (1 предложений)
- `ch07-chapter-1/` - Chapter 7: Chapter 1 (146 предложений)
- `ch08-chapter-2/` - Chapter 8: Chapter 2 (139 предложений)
- `ch09-chapter-3/` - Chapter 9: Chapter 3 (282 предложений)
- `ch10-chapter-4/` - Chapter 10: Chapter 4 (171 предложений)
- `ch11-chapter-5/` - Chapter 11: Chapter 5 (391 предложений)
- `ch12-chapter-6/` - Chapter 12: Chapter 6 (170 предложений)
- `ch13-chapter-7/` - Chapter 13: Chapter 7 (169 предложений)
- `ch14-chapter-8/` - Chapter 14: Chapter 8 (129 предложений)
- `ch15-part-ii/` - Chapter 15: Part II (1 предложений)
- `ch16-chapter-9/` - Chapter 16: Chapter 9 (164 предложений)
- `ch17-chapter-10/` - Chapter 17: Chapter 10 (86 предложений)
- `ch18-chapter-11/` - Chapter 18: Chapter 11 (117 предложений)
- `ch19-chapter-12/` - Chapter 19: Chapter 12 (188 предложений)
- `ch20-chapter-13/` - Chapter 20: Chapter 13 (161 предложений)
- `ch21-chapter-14/` - Chapter 21: Chapter 14 (74 предложений)
- `ch22-part-iii/` - Chapter 22: Part III (1 предложений)
- `ch23-chapter-15/` - Chapter 23: Chapter 15 (194 предложений)
- `ch24-chapter-16/` - Chapter 24: Chapter 16 (235 предложений)
- `ch25-chapter-17/` - Chapter 25: Chapter 17 (66 предложений)
- `ch26-chapter-18/` - Chapter 26: Chapter 18 (259 предложений)
- `ch27-chapter-19/` - Chapter 27: Chapter 19 (204 предложений)
- `ch28-chapter-20/` - Chapter 28: Chapter 20 (94 предложений)
- `ch29-chapter-21/` - Chapter 29: Chapter 21 (311 предложений)
- `ch30-part-iv/` - Chapter 30: Part IV (1 предложений)
- `ch31-chapter-22/` - Chapter 31: Chapter 22 (118 предложений)
- `ch32-chapter-23/` - Chapter 32: Chapter 23 (281 предложений)
- `ch34-chapter-24/` - Chapter 34: Chapter 24 (84 предложений)
- `ch35-chapter-25/` - Chapter 35: Chapter 25 (144 предложений)
- `ch36-epilogue/` - Chapter 36: Epilogue (48 предложений)
- `ch37-appendix-one/` - Chapter 37: Appendix One (29 предложений)
- `ch38-appendix-two/` - Chapter 38: Appendix Two (125 предложений)
- `ch39-appendix-two/` - Chapter 39: Appendix Two (1 предложений)


## Формат

- Каждое предложение - отдельная строка для перевода
- Контекст каждого предложения - весь абзац
- Файлы: `<глава>/<язык>/messages.po`

## Использование в Weblate

1. Каждая папка главы = отдельный компонент
2. Маска файла: `*/messages.po`
3. Базовый файл: `en/messages.po`
