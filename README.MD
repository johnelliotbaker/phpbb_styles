Installation Instructions
---

```
cd /var/www/forum
rm -rf styles
mkdir styles
cd styles
git clone https://github.com/johnelliotbaker/phpbb_styles.git .
sudo chown -R www-data:www-data /var/www/forum
sudo chmod -R g+rwX /var/www/forum
```
