# Инструкция по установке Eclipse Modeling Tools и JavaFX для операционной системы Windows
Для работы с приложениями на базе Amalgama Platform нам понадобится следующий набор софта:

1. **Eclipse Modeling Tools 2024-09**.  
[Ссылка на скачивание](https://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/2024-09/R/eclipse-modeling-2024-09-R-win32-x86_64.zip )   

2. **JavaFX 21.0.4**.  
[Ссылка на скачивание](https://download2.gluonhq.com/openjfx/21.0.4/openjfx-21.0.4_windows-x64_bin-sdk.zip )

## Порядок установки:

1. Скачайте и распакуйте **Eclipse Modeling Tools** в удобное для вас место (мы рекомендуем делать это не на системном диске, например, на диске D).
2. Скачайте и распакуйте архив с  **JavaFX 21.0.4** в `С:\Program Files\Java`.  
В результате должна появиться папка `C:\Program Files\Java\javafx-sdk-21.0.4\`
3. Создайте переменную окружения ***JAVAFX_HOME***.  
Открыть диалог [настройки переменных окружения](https://www.google.com/search?q=%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0+%D0%BF%D0%B5%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D1%8B%D1%85+%D0%BE%D0%BA%D1%80%D1%83%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F+%D0%B2+windows )  
Обновить/добавить переменную ***JAVAFX_HOME*** (папка, где установлен javafx 21, например, `C:\Program Files\Java\javafx-sdk-21.0.4\`).

4. Открыть Eclipse и создать новый воркспейс. Мы рекомендуем создавать папку для нового воркспеса не на системном диске, например, `D:\EclipseWorkspaces\SmartPlant\workspace`. 
5. В верхнем меню во вкладке **Help** перейти в **Eclipse Marketplace**. В открывшемся окне в поле поиска написать ***efxclipse***, нажать Enter и скачать найденный плагин. Eclipse предложит перезагрузить воркспейс, необходимо сделать это.
