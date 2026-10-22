# yewildy

对日语学习、雅思、游戏、音乐、效率工具和电路可视化感兴趣。这里整理几个围绕这些兴趣的小工具。

Interested in Japanese study, IELTS practice, games, music, productivity tools and circuit visualization. Here are a few small tools related to those interests.

## 小工具 / Small tools

### [Focus Log · 专注小记](https://github.com/yewildy/focus-log)

给一段学习或练琴时间定个目标，结束后留下记录。支持暂停与恢复、七日分类统计、CSV 导出和导入。数据保存在当前浏览器。

Set a goal for a study or piano session and keep a record when it finishes. Includes pause/resume, seven-day category summaries, and CSV export/import. Data stays in the current browser.

HTML · CSS · JavaScript · localStorage

### [RC Step View · RC 充放电](https://github.com/yewildy/rc-step-view)

调整 R、C 和电压，查看理想 RC 电路的充放电曲线。可以保留一条曲线作对照，读取同一时刻的电压，也有一个 10 / 22 µF 的电容对照例子。

Adjust R, C and voltage to inspect ideal RC charging and discharging curves. Keep one reference curve, compare voltages at the same time, or load the 10 / 22 µF capacitance example.

HTML · CSS · JavaScript · SVG

### [IELTS Practice Log · 雅思练习小记](https://github.com/yewildy/ielts-practice-log)

保存口语与写作练习后的复盘和下一步，按关键词、日期或类别找回。支持修改复盘、回看目标、完整 JSON 导出和 SQLite 备份，记录保存在本地。

Save reflections and next steps after speaking or writing practice, then find them by keyword, date or skill. Includes reflection editing, goal review, full JSON export and SQLite backups, with local storage.

Python 标准库 / standard library · SQLite

## 试用 / Try them

下载前两个仓库后，用浏览器打开各自的 `index.html`。雅思练习小记已在 Python 3.12 下检查；在它的仓库目录运行 `python practice_log.py --help`，再按 README 中的合成示例试一条记录。

Download either browser tool and open its `index.html`. IELTS Practice Log has been checked with Python 3.12: run `python practice_log.py --help` in its repository, then try the synthetic example in its README.

各仓库的 README 有具体用法、当前限制和一个可以动手修改的小练习。

Each repository's README has usage details, current limits and a small code exercise.
