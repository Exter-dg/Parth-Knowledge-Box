
> [!tip] Used to list files in the directory

## LS Options

| Options | Usage                                            |
| ------- | ------------------------------------------------ |
| -l      | Listing file and directory permissions           |
| -h      | Listing file sizes in easy format (KB, MB, GB)   |
| -a      | View Hidden files                                |
| -R      | List files recursively                           |
| -F      | Folder names will appear with a ==/== at the end |
| --color | Display using colors to easily distinguish       |


## File permissions

Refer [this](https://www.redhat.com/sysadmin/linux-file-permissions-explained)

```
rw-r--r--
```
- Owner: rw = 4+2+0 = 6
- Group: r-- = 4+0+0 = 4
- Others: r-- = 4+0+0 = 4

Can be modified using [[chmod]]
