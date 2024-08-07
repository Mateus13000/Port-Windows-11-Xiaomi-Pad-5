<img align="right" src="https://raw.githubusercontent.com/erdilS/Port-Windows-11-Xiaomi-Pad-5/main/nabu.png" width="425" alt="Windows 11 Running On A Xiaomi Pad 5">

# Запуск Windows на Xiaomi Pad 5

## Настройка двойной загрузки между Windows и Android

### Требования 
- ```Мозг```
- ```Рутированный планшет```
- ```Уже установленная Windows на планшете```
- [```Образ UEFI```](https://github.com/erdilS/Port-Windows-11-Xiaomi-Pad-5/releases/download/UEFI/uefi-v3.img)
- [```Приложение WoA Helper```](https://github.com/Marius586/WoA-Helper-update/releases/tag/WOA)

## Настройка приложения dualboot
> В этом руководстве предполагается, что у вас есть root, если это не так, пожалуйста, используйте [root guide](2-rootguide-en.md ) чтобы получить рут 

### Установка - Android
- Скачайте и установите приложение **WOA Helper**, затем откройте его и предоставьте ему root-доступ.
- Скачайте **образ UEFI** и поместите его в папку с именем `UEFI` в вашем внутреннем хранилище.
- Откройте приложение WOA Helper и используйте **`STA CREATOR`** в **`WOA TOOLBOX`**.
> [!Important]
> Если папка `/sdcard/Windows` пуста, ваша прошивка не поддерживает монтирование, и вам придётся создать резервную копию boot.img внутри приложения, а затем  вручную скопировать её в Windows после загрузки в неё (например, загрузив её куда-нибудь, а затем скачав при загрузке в Windows). То же самое относится и к файлам StA, которые также создаются в вашем внутреннем хранилище.
>
> Сделайте то же самое, если папка доступна только для чтения.
- Нажмите кнопку **`БЫСТРАЯ ЗАГРУЗКА В WINDOWS`**.

### Установка - Windows
> [!Tip]
> If this is your first time booting Windows and you wish to skip the Microsoft Account login, press the **I don't have internet** button in the WiFi page, then when prompted, press the **Continue with limited setup** button.
- Перейдите к `C:\sta` и создайте ярлык **sta.exe** на вашем рабочем столе, если таковой не существует 

#### Загрузка в Android
- Запустите новый ярлык на своем рабочем столе (вы также можете прикрепить его к своему меню "Пуск" / панели задач для удобства доступа).

#### Загрузка в Windows
- Нажмите **`БЫСТРАЯ ЗАГРУЗКА В WINDOWS`** в приложении или используйте недавно созданный переключатель на панели быстрых настроек
  
## Готово!


> [!TIP]
> Не забудьте заглянуть на страницу [**```Полезные приложения и инструкции```**](Additional-materials-ru.md). Там вы найдёте руководство по активации Windows и другую полезную информацию.
