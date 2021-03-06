[![Build Status](https://travis-ci.org/davpsh/commerce_yandex_checkout.svg?branch=8.x-2.x)](https://travis-ci.org/davpsh/commerce_yandex_checkout)

# yandex-money-cms-v2-drupal8

С помощью модуля можно настроить прием платежей через Яндекс.Кассу

[Инструкция по настройке](https://yandex.ru/support/checkout/instructions/drupal8.html)

**Требования к CMS**
* версия 8.x;
* PHP 5.3 или выше;
* расширение libCurl.

### О Кассе
Сервис, который позволяет включить прием платежей на сайте.

[Сайт Кассы](http://kassa.yandex.ru/)

#### Условия
* подходит для юрлиц и ИП,
* деньги приходят на расчетный счет,
* комиссия берется с каждого успешного платежа.

Для использования нужно [подключиться к Яндекс.Кассе](https://money.yandex.ru/joinups) и получить в личном кабинете на сайте Кассы параметры **shopId** и **Секретный ключ**.

### Способы приема платежей
Вы можете выбрать любое количество способов из списка:

* Банковские карты — Visa, Mastercard и Maestro, «Мир»;
* Яндекс.Деньги;
* Webmoney;
* QIWI Wallet;
* Наличные;
* Альфа-Клик;
* Сбербанк Онлайн;
* Баланс мобильного — Билайн, Мегафон, МТС, Tele2.

### Дополнительные возможности

**Оплата на стороне Яндекса**

Включите в модуле оплату на стороне Яндекса — и не придется размещать на своем сайте все способы оплаты. Вместо этого останется одна кнопка «Заплатить».
 
[Пример в демо-магазине Кассы](https://kassa.yandex.ru/demo/index.html)

**Отправка данных для чеков по 54-ФЗ**

Если вы подключите решение Кассы для 54-ФЗ, модуль будет отправлять в Кассу данные для чека вместе с информацией о заказе.
 
[Подробности на сайте Кассы](https://kassa.yandex.ru/features) 

### Контакты
Если у вас есть вопросы или идеи для модуля, напишите нам: cms@yamoney.ru

В письме укажите:
* версию платформы,
* версию модуля (его можно посмотреть на странице настроек),
* идею или проблему,
* снимок экрана, о котором говорите.
