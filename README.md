# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list
https://photos.google.com/album/AF1QipPMJM1dR0TS721PhCJKOhdBcaeu_r6blfjxOM1a/photo/AF1QipMxpS-1X02hMojB5AgrLDNU9dpxYopaJJhw_IXV

# Получаем контакт по id

node index.js --action get --id 5
https://photos.google.com/album/AF1QipPMJM1dR0TS721PhCJKOhdBcaeu_r6blfjxOM1a/photo/AF1QipMiMCg-3utiXj2qhBKKBmQ22N19crHz9Hgqqko5

# Добавялем контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://photos.google.com/album/AF1QipPMJM1dR0TS721PhCJKOhdBcaeu_r6blfjxOM1a/photo/AF1QipOVRcqddpfJZZWaO-6q7ZMOyW2GnCyOrK7JUjDJ

# Удаляем контакт

node index.js --action remove --id=3
https://photos.google.com/album/AF1QipPMJM1dR0TS721PhCJKOhdBcaeu_r6blfjxOM1a/photo/AF1QipMh6qXTbBlOHQmE7TQFYFhbizpWc0b60PNzWMDN
