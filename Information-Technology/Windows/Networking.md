# Command Prompt

## Find all relevant client networking info
- ipconfig /all
- `displays all networking information of the client like DNS servers, DNS Suffix Search List, host name, WINS servers list`

## Remove/Add client from/to the DHCP server list (caution: may lose network access)
- ipconfig /release
- ipconfig /renew
- `The /release and /renew switches are useful if settings have changed on the DHCP server and the client needs to update its local configuration`

## Clear DNS & NetBIOS name resolutions on client computer
- ipconfig /flushdns
- nbtstat –R (requires administrator privileges)
- nbtstat -RR (requires administrator privileges)

## Namespace lookup
- nslookup <dns_name or ip_address> 
- `retrieves the relevant address information directly from the DNS cache of name servers. Can help determine which name server is authoritative for that client resolution`
- nblookup <dns_name or ip_address>
- `this is the same as nslookup but for WINS namespace. This requires a downloaded software called nblookup.exe (Different from cmd.exe)`

## Trace the route to destination (note: useful when a destination takes multiple server hops to reach)
- tracert <dns_name or ip_address>

## Check connectivity
- ping <dns_name or ip_address>
- pathping <dns_name or ip_address>
- `Show client and destination information (note: similar to tracert command)`
- ping -t <dns_name or ip_address>
- `Consistent ping`
