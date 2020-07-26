# recurso-pacemaker
Script sencillo para usar recurso lsb en pacemaker

Agregar con:

pcs resource create RECURSO_LSB lsb:reccluster op monitor interval=3s op start timeout=120s  op stop timeout=120s
