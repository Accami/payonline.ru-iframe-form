# payonline.ru-iframe-form

Скрипт для подключения payonline.ru через iframe. Идеально подходит для облачных сайтов. 

# Установка

Залить файл payment.php на удаленный сервер. 

## Предварительно сконфигурируйте:

* MerchantId - Находится в личном кабинете payonline.ru
* PrivateSecurityKey - Находится в личном кабинете payonline.ru
* Currency - Валюта (доступны следующие валюты | USD, EUR, RUB)
* FailUrl - В случае неуспешной оплаты, плательщик будет переадресован, на данную страницу.
* ReturnUrl - В случае успешной оплаты, плательщик будет переадресован, на данную страницу. 

# Подключение

```bash
<iframe src="yoursite.com/payment.php" width="600" height="500" align="left">
    Ваш браузер не поддерживает плавающие фреймы!
</iframe>
```

# Скриншот формы

<img src="https://pp.vk.me/c604624/v604624882/2750c/4UdoipRAnkE.jpg" alt="Screen" />
