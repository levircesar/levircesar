### Hello , my name is Levir César

# **Im student of Computer Engineering**

<a href="https://www.levirlemos.online">Site Portifólio</a>

```javascript
  async user.index({
    name:     'Levir César',
    age:       22, 
    city:     'Fortaleza',
    homepage: 'https://levirlemos.online',
    stack:    ['HTML','CSS','Javascript','NodeJS','ReactJS','C','C++'],
    hobby:    ['tocar instrumentos','animes','series']
  });

  return response.status(201).json(user);
```

# Details

<p align="justify">
  <a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=levircesar&show_icons=true&count_private=true&theme=dracula&hide=issues" />
  </a>
    <a href="https://github.com/anuraghazra/github-readme-stats">
    <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=levircesar&layout=compact&theme=dracula" />
  </a>
</p>

#Dica para copiar um repositório
```bash
npx degit <url do repositorio> [Nome_do_projeto]
```


### gecko driver
Para ignorar certificados de proteção no Selenium WebDriver Para o Firefox
```
ProfilesIni profileIni = new ProfilesIni();
FirefoxProfile profile = profileIni.getProfile("default");
FirefoxOptions options = new FirefoxOptions();
options.setProfile(profile);
DesiredCapabilities cap = new DesiredCapabilities();
cap.setAcceptInsecureCerts(true);
options.addCapabilities(cap);
WebDriver driver = new FirefoxDriver(options);
```
