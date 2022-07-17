We have not been able to verify your authority to this domain. On your domain registrar's website, locate your Domain Name System (DNS) settings and enter the following two 

CNAMEs: (
    Name: news, 
    Destination: ghs.google.com) and (
    Name: aqrdudrolnmg, 
    Destination: gv-u7ffpcitnmxqqv.dv.googlehosted.com). 
    
    See https://support.google.com/blogger/answer/1233387 for detailed instructions.
BUY A DOMAIN
DELETE
CANCEL
SAVE

-- Below you can see the list of the essential records to be created: 

Hostname	Record Type	Priority	Value
@	MX	10	mx1.privateemail.com
@	MX	10	mx2.privateemail.com
@	TXT	
v=spf1 include:spf.privateemail.com ~all


And in this table you can find the additional records (they will not affect email delivery itself and can be skipped): 

Hostname	Record Type	Value
mail	CNAME	privateemail.com
autodiscover	CNAME	privateemail.com
autoconfig	CNAME	privateemail.com


Service	Protocol	Record Type	Priority	Weight	Port	Value
_autodiscover	_tcp	SRV	0	0	443	privateemail.com


NOTE: @ stands for yourdomain.com; mail, autodiscover and autoconfig stand for sub-domains mail.yourdomain.com, autodiscover.yourdomain.com and autoconfig.yourdomain.com correspondingly. 
