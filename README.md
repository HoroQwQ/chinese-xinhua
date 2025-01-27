# chinese-xinhua

中华新华字典数据库和 API 。收录包括 14032 条歇后语，16142 个汉字，264434 个词语，31648 个成语。

## Project Structure

```
chinese-xinhua/
|
+- data/ <-- 数据文件夹
|  |
|  +- idiom.json <-- 成语
|  |
|  +- word.json <-- 汉字
|  |
|  +- xiehouyu.json <-- 歇后语
|  |
|  +- ci.json <-- 词语
```

## Database Introduction

### 成语 (idiom.json)

```json
[
    {
        "derivation": "语出《法华经·法师功德品》下至阿鼻地狱。”",
        "example": "但也有少数意志薄弱的……逐步上当，终至堕入～。★《上饶集中营·炼狱杂记》",
        "explanation": "阿鼻梵语的译音，意译为无间”，即痛苦无有间断之意。常用来比喻黑暗的社会和严酷的牢狱。又比喻无法摆脱的极其痛苦的境地。",
        "pinyin": "ā bí dì yù",
        "word": "阿鼻地狱",
        "abbreviation": "abdy"
    },
    ...
]
```
