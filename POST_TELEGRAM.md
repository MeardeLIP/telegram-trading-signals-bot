# Пост для Telegram (черновик)

**Заголовок:**  
**Торговые сигналы в Telegram** — бот под валютные пары и экспирации

---

**Текст:**

Сдал **коммерческий заказ** — Telegram-бот, который выдаёт **сигналы UP/DOWN** по выбранной **валютной паре** и **таймфрейму**.

**Что внутри:**  
• **API:** Telegram Bot API (**aiogram 3**), **HTTP-интеграция** с **Pocket Option affiliate API** (проверки, партнёрская воронка)  
• Индикаторы на **pandas** (MA/EMA, RSI, MACD); **мультипровайдерный** слой котировок под **внешние REST API**  
• Онбординг, лимиты на запросы, SQLite (**SQLAlchemy**), деплой на **VPS** (**systemd**), сопровождение после запуска

**Стек:** Python, aiogram, REST API, aiohttp, SQLAlchemy, pandas — **[ссылка на README на GitHub]**

---

**Короткий вариант:**

Telegram-бот сигналов · Python, aiogram, REST API, pandas → [ссылка]
