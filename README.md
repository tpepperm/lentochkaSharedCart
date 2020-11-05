# lentochkaSharedCart

Это приложение предназначено для совершения совместных покупок между пользователями.

***Небольшой disclaimer***: Мы еще новички и не умеем в архитектуру. Просьба понять и простить😊

## Список доступных логинов пользователей:
1. alice
2. alex
3. tony
4. kate12
5. tina
6. rita94

Пароль для всех пользователей одинаковый: 123456

Функция создания пользователя и добавления его в базу не предусмотрена, 
поскольку авторизация носит чисто номинальный характер.

## Разделы:

1. 🏷 **Каталог**

Каталог товаров (образец).
Со страницы каталога можно добавить товар в личную корзину. Также есть поиск по каталогу. 
По нажатию на ячейку товара открывается страница данного товара. С этой страницы можно 
добавить товар как в личную корзину, так и в общую корзину. Если список друзей пользователя пуст,
то добавить товар в общую корзину нельзя (вылетает предупреждение об ошибке)

2. 👨‍👩‍👧‍👧 **Люди**

Страница со списком людей, которые имеют доступ к общей корзине. Есть функция добавления 
пользователей по логину. Если список людей пустой, то пользователь, который первым добавляет 
кого-либо в этот список, является хозяином общей корзины. 
Добавлять людей в список может только хозяин корзины.
Хозяин корзины обозначается звездочкой в списке людей.
Если потянуть экран вниз, то данные о составе группы обновятся.

3. 🛍 **Корзина**

Страница корзины разделена на две корзины: личную и общую. 
В общей корзине список товаров разделен по пользователям, которые данные товары добавили.
Данные общей корзины при добавлении другим пользователем товаров, обновляются, если потянуть экран вниз.

4. 👩🏼‍💻 **Профиль**

Профиль пользователя. С этой страницы можно выйти из своего аккаунта.
Также можно установить фотографию профиля.
