# Chapter 01: Introduction to the Web

## 1.1 Internet

The internet is an international network of connected computers. No company owns the internet; it is a cooperative effort governed by a system of standards and rules. The purpose of connecting computers together, of course, is to share information. There are many ways information can be
passed between computers, including email (POP3/IMAP/SMTP), file transfer (FTP), secure shell (SSH), and many more specialized modes upon which the internet is built. These standardized methods for transferring data or documents over a network are known as protocols.

### Comparison with the Web

The web is a subset of the internet. It is just one of many ways information can be transferred over networked computers.

The web (originally called the World Wide Web, thus the “www” in site addresses) is just one of the ways information can be shared over the internet. It is unique in that it allows documents to be linked to one another via hypertext links—thus forming a huge “web” of connected information. The web uses a protocol called HTTP (HyperText Transfer Protocol). That acronym should look familiar because it is the first four letters of nearly all website addresses, as we’ll discuss in an upcoming section.

World Wide Web browser software, such as Microsoft's Internet Explorer/Edge, Mozilla Firefox, Opera, Apple's Safari, and Google Chrome, lets users navigate from one web page to another via hyperlinks embedded in the documents. These documents may also contain any combination of computer data, including graphics, sounds, text, video, multimedia and interactive content that runs while the user is interacting with the page. Client-side software can include animations, games, office applications and scientific demonstrations. Through keyword-driven Internet research using search engines like Yahoo!, Bing and Google, users worldwide have easy, instant access to a vast and diverse amount of online information. Compared to printed media, books, encyclopedias and traditional libraries, the World Wide Web has enabled the decentralization of information on a large scale.

The Web is therefore a global set of documents, images and other resources, logically interrelated by hyperlinks and referenced with Uniform Resource Identifiers (URIs). URIs symbolically identify services, servers, and other databases, and the documents and resources that they can provide. Hypertext Transfer Protocol (HTTP) is the main access protocol of the World Wide Web. Web services also use HTTP to allow software systems to communicate in order to share and exchange business logic and data.

> **Note:** The web was born in a particle physics laboratory (CERN) in Geneva, Switzerland, in 1989. There a computer specialist named Tim Berners-Lee first proposed a system of information management that used a “hypertext” process to link related documents over a network. He and his partner, Robert Cailliau, created a prototype and released it for review. For the first several years, web pages were text-only. It’s difficult to believe that in 1992, the world had only about 50 web servers, total. The real boost to the web’s popularity came in 1992 when the first graphical browser (NCSA Mosaic) was introduced, and the web broke out of the realm of scientific research into mass media. The ongoing development of web technologies is overseen by the World Wide Web Consortium (W3C).

## 1.2 IP Addresses and Ports

### IP addresses

IP Address is a unique address assigned to a computing devices such as computers, tablets and smartphones to communicate with other devices within the Internet. No device can connect to the Internet without a public IP address, and a public IP address is assigned to you by the Internet Service Provider (ISP) you are subscribing from. There are two versions of IP in use today, IPv4 (32-bit) and IPv6 (128-bit). There are two types of IP addresses: public and private. To use the Internet, you'll need a public IP address. To connect to a local area network such as your home or work network, a private IP address is suffice.


An Internet Protocol address (IP address) is a numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. An IP address serves two principal functions: host or network interface identification and location addressing.

The IP address space is managed globally by the Internet Assigned Numbers Authority (IANA), and by five regional Internet registries (RIRs) responsible in their designated territories for assignment to end users and local Internet registries, such as Internet service providers. IPv4 addresses have been distributed by IANA to the RIRs in blocks of approximately 16.8 million addresses each. Each ISP or private network administrator assigns an IP address to each device connected to its network. Such assignments may be on a static (fixed or permanent) or dynamic basis, depending on its software and practices.

Internet Protocol version 4 (IPv4) defines an IP address as a 32-bit number. However, because of the growth of the Internet and the depletion of available IPv4 addresses, a new version of IP (IPv6), using 128 bits for the IP address, was developed in 1995, and standardized in December 1998. In July 2017, a final definition of the protocol was published. IPv6 deployment has been ongoing since the mid-2000s.

