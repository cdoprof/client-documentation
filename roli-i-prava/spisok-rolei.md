# Список ролей

<div class="hint info">
Роль — это удобный способ группировать права и упрощать управление доступом
</div>

## Администратор

Главная роль в системе для разработчиках или представителей компании

```
Полный доступ
```

## Менеджер

Роль с большим кол-вом возможностей, которая направлены на управление систем арендаторов

```
Полный доступ к выпущенным устройствам (devices-all)
Полный доступ к архиву выпущенных устройств (devices-archive-all)
Полный доступ к отчетам устройств (devices-reports-all)
Полный доступ к шаблонам отчетов (reports-templates-all)
Полный доступ к пользователям (users-all),
Полный доступ к архиву пользователей (users-archive-all)
Полный доступ к группам (groups-all)
Полный доступ к контрагентам (counterparties-all)
Полный доступ к архиву контрагентов (counterparties-archive-all)
```

## Инженер

Роль которая дает возможности профилировать устройства (просмотр, отладка и тп)

```
Просмотр выпущенных устройств (devices-show)
```

## Диспетчер

Роль для слежения за устройством, которая включает формирование отчета, выгрузку и другое

```
Просмотр выпущенных устройтсв (devices-show)
Просмотр отчетов (devices-reports-show)
Формирование отчетов (devices-reports-formation)
Скачивание отчетов (devices-reports-download)
Просмотр токенов временного доступа (devices-tracking-tokens-show)
Отправка комманд на устройства (devices-send-commands)
```

## Специалист тех. поддержки

Роль для сотрудников технической поддержки, которые модерируют обращения

```
Полный доступ к обращениям
```

Таблица связей ролей с правами

<table><thead><tr><th width="245.14453125">Право</th><th width="147.20703125">Администратор</th><th width="101.9765625">Менеджер</th><th width="90.9375">Инженер</th><th width="109.89453125">Диспетчер</th><th>Тех. поддержка</th></tr></thead><tbody><tr><td>Просмотр контрагентов</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Добавление контрагентов</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Редактирование контрагентов</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Удаление контрагентов</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Полный список прав по контрагентам</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td></tr><tr><td>Просмотр архива контрагентов</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td></tr><tr><td>Добавление контрагентов в архив</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Восстановление организации из архива</td><td><ul class="contains-task-list"><li><input type="checkbox" checked> </li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Полный доступ к архиву пользователей</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td></tr><tr><td>Просмотр пользователей</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Добавление пользователей</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Редактирование пользователей</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Удаление пользователей</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Полный права на пользователей</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td></tr><tr><td>Просмотр архива пользователей</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Добавление пользователей в архив</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Восстановление пользователей из архива</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Полные права на архив пользователей</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td></tr><tr><td>Просмотр выпущенных устройств</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td></tr><tr><td>Добавление выпущенных устройств</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Редактирование выпущенных устройств</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Отправка команд на выпущенные устройства</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td><ul class="contains-task-list"><li><input type="checkbox"></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td></tr><tr><td>Полный доступ к выпущенным устройствам</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td></tr><tr><td>Просмотр архива выпущенных устройств</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td><ul class="contains-task-list"><li><input type="checkbox"></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td></tr><tr><td>Добавление выпущенных устройств в архив</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Восстанавливать выпущенные устройства из архива</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Полный доступ к архиву выпущенных устройств</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td></tr><tr><td>Просмотр токенов временного отслеживания</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td><ul class="contains-task-list"><li><input type="checkbox"></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td></tr><tr><td>Добавление токенов временного отслеживания</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Удаление токенов временного отслеживания</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Полный доступ к токенам временного отслеживания</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td></tr><tr><td>Просмотр отчетов по выпущенным устройствам</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Формирование отчетов по выпущенным устройствам</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox"></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td></tr><tr><td>Скачивание отчетов по выпущенным устройствам</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td><ul class="contains-task-list"><li><input type="checkbox"></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td></tr><tr><td>Полный доступ к отчетам по выпущенным устройствам</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td></tr><tr><td>Просмотр обращений</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Редактирование обращений</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Полный доступ к обращениям</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td></tr><tr><td>Просмотр групп</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Добавление групп</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Редактирование групп</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Удаление групп</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Полный доступ к группам</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td></tr><tr><td>Просмотр шаблонов отчетов</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td><ul class="contains-task-list"><li><input type="checkbox"></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td></tr><tr><td>Добавление шаблонов для отчетов</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Редактирование шаблонов отчетов</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Удаление шаблонов для отчетов</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td><td></td></tr><tr><td>Полный доступ к шаблонам отчетов</td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td><ul class="contains-task-list"><li><input type="checkbox" checked></li></ul></td><td></td><td></td><td></td></tr></tbody></table>

