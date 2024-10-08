WeatherApp

Описание

WeatherApp — это WPF-приложение, созданное на языке C# для выполнения нескольких учебных заданий. Приложение включает в себя четыре окна, каждое из которых выполняет отдельное задание:

 • Переводчик русско-английских слов о погоде
 • Арифметический калькулятор
 • Проверка диапазона чисел
 • Проверка пароля для доступа к секретному сообщению

Функциональность

Главное окно

Главное окно приложения содержит кнопки для открытия каждого задания. При нажатии на кнопку открывается соответствующее окно.

Задание 1: Русско-английский переводчик

 • Окно позволяет пользователю ввести одно из 10 слов о погоде на русском языке.
 • При нажатии на кнопку “Перевести” приложение отображает перевод слова на английский язык.
 • Если слово не входит в словарь, выводится сообщение: “Такого слова нет.”

Задание 2: Калькулятор

 • Пользователь вводит знак арифметической операции (+, -, *, /) в окно калькулятора.
 • Приложение выполняет операцию над заданными переменными operand1 и operand2 и отображает результат.
 • Если пользователь выбирает деление на ноль, приложение уведомляет его об ошибке.

Задание 3: Проверка диапазона

 • Окно позволяет пользователю ввести число от 0 до 100.
 • Программа проверяет, попадает ли число в один из заданных диапазонов: [0 - 14], [15 - 35], [36 - 50], [51 - 100].
 • Если введенное число вне диапазона, выводится сообщение: “Число вне диапазона или неверный ввод.”

Задание 4: Проверка пароля

 • Окно запрашивает у пользователя пароль.
 • Если введенный пароль совпадает с заданным значением, программа открывает доступ к секретному сообщению.
 • При неверном пароле выводится сообщение об ошибке, и программа предлагает ввести пароль еще раз.

Установка и запуск

 1. Клонируйте репозиторий на свой компьютер:

git clone https://github.com/neroun4/WeatherApp.git


 2. Откройте проект в Visual Studio.
 3. Постройте и запустите проект, нажав на F5 или выбрав “Запустить” в меню “Отладка”.

Структура проекта

 • MainWindow.xaml и MainWindow.xaml.cs: Главное окно с кнопками для доступа ко всем заданиям.
 • TranslatorWindow.xaml и TranslatorWindow.xaml.cs: Окно для перевода русских слов о погоде на английский.
 • CalculatorWindow.xaml и CalculatorWindow.xaml.cs: Окно для выполнения арифметических операций.
 • RangeCheckerWindow.xaml и RangeCheckerWindow.xaml.cs: Окно для проверки диапазона введенного числа.
 • PasswordWindow.xaml и PasswordWindow.xaml.cs: Окно для проверки правильности пароля.

Используемые технологии

 • Язык программирования: C#
 • Платформа: WPF (Windows Presentation Foundation)
 • Среда разработки: Visual Studio

Контакты

Если у вас возникли вопросы или предложения, не стесняйтесь связаться со мной:

 • GitHub: NerouN (https://github.com/neroun)
