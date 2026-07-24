<div align="center">

# AlphaCV

### Task Check-in Hub

把阶段任务、长期任务和每日推进记录在 GitHub 上。

<a href="https://github.com/AlphaCV/Task-Checkin/issues/new?template=checkin.yml">
  <img alt="Daily Check-in" src="https://img.shields.io/badge/Daily_Check--in-2da44e?style=for-the-badge&logo=github&logoColor=white">
</a>
<a href="https://github.com/AlphaCV/Task-Checkin/issues/new?template=add-task.yml">
  <img alt="New Task" src="https://img.shields.io/badge/New_Task-0969da?style=for-the-badge&logo=githubactions&logoColor=white">
</a>
<a href="https://alphacv.github.io/Task-Checkin/">
  <img alt="Dashboard" src="https://img.shields.io/badge/Dashboard-8250df?style=for-the-badge&logo=githubpages&logoColor=white">
</a>

<br>
<br>

<a href="https://alphacv.github.io/Task-Checkin/">
  <img alt="Task Check-in board" src="https://raw.githubusercontent.com/AlphaCV/Task-Checkin/main/docs/checkin-card.svg" width="920">
</a>

<br>

<sub>
Issue Forms record tasks and check-ins. GitHub Actions refresh the SVG automatically.
</sub>

</div>

---

<details>
<summary><strong>How I use this board</strong></summary>

| Action | Entry | Description |
| --- | --- | --- |
| Daily check-in | [Open form](https://github.com/AlphaCV/Task-Checkin/issues/new?template=checkin.yml) | Add today's progress to an existing task. |
| New task | [Open form](https://github.com/AlphaCV/Task-Checkin/issues/new?template=add-task.yml) | Create a separate task block with priority and cadence. |
| Full dashboard | [Open page](https://alphacv.github.io/Task-Checkin/) | View task cards, heatmap, records and anime check-in scenes. |

Local update example:

```bash
python scripts/update_checkins.py add-checkin --task daily-work-log --note "完成今天的工作记录" --progress 80
python scripts/render_checkin_svg.py
```

</details>
