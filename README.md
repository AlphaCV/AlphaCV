# Hi, I'm AlphaCV

[![今日打卡](https://img.shields.io/badge/%E4%BB%8A%E6%97%A5%E6%89%93%E5%8D%A1-2ea44f?style=for-the-badge)](https://github.com/AlphaCV/Task-Checkin/issues/new?template=checkin.yml)
[![新增任务](https://img.shields.io/badge/%E6%96%B0%E5%A2%9E%E4%BB%BB%E5%8A%A1-0969da?style=for-the-badge)](https://github.com/AlphaCV/Task-Checkin/issues/new?template=add-task.yml)
[![详细看板](https://img.shields.io/badge/%E8%AF%A6%E7%BB%86%E7%9C%8B%E6%9D%BF-8250df?style=for-the-badge)](https://alphacv.github.io/Task-Checkin/)

![Task Check-in](https://raw.githubusercontent.com/AlphaCV/Task-Checkin/main/docs/checkin-card.svg)

## 使用说明

- `今日打卡`: 给已有任务添加打卡记录
- `新增任务`: 添加一个新的独立任务块
- `详细看板`: 打开完整任务打卡界面
- 每个任务块里都有 `ID`，打卡时填写这个 ID

本地更新也可以使用：

```bash
python scripts/update_checkins.py add-checkin --task daily-work-log --note "完成今天的工作记录" --progress 80
python scripts/render_checkin_svg.py
```
