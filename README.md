# Проект 4

### Реализован вариант 2. iDNA

Реализовано:
1. Добавлена локализация (русский язык или английский если изначально был русский). 
2. Добавлены всплывающие окна для подтверждения открытия и закрытия приложения. Сохранение в приложении не реализовано, поэтому и подтверждения тоже нет.
3. Сохраняются настройки эволюции в системе (user defaults) и загружаются при новом запуске приложения.

Не реализовано:
4. Использовать движение мыши в качестве источника случайности. Перед стартом эволюции пользователю должен совершить несколько движений мышью; координаты курсора будут использоваться в качестве некоторых исходных данных для генератора случайных чисел. Сбор этих координат должен отоброжаться прогресс-баром.
=> arc4random и так достаточно случайна, поэтому я так и не придумал куда приделывать это колесо (ценой потерянных балов).