# Macbook_a1706_T1-chip_Desable
Hide a stuck Apple T1 in DFU/Recovery from macOS using an OpenCore USB map. 

This repository was created primarily to preserve a completed project. It would be great if others find it useful. It was built using OpenCore and a fair amount of my own patience!

If the T1 chip on your laptop isn't working, you can still boot the system using OpenCore; however, the chip will remain visible to the OS—often appearing in Recovery or DFU mode—which can interfere when working with an iPhone. This patch was created to hide the T1 chip from the system. It adds a map of disabled USB ports to OpenCore, effectively making the T1 chip invisible to the OS.

For technical details, please refer to the README file in Zip archive.

T1_DFU-to-Recovery - аpplication for switching the chip from DFU to Recovery mode from within the system itself. Upon reboot, it reverts to DFU mode.

RU:
Этот репозиторий создан, скорее, с целью сохранить свой готовый проект. Если он кому-то пригодиться, будет здорово. Создан с помощью Кодекс и моего терпения).

Если на вашем ноутбуке не работает чип Т1, вы можете загрузить систему через OpenCore, но чип продолжит висеть в системе в Recovery или DFU, мешая прошивке и джейлу ваших устройств. Чтобы скрыть этот чип из системы и был создан этот патч. Он добавляет карту отключенных USB-линий в OpenCore и система перестает видеть чип Т1.

Технические подробности читайте в файле README в архиве.

T1_DFU-to-Recovery - приложение для перевода чипа из DFU в Recovery в самой системе. После перезагрузки DFU возвращается. 
