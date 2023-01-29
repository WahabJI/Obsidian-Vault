# <u>Section 1</u>

## Section 1.1

- The internet started off as **4** computers in 1969. Today, the internet is the largest and most popular computer network.
- WWW or "Wirld WIde Web" was a way developed by Tim Berners-Lee in the early 1990's asa more convenient way for computer to communicate.
- HTTP is a protocol for transferring HTML files betweek computers
- HyperText Markup Language (==HTML==) is a standardmarkup language for web documents.
	- Document ***markup*** are special markings within the document providing additional information about links, formatting, and immages.
- ![[Pasted image 20230123162355.png]]
- Difference between **web** and **internet**
	- <u>internet</u>: the interconnection of computers communicating using a set of rules.
	- <u>web</u>: One particular use of the internet
- ### 1.1.3 participation activity
	- First Website was published when?
		- **1991**
	- When was Yahoo created?
		- **1994**
	- How many websites in 2001?
		- **30 million**
	- How many websites in 2011
		- **350 millionW*e*
	- In what year did the number of internet users surpass 3 billion?
		- **2015**
- **Web Browser**: downloads HTML document from a web server and displays it to the user allowing interaction.
- Web standards are controlled by the World Wide Web Consortium (W3C).
	- They however relinquished HTML standard publications to the *Web Hypertext Application Technology Working Group (WHATWG)* who create the **HTML Living Standard**.
	- ![[Pasted image 20230123165552.png]]
	- A modern web page is composed of HTML, CSS, and Javascript.
		- HTML defines the structure and content of a webpage.
		- CSS specifies the layout and visible appearance.
		- JavaScript describes the dynamic behaviors and actions of a webpage.

## Section 1.2

- IP Adress is short for Internet Protocol and a typica one is usually 32-bits divides into four 8-bit groups and often written as a decimal number.
	- Part of an **internet packet** wihch contains To and From IP addresses.
	- IPv4 or also known as the original Internet Protocol has 32-bit addresses which can represent 2<sup>32</sup> or about 4 billion unique addresses.
	- IPv6 is a newer version of this protocol which uses 128-bit addresses capable of representing 2<sup>128</sup> or 3.4 x 10<sup>38</sup> addresses which is not only a shit ton but should be good for a while.
- Domain name is a name for an IP address.
- DNS server is short for Domain Name System and is contacted to change the domain name to IP addresses.
	- 13 DNS servers (called **root servers**) exist in the world and a computer's operating system or an ISP keeps a reference to the root servers' IP address.
- ## 1.2.4 Participation Activity
	- Websites can have **BOTH** an IP address and domain name
	- A DNS Server's primary role is to convert the domain name to an IP address.
- Domain names are hierarchial. 
	- A domain name can belong to a ***top-level domains (TLD)*** such as .com, .net, .org, .edu, and .gov.
	- In addition to that, each country is assigned a unique two-letter ***country code top-level domain (ccTLD)*** lke .uk and .ru. 
	- After that, we have ***second-level domains*** such as the wikipedia in wikipedia.org and is commony an organizations name 
- **ICANN** is the organization that manages TLDs and now allows companies and organizations to create customized TLDs such as .church and .pizza.
- A ***URL (Uniform Resource Locator)*** is the location of a web resource on the web.
	- A ***web resource*** is any retrievable item, like an HTML file, image, video, CSS stylesheet, etc.
- A URL is composed of several parts:
	- **Scheme**: Characters at the beginning of a URL followed by ":" or "://" and include things such as *http, https, mailto, and file*.
	- **Hostname**: The complete domain namefollowing the scheme in a URL.
	- **Path**: The characters to the right of the hostname in a URL.
	- **Query string**: Optional characters to the right of the "?" in a URL that provides data for the web server.
	- **Fragment**: Optional characters at the end of a URL that start with a "#" and refer to a certain location within a webpage.
- If a web server is reached but the specific requested page isn't found, the server returns a ***404*** status code.
## Section 1.3

