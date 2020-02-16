# stands-05-bash

Стенд для занятия "Bash"

# Connect to vagrant bash
`vagrant ssh bash`
`sudo -i`
`yum install bash-completion -y`


# Примеры из урока

`egrep -v "^#|^$" /etc/sudoers`

### Приглашение оболочки

#### http://ezprompt.net/ - Приглашение оболочки

`export PS1="[\[\e[34m\]\d\[\e[m\] - \[\e[36m\]\A\[\e[m\]\[\e[32m\]\w\[\e[m\]]\\$"`

`export PS1="\e[0;31m[\u@\h \W]\$ \e[m"`

#### Приветствия

`echo "echo $USER" >> ~/.bash_profile`
`echo "echo \$USER" >> ~/.bash_profile`
`echo 'echo $USER' >> ~/.bash_profile`

`alias` - посмотреть все алиасы

`alias la='ls -A'` - задать алиас la

`alias lala='la -la'` - задать новый алиас lala


### Переменные окружения
`env` - вывести все системные переменные
`printenv` - или так

#### Установить переменную
`export var=var`

#### Считать переменную
`echo $var`
