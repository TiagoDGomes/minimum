# Minimum

O projeto Minimum tem como objetivo armazenar scripts simples e diretos ao ponto para obter uma determinada funcionalidade.

Cada pasta representa uma funcionalidade, e nela os scripts estão organizados em uma estrutura simples, onde cada arquivo tem um prefixo numérico de 000 a 100. 
O prefixo 000 corresponde ao script que contém a preparação, enquanto o 100 corresponde ao teste final. Os scripts com prefixos acima de 100 são complementares, mas podem ser úteis para a execução do sistema.

## Scripts disponíveis

- **Linux**: permite a criação de um Linux básico do zero, compilando o código-fonte e executando-o no emulador QEMU.
Utiliza também o [syslinux](https://repo.or.cz/syslinux.git) para o boot e o [busybox](https://git.busybox.net/busybox/) para os binários do sistema.