- The ***HyperText Transfer Protocol (HTTP)*** is a networking protocol that runs over TCP/IP and governs communication between web browsers and web servers.
	- *HTTP/1.1* used for most of the web's life time.
	- *HTTP/2* is a reltively new HTTP standard that speeds-up the transfer of information between web browsers and web servers.
	- *HTTP/3* is currently in development and improves the speed of the previous version by using UDP to transport data packets instead of TCP.
	- An ***HTTP*** <u>request</u> is a message sent from web browser to the web server often used to send back information.
	- An ***HTTP*** <u>response</u> is a message sent from the web server back to the web browser in a response to a HTTP request.
	- ***Transmission Control Protocol/Internet Protocol (TCP/IP)*** is a protocol suite that governs how data packets are transferred over the internet from one machine to another. 
- An HTTP <u>request</u> and HTTP <u>response</u> are both composed of 4 parts:
	- ==Start Line:== the start line specifies the HTTP version being used.
		- A <u>requests</u> start line includes a request type and path
		- A <u>responses</u> start line includes a status code and phrase?
	- ==Header Fields:== There can be >= 0 header fields. There are a keyword that is followed by a colon and a value. They supply additional information about the req or res.
	- ==Empty Line==
	- ==Message Body:== A message body contains data being transferred between a web browser and web server. 
		- In a req, a message body may be empty or contain submitted form data.
		- In a res, the message body may contain the requested resource.
	![[Pasted image 20230128200743.png]] 
	- The ***Internet Assigned Numbers Authority (IANA)*** is a standards org that manages various internet numbers and symbols like global IP address allocation, root zone management in DNS, and media types.
	- ==**Common HTTP request methods**==
	![[Pasted image 20230128201127.png]]
	- ==**Common HTTP response status codes**==
	![[Pasted image 20230128201202.png]]
	- ***URL Shortneing*** is a technique to create shorter URLs. They are convenient for sharing on social media. These shorter URLs repond with 301 status code and a Location header with the webpage's full URL.
	- A ***browser cache*** is an area on the computer's file system where web content can be stored by the web browser for a quick retrieval later and can reduce the amount of net traffic required to display previously visited webpages.
	- An ***entity tag (ETag)*** is an identifier for a specific version of a web resource. When a resource changes, so should the ETag associated with the resource.
	- ==Network Sniffer:== is a software that monitors network traffic and allows users to inspect HTTP requests and responses
		- **HTTPS** encrypts HTTP traffic between a broswer and web server so that a netwrok sniffer cannot intercept sensitive information like passwords, credit card numbers etc.
	- HTTPS uses a protocol called ***Transport Layer Security (TLS)***, which uses asymmetric public keys to encrypt data. For a website to use HTTPS, it must acquire a <u>digital certificate</u>, issued by a trusted <u>certificate authority</u>, that contains a public key used by TLS to encrypt said data.
	- ==Steps in an HTTPS transaction==
	![[Pasted image 20230128202300.png]]

## Section 1.4

- ==Important Mobile Development Topics==
![[Pasted image 20230128202938.png]]
- **Internet of Things (IoT):** The global collection of communicating devices that sense and control technology on behalf of humans. These can range from temperature sensors to a satellite-based laser scanner used to discover archaelogical sites hidden by vegetation. They display >= 1 of the following characteristics:
	- Gather information about the physical world
	- Share the sensor data with control systems
	- Interact with hardware to execute commands sent by control systems.
- **Web Accessibility:** The ability of users with disabilities to access and use a webpage with reasonable efforts. Some conditions affecting this are:
	- Visual problems
	- Hand control issues
	- Seizures caused by flashing
	- Cognitive challenges such as dyslexia
- **Cognitive Computing:** The use of artificial intelligence techniques and access to vast amounts of data to simulate human problem soling in complex situations with ambiguity, changing data and even conflicting information.
- **Seperation of Concerns:** A design principle of breaking up web content using distinct languages and documents that overlap as little as possible. This is broken up into 3 key languages;
	- <u>HTML</u> is the language that describes the page content
	- <u>CSS</u> is the language that describes page layout
	- <u>JavaScript</u> is the language that provides interactive functionality

## Section 1.5

- ==Common HTML elements==
![[Pasted image 20230128203953.png]]

