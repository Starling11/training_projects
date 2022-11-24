Входные данные: историческая информация о продажах игр, оценки пользователей и экспертов, жанры и платформы. 
Цель: выявить определяющие успешность игры закономерности для дальнейшего планирования рекламной компании. Работа над проектом завершена.

Описание данных: 
* Name — название игры
* `Platform` — платформа
* `Year_of_Release` — год выпуска
* `Genre` — жанр игры
* `NA_sales` — продажи в Северной Америке (миллионы проданных копий)
* `EU_sales` — продажи в Европе (миллионы проданных копий)
* `JP_sales` — продажи в Японии (миллионы проданных копий)
* `Other_sales` — продажи в других странах (миллионы проданных копий)
* `Critic_Score` — оценка критиков (максимум 100)
* `User_Score` — оценка пользователей (максимум 10)
* `Rating` — рейтинг от организации ESRB. 

Выводы: Графики за 2014-2016 год говорят нам о том, что у всех платформ спад в данный период. В период 2014-2015 PS4 и XOne росли. Лидерами по продажам в 2016 году (по уменьшенью популярности) являются: PS4, XOne, 3DS, PC.
Зависимости продаж от отзывов пользователей практически нет. На продажи по всем платформам немного влияют отзывы критиков.
В 2014-2016 годах больше всего игр было созданно в жанре Action. На втором и третьем месте по количеству игр: Role-Playing, Adventure. Меньше всего написано игр в жанре Puzzle, Strategy, Platform. 
По продажам на первом месте жанры: Action, Shooter, Sports, Role-Playing. 
Самые не популярные: Puzzle, Strategy, Simulation.

Библиотеки: pandas, numpy, seaborn, matplotlib.pyplot, collections, scipy.