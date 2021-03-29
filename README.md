#Отчёт о тестировании Credit Card Number Validator
##Краткое описание
23.03.2021-25.03.2021 было проведено тестирование функциональности валидации номера банковской карты приложения Credit Card Number Validator.

На тестирование затрачено: 48 часов

##В результате тестирования выявлены следующие дефекты:

* Ошибка при попытке валидации номера карты American Express (AMEX) - https://github.com/Anastasia-Sterh/Java1.1/issues/1
* Ошибка при попытке валидации номера карты Diners Club - Carte Blanche - https://github.com/Anastasia-Sterh/Java1.1/issues/2
* Ошибка при попытке валидации данных карты Diners Club - International - https://github.com/Anastasia-Sterh/Java1.1/issues/3

##Описание процесса тестирования
В процессе тестирования использовались следующие артефакты*:

* Тест-кейс

В качестве тестовых данных использовались данные с сайте freeformatter.com:

* VISA: 4556454728130823
* MasterCard: 5444188123069789
* American Express (AMEX):340381405531503
* Discover:6011137650022282
* JCB:3589126910328620
* Diners Club - North America:5560260219982924
* Diners Club - Carte Blanche:30305034826096
* Diners Club - International:36991248594937
* Maestro: 6763581148396818
* Visa Electron: 4026159491465288
* InstaPayment: 6389871532033687

##Тестирование производилось в следующем окружении:

* Windows 10 Домашняя х64
* Java 11