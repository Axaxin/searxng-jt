# searxng-jtdocker

启动之前，生成密钥：

cd /root/searxng-jtdocker

sed -i "s|ultrasecretkey|$(openssl rand -hex 32)|g" searxng/settings.yml
