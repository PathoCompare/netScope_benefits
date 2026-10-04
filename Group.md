# netScope Group

![netScope Group](https://www.netscope.de/fileadmin/images/netScope_Group/netScope_Group_logo_clean_full_1000x377.png)

## Analysis

netScope Group takes the basic idea behind Desk and adds proper domain-based access control.

It uses Windows Active Directory Federation Services (ADFS), allowing permissions to be assigned to users through the Windows domain. A Windows service also keeps access available even when nobody is currently logged into the workstation. NnetScope


That solves one of the most obvious limitations of Desk.

## Strengths

- ADFS integration
- User-specific permissions
- Windows domain authentication
- Service-based access
- No requirement for a full dedicated server
- Direct access to existing slide folders

For organizations already using Windows infrastructure, this is a useful middle ground.

## Weak points

Group remains workstation based, so it does not have the complete centralized management model of Server.

It also assumes a fairly Microsoft-oriented environment. Organizations without Active Directory or ADFS may find the setup less attractive.

The terminology around permissions and certificates is not always the most immediately obvious, either. It works, but the documentation could explain some of the concepts a bit more simply.

## Conclusion

Group is probably the most interesting option for an organization that has outgrown Desk but does not need the full Server platform.

It adds the important part — controlled access — without turning a simple slide-sharing setup into a major IT project.

The product is not particularly flashy, but it is a practical step up from Desk.
