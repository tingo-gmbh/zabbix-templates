# Template HW Panasonic PT-RZ660 by HTTP

## Item
There is one «master item» (Zabbix raw items) which does the collecting of the data over an «HTTP agent» Item-Type. It will just go take the Raw-Data of `http://{HOST.CONN}/cgi-bin/projector_status.cgi?lang=e`, because the PT-RZ660 has no other Info-Interface (like XML, JSON or something; except sending Mails).

## Macros
Adjust the Macros inside the Template according to your setup of the Panasonic PT-RZ660. Username (`user1`) and Password (`panasonic`) are the default ones (check PT-RZ660 Manual, Page 157).

`{$SOURCE}` has no value, because we don't know what your source should be. Click on «Change» to enter your source.
**Attention** If you are not changing this Macro, there will be a warning, because there is an enabled Trigger. Also be careful, the Trigger is based on RegEx, so if you misspell the your source, there will be a warning. Check the Interface of PT-RZ660 there you see how the source is written; normally everything UPPERCASE.

![template-hw-panasonic-pt-rz660-http-macros.jpg](https://raw.githubusercontent.com/tingo-gmbh/zabbix-templates/master/images/template-hw-panasonic-pt-rz660-http-macros.jpg?token=AKD4DCQEH53BAMZS7TCLLHK5VS37Y)
