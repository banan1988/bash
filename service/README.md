# bash -> scripts
File sample-service.sh consists of example and template of unix sample-service
Allowed calls:
- start
- stop
- restart
- status

You can test it like:
sudo ./sample-service.sh start

If you want make a real service from that script you need:
- move it to the /etc/inid.d
- add "executable" flag +x - chmod +x /etc/init.d/sample-service.sh
- send to service some call - e.g sudo service sample-service start
