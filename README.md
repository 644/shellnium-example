# shellnium-example
[Shellnium](https://github.com/Rasukarusan/shellnium) is the selenium webdriver for bash. This is an example of how you'd archive a webpage in .png format.

I plan to fork shellnium at some point, refactor the code, add more features (namely cookie support), and provide more robust examples like this one. The original author of shellnium did a great job, however it wasn't as intuitive to use as python's selenium.

# Usage
```bash
wget https://raw.githubusercontent.com/644/shellnium-example/main/archivepage
chmod u+x archivepage
./archivepage https://example.com https://example2.com
```

You will need chromedriver and chromium installed, along with shellnium, which can be found here: https://github.com/Rasukarusan/shellnium

# License
MIT
