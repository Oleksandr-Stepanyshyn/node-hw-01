# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list
https://monosnap.com/file/RFFCMWelodIiVSMZafZvQKclgas3OK

# Получаем контакт по id

node index.js --action get --id 5
https://monosnap.com/file/LMenLcjdPsFNpmAy9cyigfvq5zrprX

# Добавялем контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/h86RyN9zLERCuzojlBKNWn7B8ahDoA

# Удаляем контакт

node index.js --action remove --id=3
https://monosnap.com/file/uFVMhQJVr8r3LBWjeFkkTv4Ehcg4UA
