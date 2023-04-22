# TheHarvester

**TheHarvester** - это инструмент для сбора информации о целевой организации или домене. Он может использоваться для поиска электронных адресов, доменных имен, поддоменов, IP-адресов, имен пользователей и другой информации, которая может быть полезна для проведения атаки на целевую организацию.

```
theharvester -d <domain> -l <limit> -b <source>
```

- `-d <domain>`: указывает домен, для которого нужно собрать информацию.
- `-l <limit>`: указывает количество результатов, которые нужно получить.
- `-b <source>`: указывает источник, из которого нужно получить информацию.

Дополнительные параметры:

```
-theharvester -h
```

- `-h`: выводит справочную информацию о командах и параметрах.

```
theharvester -d <domain> -l <limit> -b <source> -f <filename>
```

- `-f <filename>`: указывает имя файла, в который нужно сохранить результаты.

```
theharvester -d <domain> -l <limit> -b <source> -e <format>
```

- `-e <format>`: указывает формат, в котором нужно сохранить результаты (html, xml, csv, txt).

```
theharvester -d <domain> -l <limit> -b <source> -c
```

- `-c`: указывает, что нужно использовать поиск по кэшу Google.

```
theharvester -d <domain> -l <limit> -b <source> -v
```

- `-v`: выводит подробную информацию о процессе сбора данных.

```
theharvester -d <domain> -l <limit> -b <source> --shodan <api_key>
```

- `--shodan <api_key>`: указывает API-ключ для использования Shodan в качестве источника.

```
theharvester -d <domain> -l <limit> -b <source> --hunter <api_key>
```

- `--hunter <api_key>`: указывает API-ключ для использования Hunter в качестве источника.

```
theharvester -d <domain> -l <limit> -b <source> --virustotal <api_key>
```

- `--virustotal <api_key>`: указывает API-ключ для использования VirusTotal в качестве источника.

```
theharvester -d <domain> -l <limit> -b <source> --all
```

- `--all`: указывает, что нужно использовать все доступные источники.