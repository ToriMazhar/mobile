# Тестирование мобильных приложений  
1. В рамках выполнения заданий по тестированию мобильного приложения "shopping-list" были созданы:  
* [чек-листы](https://docs.google.com/spreadsheets/d/14tGcTq0n9YNvQM1IAqUqu-U2s_uFKhKaxFMop0w-6nQ/edit?gid=0#gid=0) для тестирования основных функциональностей приложения и общих проверок;
* 15 [тест-кейсов](https://github.com/ToriMazhar/mobile/blob/main/%D0%A2%D0%B5%D1%81%D1%82-%D0%BA%D0%B5%D0%B9%D1%81%D1%8B_mobile.pdf) (QASE);  
* [отчеты о дефектах](https://docs.google.com/spreadsheets/d/1VN9DmRhBAARzidsIvg6teC8IZxd7LmiV/edit?gid=1264840991#gid=1264840991) - выгружены из YouTrack по результатам тестирования по чек-листам и тест-кейсам. Запуск тест-кейсов, осуществлялся через Test Run в QASE ([тестовый прогон](https://drive.google.com/file/d/1SBudWK5_4Wi7tjZTyq44ZQtXFAYwOsVU/view?usp=sharing));
* [отчет по результатам тестирования](https://docs.google.com/document/d/1ZclzmQQ0ZYLniyYF394nIMeRvb1lnb0C/edit)
  
Приложение "shopping-list" было скачано из APK-файла с помощью эмулятора Android Studio.
"shopping-list" позволяет составить список задач с возможностью добавлять, редактировать, удалять задачи, а также отмечать выполнение задач.

2. В рамках задания по перехвату и изменению трафика скачан Charles Proxy и настроен для смартфона.
Были повторены различные тестовые сценарии для приложения ["Интернет-магазин"](https://demoshopping.ru/) и записано [видео](https://drive.google.com/file/d/18tIu_KgQlQ1paHJzkBSafj7xG_V0PD1q/view?usp=sharing) по следующим задачам:
* Добавьте несколько разных товаров в корзину,  отправьте запрос на удаление любого из них из корзины, но видоизмените его так, чтобы он удалил другой товар;
* Смоделируйте ситуацию, при которой при обращении к https://demoshopping.ru пользователь увидит в браузере любую картинку.

Для примера представлен [скриншот перехваченного запроса](https://github.com/ToriMazhar/mobile/blob/main/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82_%D0%BF%D0%B5%D1%80%D0%B5%D1%85%D0%B2%D0%B0%D1%82%D0%B0%20%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81%D0%B0%20%D1%81%20%D0%BC%D0%BE%D0%B1%20%D1%83%D1%81%D1%82%D1%80%D0%BE%D0%B9%D1%81%D1%82%D0%B2%D0%B0.png) с мобильного устройства, где в header user-agent видна информация об устройстве.  


