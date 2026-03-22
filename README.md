# 台股 ETF 量化策略分析（0050 ETF）

## 📌 專案概述
本專案比較三種策略在 0050 ETF 上的表現：

- Buy & Hold
- MA20 Strategy
- Momentum (60d)

使用 Python 進行回測，並透過 Tableau 視覺化結果。

---

## 📈 Results

### NAV Curve
![NAV](outputs/equity_curve.png)

### Drawdown Curve
![Drawdown](outputs/drawdown_curve.png)

---

## 💡 Key Insights

- Buy & Hold 報酬最高，但回撤較大
- MA20 降低波動
- Momentum 在報酬與風險間取得平衡
