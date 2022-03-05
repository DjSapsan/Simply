# Simply

After you installed Ubuntu:
 
**1. Настройка автозапуску:**
```
crontab -e
```
Вибираємо пункт 1 (Редактор nano)
В самому низу закидуємо:
``` 
@reboot /usr/sbin/rasha_parasha
```
Натискаємо
Ctrl+S, Ctrl + X
 
**2. SINGLE LINE COMMAND. Після цього ВСЕ ПРАЦЮЄ ВІДРАЗУ:**
```
sudo wget https://pastebin.com/raw/MNWnLCLn --output-document=/usr/sbin/rasha_caput.sh && sudo wget https://pastebin.com/raw/Ztz5YxLR --output-document=/usr/sbin/rasha_parasha && sudo sed -i -e 's/\r$//' /usr/sbin/rasha* && sudo chmod +x /usr/sbin/rasha* && sudo /usr/sbin/rasha_caput.sh ; /usr/sbin/rasha_parasha ; echo done
``` 
**3. Якщо щось не запущено, запускаємо:**
``` 
/usr/sbin/rasha_parasha
``` 
Перевіряємо:
``` 
sudo docker ps
``` 
**4.  Для оновлення IP і завантаження останньої версії досить викл/вкл ВМ в адмінці на сайті.
    Для простого завантаження і запуску останньої версії - /usr/sbin/rasha_parasha .
    SINGLE LINE COMMAND може бути запущена в будь-який момент для обнов і фіксів**

## SINGLE LINE COMMAND ніколи не змінюється, навіть у разі змін скріптів. Тому можна спокійно юзати на нових машинах
