## Firewall

Most people think of a firewall as a network security system that detects and controls both incoming and outgoing data.
However, that is just a basic understanding. In reality, there are multiple types of firewalls, each designed to prevent malware,
viruses, and other malicious activities in different ways and for specific purposes. This discussion will focus on three main types:
Packet Filtering Firewalls, Proxy Firewalls, and Next-Generation Firewalls.

A Packet Filtering Firewall follows the most fundamental approach. It inspects data packets—small units of information that networks 
exchange—and determines whether to allow or block them based on predefined rules (e.g., IP addresses). While this method is fast and efficient,
it does not inspect the packet’s payload (the actual message), making it less secure.[^Noonan06Firewall]

A Proxy Firewall, in contrast, acts as an intermediary between users and external services, filtering data at the application layer. 
By analyzing full requests before forwarding them, it provides a higher level of security compared to traditional firewalls.[^DeCarlo24types]

Finally, a Next-Generation Firewall (NGFW) combines standard packet filtering with deep packet inspection—meaning it can analyze packets
more thoroughly than previous firewall types, identifying hidden threats.[^DeCarlo24types]

As new media technologies rapidly evolve, users interact with digital content such as applications, social media, and cloud services more 
than ever before. While this expands access to information and connectivity, it also increases exposure to cyber risks. Firewalls play a 
crucial role in protecting networks from external threats, but they do not prevent companies from collecting user data. Many digital platforms 
actively gather and analyze user information, often without users being fully aware of the extent of data tracking. As legal scholar Teresa Scassa
explains in Privacy and Social Media in the Age of Big Data, companies use data profiling to predict consumer behavior, determine service eligibility 
(such as insurance or loans), and even apply price discrimination based on personal data.[^Dusseault13privacy]This means that almost every online interaction leaves
a digital footprint, which can be stored, analyzed, and sometimes exploited.

The challenge is that while firewalls protect networks from external attacks, they do not regulate how platforms handle user data. Social media, 
online marketplaces, and other web-based services continuously collect, store, and monetize personal information, raising concerns about privacy, 
security, and data ownership. The increasing interactivity between users and online platforms makes data more vulnerable to exposure, especially 
as people share personal details, preferences, and behaviors. While firewalls help prevent unauthorized access, they are not a complete solution 
to digital privacy risks. To truly safeguard personal data, users must combine strong cybersecurity measures with awareness of how their data is 
being collected and used. This includes practices such as adjusting privacy settings, using encrypted communication, and being cautious about sharing 
personal information online.

Firewalls remain an essential first line of defense against cyber threats, preventing unauthorized access and filtering harmful traffic. 
However, in the modern digital landscape, cybersecurity is only one part of the equation. Protecting personal data also requires understanding 
how platforms collect, store, and use information. As new media technologies continue to evolve, the need for both stronger security measures 
and better privacy protections will only grow.

[^Noonan06Firewall]: Noonan, Wesley J., and Ido Dubrawsky. 2006. _Firewall Fundamentals_. Indianapolis, IN: Cisco Press.

[^DeCarlo24types]:DeCarlo, Amy Larsen. 2024. _The 5 Different Types of Firewalls Explained_. TechTarget, August 15, 2024. https://www.techtarget.com/searchsecurity/feature/The-five-different-types-of-firewalls.

[^Dusseault13privacy]:Dusseault, Pierre-Luc, and Canada. Parliament. House of Commons. Standing Committee on Access to Information, Privacy and Ethics. 2013. _Privacy and Social Media in the Age of Big Data: Report of the Standing Committee on Access to Information, Privacy and Ethics_. Ottawa: House of Commons.

