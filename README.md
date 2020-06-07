# installation et lancement

```
Compilation BCM4_CPS -> bcm.jar
cd BCM4_CPS/
ant dist

Installatin
cp BCM4_CPS/bcm.jar mourad-alpha/lib
cd mourad-alpha/
ant dist

Exemple de lancement 3 brokers
./start-cyclicbarrier-performance-3-broker& 
./start-gregistry-performance-3-broker& 
./start-performance-3-broker-all

```
