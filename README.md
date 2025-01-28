# chinese-xinhua
基于chinese-xinhua项目，筛选了其中四字成语并分离其每个字的拼音与音调，可以用于汉字Wordle（四字成语猜测问题）小游戏及其自动化解题器的开发。
## 数据库及其来源
数据来源于中华新华字典项目，链接：https://github.com/pwxcoo/chinese-xinhua

通过运行database_json.py创建搜索数据库idiom_data.json,其具体格式为：
```json
[
      "阿鼻地狱": {
    "word": "阿鼻地狱",
    "pinyin": "ā1 bí2 dì4 yù4",
    "pinyin_initials": "abdy",
    "characters": [
      {
        "char": "阿",
        "initial": "",
        "final": "a",
        "tone": 1,
        "position": 1
      },
      {
        "char": "鼻",
        "initial": "b",
        "final": "i",
        "tone": 2,
        "position": 2
      },
      {
        "char": "地",
        "initial": "d",
        "final": "i",
        "tone": 4,
        "position": 3
      },
      {
        "char": "狱",
        "initial": "y",
        "final": "u",
        "tone": 4,
        "position": 4
      }
    ],
    "explanation": "阿鼻梵语的译音，意译为无间”，即痛苦无有间断之意。常用来比喻黑暗的社会和严酷的牢狱。又比喻无法摆脱的极其痛苦的境地。",
    "source": "语出《法华经·法师功德品》下至阿鼻地狱。”",
    "example": "但也有少数意志薄弱的……逐步上当，终至堕入～。★《上饶集中营·炼狱杂记》"
  },
    ...
