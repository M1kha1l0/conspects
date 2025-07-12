---
tags:
  - python
  - linux
---
# Источники
https://losst.pro/peremennaya-path-v-linux
https://newtechaudit.ru/virtualnoe-okruzhenie-v-linux/
https://ru.hexlet.io/courses/python-setup-environment/lessons/venv/theory_unit

# Конспект

`$ sudo apt install python3-venv`
	установка пакета venv
	
`$ python3 -m venv my_venv`
	создание каталога с менеджером пакетов **pip** 
	my_venv - название виртуальной среды, на месте названия можно указать путь к каталогу, если он отсутствует, то создаст.
`$ source ~/path/to/venv/bin/activate`
	активация виртуальной среды

==далее все действия в виртуальной среде== 
`$ pip freeze` 
	команда выдаст список установленных библиотек в данной виртуальной среде
``