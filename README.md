# python-learn
Скриптик подсчёта времени перебора словаря 
:)
Использование: 
user@serv$ python3 spck.py -s 1500 -f /path/to_the_dictionary/mydict.txt

Можно скопировать файл в /usr/bin и вызывать скрипт как обычную команду в bash:
user@serv$ cp spck.py /usr/bin/spck
user@serv$ spck -s 1500 -f ~/mydict.txt

Cкорость перебора можно узнать в выводе команды aircrack-ng -S, естественно, aircrack-ng должен быть установлен,
также можно узнать скорость перебора утилиты pyrit, набрав pyrit benchmark.


