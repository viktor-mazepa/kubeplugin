# Опис
kubeplugin це простий плагін для kubectl, що написаний на bash. Його призначення - виводити користувачу інформацю про наявні поди в заданному неймспейсі

## Встановлення
```
git clone https://github.com/viktor-mazepa/kubeplugin.git
cd kubeplugin/scripts
chmod +x kubeplugin
```

## Використання
Виконайте команду
```
./kubeplugin pod kube-system
```
Результат буде вивидено в табличному форматі - Resource|Namespace|Name|CPU(core)|
Memory|

## Демо
![Alt Text](/demo/kubeplugin_demo.gif)
