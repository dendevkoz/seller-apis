# seller-apis 

## Описание программы

### seller.py

Данный скрипт автоматизирует процессы продажи на сайте **OZON**
Скрипт связывается с кабинетом продавца и позволяет:
  - Обновлять информацию о товарах
  - Загружать актуальную информацию об остатках с сайта **Casio** и обновлять на **OZON**
  - Обновлять цены
  - Скрипт защищен от ошибок и сообщает пользователь о их возникновении


### market.py

Данный скрипт позволит автоматически обновлять информацию о ценах и остатках товаров на **Яндекс.Маркет**.
Скрипт связывается с **Яндекс.Маркет**, сверяет данные на маркетплейсе с вашими данными и производит обновление.
  - Сверяет кол-во остатков на складе с информацией на сайте **Яндекс.Маркет**
  - Позволяет менять цены на товары
  - Скрипт учитывает разные системы доставки
      - **FBS** (cортировочные центры и пункты приема заказов)
      - **DBS** (доставка продавцом)
