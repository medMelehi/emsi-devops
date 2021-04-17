this is web server project
sudo awk '{if (match(,var)) gsub(/[0-9]+/,80); print bash;}' var=listen /etc/nginx/sites-enabled/default > tmp && sudo mv tmp /etc/nginx/sites-enabled/default