IP addresses are usually written and displayed in human-readable notations, such as `172.16.254.1` in IPv4, and `2001:db8:0:1234:0:567:8:1` in IPv6. The size of the routing prefix of the address is designated in CIDR notation by suffixing the address with the number of significant bits, e.g., 192.168.1.15/24, which is equivalent to the historically used subnet mask 255.255.255.0.

> **IP Geolocation:** is the mapping of an IP address to the geographic location of the internet from the connected device. By geographically mapping the IP address, it provides you with location information such as the country, state, city, zip code, latitude/longitude, ISP, area code, and other information.
>
>Your IP Location can be found using our IP Lookup tool. No IP Lookup tool is 100% accurate due to many different factors. Some of those factors include where the owner of the IP has it registered, where the agency that controls the IP is located, proxies, cellular IPs, etc. If you are in the US and the controlling agency of the IP is located in Canada, chances are the IP address lookup results will show as Canada. Showing a Canadian IP while in the northern US is very common among mobile users on the Verizon network.
>
> There are many different IP location databases in which you can pull from. Most vendors claim a 98% or higher accuracy. IP mapping to specific cities can sometimes vary slightly based upon the location of the nearest ISP provider's network hub.
>
> Geolocation finder websites: https://www.iplocation.net/ or https://tools.keycdn.com/geo.

### Ports

A computer port is a type of electronic, software- or programming-related docking point through which information flows from a program on your computer or to your computer from the Internet or another computer in a network. (A network, by the way, is a series of computers that are physically or electronically linked.)

In computer terms, a computer or a program connects to somewhere or something else on the Internet via a port. Port numbers and the user's IP address combine into the "who does what" information kept by every Internet Service Provider.

Ports are numbered for consistency and programming. The most commonly used and best known ports are those numbered 0 to 1023 dedicated for Internet use, but they can extend far higher for specialized purposes. Each port set or range is assigned specialized jobs or functions, and that's generally all they do. Usually, all identical system services or functions use the same port numbers on the receiving servers.

For example, all computers accessing or requesting Quote of the Day will always use port 17, because that port is officially reserved for that purpose, and only requests for that service use port 17. Outgoing information is channeled through a different or private port, keeping the "incoming line" open for others. Email received on a local computer generally uses a TCP port 25. File Transport Protocol or FTP uses port 21, to name only a few port assignments.

#### Range Groups

`0 to 1023` - Well known port numbers. Only special companies like Apple QuickTime, MSN, SQL Services, Gopher Services and other prominent services have these port numbers.

`1024 to 49151` - Registered ports; meaning they can be registered to specific protocols by software corporations.

`49152 to 65536` - Dynamic or private ports; meaning that they can be used by just about anybody.

## 1.3 Protocols:

The Internet standards describe a framework known as the Internet protocol suite. This is a model architecture that divides methods into a layered system of protocols, originally documented in RFC 1122 and RFC 1123. The layers correspond to the environment or scope in which their services operate. At the top is the application layer, space for the application-specific networking methods used in software applications. For example, a web browser program uses the client-server application model and a specific protocol of interaction between servers and clients, while many file-sharing systems use a peer-to-peer paradigm. Below this top layer, the transport layer connects applications on different hosts with a logical channel through the network with appropriate data exchange methods.

Underlying these layers are the networking technologies that interconnect networks at their borders and exchange traffic across them. The Internet layer enables computers ("hosts") to identify each other via Internet Protocol (IP) addresses, and route their traffic to each other via any intermediate (transit) networks. Last, at the bottom of the architecture is the link layer, which provides logical connectivity between hosts on the same network link, such as a local area network (LAN) or a dial-up connection. The model, also known as TCP/IP, is designed to be independent of the underlying hardware used for the physical connections, which the model does not concern itself with in any detail. Other models have been developed, such as the OSI model, that attempt to be comprehensive in every aspect of communications. While many similarities exist between the models, they are not compatible in the details of description or implementation. Yet, TCP/IP protocols are usually included in the discussion of OSI networking.

