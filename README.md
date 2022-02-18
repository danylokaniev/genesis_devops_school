# genesis_devops_school

```bash
git clone https://github.com/danylokaniev/genesis_devops_school.git && cd genesis_devops_school && sudo docker-compose up
```

Перейти за посиланням на `http://localhost:8000`

З самого завдання не зовсім зрозуміло, чи потрібно запустити чистий wordpress, пройти реєстрацію, самостійно заповнити першу сторінку або запустити вже зі створеними раніше сторінками.

Для першого варіанту вистачить запустити docker-compose без папки mydata.

Другий варіант логічніший, тому вирішив зробити таким чином.

В папці `mydata/db_data`  знаходяться приватні ключі. Звичайно їх потрібно було передавати приватним чином, але для простоти запуску додав їх одразу до репозиторію.




