# searxng-jt


```bash
git clone https://github.com/Axaxin/searxng-jt.git
cd /root/searxng-jtdocker
sed -i "s|ultrasecretkey|$(openssl rand -hex 32)|g" searxng/settings.yml
docker network create searxng.io
```