The most prominent component of the Internet model is the Internet Protocol (IP), which provides addressing systems, including IP addresses, for computers on the network. IP enables internetworking and, in essence, establishes the Internet itself. Internet Protocol Version 4 (IPv4) is the initial version used on the first generation of the Internet and is still in dominant use. It was designed to address up to ~4.3 billion (109) hosts. However, the explosive growth of the Internet has led to IPv4 address exhaustion, which entered its final stage in 2011,[66] when the global address allocation pool was exhausted. A new protocol version, IPv6, was developed in the mid-1990s, which provides vastly larger addressing capabilities and more efficient routing of Internet traffic. IPv6 is currently in growing deployment around the world, since Internet address registries (RIRs) began to urge all resource managers to plan rapid adoption and conversion.

#### HTTP(S)

The Hypertext Transfer Protocol (HTTP) is an application protocol for distributed, collaborative, hypermedia information systems.[1] HTTP is the foundation of data communication for the World Wide Web, where hypertext documents include hyperlinks to other resources that the user can easily access, for example by a mouse click or by tapping the screen. HTTP was developed to facilitate hypertext and the World Wide Web.

Hypertext Transfer Protocol Secure (HTTPS) is an extension of the Hypertext Transfer Protocol (HTTP) for secure communication over a computer network, and is widely used on the Internet.[1][2] In HTTPS, the communication protocol is encrypted using Transport Layer Security (TLS), or, formerly, its predecessor, Secure Sockets Layer (SSL). The protocol is therefore also often referred to as HTTP over TLS,[3] or HTTP over SSL.

The principal motivation for HTTPS is authentication of the accessed website and protection of the privacy and integrity of the exchanged data while in transit. It protects against man-in-the-middle attacks. The bidirectional encryption of communications between a client and server protects against eavesdropping and tampering of the communication.[4] In practice, this provides a reasonable assurance that one is communicating without interference by attackers with the website that one intended to communicate with, as opposed to an impostor.

Historically, HTTPS connections were primarily used for payment transactions on the World Wide Web, e-mail and for sensitive transactions in corporate information systems.Since 2018, HTTPS is used more often by web users than the original non-secure HTTP, primarily to protect page authenticity on all types of websites; secure accounts; and keep user communications, identity, and web browsing private.

> **Note:** As of April 2018, 33.2% of Alexa top 1,000,000 websites use HTTPS as default, 57.1% of the Internet's 137,971 most popular websites have a secure implementation of HTTPS, and 70% of page loads (measured by Firefox Telemetry) use HTTPS.


#### FTP

The File Transfer Protocol (FTP) is a standard network protocol used for the transfer of computer files between a client and server on a computer network.

FTP is built on a client-server model architecture using separate control and data connections between the client and the server.[1] FTP users may authenticate themselves with a clear-text sign-in protocol, normally in the form of a username and password, but can connect anonymously if the server is configured to allow it. For secure transmission that protects the username and password, and encrypts the content, FTP is often secured with SSL/TLS (FTPS) or replaced with SSH File Transfer Protocol (SFTP).

#### SSH

Secure Shell (SSH) is a cryptographic network protocol for operating network services securely over an unsecured network.[1] Typical applications include remote command-line login and remote command execution, but any network service can be secured with SSH.

SSH provides a secure channel over an unsecured network in a client–server architecture, connecting an SSH client application with an SSH server.[2] The protocol specification distinguishes between two major versions, referred to as SSH-1 and SSH-2. The standard TCP port for SSH is 22. SSH is generally used to access Unix-like operating systems, but it can also be used on Windows. Windows 10 uses OpenSSH as its default SSH client.

## 1.4 Browsers

A web browser (commonly referred to as a browser) is a software application for accessing information on the World Wide Web. Each individual web page, image, and video is identified by a distinct URL, enabling browsers to retrieve and display them on the user's device.

A web browser is not the same thing as a search engine, though the two are often confused.[1] For a user, a search engine is just a website, such as google.com, that stores searchable data about other websites. But to connect to and display websites on their device, a user needs to have a web browser installed

