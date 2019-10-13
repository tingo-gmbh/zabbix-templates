# Template HW Panasonic PT-RZ660 by HTTP

## Applications
| Application |
| ------ |
| Input |
| Light |
| Power |
| Projector |
| Temperature |
| Zabbix raw items |

## Items
| Name | Key | Interval | History | Trends | Type | Applications |
| ------ | ------ | ------ | ------ |  ------ |  ------ |  ------ |
| Get: projector_status.cgi | ptrz660.http.projector_status | 1m | 1h | 0 | HTTP agent | Zabbix raw items |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |
| x | x | x | x | x | x | x |


## Macros
Adjust the Macros inside the Host (not Template) according to your setup of the Panasonic PT-RZ660. Username (`user1`) and Password (`panasonic`) are the default ones (check PT-RZ660 Manual, Page 157).

`{$SOURCE}` has no value, because we don't know what your source should be. Click on «Change» to enter your source.
**Attention** If you are not changing this Macro, there will be a warning, because there is an enabled Trigger. Also be careful, the Trigger is based on RegEx, so if you misspell your source, there will be a warning. Check the Interface of PT-RZ660 there you see how the source is written; normally everything UPPERCASE.

![template-hw-panasonic-pt-rz660-http-macros.jpg](https://raw.githubusercontent.com/tingo-gmbh/zabbix-templates/master/images/template-hw-panasonic-pt-rz660-http-macros.jpg?token=AKD4DCQEH53BAMZS7TCLLHK5VS37Y)
