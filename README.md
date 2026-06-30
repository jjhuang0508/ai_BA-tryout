#  晋亿实业股票行情面板

这是一个基于 Web 的股票数据可视化面板，展示晋亿实业 (601000.SH) 的近一年交易数据。

## 🎯 功能特点

- **K 线图展示**: 专业的蜡烛图显示每日开盘价、收盘价、最高价、最低价
- **成交量分析**: 柱状图展示每日交易活跃度
- **实时统计**: 最新价、涨跌幅、最高/最低价、总成交量、总成交额
- **时间周期切换**: 支持查看全部、近 6 个月、近 3 个月、近 1 个月数据
- **响应式设计**: 完美适配电脑和手机浏览

##  在线访问

访问地址：https://jjhuang0508.github.io/ai_BA-tryout/

## 📊 数据来源

- **数据提供商**: TuShare Pro (https://tushare.pro)
- **可视化库**: ECharts (https://echarts.apache.org)
- **股票代码**: 601000.SH (晋亿实业股份有限公司)

## 📁 文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | 主页面 |
| `601000_stock_data.json` | 股票交易数据 (JSON 格式) |
| `fetch_tushare_data.py` | 数据获取脚本 (本地使用) |

## 🔄 数据更新

数据通过 TuShare API 获取，如需更新最新数据：

1. 本地运行 `python fetch_tushare_data.py`
2. 将新生成的 `601000_stock_data.json` 上传到此仓库

## 🛠️ 本地开发

```bash
# 1. 克隆仓库
git clone https://github.com/jjhuang0508/ai_BA-tryout.git

# 2. 安装依赖
pip install tushare pandas

# 3. 获取数据
python fetch_tushare_data.py

# 4. 在浏览器打开 index.html
```

##  技术栈

- **前端**: HTML5, CSS3, JavaScript (ES6+)
- **图表库**: Apache ECharts 5.4.3
- **数据源**: TuShare Pro API
- **托管**: GitHub Pages

## ⚠️ 免责声明

- 数据仅供学习研究使用
- 不构成任何投资建议
- 股市有风险，投资需谨慎

##  许可证

MIT License

---

**最后更新**: 2026-06-29  
**维护者**: @jjhuang0508