The most popular web browsers are Chrome, Firefox, Safari, Internet Explorer, and Edge.

### Functions

The purpose of a web browser is to fetch information resources and display them on a user's device.

This process begins when the user inputs a URL, such as https://en.wikipedia.org/, into the browser. Virtually all URLs on the Web start with either http: or https: which means the browser will retrieve them with the Hypertext Transfer Protocol. In the case of https: the communication between the browser and the web server is encrypted for the purposes of security and privacy. Another URL prefix is file: which is used to display local files already stored on the user's device.

Once a web page has been retrieved, the browser's rendering engine displays it on the user's device. This includes image and video formats supported by the browser.

Web pages usually contain hyperlinks to other pages and resources. Each link contains a URL, and when it is clicked, the browser navigates to the new resource. Thus the process of bringing content to the user begins again.

To implement all of this, modern browsers are a combination of numerous software components.

### Features

All major browsers allow the user to open multiple pages at the same time, either in different browser windows or in different tabs of the same window. They also support the use of extensions to add to or modify browser operation in a variety of ways.

Common user interface features of browsers:

- Back and forward buttons to go back to the previous - page visited or forward to the next one.
- A refresh or reload button to reload the current page.
- A stop button to cancel loading the page. (In some browsers, the stop button is merged with the reload button.)
- A home button to return to the user's home page.
- An address bar to input the URL of a page and display it.
- A search bar to input terms into a search engine. (In some browsers, the search bar is merged with the address bar.)

## 1.5 URL of a web page

A Uniform Resource Locator (URL), colloquially termed a web address,[1] is a reference to a web resource that specifies its location on a computer network and a mechanism for retrieving it. A URL is a specific type of Uniform Resource Identifier (URI),[2][3] although many people use the two terms interchangeably.[4][a] URLs occur most commonly to reference web pages (http), but are also used for file transfer (ftp), email (mailto), database access (JDBC), and many other applications.

Most web browsers display the URL of a web page above the page in an address bar. A typical URL could have the form http://www.example.com/index.html, which indicates a protocol (http), a hostname (www.example.com), and a file name (index.html).

Opening a local file on your computer is as simple as double-clicking it, but to open files on remote computers, like web servers, we must use URLs so that our web browser knows where to look. For example, opening the HTML file that represents the web page explained below, is done by entering it into the navigation bar at the top of the browser you're using.

Uniform Resource Locators are most commonly abbreviated as URLs but they're also called website addresses when they refer to URLs that use the HTTP or HTTPS protocol.

### Structure of a URL

A URL can be broken down into different sections, each piece serving a specific purpose when accessing a remote file.

HTTP and FTP URLs are structured the same, as protocol://hostname/fileinfo. For example, accessing an FTP file with its URL might look something like this:

```URL
FTP://servername/folder/otherfolder/programdetails.docx
```

Which, aside from having FTP instead of HTTP, looks like any other URL you might encounter out there on the web.

Let's use the following URL, which is Google's announcement of a CPU flaw, as an example of an HTTP address and identify each part:
```URL
https://security.googleblog.com/2018/01/todays-cpu-vulnerability-what-you-need.html
```

