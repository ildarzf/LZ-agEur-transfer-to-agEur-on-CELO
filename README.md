# LZ-agEur-transfer-to-agEur-on-CELO
Иногда при  бридже через Angle.money в CELO AgEur можно попасть на лимиты бриджа и на кошелек в сети CELO приходит LZ-agEur (в других сетях лимита хватало всегда) Ситуация описана тут и ее решение в ручном режиме https://docs.angle.money/overview/guides/bridge. Скрипт позволяет проверить все кошельки на наличие LZ-agEur и перевести их в AgEur ( при условии ликвидности моста в AgEur на перевод хватает) Иначе скрипт отработает но возврата не последует. В таком случае перезапустить попозже
в файл wallets.txt вставляем приватники. 1 привтник одна строка
Запустить main.py
