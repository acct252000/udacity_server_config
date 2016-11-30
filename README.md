
### Access to server

ssh -i ~/.ssh/linuxCourse grader@35.161.147.219 -p 2200 or
ssh -i ~/.ssh/udacity_key.rsa root@35.161.147.219 -p 2200 or


(IP is 35.161.147.219, port 2200)

### URL of hosted application

[http://ec2-35-161-147-219.us-west-2.compute.amazonaws.com/]([http://ec2-35-161-147-219.us-west-2.compute.amazonaws.com/])


###Software installed with apt-get

1.  apache2
2.  libapache2-mod-wsgi
3.  postgresql
4.  git
5.  python-setuptools
6.  python-pip
7.  virtualenv
8.  libpq-dev
9.  python-dev

###Software installed with pip

1.  Flask
2.  psycopg2
3.  Flask-SQLAlchemy
4.  httplib2
5.  sqlalchemy
6.  oauth2client

### Other configuration changes

1.  Created new user grader with sudo permissions and separate key pair (linuxCourse).
2.  Updated all currently installed packages.
3.  Configured local timezone to UTC.
4.  Changed ssh port to 2200
5.  Configured the uncomplicated firewall (ufw) to only allow ports 2200 (SSH) HTTP (80) and NTP (123)
6.  Installed Apache, mod_wsgi, postgresql and other packages as above to implement earlier[item catalog project](https://github.com/acct252000/udacity_item_catalog).

### Resources Used

Resources used were listed in links provided at [project instructions].(https://docs.google.com/document/d/1J0gpbuSlcFa2IQScrTIqI6o3dice-9T7v8EDNjJDfUI/pub?embedded=true).

### udacity_key.rsa - note different key for grader below

-----BEGIN RSA PRIVATE KEY-----
MIIEowIBAAKCAQEAw56sJYEYJeA03C71IzPlOllZSIwHwXjO+diKxmooLnwOK+3s
0kwITPQv90MmIFjwCLFjmuPPHdh5R/bt7rwskI7O5T4bxUH6DcpB6BDHVjwVdJOY
Qsandi0W2gxWcjFqe2BTCtcQvwcihqHQhUVE/rP/FAAuLBkWfZWfYH5EX+astsNX
bcHPtzO/x1k7SVt8s3VetvCLVED8EgCrHhMz22dcuvZIEGx4J1IZOaFskQgP+md/
FLwOPn053DdqHFKDEz/avO+raM3ILvownvwmUKqCWQVRgsltXXm9Su079xao5EoS
MxUzv1yKIHHy2eUzFC6/szulMu3xisceqlxxKQIDAQABAoIBAH3vVaXjYPdpSr6B
YIFkNGuG/+qrc4bDToQcOuMXjny2kq0HRBHyrtlTztlhGldyyjzebmBVzo3JQfLp
bi3maM47kciVXm10VxWvoxRSUPIcRjfBmSFMIJz81BxWGwTy+TkqPuvYnshMQJbp
74MMoClVGZ73qsHq+Maqn2sQftY5WnC6xGmWUlae8eLRRf7RVoaOv/qIAgnAVeEu
CNhQ++kSMxOCc6I/hg0kjVA+aQshmlajTtkddcZDquP6JJQAIAl5oRALt+/apE22
FXwSVzQQfDvtjyDP7i/j1JJmRq5nPQBNQSdHaO1ORx1McbkGHYqbbkB2jb6yIIlY
b0cXQG0CgYEA9qwLIyycLIS3Uw06hmSrlfBRuMp8nt7LBCd3h520DwJF4mb+rQ24
qd5Sa+w1tvwtq4nM7OPIjC4ERbfwihdxpebLiTnp5p2fNKjDnFoVqc/kxGrseuhW
1A+Jwr5sYeRyQJ6PinRznsKiHr+Eg6PXUUNX559TwYRf3+8Jm984Z88CgYEAywRo
bpMUfaOK8QcDpWPSCTDSiFkmEPaXFPDN2TmsKL/T+ZSVnLemlSRgeKkovSzDyZqv
X8KtC5CeUsfqOxyay2j2g8D+Ir9oPgE20hj1orVhfAI39XqzjZCMRCwYbuoB98sN
KzdFT1/2mhPp3dPZsmk0O2ZRWAJcrszKkh4A3YcCgYBfcaZFj+dF2nxMqFuy0JUL
yRb113NszWvkSZkYYk7fV9POjGeScjK3l4xwsc7+5IiPTRx7tI9OnieNCmUKKZQR
y0GJ8VytnOOTLpGxl7G2KPitf2nNDMU7/F8jeSbaodgLZM7JldF+5nRwTU5q2SRh
DxueRanUwPGP5h/jrfVXRQKBgQC/1/h/lQkl+KdRQJmXbo6KFNK9+dBY80ytgyhi
f3dKQoujK1996qXGBcwL+X3/1g9lsYDL8wDnDtAt1bBoD43Pbe6Vbog4ebud7DPL
sb5c9R2bu9T5aevGeLOzsB+eoA8gA4b8MYyTh1FXJD45Wvo69+NdxkBT9Fd07xz1
mtiifQKBgHyBgTkIJJuhq30h8UP19BxUqopHDv70riZ7DEJcZ2mSzTMyPRG8LSrh
Y/AGQtkpghEnVtweFVt464YDJyy9Fqxbm+qGeog4XIaRMLpFR9ROIHBraO8odMS6
dSlfd77pq5Ah9PBZKHCggEODpVq84rT9XjT+tsECEBYLAnXi1nEp
-----END RSA PRIVATE KEY-----

### grader key (linuxCourse file)

-----BEGIN RSA PRIVATE KEY-----
MIIEpQIBAAKCAQEAuGLpxMSdHolq4oO7vBgtHMMcv314fjd3IvjGZmmVdp27X4ql
6mh1becnZykRaKm3IlUhtaoBdFEbmC94mq2bmeuQBHpgmCjBfNgE/T2+7xniq3m1
w1w48u0VU0/d9FKIP6vntLnyvQJoAoqCzTh8mws06o+BdeAoi/emUUMCCkoAbR0o
PtVfkMMib5XsG9oqDfBEIQuz/duwyU6UlP/Hsc6zZdMlKuCkAP9EoP9D3pFQRnJa
oBBIRMJzxzB9dJE5ggY1DyRk57hJkrAoktED7+HQe600ZjlDM4Qmg4f4YUpdWBfk
+phFFpwKHjyekmbW5W0lxEjUeouGPNNn14fSmwIDAQABAoIBADe4hIaXGBgrVOah
ArHD6JYhjGV96FTUNCeYYHSAgc93uTEVODCPYrVUvn6ZVY54g0RXz7kTaB8bh6hE
6EBuKHCqVDpWNSymXFp6+X8CEto0y2AghsJD813OMbycjSmRa2U6cOoXq3hc6suh
ygd0g4tjJpmfxnK1y+sIavVxt4Md986/BBvFeBpGv+W9o8X702PVJ0H4n9G3gejp
2Wmtxr+25EuDyOGZY7DgA2IE0yts6ya6LKJvNJVFdHFzTRkxPbwRzvtDLeQb8QOq
AZbthpXEBJdIy4hb/AWPrqe9wHNTUPutq7xGP/3UujoaZpVREiMRFaRTak3lq0GM
jGicHxkCgYEA8ih0UxxeZrDjqS8CYkIkPhGaUPItvI0rejFBVrNoDjJCw9JoXQAz
SogDZWhDNw031DKnLg9TewJlITwMe7FHXeoSSL0/53qR1ifBuSeWJrP+TaZvgAg2
xFlKe+8uVgCzG5ydeJOgtBEsFerUrQOMIGnMOHg7pn1d6T4OPV8q0d8CgYEAwu0T
M+XpaG3ukanGOkur83Ya1omSDgEvJtTpG/gsCEap7+F9QtEb9Cr6p1Dt7d6fmdZt
+QV8yrg17XaUIhJQWPwl/CdCqsEUwObDMcM3Ru0is6nh1CZ8W3DlFqlWNNdVFZ2p
jy/WdaFDpIo1iT+l6sRVrOTwl5CS84uJg0hp7sUCgYEAjSnABeL3tO1RCYL55MWh
0vz39E/5EX1J5wVnjV8wPXZXLUguxmgjfkMjl63b4O+3p9+PTW5pv795rJIQxNpn
O/wDhJut8QamlSy/5WuKQC2VBTcMsJoZMwTKQsz/OetWfbYipfOJLu8DwBMQv3rd
6NdD0XdlbnyOjjU6n9QmZgkCgYEAhKQ2kPY+YiWMVeqlTT35AG65zItIq+b6Yv42
siWqMOeE9AsI5dLNptUoQ3q6rUb0bAaSRwYI6Rl4+OHb42N68VKDtpYws2k36hwd
b1tb3hO3rXJIjciyjra/7S/FzadJ6q+iliEDWoAmO20hCQgaqyp28nPHlBt5I+kr
5f38t9ECgYEAhGdTsC+/NKPksq0pDvdJVL9nArsFdM9/+gi8k+DUu/+BqLq0MP06
nSRXerDv4uoxPeqTsDjUYb2DnKanpjRZgkPbm/6DKBqYuAoqoI9ZYopiPvFTELwg
qKR5P8e188hO7ynFcY2/Nf4z+ECNHwjUT/k537hF2qg5j4hOF8+Q2HU=
-----END RSA PRIVATE KEY-----







