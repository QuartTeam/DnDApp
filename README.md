# DnDApp
## Цель проекта
- Помощь начинающим и опытным игрокам в ориентировании в правилах НРИ Dungeons & Dragons. 
- Автоматизация процесса создания игрового персонажа и оформления его листа.
- Помощь мастерам в оформлении, созданных  ими, приключений.
- Предоставление возможности поделится своими домашними правилами с пользователям.

## Описание
Это приложение включает в себя 5 разные вкладки: справочник, листы персонажей, библиотека, приключения, мастерская.
- Справочник имеет большое количество страниц правил, которые распределены по разделам: заклинания, магические предметы, бестиарий, расы и происхождения, классы, черты, предыстории, инвентарь, игровые механики. Также должен присутствовать раздел с самыми часто используемыми правилами. Здесь они должны быть представлены в кратком виде и использоваться как шпаргалка. Еще один раздел — это инструменты: генератор добычи, сложность боя, генератор имен персонажей, генератор описания местности и т. д. 
- Вкладка с листами персонажей представляет собой список персонажей, которых создал пользователь. В каждом из них содержаться: имя, раса, класс, уровень, характеристики, способности, инвентарь, заклинания... Все эти листы полностью интерактивны и ссылаются на справочник.
- Библиотека представляет собой список контента, которым пользовался данный человек.
- Вкладка приключения включает приключения, созданные мастером с описанием: местности, не игровых персонажей, сюжетом, локациями и т.д. Содержание этих приключений так же могут ссылаться на различные статьи из справочника.
- Мастерская — это социальное пространство, где люди делится своими правилами, персонажами, приключениями.

[Примерная диаграмма активности](https://github.com/QuartTeam/DnDApp/blob/main/docs/diagram.png "architecture.md")

[Процессы](https://github.com/QuartTeam/DnDApp/blob/main/docs/process.md "architecture.md")

## Примеры аналогов
### D&D Beyond

![Screenshot_20221214-184422](https://user-images.githubusercontent.com/72492774/207613234-188cd422-2e54-477a-8b3a-5b76f5f50d48.png)
![Screenshot_20221214-184438](https://user-images.githubusercontent.com/72492774/207613013-db28d49d-9285-4497-8aa7-3231ca03b996.png)
![Screenshot_20221214-184449](https://user-images.githubusercontent.com/72492774/207613041-2c086b22-9fbe-445b-9ff3-b823291a56c0.png)
![Screenshot_20221214-184501](https://user-images.githubusercontent.com/72492774/207613066-016648b0-cd9f-4206-9562-7c19a638f1f6.png)

### 5e Companion App

![Screenshot_20221214-185646](https://user-images.githubusercontent.com/72492774/207614467-db8ec85b-b632-476a-8d31-aa3640b79620.png)
![Screenshot_20221214-185734](https://user-images.githubusercontent.com/72492774/207614521-abe92417-4054-4dfa-9b39-2084aada0f89.png)
![Screenshot_20221214-185726](https://user-images.githubusercontent.com/72492774/207614539-8b9781ee-f8f1-4c7f-b7a1-5f948768e802.png)
![Screenshot_20221214-185716](https://user-images.githubusercontent.com/72492774/207614555-21393205-7a3b-4467-8989-5a3735854c94.png)

### RPG Notes

![Screenshot_20221214-190051](https://user-images.githubusercontent.com/72492774/207615067-4ad72e92-223e-4cc4-a732-f160da3a32f0.png)
![Screenshot_20221214-190055](https://user-images.githubusercontent.com/72492774/207615151-eef2d17f-c06c-4277-a57c-1719bb37ad86.png)
![Screenshot_20221214-190059](https://user-images.githubusercontent.com/72492774/207615195-9dda9852-a249-4fff-b0ff-ea80674192f8.png)
![Screenshot_20221214-190119](https://user-images.githubusercontent.com/72492774/207615271-ad9c6d3c-633c-476c-ae21-1ac9ca8d082a.png)

Большое количество аналогов не имеет полного функционала, который был описан выше. А также большинство из них не имеют русскую локализацию.

## Какие технологии использовать
Я предлагаю использовать такие языки программирования, как Java, C++, Kotlin. Приложение будет написано в среде разработки Android Studio. Так же будет необходимо поднять сервер с базой данных пользователей и контента, который они создают.
