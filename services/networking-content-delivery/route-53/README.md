### Route 53

  #### Docs

  ###### *Domain Registration*

  Allows registering new domain names and transferring previously registered domain names.

  ###### *DNS Service*

  Routes internet traffic to applications and other AWS services by translating domain names into IP addresses for newly and previously registered domains.

  ###### *Health Checking*

  Health checks monitor health of resources

  ###### *Hosted Zones*

  A collection of resource record sets hosted by R53 that are managed under a single domain name with the same suffix

  ###### *Supported DNS Resource Record Types*
    - A : Value is an IPv4 address in dotted decimal notation
    - AAAA : Value is an IPv6 address in colon-separated hexidecimal format
    - CNAME : Value is a domain name
    - MX : An MX record contains decimal number (priority) and domain name
    - NS : Identifies the name servers for the hosted zone; a domain name
    - PTR : Same as domain name
    - SOA : Provides info about a dpomain and corresponding hosted zone
    - SPF : Formerly used to verify email sender identity
    - SRV : Value consists of 4 space-separated values
    - TXT : Record contains a space-separated list of double-quoted strings

  ###### *DNS Constraints and Behaviors*

    - Max Response Size : Responses sent over UDP are limited to 512 bytes. If resolver supports EDNS0, R53 permits responses up to 4096 bytes over UDP without truncation.
    - Authoritative Section Processing : R53 appends NS resource record set for the relevant hosted zone to authority section of DNS response for successful queries, whereas R53 appends start of SOA record on failed queries.
    - Additional Section Processing : R53 appends resource records to the Additional section

  ###### *R53 Pricing*

    Pay only for hosted zones configured and number of queries R53 answers.

  #### Practical

  ###### *Subheading*
  - https://aws.amazon.com/about-aws/whats-new/2016/08/amazon-route-53-announces-naptr-record-support-and-dns-query-test-tool/?utm_source=clouddevweekly&utm_medium=email
  - https://www.awsarchitectureblog.com/2014/12/internet-routing.html
  - https://www.awsarchitectureblog.com/2014/03/aws-and-compartmentalization.html
  -
