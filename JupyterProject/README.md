# S&P 500 AI Prediction

Model AI prognozujący ruch S&P 500 na podstawie danych z yfinance i cech inżynierskich (rolling ratios, trendy).

## Jak działa
- Dane: yfinance (`^GSPC`)
- Model: RandomForestClassifier
- Cechy: rolling mean, ratio, trend, volume
- Testowanie: własna funkcja `backtest()`

## Uruchomienie
```bash
pip install -r requirements.txt
jupyter lab
