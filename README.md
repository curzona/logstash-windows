logstash-windows
================

Playground for learning logstash on Windows

Download
--------

Logstash 1.3.3

    cd logstash-1.3.3
    wget https://download.elasticsearch.org/logstash/logstash/logstash-1.3.3-flatjar.jar

Logstash 1.4.0
    
    cd logstash-1.4.0
    wget https://download.elasticsearch.org/logstash/logstash/logstash-1.4.0.tar.gz
    
NXLog 2.7.1191

    cd nxlog-2.7.1191
    wget http://downloads.sourceforge.net/project/nxlog-ce/nxlog-ce-2.7.1191.msi
    msiexec /i nxlog-ce-2.7.1191.msi /quiet

Problems
--------
- nxlog stop sending logs after restarting the system
- nxlog misses many logs from the Windows event log
- logstash dumps a stack trace after resuming from sleep with tcp/udp output
- logstash 1.4.0 dumps a stack trace with an eventlog input


