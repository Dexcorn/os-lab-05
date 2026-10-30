# Задание 1. Создание диска, разметка, файловые системы 

вывод lsblk /dev/loop0 после разметки
<img width="1059" height="769" alt="изображение" src="https://github.com/user-attachments/assets/2d340763-01b8-4887-95fc-45437bc94dc7" />

вывод blkid: UUID и тип каждого раздела

<img width="1089" height="743" alt="изображение" src="https://github.com/user-attachments/assets/47611c5b-2971-417e-b831-63aa15f22ae0" />

вывод df -hT

<img width="847" height="235" alt="изображение" src="https://github.com/user-attachments/assets/156ee83f-bdb9-4358-bac3-5cc1f147c8cb" />

## ответьте: почему ext4-раздел сразу занят на несколько процентов, хотя вы ничего не записали?

Раздел сразу занят, потому что система при форматирование создает служебные структуры, журнал, каталог lost+found 
