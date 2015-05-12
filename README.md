Sanction - to impose a sanction on; penalize, especially by way of discipline. 

===============================================================================

This script is meant to be a quick and effective method to block entire ip 
blocks belonging  to a specific country. You can block a specific port or ban 
the IP outright.

Note: Long term firewall management is better handled by an external device
(firewall, DoS mitigation services, etc). That said, sometimes you need a 
quick way to stem the tide until you can get those services in place. That's
where Sanction comes in.

Example usage:

...
[darke@pabu sanction]$ sudo ./sanction 

Enter the name of the country to block : China
Enter the specific port number to block or ALL to block all access: 25

Country = China
Port = 25

Please confirm (y or n) : y

China is the 2 letter abbreviation: cn
Obtaining IP blocks now...
Formulating IPTables rules...
Applying IPtables rules...

Success! The requested rules have been applied.
To remove them, run the command (as root):

/tmp/sanction.remove.cn.rules

or just restart iptables.
...

In the event more than one country is matched, it will present you a menu
of options.

Any issues, questions, or ideas for improvements can be sent to adarke@gmail.com
