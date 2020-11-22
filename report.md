17.11.2020-17.11.2020 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 30 мин.

В результате тестирования выявлены следующие дефекты:

https://github.com/ilonadobro/Java1.2/issues/2

https://github.com/ilonadobro/Java1.2/issues/3

**Описание процесса тестирования**

В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:
```
VISA:
4532873460632945 - OK
4568931810284945 - OK
4539849268990949050 - FAIL
Diners Club - International:
36924978158953 - FAIL
36086338937987 - FAIL
36108048210370 - FAIL
MasterCard:
5502508767810116 - OK
2221006541060311 - OK
5348773160407328 - OK
JCB:
3530160192848492207 - FAIL
3541545073563912434 - FAIL
```
**Тестирование производилось в следующем окружении:**
```
ОС: Windows 10 x64
Версия Java: "11.0.9" 2020-10-20
```