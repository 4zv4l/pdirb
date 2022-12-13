# pdirb
minimalist url brute force script in Perl

# usage
```
➜ ./pdirb.plx -u http://localhost:8000 -w ./wordlist.txt

     ▄▄▄▄▄▄▄ ▄▄▄▄▄▄  ▄▄▄ ▄▄▄▄▄▄   ▄▄▄▄▄▄▄ 
    █       █      ██   █   ▄  █ █  ▄    █
    █    ▄  █  ▄    █   █  █ █ █ █ █▄█   █
    █   █▄█ █ █ █   █   █   █▄▄█▄█       █
    █    ▄▄▄█ █▄█   █   █    ▄▄  █  ▄   █ 
    █   █   █       █   █   █  █ █ █▄█   █
    █▄▄▄█   █▄▄▄▄▄▄██▄▄▄█▄▄▄█  █▄█▄▄▄▄▄▄▄█

[$] website url  : http://localhost:8000
[$] wordlist path: ./wordlist.txt

[x] http://localhost:8000/admin/
[x] http://localhost:8000/php_settings/
[✔] http://localhost:8000/error/
[✔] http://localhost:8000/pdirb/
[x] http://localhost:8000/index.html
```
or
```
➜ ./pdirb.plx                                           

     ▄▄▄▄▄▄▄ ▄▄▄▄▄▄  ▄▄▄ ▄▄▄▄▄▄   ▄▄▄▄▄▄▄ 
    █       █      ██   █   ▄  █ █  ▄    █
    █    ▄  █  ▄    █   █  █ █ █ █ █▄█   █
    █   █▄█ █ █ █   █   █   █▄▄█▄█       █
    █    ▄▄▄█ █▄█   █   █    ▄▄  █  ▄   █ 
    █   █   █       █   █   █  █ █ █▄█   █
    █▄▄▄█   █▄▄▄▄▄▄██▄▄▄█▄▄▄█  █▄█▄▄▄▄▄▄▄█

[$] website url  : http://localhost:8000
[$] wordlist path: ./wordlist.txt

[x] http://localhost:8000/admin/
[x] http://localhost:8000/php_settings/
[✔] http://localhost:8000/error/
[✔] http://localhost:8000/pdirb/
[x] http://localhost:8000/index.html
```
