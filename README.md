# SparkDesign
# 基于 Spark 的网络安全流量分析

## 快速开始
```bash
git clone <your-repo>
cd spark-network-security-analysis
pip install -r requirements.txt

# 1. 下载 CIC-IDS2017 数据放入 data/
# 2. 一键运行
./run_all.sh

# 3. 启动仪表盘
streamlit run dashboard/app.py
