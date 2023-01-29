# networking/VirtualBox 📦

![Screenshot_12](https://user-images.githubusercontent.com/48568917/215354802-43d6be53-4b87-4281-bdc2-bf6bd32218bc.jpg)


Practical task on networking and its implementation.
There is a host Server_1, that is, a computer running VirtualBox.
There is Client_1, that is, a virtual image of OS Linux.
There is Client_2, that is, a virtual image of CentOS.
Network addresses are as follows:
net2 - 10.94.12.0
net3 - 10.7.94.0

![networking](https://user-images.githubusercontent.com/48568917/215354842-32aa287c-3961-4f84-8a55-ba46359ca020.jpg)

<p align="center">illustration created by me for better understanding</p>

![img0](https://user-images.githubusercontent.com/48568917/215356175-6bb00d16-592d-4eb3-9aac-f294e274ae2f.JPG)

You can copy a file from this repository to view the main commands.

![img1](https://user-images.githubusercontent.com/48568917/215356283-ef4a8d3c-b683-4308-aa9d-0a1ae178e799.JPG)

I create virtual images for further adjustments.

I will use the ifconfig command to monitor network settings. 
With its help, you can also enable and disable network interfaces, configure their parameters, switch modes and much more.

![img3](https://user-images.githubusercontent.com/48568917/215356439-6ff30fa5-600f-473f-9982-287a7d87124e.JPG)

![img4](https://user-images.githubusercontent.com/48568917/215356446-b8793430-c909-4ad6-b2f4-12c0f03772b6.JPG)

![img5](https://user-images.githubusercontent.com/48568917/215356455-304d7449-3cc4-4f57-96da-4055aa6d6124.JPG)

Before starting the settings, you need to configure all environments, install commands for using ping, traceroute.

I turn off the virtual machines to perform the settings in the Network tab.

![img6](https://user-images.githubusercontent.com/48568917/215356837-f32a3e10-06b3-446f-bd35-214038e54907.JPG)

![img7](https://user-images.githubusercontent.com/48568917/215356839-e358f290-0e18-48cc-8f4e-57be5bb2fefc.JPG)

![img8](https://user-images.githubusercontent.com/48568917/215356845-67e38455-30f8-47ef-9d4a-d6fbc03517be.JPG)

Rechecking ifconfig.

![img9](https://user-images.githubusercontent.com/48568917/215356887-231963c9-595c-43a7-b554-f180e774fc61.JPG)

![img10](https://user-images.githubusercontent.com/48568917/215356898-d027cea4-315b-453f-bfba-e2bf8e4d1de7.JPG)

![img11](https://user-images.githubusercontent.com/48568917/215356907-9eb94d97-e329-4543-8feb-1585b73a03d8.JPG)

I edit the .yaml file using netplan, manage the network.

![img12](https://user-images.githubusercontent.com/48568917/215357122-a0142b65-4e02-40dd-a0e0-10f62b6d77a7.JPG)

Next, I edit the dhcp server.

![img13](https://user-images.githubusercontent.com/48568917/215357239-a663604f-6e42-45f6-ba7d-22b4b819b693.JPG)

![img14](https://user-images.githubusercontent.com/48568917/215357279-a086460c-09ec-43de-a67f-da6c4e7af2f1.JPG)

![img21](https://user-images.githubusercontent.com/48568917/215357762-a591eaa1-e61b-4169-b4f7-86b1ecb7d1eb.JPG)

I use ping and traceroute to checking connectivity.

![img22](https://user-images.githubusercontent.com/48568917/215357818-d24e8b8f-7686-4e84-a1f4-4e1a2276d8bf.JPG)

![img15](https://user-images.githubusercontent.com/48568917/215357578-512dad81-e673-4385-83f7-6abc5d415577.JPG)

![img16](https://user-images.githubusercontent.com/48568917/215357587-fc160a02-3f39-49d8-8297-896404b8819a.JPG)

![img17](https://user-images.githubusercontent.com/48568917/215357594-d4d17e0d-bc97-494b-99f8-b9c10655de7d.JPG)

Editing another .yaml file this time for lo and the Client_1.

![img18](https://user-images.githubusercontent.com/48568917/215357649-7e6469ce-729a-4298-9f74-22fdb69de625.JPG)

![img19](https://user-images.githubusercontent.com/48568917/215357706-2c0de09a-a1b1-4393-aa21-27e52d158100.JPG)

![img20](https://user-images.githubusercontent.com/48568917/215357727-dd970ef9-a5d0-4ba8-99d4-a6faf7c70c48.JPG)

![img23](https://user-images.githubusercontent.com/48568917/215357847-7ded6e34-97f8-4518-891d-010f33085d41.JPG)

Settings for ssh service.

![img24](https://user-images.githubusercontent.com/48568917/215357864-3aed0779-92cd-4dda-9747-3c0a9d80f187.JPG)

![img25](https://user-images.githubusercontent.com/48568917/215357871-41207fa8-1f36-43e1-97a6-6862cd3d668e.JPG)

