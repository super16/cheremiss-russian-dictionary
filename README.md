# Черемисско-русский словарь

Оцифрованная версия Черемисско-русского словаря В. П. Троицкого[^1] в XML-разметке согласно стандартам
[TEI](https://tei-c.org/).

[^1]: *В. П. Троицкій Черемисско-русскій словарь — Казань: Типо-литографія Императорскаго Университета, 1895*.
[Источник](https://elib.rgo.ru/handle/123456789/231229)

## Как собрать / How to build

### Unix

```bash
xmllint --xinclude --noxincludenode --format index.xml --output cheremiss-russian-dictionary.xml
```
