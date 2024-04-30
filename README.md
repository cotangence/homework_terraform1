Задание 1

![image](https://github.com/cotangence/homework_terraform1/assets/160312212/6d5b4e0e-ef12-4b55-8ee0-88514d98b2dc)

![image](https://github.com/cotangence/homework_terraform1/assets/160312212/56625c27-4612-48ba-bed4-c0d2a4f10bc4)

Были ошибки в имени парметра для platform_id и указан один CPU  но минимальное количество 2 

Параметры preemptible = true - прерываемая ВМ ценник на такую ВМ сильно ниже, но раз в сутки она выключается.

core_fraction=5  - гарантированная доля ядра также позволяет значительно сэкономить на ВМ , на машинах с большой нагрузкой данный параметр использовать не стоит.


Задание 2

![image](https://github.com/cotangence/homework_terraform1/assets/160312212/fcce77f8-1f18-4cc9-a701-763d1c020f40)
