###Trainers: Uladzimir Halushka

###Slides
http://slides.com/uladzimirhalushka/deck-1

###Useful links
http://alistapart.com/article/the-art-of-the-commit
https://github.com/rolling-scopes/front-end-course/wiki/Git-guidelines

###Git Basics
  - ...
  - Адекватные имена коммитов
  - Адекватные имена бранчей

###Git Story
- git history
- git architecture
- git aliases

###Online course
- https://www.codeschool.com/courses/try-git
- https://www.codeschool.com/courses/git-real

----------

насчет коммитов:

в ходе code review PRы можно рассматривать с двух сторон:
1. конечный diff с веткой, в которую предполагается merge
2. покоммитный анализ истории ветки

в первом случае делается акцент на результате, то есть, ревьюеров может в принципе что-то не устроить в итоговом списке изменений в бранче

во втором случае, обычно, если PR/проект сложные, вопросы могут возникнуть к составу PRa, например, если изменений очень много и финальный diff поражает воображение размерами, или набор изменений недостаточно освещен в описании PRа

тогда большое количество коммитов помогает, так как это попросту означает больше информации об истории: коммит — это именованные изменения и одновременно структурная единица (например, 1 коммит = 1 sub-feature):

Commit #2  Add stylesheets
Commit #1  Add some source code
Commit #0  Set up infrastructure

по этим коммитам можно разобрать PR на части, к примеру, разными членами команды с разными ролями и профессиональными областями :)