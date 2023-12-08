# Документация по разработке Игровых режимов PixelCombats

Предполагается, что вы немного знаете JavaScript и будете работать на компьютере, для удобного написания кодов и работы с режимами.

## Cоздаем свой режим (на основе уже существующего):
1. Регистрируемся на [GitHub](https://github.com/)
1. Ищем официальный режим в игре (можно и не офиц, но лижбы репозиторий был открыт)
1. Находим в игре кнопку со ссылкой на репозиторий и кликаем, откроется репозиторий режима. Там можно посмотреть все файлы режима и что там и как сделано.
   <br>Для примера вот наши официальные репозитории:
    - [TDM](https://github.com/kkohno/PixelCombats.GameModes.TDM)
    - [Мир](https://github.com/kkohno/PixelCombats.GameModes.Peace)
    - [Редактор Карт](https://github.com/kkohno/PixelCombats.GameModes.Editor)
    - [Паркур](https://github.com/kkohno/PixelCombats.GameModes.Parcour)
    - [Захват](https://github.com/kkohno/PixelCombats.GameModes.Capture)
1. Жмем в открывшемся репозитории кнопку fork (создаете свою копию репозитория). Однако можете и сами репозиторий создать. Если боитесь за свои коды, то делайте закрытый репозиторий.
1. Создаем новый режим в самой игре (думаю кнопку все нашли).
1. Привязываем в открывшемся окне, если еще не привязывали, свой [GitHub](https://github.com/) аккаунт к аккаунту в игре.
1. Привязываете свой созданный репозиторий к режиму, указав ссылку на репозиторий (или его имя).
1. Жмем в игре кнопку обновить с [GitHub](https://github.com/) (это применяет все изменения на репозитории к режиму в игре).

## Вносим изменения в режим:
1. Для удобства можете скачать программу [GitHub Desctop](https://desktop.github.com/) или другую, для работы с Git.
1. Cкачиваете созданный репозиторий себе на компьютер (нажав в репозитории Code->Open With GitHub Desctop).
1. Вносите в папке репозитория все изменения.
1. В приложении [GitHub Desctop](https://desktop.github.com/) (или какая у Вас там будет) жмете комит (это локально фиксирует сделанные изменения)
1. В тойже программе жмем отправить (Push origin). После этого шага все изменения отправлены на репозиторий [GitHub](https://github.com/).
1. В игре выбираем свой режим и там жмем кнопку обновить с [GitHub](https://github.com/). Это переносит изменения с репозитория в игру.

Полезное:
* [задавайте оффициальные карты для режима](GameModeOfficialMaps.md)