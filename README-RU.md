Набор скриптов и модификаций Debian Linux для загрузки по pxe и запуска в киоск-режиме

1. ladoshka-initramfs - изменения для initrd
   добавленна поддержка зхагрузки образа по tftp и распаковка в tmpfs и синхроназация рут раздела rsync'ом 
   примеры для загрузки по tftp ladoshka-initramfs/tftp.pxelinux.cfg.example и rsync ladoshka-initramfs/rsync.pxelinux.cfg.example

2. ladoshka-etc - небольшие изменения для /etc для монтирования раздела в RO, монтирует все необходимые для записи каталоги в tmpfs 
