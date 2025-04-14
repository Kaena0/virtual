# Звіт до роботи

---

### **Тема:** Робота у віртуальному середовищі Python  
### **Мета роботи:** Ознайомитись із створенням, активацією та використанням ізольованих віртуальних середовищ у Python. Навчитись працювати з бібліотекою `requests` та зберігати залежності проєкту.

---

## Виконання роботи

### ✅ Результати виконання завдання:

1. **Створили** віртуальне середовище командою:

2. **Активували середовище**:
- Windows:  
  ```
  venv\Scripts\activate
  ```
- Linux/macOS:  
  ```
  source venv/bin/activate
  ```

3. **Встановили бібліотеку**:

4. **Створили програму `main.py`:**

```python
import requests

response = requests.get('https://api.github.com')
print("Status code:", response.status_code)
pip freeze > requirements.txt
deactivate

## 📸 Вставлені рисунки (скріншоти)

_Скріншоти виконання роботи з терміналу, файлів та GitHub:_

![](https://raw.githubusercontent.com/Kaena0/virtual/main/virtualenv_task/screenshots/main-py.png)  
![](https://raw.githubusercontent.com/Kaena0/virtual/main/virtualenv_task/screenshots/requirements.png)




