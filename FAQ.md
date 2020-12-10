# Rocky Linux FAQ

## General

### What is Rocky Linux ?

Rocky Linux is a free and open source operating system based upon the Linux kernel. It is derived from the Red Hat Enterprise Linux (RHEL) distribution. 

### What is the purpose of Rocky Linux ?

Rocky Linux exists to provide a free enterprise class computing platform and strives to maintain 100% binary compatibility with its upstream source, Red Hat Enterprise Linux (RHEL). 

We want Rocky Linux to be:
* a **solid** distro alternative for server production environments.
* a **trusted** distro with transparent processes, decisions and artifacts.
* a **stable** paced distro, with predictable release dates.
* a **grounded** distro on FOSS principles and on a self-governing decision forum.

### What is the difference between Rocky Linux and RHEL ?

Rocky Linux mainly changes packages to remove trademarked vendor branding and artwork.

Rocky Linux does not contain Red Hat Enterprise Linux or Fedora Linux; nor does it have any of their certifications, although it is built from the same source code as Red Hat Enterprise Linux.

### Why another RHEL based distro ? Don't we have enough distros out there ?

Yes. There are many Linux distributions based on the source code of [Red Hat Enterprise Linux](https://en.wikipedia.org/wiki/Red_Hat_Enterprise_Linux) (RHEL). You can see an overview [here](https://en.wikipedia.org/wiki/Red_Hat_Enterprise_Linux_derivatives). 

Unfortunately, some of them are discontinued, some of them have closed communities and others are driven by private companies.

One of the reasons for Rocky Linux is to be **an independent and transparent community, self-governed, not to be sold, not to be shutdown, not to be driven by a particular company's interest**.

### Why now ?

CentOS has recently shifted direction. CentOS announced on 2020-12-08 that they will shift from following the latest RHEL sources release (downstream, what CentOS has been doing from its origins) towards only being a development branch ahead of RHEL release (upstream), and renamed as *CentOS Stream*. See the official announcement [here](https://blog.centos.org/2020/12/future-is-centos-stream/).

This means CentOS Stream will provide continuous upgrades vs a planned release cycle. This means CentOS Stream may not be as stable as it used to be. This means we will no longer be able to use CentOS for our production environments.
 
We believe continuous delivery is great, but we think that was Fedora's purpose and reason to be, no need for CentOS Stream. 

We need what "old" CentOS was: a stable free and open source distro for our production environments. 
 
### Why the name "Rocky" Linux ? 

The name proposal came from Gregory Kurtzer, just some hours after the project started spinning:

> Thinking back to early CentOS days... My cofounder was Rocky McGaugh. He is no longer with us, so as a H/T to him, who never got to see the success that CentOS came to be, I introduce to you... Rocky Linux.

### Why not naming it CentOS-ng Linux or something else ? Why not reusing the same or similar name and branding as CentOS and use that momentum ?

Strangely enough, CentOS name and branding are currently owned by Red Hat. While it is true that it would have been great to be able to keep using CentOS name and branding to avoid confusing our users, we do not want to get into any legal issues.

We also believe "Rocky" name provides a good picture aligned to our main driver: being a solid and trustworthy distro (and cheap and available as just a simple rock).

### Who drives Rocky Linux ?

We all do. Rocky is a community-driven project. It has been kicked-off, mentored and being lead by Gregory Kurtzer, one of the founders of the CentOS project together with a group of enthusiastic people from different backgrounds.

### How many flavours do you support ? Do you plan to distribute a Desktop version ? A minimal / slime version ? Other X window managers like Xfce / MATE / other ?

Our first aim is to focus in what CentOS was: **a stable distro for servers**. 

We may take a look back at this question later on. 

### When are you going to release Rocky ?

We've just started, and we're setting up our processes, tools, org,...

There is currently no ETA at present for a release. 
 We will publish all updates in our homepage (https://rockylinux.org/) and other channels. 

Stay tuned!

### How can I help ?

Join us in our [#rocky](https://join.slack.com/t/hpcng/shared_invite/zt-gy0st6mt-ijgUaSvfdeEOhfXXfIstrQ) slack channel or in our [Rocky Linux forum](https://forums.rockylinux.org/).
