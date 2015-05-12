Sanction - to impose a sanction on; penalize, especially by way of discipline. 

===============================================================================

This script is meant to be a quick and effective method to block entire ip 
blocks belonging  to a specific country. You can block a specific port or ban 
the IP outright.

Note: Long term firewall management is better handled by an external device
(firewall, DoS mitigation services, etc). That said, sometimes you need a 
quick way to stem the tide until you can get those services in place. That's
where Sanction comes in.

usage:

[darke@pabu sanction]$ sudo ./sanction 

You will be prompted for the options and provided with a script to remove the
iptables rules that sanction creates.

In the event more than one country is matched, it will present you a menu
of options.

Any issues, questions, or ideas for improvements can be sent to adarke@gmail.com
