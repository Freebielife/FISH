# FISH Observatory

Контракт: EQATcUc69sGSCCMSadsVUKdGwM1BMKS-HKCWGPk60xZGgwsK
Raw: 0:1371473af6c19208231269db1550a746c0cd4130a4be1ca09618f93ad3164683
Decimals: 9. Метаданные проверены через TonAPI 25.11.2026.

Изображение пользователя встроено в баннер, значки разделов и фон операций.
Самодостаточный index.html: без внешних шрифтов, скриптов и изображений. Можно загрузить одним файлом через @ResiStorageBot.

Источники:
- https://tonapi.io/v2/jettons/EQATcUc69sGSCCMSadsVUKdGwM1BMKS-HKCWGPk60xZGgwsK
- https://www.tonfish.io/ — ссылки на Telegram и X взяты с сайта.
- https://api.geckoterminal.com/api/v2/networks/ton/tokens/EQATcUc69sGSCCMSadsVUKdGwM1BMKS-HKCWGPk60xZGgwsK/pools

Лента использует подтверждённые прямые FISH/TON обмены STON.fi. Другие найденные пары показаны в пулах. DeDust не добавлен в ленту: проверенные события пула не содержали распознанных JettonSwap.
История загружается постепенно; полнота и ошибки отражаются по каждому разделу. Отсутствующие данные не заменяются нулями. Заморозка и стейкинг не настроены.

Обновление: python3 -m scripts.refresh_observatory
Сборка: python3 build.py
Проверка: python3 verify.py

GitHub Actions содержит расписание раз в 30 минут. Репозиторий: https://github.com/Freebielife/FISH. Кнопка обновления и автопроверка страницы каждые 5 минут загружают снимок из этого репозитория (raw + GitHub API fallback). Отображение работает из встроенного снимка при недоступности сети. Для обновления оформления в TON Storage необходимо загрузить новый HTML. Сбор данных по расписанию GitHub Actions: каждые 30 минут, на 17-й и 47-й минуте часа UTC; фактический плановый запуск проверяется отдельно. Подключение к общему Cloudflare runner не подтверждено. При ошибке сети сохранённые данные остаются на экране.

## Самоописание токена

FISH is a meme token inspired by $PEPE. FISH aims to become the representative meme token of the TON ecosystem. It's just a fun token that doesn't guarantee any value, but that's why it has no limits.

Источник: метаданные контракта; заявления проекта не являются независимой оценкой.
