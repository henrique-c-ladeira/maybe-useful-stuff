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
https://sizze.io/

storybook
ant-design react
```

## react native
```
keytool -genkey -v -keystore my-release-key.keystore -alias my-key-alias -keyalg RSA -keysize 2048 -validity 10000
```
icons
https://oblador.github.io/react-native-vector-icons/

Workaround go up android

```
rm android/app/src/main/assets/index.android.bundle

react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res

---> Apagar drawble pasta Res
```

Mac M1 fix
```
post_install do |installer|
    installer.pods_project.targets.each do |target|
      target.build_configurations.each do |config|
        config.build_settings["ONLY_ACTIVE_ARCH"] = "NO"
      end
    end
  end
  
---> excluded archtecture: arm64
```
## reset css
```
https://meyerweb.com/eric/tools/css/reset/
```
