# PostgreSQL & Typeorm

При выставлении оценок используйте [рекомендации RSSchool](https://docs.rs.school/#/cross-check-flow?id=%d0%9f%d1%80%d0%b8%d0%bd%d1%86%d0%b8%d0%bf-%d0%be%d1%86%d0%b5%d0%bd%d0%ba%d0%b8-%d1%80%d0%b0%d0%b1%d0%be%d1%82%d1%8b-%d0%bf%d1%80%d0%b8-cross-check-%d0%bf%d1%80%d0%be%d0%b2%d0%b5%d1%80%d0%ba%d0%b5).

Максимальная оценка - **180 баллов**. Минимальная оценка - **0 баллов**.

1. В качестве источника данных для `users` используется **PostgreSQL** база данных, работа с которой происходит при помощи `typeorm` **+40 баллов**.
2. В качестве источника данных для `tasks` используется **PostgreSQL** база данных, работа с которой происходит при помощи `typeorm` **+40 баллов**.
3. В качестве источника данных для `boards` используется **PostgreSQL** база данных, работа с которой происходит при помощи `typeorm` **+40 баллов**.
3. Для создания таблиц с сущностями используются миграции. **+50 баллов**
4. Переменные, используемые для подключения к базе данных, хранятся в `.env` **+10 баллов**.

Штрафы:
* Наличие изменений в тестах либо в workflow **минус 100 баллов**
* Внесение изменений в репозиторий после дедлайна не считая коммиты, вносящие изменения только в `Readme.md` **минус 30% от максимального балла за задание (для этого задания 54 баллов)**
* За **каждую** ошибку линтера при запуске `npm run lint` на основе **локального конфига** **-20 баллов** (именно `errors`, не `warnings`)
* За **каждую** ошибку компилятора **-20 баллов**
* За каждый непроходящий тест **-20 баллов**
* Имеются явно указанные типы `any`, `unknown` **-20 баллов** за каждое использование
* За отсутствие отдельной ветки для разработки **-20 баллов**
* За отсутствие `Pull Request` **-20 баллов**
* За неполную информацию в описании `Pull Request` (отсутствует либо некорректен один из 3 обязательных пунктов) **-10 баллов**
* Меньше 3 коммитов в ветке разработки, не считая коммиты, вносящие изменения только в `Readme.md` — **-20 баллов**