Политика конфиденциальности OCOS / OCOS Privacy Policy
Русская версия
Дата вступления в силу: 05.10.2026

Разработчик: Mishchenko Sergei, контакт: msi.mail@yandex.ru

Кратко
OCOS — VPN-клиент для серверов ocserv (протокол OpenConnect / AnyConnect) для iPhone. Приложение не собирает данные пользователя, не отправляет их разработчику и не передаёт третьим лицам. Весь трафик при включённом VPN направляется только на сервер, который указал сам пользователь.

Какие данные обрабатываются
Профили подключения — название, адрес сервера, имя пользователя, группа авторизации и настройки (в том числе режимы «Только TCP» и «Подключаться автоматически»). Хранятся на устройстве в данных приложения. Эти данные могут входить в резервные копии устройства по общим правилам iOS.

Пароль — хранится на устройстве в системной связке ключей iOS (Keychain), а не в файлах профилей. Пароль не покидает устройство, кроме отправки на VPN-сервер пользователя при входе.

Учётные данные при подключении передаются только на VPN-сервер, который указал пользователь, по защищённому соединению (TLS). Разработчик не имеет доступа к этому серверу и к этим данным.

Сведения о клиенте. В рамках протокола AnyConnect VPN-серверу передаются стандартные сведения о клиенте: платформа (iOS), версия клиента и обобщённые сведения об устройстве. Это нужно для работы протокола и адресуется только серверу пользователя.

Сетевой трафик при включённом VPN шифруется и направляется на сервер пользователя. Приложение не анализирует, не записывает и не изменяет содержимое трафика. Параметры туннеля (адрес, DNS, MTU, объём трафика, причина последней ошибки) показываются в приложении и не покидают устройство.

Системные журналы. Служебные сообщения работы VPN-расширения записываются в системный журнал iOS на устройстве и не отправляются разработчику.

Чего приложение не делает
не содержит аналитики, рекламы и систем сбора отчётов о сбоях;
не отправляет данные разработчику и третьим лицам;
не отслеживает пользователя и не использует идентификаторы для рекламы;
не использует трафик для рекламы или монетизации;
не запрашивает доступ к контактам, геопозиции, камере, микрофону и фото.
Компоненты с открытым исходным кодом
Приложение использует OpenConnect (LGPL 2.1), OpenSSL (Apache 2.0) и KCP (MIT). Версии, ссылки на исходный код и полные тексты лицензий доступны в приложении: «Настройки → Правовая информация и лицензии».

Безопасность
Параметр «Разрешить невалидный сертификат» отключает проверку сертификата сервера и снижает защиту соединения. Включайте его только для собственного сервера, если понимаете риск.

Удаление данных
Профиль и пароль можно удалить в самом приложении («Конфигурации» → профиль → «Удалить конфигурацию»). Все данные также удаляются при удалении приложения с устройства.

Дети
Приложение не предназначено для детей младше 13 лет и не собирает их данные.

Изменения
Изменения публикуются на этой странице с новой датой вступления в силу.

Контакты
msi.mail@yandex.ru

English version
Effective date: October 5, 2026

Developer: Mishchenko Sergei, contact: msi.mail@yandex.ru

Summary
OCOS is a VPN client for iPhone that connects to ocserv servers (OpenConnect / AnyConnect protocol). The app does not collect user data, does not send it to the developer, and does not share it with third parties. While the VPN is on, traffic goes only to the server the user specified.

Data the app handles
Connection profiles — name, server address, user name, authentication group and settings (including "TCP only" and "Connect automatically"). They are stored on the device in the app's data and may be included in device backups under standard iOS rules.

Password — stored on the device in the iOS Keychain, not in profile files. The password leaves the device only when it is sent to the user's own VPN server during sign-in.

Sign-in credentials are sent only to the VPN server the user specified, over a secure connection (TLS). The developer has no access to that server or to these credentials.

Client information. As part of the AnyConnect protocol, the VPN server receives standard client details: platform (iOS), client version and generic device information. This is required by the protocol and goes only to the user's own server.

Network traffic is encrypted while the VPN is on and sent to the user's server. The app does not inspect, record or modify the content of the traffic. Tunnel parameters (address, DNS, MTU, traffic counters, last error reason) are shown in the app and never leave the device.

System logs. Diagnostic messages from the VPN extension are written to the device's system log and are not sent to the developer.

What the app does not do
contains no analytics, advertising or crash-reporting services;
does not send data to the developer or to third parties;
does not track the user or use advertising identifiers;
does not use traffic for advertising or monetization;
does not request access to contacts, location, camera, microphone or photos.
Open-source components
The app uses OpenConnect (LGPL 2.1), OpenSSL (Apache 2.0) and KCP (MIT). Versions, source links and full license texts are available in the app: Settings → Legal and licenses.

Security
"Allow invalid certificate" turns off server certificate verification and weakens the connection's protection. Enable it only for your own server and only if you understand the risk.

Deleting data
A profile and its password can be deleted in the app (Configurations → profile → Delete configuration). All data is also removed when the app is deleted from the device.

Children
The app is not directed to children under 13 and does not collect their data.

Changes
Changes are published on this page with a new effective date.

Contact
msi.mail@yandex.ru
