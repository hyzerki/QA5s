
***URL приложения:***  https://www.sportmaster.by/

## ***Тест кейсы:***
***Тест:*** 1

***Заглавие:*** 
Добавление товара в корзину 

**Предусловия:**
 1. Открыта страница: https://www.sportmaster.by/product/26508520299/
 
**Шаги воспроизведения:**
1. Нажать на любую доступную кнопку выбора размера
2. Нажать на кнопку "В КОРЗИНУ"

**Ожидеаемый результат:**
- товар добавится в корзину

**Фактический результат:**
- появилось модальное окно предпросмотра корзины с заголовком "Товар добавлен в корзину" и товар отображается в корзине

**Окружение:**
-  **ОС:** Microsoft Windows 11 Home
-  **Браузер:** Edge

 ----------

***Тест:*** 2

***Заглавие:*** 
Ввод некорректных данных о количестве товара в корзине 

**Предусловия:**
 1. Открыта страница корзины: https://www.sportmaster.by/basket_list/
 
**Шаги воспроизведения:**
1. С помощью клавиатуры ввести "ваоыдфаовлдафы" в поле "Количество"
2. Нажать Enter на клавиатуре

**Ожидеаемый результат:**
- Осталось прежнее, корректное значение

**Фактический результат:**
- Осталось прежнее, корректное значение

**Окружение:**
-  **ОС:** Microsoft Windows 11 Home
-  **Браузер:** Edge

 ----------

***Тест:*** 3

***Заглавие:*** 
Добавление товаров в сравнение 

**Предусловия:**
 1. Открыта страница с толстовками и свитшотами: https://www.sportmaster.by/catalog/muzhskaya_odezhda/dzhempery_i_svitery/
 2. Отсутствие товаров в сравнении
 
**Шаги воспроизведения:**
1. Навести курсор на любой из представленных товаров
2. Нажать на кнопку "Добавить к сравнению"

**Ожидеаемый результат:**
- В навигационной панели около ссылки "Список сравнения" число 0 изменится на 1

**Фактический результат:**
- В навигационной панели около ссылки "Список сравнения" число 0 изменилось на 1

**Окружение:**
-  **ОС:** Microsoft Windows 11 Home
-  **Браузер:** Edge


 ----------

***Тест:*** 4

***Заглавие:*** 
Удаление товара из корзины

**Предусловия:**
 1. Открыта страница корзины: https://www.sportmaster.by/basket_list/
 2. Наличие одного товара в корзине
 
**Шаги воспроизведения:**
1. Навести курсор на товар в корзине
2. Нажать на кнопку "Удалить"

**Ожидеаемый результат:**
- Из корзины удалится товар и ничего больше не останется

**Фактический результат:**
- Из корзины удалилтся товар и вместо списка товаров указано сообщение "В корзине ничего нет"

**Окружение:**
-  **ОС:** Microsoft Windows 11 Home
-  **Браузер:** Edge


 ----------

***Тест:*** 5

***Заглавие:*** 
Поиск по каталогу товаров 

**Предусловия:**
 1. Открыта любая страница: https://www.sportmaster.by/
 
**Шаги воспроизведения:**
1. Нажать на поле "Поиск" в навигационной панели сайта
2. Ввести "Свитшот"
3. Нажать кнопку с иконкой лупы

**Ожидеаемый результат:**
- Будут представлены все товары в названии которых есть слово "Свитшот" без учёта регистра

**Фактический результат:**
- Отобразились все товары в названии которых есть слово "Свитшот"

**Окружение:**
-  **ОС:** Microsoft Windows 11 Home
-  **Браузер:** Edge


 ----------

***Тест:*** 6

***Заглавие:*** 
Добавление товаров в избранное 

**Предусловия:**
 1. Открыта страница любого товара: https://www.sportmaster.by/product/23004590299/
 2. Отсутствие авторизации на сайте
 
**Шаги воспроизведения:**
1. Нажать на кнопку "В избранное"
2. В навигационной панели нажать на кнопку "КАБИНЕТ"
3. В появившемся дропдауне нажать на "Избранное"

**Ожидеаемый результат:**
- Откроется страница "Избранное", на которой отобразится добавленный в избранное товар

**Фактический результат:**
- Откроется страница "Избранное", на которой отобразится добавленный в избранное товар

**Окружение:**
-  **ОС:** Microsoft Windows 11 Home
-  **Браузер:** Edge


 ----------

***Тест:*** 7

***Заглавие:*** 
Сортировка товаров в каталоге

**Предусловия:**
 1. Открыта страница каталога с толстовками и свитшотами: https://www.sportmaster.by/catalog/muzhskaya_odezhda/dzhempery_i_svitery/
 
**Шаги воспроизведения:**
1. Нажать на кнопку выпадающего списка "По популярности"
2. В выпавшем списке нажать на пункт "По цене ↑"

**Ожидеаемый результат:**
- Товары отобразятся в отсортированном по возрастанию цены виде

**Фактический результат:**
- Товары отобразились в отсортированном по возрастанию цены виде

**Окружение:**
-  **ОС:** Microsoft Windows 11 Home
-  **Браузер:** Edge


 ----------

***Тест:*** 8

***Заглавие:*** 
Просмотр таблицы размеров для товара 

**Предусловия:**
 1. Открыта страница товара, для которого доступен выбор размера: https://www.sportmaster.by/product/26735580299/
 
**Шаги воспроизведения:**
1. Нажать на кнопку "Таблица размеров"

**Ожидеаемый результат:**
- Отобразится таблица размеров для просматриваемого товара

**Фактический результат:**
- Появилось модальное окно "Таблица размеров" содержащее в себе таблицу размеров для просматриваемого товара

**Окружение:**
-  **ОС:** Microsoft Windows 11 Home
-  **Браузер:** Edge


 ----------

***Тест:*** 9

***Заглавие:*** 
Выбор размера товара 

**Предусловия:**
 1. Открыта страница с товаром, для которого доступен выбор размера: https://www.sportmaster.by/product/26776220299/
 
**Шаги воспроизведения:**
1. Нажать любую из доступных кнопок находящихся под заголовком "РАЗМЕР:"

**Ожидеаемый результат:**
- Нажатая кнопка изменит свой вид

**Фактический результат:**
- Нажатая кнопка изменила свой цвет на `#005BAA`

**Окружение:**
-  **ОС:** Microsoft Windows 11 Home
-  **Браузер:** Edge


 ----------

***Тест:*** 10

***Заглавие:*** 
Удаление всех товаров из Избранного

**Предусловия:**
 1. Открыта страница с избранными товарами: https://www.sportmaster.by/favourites/
 2. Наличие одного и более товаров в "Избранном"
 
**Шаги воспроизведения:**
1. Нажать на кнопку "Очистить весь список"
2. В появившемся модальном окне нажать на кнопку "ДА, УДАЛИТЬ"

**Ожидеаемый результат:**
- Список избранных товаров станет пустым

**Фактический результат:**
- На месте отображения избранных товаров появилась надпись "В избранном ничего нет. Воспользуйтесь поиском, чтобы найти всё что нужно"

**Окружение:**
-  **ОС:** Microsoft Windows 11 Home
-  **Браузер:** Edge
