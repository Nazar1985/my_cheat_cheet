## Intro


#!/bin/bash 

`name.sh` - имя файла

`$` - 

`$@` - все параметры, по которым можно пройти в цикле

`$*` - все параметры, которые выводятся как единая строка, разделенные первым символом IFS.

`$#` - специальный параметр в bash, который дает число позиционных параметров в десятичном формате.

`$$` - выдаст PID шелла

`$!` - дает идентификатор процесса последнего выполненного фонового процесса

`$?` - Дает статус выхода последней выполненной команды. `if [ "$?" -ne "0" ]; then`

`$-` - Параметры, заданные с помощью встроенной команды Set

`$_` - Дает последний аргумент предыдущей команды. При запуске оболочки выдает абсолютное имя файла скрипта шелла, который выполняется.