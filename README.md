# CSharpMathParser

## Описание:
Парсер и калькулятор математических выражений с двумя неизвестными параметрами

## Практическое применение

Доступен один публичный статический метод ***calculate*** который и следует вызывать для решения

```C#
public static double calculate(double x, double y, string infixPhrase)
```

***x*** и ***y*** - задаваемые параметры,

***infixPhrase*** - математическое выражение


## Пример использования

```C#
string mathExpression = "x^  2 + y ^ 2 + 100 + sin(pi)";
Console.WriteLine(MathParser.calculate(0.5, 0.5, mathExpression).ToString());
```

## Справка

Поддерживаются следующие токены в выражении:
***( ) + - * / ^ sin cos tg ctg ln pi e x y***
