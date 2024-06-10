````markdown
# Paar

Paar - это простое key/value хранилище, реализующее команды GET, SET, DELETE, EXPIRE и другие, с возможностью сохранения данных на диск.

## Описание

Paar был создан для улучшения навыков программирования на Go. Этот проект представляет собой простое и эффективное хранилище ключ-значение, которое можно использовать для различных задач хранения данных. Paar поддерживает основные команды для работы с данными и позволяет сохранять состояние на диск для долговременного хранения.

## Возможности

- **GET**: Получить значение по ключу.
- **SET**: Установить значение по ключу.
- **DELETE**: Удалить значение по ключу.
- **EXPIRE**: Установить время жизни для ключа.

## Установка

Для установки Paar потребуется Go версии 1.20 или выше.

```sh
git clone https://github.com/ethaningenium/paar.git
cd paar
make run
```
````

## Использование

## Команды

- **GET key**: Возвращает значение, связанное с `key`.
- **SET key value**: Устанавливает `value` для `key`.
- **DELETE key**: Удаляет значение, связанное с `key`.
- **EXPIRE key 1s1m1h1d**: Устанавливает время жизни ключа `key` в секундах/минутах/часах/дней.

## Вклад

Вклад в проект приветствуется! Пожалуйста, создайте форк репозитория и отправьте PR с вашими изменениями.

---

Спасибо за использование Paar! Если у вас есть какие-либо вопросы или предложения, не стесняйтесь обращаться.

```

Этот README.md файл включает основную информацию о проекте, его установке, использовании и доступных командах. Вы можете адаптировать его в соответствии с вашими потребностями и особенностями вашего проекта.
```