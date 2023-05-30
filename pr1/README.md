## Цель работы

Получить сведения о системе

## Исходные данные

1\. Программное обеспечение AstraLinux

2\. Rstudio

## План работы

1.  Получить сведения версию ядра
2.  Получить полные сведения о ядре
3.  Используемый дистрибутив
4.  Получить модель процессора
5.  Скрытые файлы

## Ход работы:

1.  Получаем версию ядра при помощи команды uname -r

```{bash}
uname -r
```
![Alt-текст](https://github.com/DariaShch/Lab/blob/main/pr1/1.png)
2.  Получаем полные сведения о ядре при помощи команды uname -a

```{bash}
uname -a
```
![Alt-текст](https://github.com/DariaShch/Lab/blob/main/pr1/2.png)
3.  Используей дистрибутив получаем при помощи команды lsb_release -a

```{bash}
lsb_release -a
```
![Alt-текст](https://github.com/DariaShch/Lab/blob/main/pr1/3.png)
4.  Полную информацию получаем при помощи команды cat /proc/cpuinfo

```{bash}
cat /proc/cpuinfo 
```
![Alt-текст](https://github.com/DariaShch/Lab/blob/main/pr1/4.png)
![Alt-текст](https://github.com/DariaShch/Lab/blob/main/pr1/4pr.png)
5.  Модель процессора получаем при помощи команды cat /proc/cpuinfo \| grep "model name"

```{bash}
cat /proc/cpuinfo | grep "model name"
```
![Alt-текст](https://github.com/DariaShch/Lab/blob/main/pr1/5.png)
6.  Все скрытые файлы смотрим при помощи команды ls -a

```{bash}
ls -a
```
![Alt-текст](https://github.com/DariaShch/Lab/blob/main/pr1/6.png)

## Вывод
Привыполнении данного задания я узнала, как работать с базовыми командами Linux для получения сведений об операционной системе
