
## import 
 in `~/.lldbinit`
```
command script import /<PATH>/cclet.py
command script import /<PATH>/preturn.py
command script import /<PATH>/enum_open.py
```


# USAGE
## cclet.py
in lldb console
```
(lldb) <instanceName>.<targetLetMember> = "hogehoge"
```

## enum.py
 * Enumの付属値を取得する。
 タプルのように付属値の番号を指定する必要がある。
in lldb console
```
(lldb) enum_open <enum With AttValue>.0
```

## preturn.py
* メソッドの返り値を操作する。
<img width="1173" alt="screen shot 2018-09-02 at 9 53 18" src="https://user-images.githubusercontent.com/14083051/44951112-28f0d780-ae96-11e8-860d-0f0b844785e2.png">


