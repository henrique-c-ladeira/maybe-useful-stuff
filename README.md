# maybe-useful-stuff

## git config --global --edit

```
[core]
	editor = code --wait
[user]
	name = Henrique Curzio Ladeira
	email = henrique.c.ladeira@gmail.com
[alias]
	s = !git status -s
	c = !git add --all && git commit -m
	l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'	
```

## generate openssl
```
openssl genrsa -out private.pem 2048
openssl rsa -in private.pem -pubout > public.pem
```

## misc (check later)
```
rive.app

react libs:
	polished
	framermotion

sites:
https://undraw.co/illustrations
```

## react native
```
keytool -genkey -v -keystore my-release-key.keystore -alias my-key-alias -keyalg RSA -keysize 2048 -validity 10000
```

## reset css
```
https://meyerweb.com/eric/tools/css/reset/
```
