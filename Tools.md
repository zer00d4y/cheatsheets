# Recon

## Passive: 

whois

nslookup

dig

[Whois Lookup](https://whois.domaintools.com)

[viewdns.info](https://viewdns.info)

[robtex](https://www.robtex.com)

[DNSdumpster](https://dnsdumpster.com)

[crt.sh](https://crt.sh)

[ICANN Lookup](https://lookup.icann.org)

[sitereport netcraft](https://sitereport.netcraft.com/?url=)

[Web Archive](https://web.archive.org)

[Shodan](https://www.shodan.io)

| **Purpose** | **Commandline Example** |
| --------------|-------------------|
| Lookup WHOIS record | `whois example.com` | 
| Lookup DNS A records | `nslookup -type=A example.com` | 
| Lookup DNS MX records at DNS server | `nslookup -type=MX example.com 1.1.1.1` | 
| Lookup DNS TXT records | `nslookup -type=TXT example.com` |
| Lookup DNS A records | `dig example.com A` | 
| Lookup DNS MX records at DNS server | `dig @1.1.1.1 example.com MX` | 
| Lookup DNS TXT records | `dig example.com TXT` | 

## Active: 

ping

traceroute

telnet

| **Command** | **Example** |
| --------------|-------------------|
| ping | `ping -c 10 MACHINE_IP` on Linux or macOS | 
| ping | `ping -n 10 MACHINE_IP` on MS Windows | 
| traceroute | `traceroute MACHINE_IP` on Linux or macOS | 
| tracert | `tracert MACHINE_IP` on MS Windows |
| telnet | `telnet MACHINE_IP PORT_NUMBER` | 
| netcat as client | `nc MACHINE_IP PORT_NUMBER` | 
| netcat as server | `nc -lvnp PORT_NUMBER` | 

| **Operating System** | **Developer Tools Shortcut** |
| --------------|-------------------|
| Linux or MS Windows | `Ctrl+Shift+I` | 
| macOS | `Option + Command + I` | 

# Web 

# Reverse 

IDA (Interactive DisAssembler) - комбайн из интерактивного дизассемблера, декомпилятора и отладчика. Используют чаще всего при реверсе. Есть Free-версия и Pro - платная. Free спокойно хватает для x64/x86.

Ghidra - комбайн из интерактивного дизассемблера, декомпилятора и отладчика. Бесплатная.

Radare2 - комбайн из интерактивного дизассемблера, отладчика. Open Source.

Binary Ninja - комбайн из интерактивного дизассемблера, декомпилятора и отладчика. Платный.

Hopper Disassembler - комбайн из интерактивного дизассемблера, декомпилятора и отладчика. Платный и Free-версия.

x64dbg - дизассемблер, идейное продолжение и развитие продолжение OllyDbg. Open Source.

Cutter - комбайн из интерактивного дизассемблера, декомпилятора и отладчика. Open Source.

WinDbg - отладчик, разработанный компанией Microsoft. В основном под Linux. Способен отлаживать ядро и обычные программы. Бесплатный.

QIRA - отладчик и дизассемблер с возможностью запоминания выполненных инструкций.

Отладчики и декомпиляторы для программ под платформу .NET

dnSpy - декомпилятор и дизассемблер и отладчик для платформы .NET. Open Source.

.NET Reflector - платный декомпилятор для .NET. Платный.

Декомпиляторы для программ на Java и под Android

ByteCode Viewer - инструмент для анализа байт-кода Java-приложений, используя различные декомпиляторы. Open Source.

jadx - декомпилятор DEX-файлов, JAR и APK-файлов в исходный код. Open Source.

JD-GUI - декомпилятор для Java. Open Source.

APKTool - инструмент для декомпиляции и компиляции Android-приложений. Open Source.

Декомпиляторы для программ на Python

PyInstaller Extractor - скрипт для извлечения содержимого EXE-файла, созданного PyInstaller. Open Source.

uncompyle6 - декомпилятор байт-кода Python (файлы PYC). Open Source.

decompyle3 - декомпилятор байт-кода Python (файлы PYC). Open Source.

pycdc - дизассемблер и декомпилятор байт-кода языка Python (файлы PYC). Open Source.

pdb - интерактивная среда отладки для программ на Python.

Декомпиляторы для программ под игровой движок Godot

Godot RE Tools - декомпилятор Godot. Open Source.

Вспомогательные инструменты при реверсе

Wireshark - комбайн для перехвата трафика. Open Source.

Angr - фреймворк для символьного выполнения и анализа программ. Open Source.

Frida - инструмент для динамического анализа и манипулирования с исполняемыми файлами, процессами и системами. Open Source.

Volatility Framework - фреймворк для анализа памяти компьютеров. Open Source.

Инструменты для анализа файлов

Detect It Easy - это инструмент для идентификации типа, формата и защиты разных файлов. Open Source.

Resource Hacker - это инструмент для анализа и модификации ресурсов в исполняемых файлах и библиотеках Windows. Бесплатный.

Process Explorer - продвинутый диспетчер задач. Бесплатный.

Process Hacker - продвинутый диспетчер задач. Бесплатный.

Process Monitor - это инструмент для мониторинга и анализа активности процессов в операционной системе Windows. Бесплатный.

Regshot - приложение для отслеживания изменений в реестре.

PE-bear - это инструмент для анализа исполняемых файлов формата PE. Open Source.

XELFViewer - инструмент для анализа исполняемых файлов формата ELF. Open Source.

XPEViewer - инструмент для анализа исполняемых файлов формата PE. Open Source.

XMachOViewer - инструмент для анализа исполняемых файлов формата MachO. Open Source.

XAPKDetector - Android/APK/DEX детектор и анализатор. Open Source.

HEX-редакторы

ImHex - продвинутый HEX-редактор. Open Source.

010 Editor - продвинутый платный HEX-редактор. Платный и бесплатный.

Обфускаторы .NET

de4dot - деобфускатор .NET. Open Source.

ПО для виртуализации, эмуляции, контейнеризации

VirtualBox - ПО для виртуализации операционных систем. Open Source/бесплатное.

VMware Workstation - ПО для виртуализации операционных систем. Платное.

QEMU - ПО для виртуализации и эмуляции аппаратного обеспечения. Open Source.

Docker - это платформа для контейнеризации приложений, в котором удобно запускать определённые инструменты. Open Source.

VirusTotal - сервис для проверки файлов на вредоносность через популярные антивирусы. Бесплатно.

Sandboxie/Sandboxie Plus - песочница для запуска приложений в изолированной среде.
