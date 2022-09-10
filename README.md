# searxng-jtdocker


git clone 
cd /root/searxng-jtdocker
sed -i "s|ultrasecretkey|$(openssl rand -hex 32)|g" searxng/settings.yml
