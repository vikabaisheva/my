# my
туох да улаханый)
уларыйыы баар дуо
Земля
Венера
Марс
Нептунс
#Изменения 7.11 Добавил команду проверки количества пиров, Также бот автоматически каждые INFOTIME (у меня 10 сек) проверяет количество пиров. И если пиров меньше равно 2 перезагружает ноду

обновляем пакеты
sudo apt update && sudo apt upgrade -y
скачиваем репозиторий
git clone https://github.com/tarabukinivan/haqq_bot.git
Устанавливаем nodejs и npm
curl -sL https://deb.nodesource.com/setup_16.x | sudo -E bash - && \
sudo apt-get install nodejs -y && \
echo -e "\nnodejs > $(node --version).\nnpm  >>> v$(npm --version).\n"
результат выполнения должен быть примерно такой:
