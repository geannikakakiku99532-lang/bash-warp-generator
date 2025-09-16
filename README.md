# Сгенерируйте конфиг Cloudflare WARP для AmneziaWG и AmneziaVPN

Этот bash скрипт сгенерирует конфиг Cloudflare WARP для AmneziaVPN.

Не стоит выполнять его локально, так как РКН заблокировал запросы для получения конфига. Вместо этого лучше выполнять на удалённых серверах.

## Вариант 1: Aeza Terminator

1. Заходим на https://terminator.aeza.net
2. Выбираем **`debian`**
3. Вставляем команду (Shift + Insert):

```bash
bash <(wget --inet4-only -qO- https://raw.githubusercontent.com/geannikakakiku99532-lang/bash-warp-generator/refs/heads/main/warp_generator.sh)
```

4. После того, как конфиг сгенерируется, копируем его, либо скачиваем файлом по ссылке и импортируем в AmneziaVPN!👍

