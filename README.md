# 5G-Network-Slicing

##ABSTRACT
Due to developing markets, there has been a large growth in users or subscribers, as well as
a wide array of use cases in recent years. To satisfy the growing demand, the operable spectrum
for base stations should be extended to accommodate more users with high data rates. The
development of the 5G network is more difficult since it must cater to multiple needs at the
same time while employing a common infrastructure. The attenuation of the signal rises when
the frequency is increased. After a specific threshold, the signal’s power cannot be increased. As
a result, the frequency range used and signal attenuation must be balanced. Milimeter Waves,
Small-cell, Massive MIMO, and Beamforming are some of the technologies needed to efficiently
offer 5G networks. The key foundation for 5G implementation is network slicing, which allows
for diverse and possibly opposing quality of service or QoS requirements. Each slice has an
SLA(Service level agreement) defined which allows monitoring of whether the required SLA is
met.
Network slicing is an end-to-end approach that uses similar infrastructure to cover all current
network blocks while creating numerous logical networks with varied QoS requirements. The
principal network that formed the initial connection between the user and the base station is
RAN slicing, which is the section between the client and the base station. We will investigate
and simulate the various 5G use cases in this article, including eMBB for high data rate, uRLLC
for low latency, and mMTC for more subscribers. To simulate the different parameters of the
RAN Slicing, we used Slicesim, an open-source software.
