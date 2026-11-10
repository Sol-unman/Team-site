# Проверка VHS, часть III — v4.5.1

## Что проверено

- 99 отдельных сочетаний: 11 сцен × 9 размеров экрана. В каждом случае отрисованы три момента сцены; проверены холст и доступные элементы управления.
- 53 дополнительные проверки: границы таймера, неверные/повторные действия, пауза, клавиатура, извлечение, звук, структура переходов, ошибки браузера и HTTP.
- Полное прохождение успешной ветки на компьютере и телефоне; реальные проверки трёх секунд на выбор и шести секунд ожидания Фога.
- Отдельная проверка реального зависания основного потока на 3,15 секунды; проверка спокойного режима и прежних кассет.

## Исправлено

- Опоздавшее действие больше не принимается после длительного зависания кадра; таймер выбора останавливается при скрытии вкладки.
- Если таймер переключил сцену, движок сразу использует новую сцену для отрисовки.
- В спокойном режиме подавлена вспышка дробовика и убрано пульсирование лазеров.
- Исправлена фраза при досрочном извлечении, уточнена доступная подпись группы кнопок.

## Результаты 99 проверок

- OK — 320x568 p3_tape
- OK — 320x568 p3_arrival
- OK — 320x568 p3_class
- OK — 320x568 p3_choice
- OK — 320x568 p3_fail
- OK — 320x568 p3_scare
- OK — 320x568 p3_shot
- OK — 320x568 p3_punch
- OK — 320x568 p3_impact
- OK — 320x568 p3_confront
- OK — 320x568 p3_lasers
- OK — 360x640 p3_tape
- OK — 360x640 p3_arrival
- OK — 360x640 p3_class
- OK — 360x640 p3_choice
- OK — 360x640 p3_fail
- OK — 360x640 p3_scare
- OK — 360x640 p3_shot
- OK — 360x640 p3_punch
- OK — 360x640 p3_impact
- OK — 360x640 p3_confront
- OK — 360x640 p3_lasers
- OK — 375x667 p3_tape
- OK — 375x667 p3_arrival
- OK — 375x667 p3_class
- OK — 375x667 p3_choice
- OK — 375x667 p3_fail
- OK — 375x667 p3_scare
- OK — 375x667 p3_shot
- OK — 375x667 p3_punch
- OK — 375x667 p3_impact
- OK — 375x667 p3_confront
- OK — 375x667 p3_lasers
- OK — 390x844 p3_tape
- OK — 390x844 p3_arrival
- OK — 390x844 p3_class
- OK — 390x844 p3_choice
- OK — 390x844 p3_fail
- OK — 390x844 p3_scare
- OK — 390x844 p3_shot
- OK — 390x844 p3_punch
- OK — 390x844 p3_impact
- OK — 390x844 p3_confront
- OK — 390x844 p3_lasers
- OK — 430x932 p3_tape
- OK — 430x932 p3_arrival
- OK — 430x932 p3_class
- OK — 430x932 p3_choice
- OK — 430x932 p3_fail
- OK — 430x932 p3_scare
- OK — 430x932 p3_shot
- OK — 430x932 p3_punch
- OK — 430x932 p3_impact
- OK — 430x932 p3_confront
- OK — 430x932 p3_lasers
- OK — 768x1024 p3_tape
- OK — 768x1024 p3_arrival
- OK — 768x1024 p3_class
- OK — 768x1024 p3_choice
- OK — 768x1024 p3_fail
- OK — 768x1024 p3_scare
- OK — 768x1024 p3_shot
- OK — 768x1024 p3_punch
- OK — 768x1024 p3_impact
- OK — 768x1024 p3_confront
- OK — 768x1024 p3_lasers
- OK — 1024x768 p3_tape
- OK — 1024x768 p3_arrival
- OK — 1024x768 p3_class
- OK — 1024x768 p3_choice
- OK — 1024x768 p3_fail
- OK — 1024x768 p3_scare
- OK — 1024x768 p3_shot
- OK — 1024x768 p3_punch
- OK — 1024x768 p3_impact
- OK — 1024x768 p3_confront
- OK — 1024x768 p3_lasers
- OK — 1280x800 p3_tape
- OK — 1280x800 p3_arrival
- OK — 1280x800 p3_class
- OK — 1280x800 p3_choice
- OK — 1280x800 p3_fail
- OK — 1280x800 p3_scare
- OK — 1280x800 p3_shot
- OK — 1280x800 p3_punch
- OK — 1280x800 p3_impact
- OK — 1280x800 p3_confront
- OK — 1280x800 p3_lasers
- OK — 844x390 p3_tape
- OK — 844x390 p3_arrival
- OK — 844x390 p3_class
- OK — 844x390 p3_choice
- OK — 844x390 p3_fail
- OK — 844x390 p3_scare
- OK — 844x390 p3_shot
- OK — 844x390 p3_punch
- OK — 844x390 p3_impact
- OK — 844x390 p3_confront
- OK — 844x390 p3_lasers

## Границы проверки

Проверки выполнялись в Chromium с разными размерами окна; физические iPhone/Android и другие браузеры отдельно не испытывались. Это не 99 полных построчных ревизий и не гарантия отсутствия всех ошибок.
