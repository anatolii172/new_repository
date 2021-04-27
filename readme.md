- Установите git и сгенерируйте пару ssh ключей. Авторизуйте  публичный ключ на github.com.

ssh-keygen -b 4096 -C "anatolii_tregub@epam.com"
 
- Укажите свой user.name и user.email в git.

git config --global user.name "Anatolii Tregub"
git config --global user.email "anatolii_tregub@epam.com)"

![ ](./images/image_001.jpg "1")

- Создайте новый репозиторий на github.com и склонируйте его локально на свой компьютер.

![ ](./images/image_002.jpg "1")

git clone https://github.com/anatolii172/new_repository.git


- Создайте файл названием song.txt и поместите туда половину текста  любимой песни.

![ ](./images/image_003.jpg "1")

- Сделайте коммит с названием "add first half of my favorite song" и отправьте его на сервер.

![ ](./images/image_004.jpg "1")

- Убедитесь что на github есть файл song.txt с текстом песни.

![ ](./images/image_005.jpg "1")


- Используя веб-интерфейс гитхаба добавьте вторую половину текста песни и сделайте коммит с названием "finish my song".

![ ](./images/image_006.jpg "1")

- В локальном репозитории сделайте pull и убедитесь что коммит, который вы создали на github, подтянулся и у вас полный текст песни.

![ ](./images/image_007.jpg "1")