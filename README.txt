#TaskA:
#Find the average number of bytes for lines of each response code.

#TaskB:
#Count the number of log entries that happen between two given timestamps.

#to perform these task, AsterixDB should be running on the system.
#The permissions for file AsterixDB.sh should be changed to 755 as follows:

chmod 755 AsterixDB.sh

#enter the following command to execute the file:
./AsterixDB.sh 127.0.0.1:///<file-location> <timestamp1> <timestamp2>

#for eg:
./AsterixDB.sh 127.0.0.1:///home/hdp/Desktop/CS226/Assignment3/nasa.tsv 804571212 804571400

