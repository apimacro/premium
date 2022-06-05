## premium.pl

scenarios for botreck: got premium.pl , login,get history, get domains, ..

### Add to file: apifork.txt

https://github.com/botreck/premium premium

```bash
echo "https://github.com/botreck/premium premium" >> apifork.txt
```

and install in project

```bash
./apifork install
```

start using

```bash
./apidsl 'puppeteer.csv("premium.pl/login_user_screenshot.csv")'
```