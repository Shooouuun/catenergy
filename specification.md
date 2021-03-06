# Техническое задание
---
**1. Общие технические требования**

 * 1.1. Сетка: определена в макете.
 * 1.2. Адаптивность сетки: мобильная, планшетная и десктопная версии («фикс» или «резина»).
 * 1.3. Адаптивность графики: ретинизация, векторные изображения.
 * 1.4. Используемая методология: БЭМ.
 * 1.5. Используемый препроцессор: Less или Sass.
 * 1.6. Используемый инструмент автоматизации: Gulp.
 * 1.7. Используемые фреймворки: нет.
 * 1.8. Кроссбраузерность: Chrome, Firefox, Safari, Edge и Internet Explorer 11.
 * 1.9. Типографика: частично определена в макете (прочее — на усмотрение разработчика).
 * 1.10. Используемый шрифт: Oswald.

**2. Пояснения для учащихся**

 * 2.1. Обязательными к вёрстке являются все 3 страницы (главная страница, страница с формой, страница каталога).
 * 2.2. Макеты верстаются постепенно: сначала мобильная версия, далее от мобильной версии к планшетной, а затем и к десктопной.
 * 2.3. Готовить растровую и векторную графику для проекта не нужно, она будет добавлена в проект после лекции «Препроцессоры и автоматизация».
 * 2.4. Дополнительная ретиновая и адаптивная графика будет добавлена в проект после лекции «Адаптивная графика».

**Пожелания к поведению блоков**
**3. Все макеты**

 * 3.1. Между версиями (мобильная, планшетная, десктопная) сетка может быть как резиновой, так и фиксированной.
 * 3.2. При фиксированной сетке контентная область центруется и не может быть уже макетной ширины.
 * 3.3. Логотип на внутренних страницах — это ссылка на главную страницу.
 * 3.4. Главное меню в мобильной версии появляется под шапкой сайта (в макете в панели слоёв Photoshop меню выделено красным цветом).
 * 3.5. Мобильное меню может быть реализовано двумя способами:
   - реализация без JS;
   - реализация с использованием JS.
 * 3.6. При реализации без использования JS главное меню в мобильной версии должно быть всегда открыто, а иконка с крестиком — скрыта.
 * 3.7. При реализации с использованием JS блок с главным меню в мобильной версии должен открываться при нажатии на иконку «гамбургера». Когда меню открыто, иконка «гамбургера» заменяется на крестик. При нажатии на иконку с крестиком меню закрывается.
 * 3.8. Все состояния элементов при наведении и нажатии указаны в макетеcat-energy-styleguide.psd. Состояние ошибки должно быть реализовано только для обязательных полей формы (в макете они помечены звёздочкой).
 * 3.9. Логотип Академии и ссылкаHTML Academy в футере ведут на лендинг интенсива «Профессиональный HTML и CSS, уровень 2».

**4. Главная**
**Мобильная версия (cat-energy-index-mobile.psd):**

 * 4.1. Логотип состоит из упрощённой иконки и названия магазина «Кэт энерджи».
 * 4.2. Кнопка «Подобрать программу» должна вести на страницу формы для подбора программы.
 * 4.3. В блоках «Похудение» и «Набор массы» ссылкой должна быть строка, начинающаяся со слова «Каталог». При нажатии должен осуществляться переход на соответствующие разделы каталога. Страницы разделов реализовывать не нужно.
 * 4.4. В блоке «Живой пример» слайдер реализовывать не обязательно. Достаточно вёрстки с одной из фотографий кота. По желанию можно сделать «Было» и «Стало» кнопками переключения фотографий кота.
 * 4.5. Блок карты: необходимая реализация — интерактивная карта (карты Google или Яндекса), ширина подстраивается под ширину вьюпорта (но не уже контентной ширины макета), на карте размещён маркер (может быть как кастомным, так и дефолтным), центр карты соответствует центру блока в макете.

**Планшетная версия (cat-energy-index-tablet.psd):**

 * 4.6. Блоки меняют размеры и расположение согласно макету.
 * 4.7. В состав иконки логотипа добавляются новые элементы.
 * 4.8. Главное меню всегда открыто вне зависимости от его состояния на мобильной версии.

**Десктопная версия (cat-energy-index-desktop.psd):**

 * 4.9. Блоки меняют размеры и расположение согласно макету.
 * 4.10. В составе логотипа добавляются новые элементы.
 * 4.11. Фон первого блока под шапкой тянется на всю ширину экрана и состоит из двух равных частей: левая — с белым фоном, правая — с зелёным фоном и изображением кота, которое упирается в правую границу экрана.

**5. Форма**
**Мобильная версия (cat-energy-form-mobile.psd):**

 * 5.1. Должны быть реализованы кастомные элементы форм.
 * 5.2. У полей ввода телефона и почты должны быть указаны соответствующие типы для удобного заполнения с телефона.

**Планшетная версия (cat-energy-form-tablet.psd):**

 * 5.3. Блоки меняют размеры и расположение согласно макету.

**Десктопная версия (cat-energy-form-desktop.psd):**

 * 5.4. Блоки меняют размеры и расположение согласно макету.

**6. Страница каталога**
**Мобильная версия (cat-energy-catalog-mobile.psd):**

 * 6.1. Изображение и название товара – ссылки на страницу с описанием товара. Страницу с описанием товара реализовывать не нужно.
 * 6.2. Кнопка «Заказать» вызывает появление модального окна для оформления заказа. Модальное окно оформления заказа реализовывать не нужно. При отключенном JS должен осуществляться переход на страницу оформления заказа (страницу оформления заказа реализовывать не нужно).
 * 6.3. Кнопка «Показать все» показывает новые товары, загружаемые по ajax. Загрузку по ajax реализовывать не нужно. При отключенном JS должен осуществляться переход на страницу новых товаров (страницу новых товаров реализовывать не нужно).

**Планшетная версия (cat-energy-catalog-tablet.psd):**

 * 6.4. Блоки меняют размеры и расположение согласно макету.

**Десктопная версия (cat-energy-catalog-desktop.psd):**

 * 6.5. Блоки меняют размеры и расположение согласно макету.
