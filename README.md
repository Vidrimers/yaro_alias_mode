# Fucking Alias Mode

Алиасы для гита и разработки

# Описание

Режим терминала Git, позволяющий быстрее использовать Dev/Git команды с помощью имеющегося терминала

Сравнение Dev/Git and yaro_alias_mode:

| DEV команды             | yaro_alias_mode |
| ----------------------- | --------------- |
| `npm run deploy`        | `dep`           |
| `npm run dev`           | `dev`           |
| `npm run lint`          | `lint`          |
| `npm run lint:fix`      | `lintfix`       |
| `npm run stylelint`     | `style`         |
| `npm run stylelint:fix` | `stylefix`      |
| `npm test`              | `tst`           |
| `npm run docs`          | `doc`           |

| GIT команды                   | yaro_alias_mode    |
| ----------------------------- | ------------------ |
| `git status`                  | `gs`               |
| `git init`                    | `init`             |
| `git add .`                   | `ga`               |
| `git commit -m 'комментарий'` | `gc 'комментарий'` |
| `git push`                    | `gp`               |
| `git checkout`                | `ch`               |
| `git branch`                  | `gb`               |
| `git clone`                   | `clone`            |
| `git merge`                   | `gm`               |
| `git remote`                  | `remote`           |
| `git pull`                    | `pull`             |

# Установка

Скопировать команды и вставить в окно терминала (GitBash) по очереди

1.  Клонировать репозиторий в терминале `cd ~ && git clone https://github.com/Vidrimers/yaro_alias_mode`.
1.  chmod yaro_alias_mode `chmod +x ~/yaro_alias_mode/`
1.  Установить скрипт `~/yaro_alias_mode/install`

# Работа с yaro_alias_mode

Чтобы yaro_alias_mode заработал, его надо активировать в терминале.

- Активировать yaro_alias_mode: `g` `<Enter>`.
- помощь по алиасам: `helpmeplz`
- Завершить работу с yaro_alias_mode: `q`.

Остальные команды можно посмотреть через терминал в `helpmeplz`, добавить свои в папке с yaro_alias_mode:
C: \ Users \ "USERNAME" \ yaro_alias_mode

Взято, переведено и исправлено отсюда: https://github.com/Tredecies/git_mode/
