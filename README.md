# Weather Data Get

本仓库已合并到 [`weather-tool`](https://github.com/dchen0212/weather-tool)，后续功能更新将主要在主仓库中维护。  
This repository has been merged into [`weather-tool`](https://github.com/dchen0212/weather-tool), and future feature updates will primarily be maintained there.

## 迁移说明 | Migration Notice

`weather-data-get` 中原有的天气数据抓取能力已经并入主仓库，当前推荐直接使用：  
The weather-data retrieval functionality originally provided by `weather-data-get` has been merged into the main repository. Please use:

- 主仓库 / Main repository: [dchen0212/weather-tool](https://github.com/dchen0212/weather-tool)

主仓库现在同时支持：  
The main repository now supports both:

- `Streamlit` 图形界面 / `Streamlit` graphical interface
- 命令行天气数据导出 / Command-line weather-data export

## 推荐替代用法 | Recommended Replacement

克隆主仓库：  
Clone the main repository:

```bash
git clone https://github.com/dchen0212/weather-tool.git
cd weather-tool
```

启动图形界面：  
Launch the GUI:

```bash
python app.py
```

使用命令行导出 CSV：  
Use the CLI to export CSV:

```bash
python app.py --lat 32.0 --lon -84.0 --start 2015-01-01 --end 2015-12-31 --unit C --out weather.csv
```

## 仓库状态 | Repository Status

本仓库建议视为归档/迁移状态，除非有特别需要，不再作为主要开发入口。  
This repository should be considered archived/migrated and is no longer the primary development entry point unless there is a special need.
