# gitflow

1. Создать репозиторий на GitHub и клонировать его на ПК.
2. Создать ветку разработки (develop) от главной ветки (master, main)
3. Создать от ветки develop feature/-ветки и мержить feature/-ветки когда, фичи будут выполнены.
4. Создание ветки release/0.1.0 от develop.
5. Когда ветка release/0.1.0 закончена, она мержится в develop и main и затем удаляется.
6. Если в ветке main обнаруживается ошибка, то создается hotfix-ветка.
7. Когда работа над hotfix-веткой завершается, то ее нужно мержить в develop и main

---

1. git clone [repository]
2. git branch
3. git branch develop
4. git checkout develop
5. git push origin develop
