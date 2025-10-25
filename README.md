# Twine
1. Добавление раздела [[Дальше]]
2. Добавление картинки персонажа <img src = "https://github.com/misterbiznes0/twine/blob/main/user1.png?raw=true">
```
<img src = "https://github.com/misterbiznes0/twine/blob/main/user1.png?raw=true">
```
3. Добавление фона 
```
tw-story {
  background-image: url('https://github.com/misterbiznes0/twine/blob/main/fon.png?raw=true');
    background-size: cover
}
```
4. Добавление подложки у текста
```
<div class="text-box">
    Парень по имени Дима сидит на занятии курса МДКд.12.01. Он записался на этот курс, потому что давно мечтал стать цифровым куратором и помогать людям осваивать современные технологии. Его преподаватель рассказал, что сегодня начнется работа над созданием сайта, который станет визитной карточкой каждого студента курса.
    [[Дальше]]
</div>
```
```
#.passage {
    position: relative;
}
#
.text-box {
    background-color: rgba(0, 0, 0, 0.7);
    color: white;
    padding: 10px;
    border-radius: 10px;
    margin-top: 10px;
    position: fixed;
    bottom: 20px;
    left: 50%;
    transform: translateX(-50%);
    width: 80%;
    max-width: 800px;
    z-index: 100;
}
```
