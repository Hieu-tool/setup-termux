<h1 style="text-align: center;">Lệnh Setup Termux</h1>

<h3 style="text-align: right;">by Hiếu tool</h3>

`lệnh setup`

[Link Download](https://apkcombo.com/vi/termux/com.termux/){target="_blank"}

> Cấp quyền bộ nhớ
```php
termux-setup-storage
```
> Update và cài python & php
```php
pkg update -y && pkg upgrade -y && pkg install php -y && pkg install python -y && pip install requests && pip install bs4 && pip install colorama && pip install pystyle && pip install pycurl && pip install beautifulsoup4 && pip install inquirer && pip install pillow && pip install console && pkg install git -y
```

# Setup Theme Termux

![Theme Termux](https://blogger.googleusercontent.com/img/a/AVvXsEhsHWEwJ--I1yMYSG2ZXHfBH8brn55c5EshOOxSBDzfwcShl5o3q861MQw-1kdXZGwSrsgbFTTPOQBw56eX87a9zvZdQ9mkXN1MJXrGtS9pQa3xBdWDNWBWLYkFN8x-IemY7n01_kSGuiWvN_PWWkiPXCzC7uqBkn6yA5C1rqQMHy-_Kfi7enSUiGuSA5IV=w556-h445)

```php
git clone https://github.com/Hieu-tool/theme-termux.git
```

```php
cd theme-termux
```

```php
bash setup.sh
```