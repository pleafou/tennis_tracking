# Нейросетевая модель для трекинга теннисного мяча по видеофрагментам матча.

## Практическое задание в рамках курса "Нейронные сети в обработке изображений".

Была реализована модель для трекинга теннисного мяча на серии видеофрагментов матча. Для каждого кадра записи необходимо было определить, есть ли мяч в кадре, и, в случае его наличия, определить координаты центра мяча на видео.

Предоставленные данные для разработки модели представляют собой набор игр (game), состоящих из нескольких клипов (clip), каждый из которых состоит из набора кадров (frame). Все видео представлены в виде последоватльности кадров в формате .jpg разрешения 1280 $`\times`$ 720.

В качетсве модели была реализована сеть Unet. Достигнутая точность метрики на тесте - 0.78

Пример работы:



https://github.com/pleafou/tennis_tracking/assets/146244585/aebdac5d-613a-4e06-904c-9396a12cd6e5


