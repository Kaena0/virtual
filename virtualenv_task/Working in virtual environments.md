# Робота у віртуальному середовищі Python

## Етапи виконання:

1. **Створено віртуальне середовище:**

2. **Активовано середовище:**
- Windows:  
  ```
  venv\Scripts\activate
  ```
- Mac/Linux:  
  ```
  source venv/bin/activate
  ```

3. **Встановлено бібліотеку:**

4. **Створено скрипт `main.py`, який виконує HTTP-запит до GitHub API:**

```python
import requests

response = requests.get('https://api.github.com')
print("Status code:", response.status_code)
pip freeze > requirements.txt
deactivate
