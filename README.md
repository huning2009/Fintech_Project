# 以Trading Valley為基礎改建之理財機器人
買入策略(Trend following)

近 52 週最高價+squeeze 產生(布林通道跑進凱勒通道裡)+momentum>0 透過以上三個指標判斷股價將有一個往上漲的趨勢

出場策略(依據投資人風險承受程度來設定)

(1)	風險接受程度(低):以 1 倍的 ATR 當作停利點，並以跌幅 10%當作一個 hard
stop。

(2)	風險接受程度(中高):以 2 倍的 ATR 當作停利點，並以跌幅 10%當作一個hard stop。

(3)	風險接受程度(高):以前 10 週的最低收盤價作為追蹤止損。

程式碼

CDDE1 -> 風險接受程度低

CODE2 -> 風險接受程度中高

CODE3 -> 風險接受程度高

Dataset：StockPrice_set_2.xlsx、Benchmark.xlsx
