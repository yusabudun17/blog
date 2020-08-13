
# Blog Guide

## Commands to Install

Installed apps
```
git
visual studio code
nodejs
```

command line
```
npm install hexo-cli -g
hexo init yusabudun
cd yusabudun
npm install
```
To test the site
```
hexo server
```

## Editing the Site

- Blog posts and pages are in source folder
- For configuration edit _config.yml
- For theme configuration edit themes/hexo-casper/_config.yml

## Deploy
```
hexo clean
hexo generate
hexo deploy
```

## Ipucları

Blog deploy
```
# deploy için adımlar
# değişiklikleri yap, yeni post eklemek veya post silemk için source/_posts klasörünü editlemen gerekir
# deploy etmeden pcden denemek için "hexo server" çalıştır http://localhost:4000
# durdurmak için ctrl c
hexo clean
hexo generate
hexo deploy
#github'a gel add file de 
#file ismini CNAME koy file içeriğine yusabudun.com yaz
```

Blog git senkron
```
#git graphe gel src branchine değişikliklerini commitle
#
```
