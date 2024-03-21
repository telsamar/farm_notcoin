﻿### Функционал  
+ _Многопоточность_
+ _Привязка прокси к сессии_
+ _Авто-покупка предметов при наличии денег (enery boost, speed boost, click boost)_
+ _Рандомное время сна между кликами_
+ _Рандомное количество кликов за запрос_
+ _Поддержка tdata / pyrogram .session / telethon .session_

### data/config.py  
_**API_ID / API_HASH** - Данные платформы, с которой запускать сессию Telegram (сток - Android)  
**MIN_CLICKS_COUNT** - Минимальное количество кликов за один запрос (считается без множителя, т.е напр. при множителе x9: 1 клик будет равнятся 9 монетам, а не одной)  
**AUTO_BUY_ENERGY_BOOST** - Автоматическая покупка Energy Boost при достижении баланса (True / False)  
**AUTO_BUY_SPEED_BOOST** - Автоматическая покупка Speed Boost при достижении баланса (True / False)  
**AUTO_BUY_CLICK_BOOST** - Автоматическая покупка Click Boost при достижении баланса (True / False)  
**USE_PROXY_FROM_FILE** - Использовать-ли Proxy из файла data/proxies.txt для аккаунтов, к которм не привязаны Proxy (True / False)  
**SLEEP_BETWEEN_CLICK** - Диапазон задержки между кликами (в секундах)
**SLEEP_BEFORE_BUY_MERGE** - Диапазон задержки перед покупкой бустов (в секундах)
**SLEEP_BEFORE_ACTIVATE_FREE_BUFFS** - Диапазон задержки перед активацией ежедневных бустов (в секундах)
**SLEEP_BEFORE_ACTIVATE_TURBO** - Диапазон задержки перед активацией Turbo (в секундах)_  


