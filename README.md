# WordPress Plugin Saints
* Biography of Saints for any date. For Orthodox sites using WordPress.
* Описание жития Святых для сайтов православной тематики.

## Contents

The WordPress Plugin Saints includes the following files:

* `CHANGELOG.md`. The list of changes to the core project.
* `README.md`. The file that you’re currently reading.
* A `Saints` directory that contains the source code - a fully executable WordPress plugin.

## Features

* The Saints is based on the [Plugin API](http://codex.wordpress.org/Plugin_API), [Coding Standards](http://codex.wordpress.org/WordPress_Coding_Standards), and [Documentation Standards](https://make.wordpress.org/core/handbook/best-practices/inline-documentation-standards/php/).
* All classes, functions, and variables are documented so that you know what you need to change.

## Installation

* The Saints can be installed directly into your plugins folder "as-is".
* Change the name of the folder with the plugin to "Saints" if it is different

## WordPress.org Preparation

The original launch of this version of the Saints included the folder structure needed for using your plugin on WordPress.org. That folder structure has been moved to its own repo here: https://github.com/Siamajor/Saints

## License

The WordPress Plugin Saints is licensed under the GPL v2 or later.

> This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License, version 2, as published by the Free Software Foundation.

> This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

> You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA 02110-1301 USA

A copy of the license is included in the root of the plugin’s directory. The file is named `LICENSE`.

# Credits

The WordPress Plugin Saints was started in 2021 by [Igor Soloshenko](https://github.com/Siamajor) and has since included a number of great contributions. 
The current version of the Saints using API https://azbyka.ru/ 

## Documentation, FAQs, and More
-- EN --
(Machine translate)
* The plugin was conceived as an addition to the page "This day in the calendar", but it can be used independently.
* The plugin displays the biographies of Saints using the shortcode [saints] for any date (with the built-in calendar widget (shortcode [s-calendar]), or the calendar plugin * Bg Orthodox Calendar *, or any other calendar widget with the YYYY-MM-DD date format ...
* The API of the site *azbyka.ru* for the specified date is used to obtain data. Application Programming Interface of the site *azbyka.ru* does not require username, password or other conditions. You can get acquainted with the full list of provided APIs at https://azbyka.ru/days/site/api_help. The Saints plugin uses the API https://azbyka.ru/days/api/saints/-date-/group.json - set saints for a given date, saints are grouped together, specifically arrays: ["title"] - names of Saints; ["image"] - the name of the miniatures of the icons of the Saints; ["description"] - text describing the lives of the Saints; ["saint_id"] - Saint's identifier; ["taks"]["title"] - titles of troparia, kontakion and prayers; ["taks"]["text"] - texts of troparia, kontakion and prayers;
* Thumbnails of icons of Saints are downloaded from the address https://azbyka.ru/days/assets/img/saints/ ["saint_id"]/["image"] for the corresponding date, have the "nofollow" attribute.
* To display brief information for a specific date, use https://azbyka.ru/days/api/presentations/-date-.json - html-block for a given date, array: ["presentations"].
* All references to places from the Bible, etc. have the nofollow attribute.
* If the calendar widget is not installed, the data for the current day will be displayed.

* In order to reduce the load on the server and speed up the page loading, you can download an archive of prepared miniatures of the Saints' icons and upload it to the /wp-content/uploads/saints-cache/directory in .zip format. When you select the appropriate source of images on the plugin settings page, the archive will be unpacked into the /wp-content/uploads/saints-cache/img/ directory
* Download address for img.zip archive (82.66 MB): https://xn--b1aplbci.xn--j1amh/wp-content/uploads/saints-cache/111/img.zip
* Plugin in Russian and Ukrainian

-- UA --
* Плагін замислювався як доповнення до сторінки "Цей день в календарі", але може використовуватися і самостійно.
* Плагін виводить за допомогою шорткода [saints] життєописи Святих на будь-яку дату (з віджетом вбудованого календаря (шорткод [s-calendar]), або календаря плагіна * Bg Orthodox Calendar *, або будь-якого іншого елемента календаря з форматом дати YYYY-MM-DD) .
* Для отримання даних використовується API сайту *azbyka.ru* на зазначений день, тому тексти будуть лише російською (Використовувати Google перекладач або будь-який інший машинний переклад для церковних текстів неможливо через жахливи помилки, що призводять до спотворення змісту). Application Programming Interface сайту *azbyka.ru* не вимагає введення логіна, пароля або інших умов. Ознайомитися з повним списком послуг API можна за адресою https://azbyka.ru/days/site/api_help. В плагіні Saints використовується API https://azbyka.ru/days/api/saints/-дата-/group.json - набір святих для заданої дати, святі об'єднані в групи, а саме масиви: ["title"] - імена святих; ["Image"] - назва мініатюр ікон святих; ["Description"] - текст опису житія Святих; ["Saint_id"] - ідентифікатор Святого; ["Taks"]["title"] - заголовки тропарів, кондаків і молитов; ["Taks"]["text"] - тексти тропарів, кондаків і молитов;
* Мініатюри ікон святих завантажуються з адреси https://azbyka.ru/days/assets/img/saints/["saint_id"]/["image"] для відповідної дати, мають атрибут "nofollow".
* Для виведення короткої інформації на конкретну дату використовується https://azbyka.ru/days/api/presentations/-дата-.json - html-блок для заданої дати, масив: ["presentations"].
* Всі посилання на місця з Біблії та ін. мають атрибут nofollow.
* Якщо не встановлено віджет календаря, будуть виводитися дані на поточний день.

* З метою зменшення навантаження на сервер і прискорення завантаження сторінки ви можете скачати собі архів підготовлених мініатюр ікон святих і завантажити його в директорію /wp-content/uploads/saints-cache/ в форматі .zip. При виборі відповідного джерела картинок на сторінці налаштувань плагіна архів буде розпакований в директорію /wp-content/uploads/saints-cache/img/
* Адреса для скачування архіву img.zip (82.66 мб): https://xn--b1aplbci.xn--j1amh/wp-content/uploads/saints-cache/111/img.zip
* Плагін російською та українською мовами

-- RU --
* Плагин задумывался как дополнение к странице "Этот день в календаре", но может использоваться и самостоятельно.
* Плагин выводит с помощью шорткода [saints] жизнеописания Святых на любую дату (с виджетом встроенного календаря  (шорткод [s-calendar]), либо календаря плагина *Bg Orthodox Calendar*, либо любого другого виджета календаря с форматом даты YYYY-MM-DD) .
* Для получения данных используется API сайта *azbyka.ru* на указанный день. Application Programming Interface сайта *azbyka.ru* не требует ввода логина, пароля или других условий. Ознакомиться с полным списком предоставляемых API можно по адресу https://azbyka.ru/days/site/api_help В плагине Saints используется API https://azbyka.ru/days/api/saints/-дата-/group.json - набор святых для заданной даты, святые объединены в группы, а конкретно массивы: ["title"] - имена Святых; ["image"] - название миниатюр икон Святых; ["description"] - текст описания жития Святых; ["saint_id"] - идентификатор Святого; ["taks"]["title"] - заголовки тропарей, кондаков и молитв; ["taks"]["text"] - тексты тропарей, кондаков и молитв; 
* Миниатюры икон Святых загружаются с адреса https://azbyka.ru/days/assets/img/saints/["saint_id"]/["image"] для соответствующей даты, имеют атрибут "nofollow".
* Для вывода краткой информации на конкретную дату используется https://azbyka.ru/days/api/presentations/-дата-.json - html-блок для заданной даты, массив: ["presentations"].
* Все ссылки на места из Библии и др. имеют атрибут nofollow.
* Если не установлен виджет календаря, будут выводиться данные на текущий день.

* В целях уменьшения нагрузки на сервер и ускорения загрузки страницы вы можете скачать себе архив подготовленных миниатюр икон Святых и загрузить его в директорию /wp-content/uploads/saints-cache/  в формате .zip. При выборе соответствующего источника картинок на странице настроек плагина архив будет распакован в директорию /wp-content/uploads/saints-cache/img/ 
* Адрес для скачивания архива img.zip (82.66 мб): https://xn--b1aplbci.xn--j1amh/wp-content/uploads/saints-cache/111/img.zip
* Плагин на русском и украинском языках