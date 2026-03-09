# EKI Eesti-vene sonaraamat

`EKIEestiVene.dictionary` — словарь для приложения `Словарь` на macOS.

## Что это за словарь

Это эстонско-русский словарь на основе данных Института эстонского языка (Eesti Keele Instituut, EKI), подготовленный в формате Apple Dictionary для использования в приложении `Словарь`.

## Что содержит словарь

- эстонские заголовочные слова
- русские переводы
- ударения в русских переводах
- поиск по словоформам эстонских слов
- блок с основными формами слова
- дополнительные формы слова на карточке

## Источники данных

Словарь основан на данных EKI:

- EVS: [Eesti-vene sonaraamat 1997-2009 ja 2019](https://arhiiv.eki.ee/litsents/idkaart/dl.cgi?D=evs)
- EVS XML: [evs_EKI_CCBY40.xml](https://arhiiv.eki.ee/litsents/idkaart/evs/evs_EKI_CCBY40.xml)
- PSV: [Eesti keele pohisonavara sonastik 2014](https://arhiiv.eki.ee/litsents/idkaart/dl.cgi?D=psv)
- PSV XML: [psv_EKI_CCBY40.xml](https://arhiiv.eki.ee/litsents/idkaart/psv/psv_EKI_CCBY40.xml)

Файлы источников помечены как `CCBY40`, поэтому при публикации и распространении словаря нужно сохранять атрибуцию EKI.

## Как установить

1. Скопируйте `EKIEestiVene.dictionary` в папку:
   ```bash
   ~/Library/Dictionaries/
   ```
2. Откройте приложение `Словарь`.
3. В настройках словарей включите `EKI Eesti-vene sonaraamat`.
4. Если словарь не появился сразу, перезапустите приложение `Словарь`.

## Примечание

Словарь предназначен для macOS и работает в приложении `Словарь`, а также в системном lookup / Force Touch после активации.
