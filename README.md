  <style>
   li {
    list-style-type: none; /* Убираем маркеры */
   }
  </style>
### Меню
<details>
    <summary>
        <b>Основные</b>
    </summary>
    <ul>
        <li>
            <details>
                <summary>
                    Дата/Время
                </summary>
                123
            </details>
        </li>
    </ul>
</details>




<details>
    <summary>
        <b>Настройки подключения к серверу</b>
    </summary>


    ##### [WisdomCloud] 

    ; 0 - Выключить подключение к серверу, 1 - включить
    `enable=1`
    ; 0 - использовать IP адрес, 1 - использовать домен
    `domainEnable=1`
    ; IP адрес сервера
    `ip=192.168.5.156`
    ; Домен
    `domain=online.sowa.pro`
    ; Порт подключения к серверу
    `port=6608`


    ```
        enable=1
        domainEnable=1
        ip=192.168.5.156
        domain=online.sowa.pro
    ```
</details>

<details>
    <summary>
        <b>Настройки Wi-Fi</b>
    </summary>

#### [Wifi]
; 0 - Выключить использование Wi-Fi, 1 - Включить
`enable=1`
; Имя беспроводной сети
`ESSID=sowa-wifi-1`
; Пароль от беспроводной сети
`passwd=123`
; Включить Wi-Fi подключение
`enable_node=1`
; 0 - статический IP адрес, 1 - динамический IP адресс
`type=1`
; IP адрес устройства
`ip=192.168.7.19`
; Маска подсети
`mask=255.255.255.0`
; Шлюз
`gateway=192.168.7.1`
; 0 - статический DNS, 1 - динамический DNS
`dns_type=1`
; Адрес DNS сервер
`dns=202.96.209.133`

#### [Wifi1]
```
ESSID=sowa-wifi-1
passwd=567
enable_node=1
type=1
ip=192.168.56.45
mask=255.255.255.0
gateway=192.168.56.1
dns_type=1
dns=8.8.8.8
```
#### [Wifi2]
#### [Wifi3]
#### [Wifi4]
#### [Wifi5]
</details>