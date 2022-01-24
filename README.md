## 1.
> Реализация паттернов IAAS не возможно без системы контроля версии.
> Применение паттернов приводит к уменьшению времени от поступления запроса на новую фичу до вывода ее в продакшн среду.
> Благодаря  CI просиходит уменьшение времени от начала написания кода до его тестирования благодаря автоматизации процессов.
> CD позволяет так же автоматичеси развернуть уже готовое приложение как в среде разработки и тестирования так и в рабочей среде.
> Благодаря тому что происходит достаточно частая регистрация новых изменении, отследить часть кода после внедрения которого начали проихсодит ошибки.

>Идемпотентность является наиболее выжным преимуществом  IaaS, так как один раз описав инфраструктуру в качестве кода можно быть уверененным что при повторонный запуск этого кода приведет к нужному результату.

## 2.
>Использваоние Ansible можно начать без особой подготовки инфраструктуры, быстрая раширяемость и исчерпаваяющая документация делает его унивесальным инструментом на всех стадиях разработки.

> Мне кажется что Push является более надежным, так как конфигурация будет отправлятся на конечный хост только после прохождения всех циклов тестировния, что скорей всего приведет к минимизации количества ошибок.

## 3.

```commandline
pugachevvv@debian-vlad:~$ vboxmanage --version
6.1.32r149290
pugachevvv@debian-vlad:~$ 
```

```commandline
pugachevvv@debian-vlad:~$ vagrant --version
Vagrant 2.2.14
pugachevvv@debian-vlad:~$ 

```
```commandline
pugachevvv@debian-vlad:~$ ansible --version
ansible [core 2.12.1]
  config file = None
  configured module search path = ['/home/pugachevvv/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/local/lib/python3.9/dist-packages/ansible
  ansible collection location = /home/pugachevvv/.ansible/collections:/usr/share/ansible/collections
  executable location = /usr/local/bin/ansible
  python version = 3.9.2 (default, Feb 28 2021, 17:03:44) [GCC 10.2.1 20210110]
  jinja version = 3.0.3
  libyaml = True
pugachevvv@debian-vlad:~$ 
```

## 4.

```commandline
vagrant@server1:~$ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
vagrant@server1:~$ 

```