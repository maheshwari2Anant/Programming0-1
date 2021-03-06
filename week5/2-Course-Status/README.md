# Статус на курсистите

Радо е изпаднал в затруднение с курса по Ruby on Rails.

Системата му е дала списък с всички кандидатствали курсисти и техния статус - дали са си предали задачите или не. Обаче Радо се е объркал и не може да разбере колко са финализираните кандидатури и колко не са.

Във файл `status.py`, напишете функция `status_count(students)`, която:

* Взима списък от речници `students`. Всеки речни в списъка има два ключа - `"name"` и `"status"`, като статусът може да е `"finalized"` или `"not_finalized"`.
* Връща речник, които има два ключа - `"finalized"` и `"not_finalized"`. Срещу всеки речник стои списък от имената на студентите, които имат дадения статус в `students`

Например, ако имаме следния списък:

```python
students = [{
              "name": "RadoRado",
              "status": "not_finalized"
            }, {
              "name": "Ivo",
              "status": "finalized"
            }, {
              "name": "Genadi",
              "status": "finalized
            }]
```

То резултатът трябва да изглежда така:

```python
{
  "finalized": ["Ivo", "Genadi"],
  "not_finalized": ["RadoRado"]
}
```
