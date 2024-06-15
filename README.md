# SneakerShop
Приложение,онлайн-магазин, который специлизуется на продаже мужской обуви. Для реализации проекта будет использован C# в связке с MySQL. Для выполнения работы данного приложение мне понадабятся следующие таблицы:

Users Table

+ UserID
+ Name
+ Email
+ PasswordHash
+ IDRole

Products Table

+ ProductID
+ Name
+ Description
+ Price
+ CategoryID
+ ImageURL

Categories Table

+ CategoryID
+ Name

Cart Table

+ CartID
+ ProductID
+ UserID

Role

+ ID
+ Role1
