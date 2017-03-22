# Master-Slave-Authoritative-Only-DNS-setup
Master-Slave Authoritative-Only DNS setup


## In progress...

This will be some kind of tool or a puppet manifest which will deploy EC2 machines on Amazon Web Services (AWS), probably in a common subnet (or may be I can provide that as an option; I can always later set them as environment variables to simply plug them), and use the NSD DNS server package/software to setup authoritative-only DNS servers in a master-slave setup. It might initially just support 2 machines to be used as dns servers, however, I intend to make it more flexible (I guess it might be one more environment variable!).

Some supporting files that I will actually use are already uploaded and can be refered with minimum changes.


### Updating my understanding...

Although it is a bare minimum setup (i.e., the currently shared files), it is decently solid. As I am currently adding to my knowledge in a sense that what is a secure method of creating this setup, there might be subtle changes over time, however, they will be infrequent.
