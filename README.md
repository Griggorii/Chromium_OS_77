# Chromium_OS_77
chromium OS testing compile OS12  based 16.04 chromium browser v77 download x64 amd64-generic

Chromium OS download : http://yadi.sk/d/YDo9_JoDwIb4WQ

Minimus size 11 Gb Гб HDDRawCopy source bin in target flash usb 

Теперь может просматривать в проводнике и ext разделы хотя ранее умел видеть только ntfs fat можно посмотреть теперь свои фаилы на томе где у вас линукс установлен

Расширение Secure Shell App надо ставить в паре с Crosh Window поможет нашей дальнеишей разработке

Alternative my hack run Crosh Window https://github.com/Griggorii/Chromium_OS_77/blob/master/Screenshot%202019-06-21%20at%2011.41.28.png

Run browser official terminal Secure Shell App 0.18 chrome-extension://pnhechapfaindjhompbnflcldabbghjo/html/nassh.html

Что бы терминал открыть в браузере ctrl+alt+t вне браузера читать ниже

Как открыть Crosh Window как у меня откройте сначала Secure Shell App подождите некоторое время там появится окно и после этого открываем Crosh Window технологию открыл пару дней назад. Ну я компилировал на своей системе и менял там настроек очень много видимо они были пренесены из различных конфигов которые я настраивал пару лет.

На счет встраивания линукса в хромиум заходим в Настройки там есть пункт Linux (beta) после этого как пишут тут  https://flatpak.org/setup/Chrome%20OS/ далее по этой технологии https://github.com/Griggorii/Chromium_OS_77/blob/master/Screenshot%202019-06-21%20at%2011.41.28.png 

https://www.it-world.ru/tech/admin/120048.html

Так быстрее разберемся и будем выпускать мою усовершенствованую ось через systemback или убунтоподобный установщик.

Так как мои успехи приватизировали всякие манжаро системы , мх линуксы то мы будем с вами создавать принципиально новую систему что бы откинуть паразитирование на моих успехах благодоря которым кто то получил нобелевку не упомянув что система разрабатывалась мною и вот этим человеком https://www.youtube.com/watch?v=1He9KYyYt6k на нас естественно спаразитировали начали выкатывать бочку типа смотрите и тут и полит пропаганда закрыла наши разработки итд.
В ходе холивара я сразу указал ещё человека , а то неторые умудряются не утираться своим величием и с помощью лаптей и матрешек доказывать своё превосходство и при этом правительство им тащит сотни нефти за их бред и булл шит.


__________________________________________________________________________________________________________________________________


Платформа

12279.0.2019_06_18_0028 (Test Build - griggorii) developer-build amd64-generic

Канал

Сейчас на канале "стабильная"

V8

7.7.27

User Agent
Mozilla/5.0 (X11; CrOS x86_64 12279.0.2019) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/77.0.3822.0 Safari/537.36
Командная строка

/opt/google/chrome/chrome --gpu-sandbox-failures-fatal=no --enable-logging --use-cras --use-gl=egl --user-data-dir=/home/chronos --enable-wayland-server --aura-legacy-power-button --login-profile=user --system-developer-mode --bwsi --homepage=chrome://newtab/ --incognito --log-level=1 --login-user=$guest --login-user=$guest --login-profile=0c7fc9db8cfe5c578ad76644d87b682b35bdb3d0 --flag-switches-begin --enable-devtools-experiments --enable-experimental-web-platform-features --enable-offer-store-unmasked-wallet-cards --enable-quic --enable-webgl2-compute-context --enable-webvr --force-color-profile=srgb --wallet-service-use-sandbox=1 --enable-features=ChromeColors --flag-switches-end --vmodule=*/chrome/browser/chromeos/account_manager/*=1,*/chromeos/components/account_manager/*=1,app_list_syncable_service=1,*/chromeos/power/auto_screen_brightness/*=1,*/forced_extensions/installation_tracker*=2,extension_downloader=2,existing_user_controller=2,*/ash/wm/tablet_mode/*=1,auto_enrollment_controller=1,*/ui/ozone/*=1,*/ui/display/manager/chromeos/*=1,update_engine=1,component_updater_service=1 --enable-features=ChromeColors --disable-sync --disable-extensions --ui-compositor-memory-limit-when-visible-mb=512

Дата сборки
вторник, 18 июня 2019 г.
