«Create Ubuntu 20.04 VM»
create vm from vagrant
Обновление ядра 
1. uname -r
5.4.0-164-generic 
2. выбор ядра с ресурса https://kernel.ubuntu.com/mainline/daily 
3. скачивание файлов через wget
https://kernel.ubuntu.com/mainline/daily/2023-10-13/amd64/linux-headers-6.6.0-060600rc5daily20231013-generic_6.6.0-060600rc5daily20231013.202310122203_amd64.deb

https://kernel.ubuntu.com/mainline/daily/2023-10-13/amd64/linux-headers-6.6.0-060600rc5daily20231013_6.6.0-060600rc5daily20231013.202310122203_all.deb

https://kernel.ubuntu.com/mainline/daily/2023-10-13/amd64/linux-image-unsigned-6.6.0-060600rc5daily20231013-generic_6.6.0-060600rc5daily20231013.202310122203_amd64.deb

https://kernel.ubuntu.com/mainline/daily/2023-10-13/amd64/linux-modules-6.6.0-060600rc5daily20231013-generic_6.6.0-060600rc5daily20231013.202310122203_amd64.deb

4. Обновление sudo dpkg -i *.deb 
5. Перезапуск sudo reboot 
6. uname -r
6.6.0-060600rc5daily20231013-generic
