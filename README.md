
# Отключение контроля остатков 1С:ERP 2.5.x (УТ 11.4, КА 2)

## Способы добавления расширения в базу 1С

1. Первый вариант добавления расширения через конфигуратор:
    
   Создаем пустое расширение через кнопку добавления


    Появится окно создания расширения. Оставляем все значения по умолчанию и жмем кнопку "ОК":

    ![img2](images/2.png)

    В списке расширений появится новое пустое расширение. выбираем новое расширение путем однократного нажатия на строчку новым пустым расширением. Затем в панели управления жмем пункт "Конфигурация" и выбираем "Загрузить конфигурацию из файла"

    ![img3](images/3.png)


    Появится окно выбора файла расширения. Выбираем расширение с контролем остатка. Появится диалоговое окно, на котором соглашаемся продолжить:

    ![img4](images/4.png)

    Затем появится еще одно окошко, которое сообщит, что расширение загружено и требуется произвести обновление конфигурации БД:
    
    ![img5](images/5.png)

    **Всё! Расширение добавлено в базу.**
    ![img6](images/6.png)


2. Добавление расширения в пользовательском режиме.
    
    Заходим в функции технического специалиста и ищем в разделе "Стандартные" пункт "Управление расширениями конфигурации"
    ![img7](images/7.png)

    Открываем консоль управления расширениями и через кнопку "добавить" добавляем наше расширение:
    ![img8](images/8.png)

    **Всё! Расширение сразу появится списке расширений.**
    ![img9](images/9.png)

ВАЖНО!
После добавления расширения следует отключить "Безопасный режим" и "Защита от опасных действий", но сделать это следует только для расширения отключения контроля остатков!
![img10](images/10.png)

![img11](images/11.png)


## Отключить контроль остатков на время сеанса согласно описаниям ниже:

Открыть настройки финансового результата и контролинга:
![img12](images/12.png)


В появившейся вкладке раскрыть настройки "Учет товаров" и нажать на кнопку "Отключить контроль остатков (на время сеанса)"
![img13](images/13.png)

**ВСЁ! Теперь можно отменять проведение документов, где присутствуют товары и где требуется вести учет остатков.**
 
    Проверено на документах "Этапы производства" и "Расходный ордер на товары"