- **https** is the protocol (like FTP is a protocol) that defines the type of server that you're communicating with.
- **security** is the hostname used to access this specific website.
- **googleblog** is the domain name.
- **com** is what's referred to as the top-level domain (TLD), some others of which include .net, .org, .co.uk, etc.
- **/2018/01/** represents the directories used to organize the webpage or file. On the web server that's holding the website files, these would be the actual folders that you'd click through to find the file that this URL is specifying.
- **todays-cpu-vulnerability-what-you-need.html** is the actual file that the URL is pointing to. If you were trying to load an image, audio file, or another file type instead of an HTML file, then the URL would end in that file extension (like a PNG or MP3).
- **security.googleblog.com** as a group is called the Fully Qualified Domain Name (FQDN).

### URL syntax rules

Only numbers, letters, and the following characters are allowed in a URL: ()!$-'_*+.

Other characters must be encoded (translated to programming code) in order to be accepted in a URL.

Some URLs have parameters that split the URL away from additional variables. For example, when you do a Google search for lifewire:

```URL
https://www.google.com/search?q=lifewire
```

The question mark you see is telling a certain script, hosted on Google's server, that you want to send a specific command to it in order to get custom results.

The specific script that Google uses to execute searches knows that whatever follows the ?q= part of the URL should be identified as the search term, so whatever is typed at that point in the URL is used to search on Google's search engine.

You can see similar behavior in the URL in this YouTube search for best cat videos:

```URL
https://www.youtube.com/results?search_query=best+cat+videos
```
>**Note:** Although spaces are not allowed in a URL, some websites use a + sign, which you can see in both the Google and YouTube examples. Others use the encoded equivalent of a space, which is %20.

URLs that use multiple variables use one or more ampersands after the question mark. You can see the example here for an Amazon.com search for Windows 10:

```URLs
https://www.amazon.com/s/ref=nb_sb_noss_2?url=search-alias%3Daps&field-keywords=windows+10
```

The first variable, url, is preceded by the question mark but the next variable, field-keywords, is preceded by an ampersand. Additional variables would also be preceded by an ampersand.

Parts of a URL are case sensitive — specifically, everything after the domain name (the directories and file name). You can see this for yourself if you capitalize the word "tools" in the example URL from my site that we deconstructed above, making the end of the URL read /free-driver-updater-Tools.htm. Try to open that page here and you can see that it doesn't load because that specific file doesn't exist on the server.​

### More on URLs

If a URL points you to a file that your web browser can display, like a JPG image, then you don't have to actually download the file to your computer in order to see it. However, for files that aren't normally displayed in the browser, like PDF and DOCX files, and especially EXE files (and many other file types), you'll be prompted to download the file to your computer in order to use it.

URLs provide an easy way for us to access a server's IP address without needing to know what the actual address is. They're like easy-to-remember names for our favorite websites. This translation from a URL to an IP address is what DNS servers are used for.

Some URLs are really long and complex and are best used if you click it as a link or copy/paste it into the browser's address bar. A mistake in a URL could generate a 400-series HTTP status code error, the most common type being a 404 error.

One example can be seen at 1and1.com. If you try to access a page that doesn't exist on their server (like this one), you'll get a 404 error. These types of errors are so common that you'll often find custom, often humorous, versions of them on some websites.

If you're having trouble accessing a website or online file that you think should be loading normally, see How to Troubleshoot an Error in a URL for some helpful ideas on what to do next.

Most URLs don't require the port name to be given. Opening google.com, for example, can be done by specifying it's port number at the end like http://www.google.com:80 but it isn't necessary. If the website were operating on port 8080 instead, you could replace the port and access the page that way.

By default, FTP sites use port 21, but others may be set up on port 22 or something different. If the FTP site isn't using port 21, you have to specify which one it's using in order to access the server correctly. The same concept applies to any URL that uses a different port than what the program used to access assumes by default that it's using.

**Reference:**

[1] https://en.wikipedia.org/wiki/URL
[2] https://www.lifewire.com/what-is-a-url-2626035

## 1.6 The anatomy of a web page

A web page (also written as webpage) is a document that is suitable for the World Wide Web and web browsers. A web browser displays a web page on a monitor or mobile device.

The web page usually means what is visible, but the term may also refer to a computer file, usually written in HTML or a comparable markup language. Web browsers coordinate various web resource elements for the written web page, such as style sheets, scripts, and images, to present the web page. Typical web pages provide hypertext that includes a navigation bar or a sidebar menu linking to other web pages via hyperlinks, often referred to as links.

On a network, a web browser can retrieve a web page from a remote web server. The web server may restrict access to a private network such as a corporate intranet. The web browser uses the Hypertext Transfer Protocol (HTTP) to make such requests to the web server.

A static web page is delivered exactly as stored, as web content in the web server's file system. In contrast, a dynamic web page is generated by a web application, usually driven by server-side software. Dynamic web pages help the browser (the client) to enhance the web page through user input to the server.


**References:**
[1] https://en.wikipedia.org/wiki/Web_page
[2]


## Web architecture


## Web visualization
