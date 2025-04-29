<h1>Django template</h1>
Template for Django start project


1. Обрати розміщення для проєкту <br>
      `D:` - перейти на обраний диск <br>
      `cd <розміщення/назва теки>` - зайти до директорії <br>
      `cd..` - вийти до попередньої директорії <br>
      `dir` - показати вміст поточної теки

2. Створити теку
   ```bash
    md 'Назва_теки'
   ```

3. Клонувати 
    ```bash
    git clone https://github.com/romanrudniev/template.django.git
    ```

4. Віртуальне середовище
   - Створити віртуальне середовище `.venv` або підключити існуюче
       ```bash
     #створення віртуального середовища
      python -m venv .venv
      ```
   - Активація віртуального середовища
   ```bash
    # Windows
    .venv\Scripts\activate
    
    # Linux & MacOS
    .venv\bin\activate
    ```

5. Встановлення необхідних модулів
   ```bash
   pip install requirements
   ```

6. Розгортаємо Django проєкт
    ```bash
   django-admin startproject <найменування_сайту> .
   ```
    Крапка вкінці вказує, що проєкт буде розгорнуто в обраній директорії.


7. Створюємо додаток
    ```bash
   python manage.py startapp <назва_додатку>
   ```

<hr>

<h2>У проєкту є дві гілки:</h2>

1. (`main`) дерикторія `templates` та `static` знаходиться у дерикторії `app`
<br>
2. (`main_templates`) дерикторія `templates` та  знаходиться у загальній дерикторії

