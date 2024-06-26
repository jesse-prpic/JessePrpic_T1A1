# Jesse Prpic Term 1 Assignment 1 - Workbook



#### Answer
Markup languages are fundamental and the foundation of creating and structuring web pages. HyperText Markup Language or more known as HTML is the most common markup language and is the backbone of web content (Varagouli, 2021).


Other languages include; XML, SGML and XHTML but for this portion of the workbook we will only focus on HTML.


Markup language can be complex and can have a lot of moving parts, some important components and concepts of markup language include;
- Elements and Tags;
   - enclose content and form elements and start and end tags
       - This can be defined by eg ('<>')
- Attributes
   - Allows you to modify element behaviour or appearances
       - This can be defined by eg ('attribute' = 'value')
- Semantics
   - Enhances the meaning of the element
       - Defined by eg ('<article>, <'section>', '<aside>')


These are only just a few of the common and important components with more others that make up the structure of a web page.


##### Reference
Varagouli, E. (2021, October 19). What Each Markup Language Is Used For. Semrush Blog. https://www.semrush.com/blog/markup-language/


## Q2


#### Answer
Packets:
A packet is a small chunk of segments (around 1500 bytes) which is from a larger message consisting of two potions, the header and the payload. The header contains the information such as its origin and destination IP address and the payload refers to the actual data.
Once the payload reaches its destination it will recombine.


An analogy of this I found useful is;
"Suppose Alice is writing a letter to Bob, but Bob's mail slot is only wide enough to accept envelopes the size of a small index card. Instead of writing her letter on normal paper and then trying to stuff it through the mail slot, Alice divides her letter into much shorter sections, each a few words long, and writes these sections out on index cards. She delivers the group of cards to Bob, who puts them in order to read the whole message" (https://www.cloudflare.com/en-au/learning/network-layer/what-is-a-packet/, 2024).


Packet and packet switching is a way to allow data to be sent securely, the world's first computer network was produced in 1969 and is the basis on which the internet still works today.


##### Reference
https://www.cloudflare.com/en-au/learning/network-layer/what-is-a-packet/


A short history of the internet | National Science and Media Museum. (n.d.). Www.scienceandmediamuseum.org.uk. https://www.scienceandmediamuseum.org.uk/objects-and-stories/short-history-internet#:~:text=The%20packet%20switching%20method%20is


IP addresses (IPv4 and IPv6):
Internet Protocol or more commonly known as IP addresses is a unique identification number, which is assigned to all computers, however is not created randomly but through maths.
Whether it is through a computer, laptop, tablets, toys etc every device with an internet connection will have this IP address associated to it and there are reasons for this with the most common task is to have the IP to identify the host or a network, or identifying the particular location of the device (A Brief Introduction to the World of IP Addresses | Tripwire, n.d.).


The difference between IPv4 and IPv6 is the age and capability of each. The IPv4 is the older of the two and has space up to 4 billion IP addresses, whereas the IPv6 holds space for trillions - ultimately replacing IPv4. By IPv6 having the address capacity of 8 sets of 4 characters (32 total, letters and numerals) separated by a colon, meanwhile IPv4 is at most 4 sets of 3 (12 numbers only) separated by a period.


The main purpose of IP addresses is being able to map out the web and send data to the right place, without this the internet would not be able to fulfil your data requests - you would not even be able to use social media, check your emails or browse the internet without it (What Is an IP Address and How Does It Work?, n.d.)


If you want to find your IP address, you can simply type "What's my IP" into Google and it will display it amongst the top search results.


##### Reference
A Brief Introduction to the World of IP Addresses | Tripwire. (n.d.). Www.tripwire.com. https://www.tripwire.com/state-of-security/brief-introduction-world-ip-addresses


What Is an IP Address and How Does It Work? (n.d.). What Is an IP Address and How Does It Work? https://www.avg.com/en/signal/what-is-an-ip-address


Routes and routing:
So far we have spoken about Packets or packet-switching and Internet Protocols (IP's), these are both needing to be used when we are talking about routes and routing. When packet-switching, routing selects the parts for IP packets to travel from their origin to the destination - these decisions are made through specialised pieces of network hardware called routers (cloudflare.com, n.d).


The importance of this comes does the efficiency and how this impacts the network communication, without routing network communications you will find yourself with network failures, website pages not loading and server crashed as it can't handle the large number of users (AWS, 2023) - ever tried to get on ticketek to get Taylor Swift tickets, this is a result of an overloaded network.


The way that this technology has evolved over the decades since its innovation is due to the creation of cloud infrastructures, involving computing resources and hardware hosted by third-party cloud providers. By having this cloud infrastructure in place you are connected virtually and the business is able to use this resource to host and run applications, which many organisations now have a hybrid approach when it comes to these networks - both on premises networks with internal hardware and cloud networks (AWS, 2023).


##### Reference
https://www.cloudflare.com/en-au/learning/network-layer/what-is-routing/


AWS. (2023). What is Routing - Beginner’s Guide to Network Routing - AWS. Amazon Web Services, Inc. https://aws.amazon.com/what-is/routing/


Domains and DNS:
The Domain Name Systems or more commonly known as DNS is the phonebook of the internet. Domain names such as coderacademy.com.au or facebook.com are an example of this, however do not get this mixed up with URL's which is a string of the website https://coderacademy.edu.au/web-development/bootcamp. DNS uses IP addresses to translate these domain names so browsers can load internet sources.
As we spoke about IP addresses and the multitude of IP addresses that are possible (trillions), DNS removes the need for humans to memorise IP addresses (Cloudflare, n.d.).


##### References
https://www.cloudflare.com/en-au/learning/dns/glossary/what-is-a-domain-name/


## Q3
- TCP
- HTTP and HTTPS
- Web Browsers (requests, rendering and developer tools)


#### Answer
TCP:
Transmission Control Protocol or TCP for short is designed to send packets across the internet, enabling message exchanged over the network between programs and devices - this ensures the data and messages a successful delivery. This method of TCP is one of the most commonly used protocols within digital network communications and end-to-end data delivery.


TCP and IP's have a similar relationship, where IP addresses send packets of informations and ensures that these arrive at their destination, TCP however is more of the assembler aspect of this relationship where it assembles all of the packets together in the right order as well as asks for missing parts of the message to be resent(cloudflare, n.d).


##### Reference
https://www.cloudflare.com/en-au/learning/ddos/glossary/tcp-ip/


HTTP and HTTPS:
HTTP stands for Hypertext Transfer Protocol and this comes into two forms, HTTP being not secure and HTTPS connections being secure and has a layer of encryption through SSL and TLS, which HTTP sites change to HTTPS once they gain a SSL certification (Chipeta, 2023).


Cloudflare, n.d. dispicts how HTTP and HTTPS are different in the following example.


When HTTP request is sent from its origin server, it sends a HTTP response;


"GET /hello.txt HTTP/1.1
User-Agent: curl/7.63.0 libcurl/7.63.0 OpenSSL/1.1.l zlib/1.2.11
Host: www.example.com
Accept-Language: en"


With the added encryption of HTTPS, the attacker receives something that displays;


"t8Fw6T8UV81pQfyhDkhebbz7+oiwldr1j2gHBB3L3RFTRsQCpaSnSBZ78Vme+DpDVJPvZdZUZHpzbbcqmSW1+3xXGsERHg9YDmpYk0VVDiRvw1H5miNieJeJ/FNUjgH0BmVRWII6+T4MnDwmCMZUI/orxP3HGwYCSIvyzS3MpmmSe4iaWKCOHQ=="


If you are a visual learner and want to understand further, check out https://howhttps.works/why-do-we-need-https/


##### Reference
https://www.cloudflare.com/en-au/learning/ssl/why-is-http-not-secure/


Chipeta, C. (2023, February 7). What is HTTPS? How it Works and Why It’s So Important | UpGuard. Www.upguard.com. https://www.upguard.com/blog/what-is-https


https://howhttps.works/why-do-we-need-https/


Web Browsers (requests, rendering and developer tools):
We can all agree that the two things that we want from a functioning website is for the content to be fast to load and smooth to interact with, these are the things that developers strive to achieve and they do this by understanding how performance can be improved and perceived.


Due to wanting to content from a website to load fast and smooth, developers have two major issues to achieving this and that is latency and how these browsers are single threaded, with the former being the biggest threat as the developers goal to to make the site load as fast as possible or at least appear like it is loading as fast as possible (Populating the Page: How Browsers Work - Web Performance | MDN, n.d.).


##### Reference
Populating the page: how browsers work - Web Performance | MDN. (n.d.). Developer.mozilla.org. https://developer.mozilla.org/en-US/docs/Web/Performance/How_browsers_work


## Q4


#### Answer
Before understanding what the key differences are between "interpreters" and compilers", we should understand what they are.


These concepts are both language processors and are used to convert codes written in high-level language into machine language codes which interprets language understood by humans and is converted into what the machine understand which is 0's and 1's. These two conecpts are translated differently - compiler translated the machine code into the program before it runs, whereas interpreter translates machine code line by line as the code runs.


The key differences involved between interpreters and compilers is; firstly the programming languages, where programming languages that use interpreters are JavaScript, Python, Ruby whereas C, C++, Java use compilers.
Another major key difference to consider is that it takes a lesser amount of time to analyse the source code using interpreters, though the overall execution is comparatively slower; this is opposite of a compiler where it it would analyse the source code taking a larger amount of time, however it would be comparatively faster than interpreters (Sassi, 2023).


Another difference to note is the types of Interpreters and Compilers there are; interpreters have 4 common types, whereas compilers have 10.


The reasons why these concepts and processors are important is compilers help catch syntax and semantic errors before we run the code, this inturn saves time and prevents crashes; interpreters on the other hand help clarify misunderstandings, interpret expressions and ensure the correct and intended message is accurately transferred and conveyed.


#### Reference
What Is a Compiler? (Definition, How It Works) | Built In. (n.d.). Builtin.com. Retrieved June 6, 2024, from https://builtin.com/software-engineering-perspectives/compiler#


Do I need an Interpreter? 7 Ways you can benefit from Interpreting Services. (n.d.). Www.globalinterpretingservices.com. https://www.globalinterpretingservices.com/blog/do-i-need-an-interpreter#:~:text=They%20can%20help%20to%20clarify


Sassi, R. B. (2023, April 24). Compiler vs. Interpreter in Programming | Built in. Builtin.com. https://builtin.com/software-engineering-perspectives/compiler-vs-interpreter


## Q5


#### Answer
In 2022 the latest survey report from Statista highlighted the programming languages most preferred by developers. Out of the 700+ languages that there are, two of the most common languages I will be speaking about today will be;
- JavaScript: at 65.36% preference, this is a high-level, object-oriented programming language built mostly for apps and follows the ECMAScript protocols.
- Python: at 48.07% preference amongst developers, this is a high-level and general purpose programming language which includes structured, functional and object-oriented paradigms.


The benefits and drawbacks of each is as follows;


JavaScript is comparatively fast and smooth allowing you to render with consistent results across all browsers. Due to the ease of the implementation and learning aspect of JavaScript this has also created a large support community.
Although there are some great benefits with JavaScript, it has drawbacks including; A single error in JavaScript code can stop rendering the entire website, each browser interprets JavaScript differently as well as the code is visible and accessible to everyone.


However, although there may be some drawbacks, it still remains the most popular and demanded programming language with over 40% of recruiters across the globe seeking to hire.

Due to the simple and easy syntax of Python, it is known in the industry to be the best programming lanuage for beginner developers. Developers may choose Python, due to how it is easily readable and facilitates dynamic coding, the main benefit  however is how it follows a step-by-step debugging process - what this means is that the execution stops as soon as an error occurs, not allowing this to pass to the console. Though this is a great benefit, Python may not be able to challenge the developers in a way that will positively impact their skills due to Python being more intuitive than most other languages. Those that do use Python experience it being slower than other languages like C or C++ and experience testing to be complex and tedious with its Runtime errors.


Similar to JavaScript, Python has its deal of benefits and drawbacks, however it still has a 38% demand amongst recruiters through the top software development companies world-wide.


##### Reference
Chavda, S. (2023, January 17). The pro’s and con’s of different programming languages and frameworks. Whitelotus Corporation. https://www.whitelotuscorporation.com/pros-and-cons-of-different-programming-languages-and-frameworks/


## Q6


#### Response
Hello Alex,


I really appreciate your reaching out to me.


My name is Jesse and I will be able to assist you and Super Awesome Museum (SAM), with all your website development needs.


So we can begin, I am wanting to clarify my understanding first and understand what you are needing.


Firstly; Museums are really cool and we should have SAM displayed on the first page. This will bring customers to know the facade of the building and will start to draw them into the website.


Secondly; we need to have different pages to know where the customers are going and what information they can collect;
   - pages being:
       - artefacts - for items that were made intentionally and are relatively old
       - objects - for items that were made without human intervention, more of your natural objects
       - paraphernalia - those items that are a conduit and needed to be used with certain activities.
       - about page - to know more about the museum and its conception
       - contact page - this can have the details of how to locate the museum, contact details and even a submission enquiries form.


Lastly and most importantly, to make sure that SAM is visible and marketable, it is important that we have a logo - if you do not have one of these yet we are also able to help and assist with this.


Please let me know your thoughts in regards to this, if you have any questions, concerns or issues please reach out and we can smooth those out.


Kind regards,


Jesse
Web Developer


## Q7



#### Answer
It is important to reflect on your past, whether that is something you had worked on, experienced or simply how you handled a situation. Although you are unable to change this from the past, you are able to reflect and understand how you would approach this scenario next time if and/or when you are faced with it.


The scenario I am bringing up is from the first project we have done, which was building the website portfolio with HTML/CSS. As mentioned, this was my first project and really my first sense of what coding is; so I had dealt with imposter syndrome and also a sense of not trusting my decision making.
Due to this, I made multiple changes throughout the project based on the appearance of the website, but the visual and coding aspect and got stuck on this for a long time.
However, if I were to go over this again I would create a reflection technique from what I could have improved on and what I would keep.


Using the Gibbs Cycle we will go through 5 steps; Description, Feelings, Evaluation, Conclusions and Action (Mind Tools Content Team, 2022).


Step 1: Description - What Happened |
As mentioned, this is due to the project where we built the website portfolio with HTML/CSS having 2 weeks to complete and submit, this project had to have a variety of requirements including media queries for different devices, be visually appealing and also documentation in terms of a README.md file.


Step 2: Feelings - Thought during |
Throughout the project and throughout the course in general, I have had strong feelings of being overwhelmed and also a sense of imposter syndrome - however, I understand that these things are normal when you are trying something new.
During this time, I was indecisive of my choices throughout the project and changed the course of the project a few times, which ultimately led me to being behind.


Step 3: Evaluation - What approaches worked |
Going into this project, even though overwhelmed and unsure of myself I was able to move forward as I know that I wouldn't be this way if this didn't mean something to me. Yes, these feelings crop up time and time and perhaps even while I am writing this sentence, however my approach was if something fails, understand why and apply what you learnt for the next time.
After a while of experimenting with new code and concepts like animation, keyframes and media queries it came easier and more enjoyable.
However, at the end of the day I was unfortunately still behind in my project and missed adding all of the media queries to the project.


Step 4: Conclusions - What has been collected |
I think in life we get in our heads and feelings surrounding the negative and what we could have done better; however, we should focus on the 9/10 things we did correct and are happy with. I am disappointed that the media queries weren't done in full and they way I wanted them, however I am absolutely happy about what I was able to build after only 3 weeks of going through the course.
If I was faced with the same situation again, I would be focusing on the aspects that are necessary to be done and not focus on how pretty that website needs to be, media queries would be something to work on in the earlier stages of the project.


Step 5: Action - A plan |
There is no point going through a reflective cycle if we do not put in place actions and an action plan moving forward.
If I were to do this project again, I would plan from start to finish on what I want the project to be and how this is going to be possible and stick with this as if a client or employer were to ask something a certain way we would deliver it with those requirements.


##### References
Mind Tools Content Team. (2022). Gibbs Reflective Cycle. Www.mindtools.com; Mind Tools Content Team. https://www.mindtools.com/ano9qiu/gibbs-reflective-cycle


## Q8


#### Answer
Career growth is something that can be inherently connected through multiple ways; this could be something that you may be working towards in your current job, or you may be looking for other work and studying to accomplish that career switch; either way it is important to create successful and dynamic relations and not burning bridges.


Keeping current connections and rapport with people is a great way to move across different paths; however we can always create these new connections and build our network.
When building new networks, there are a few things that are important; to be yourself and to have an open mind to any opportunity - to build these opportunities I would recommend the following strategies;
   - Attend industry events to meet professionals
   - Join tech organisations and use social media like linkedin and facebook for connections
   - Improve your skills by going to events like competitions and hackathons as you will learn something new and meet potential employers.


There are plenty of other ways to get your foot in the door using new and old connections through networking; it just depends on what you're going to do with it once your foot is there.


## Q9



#### Answer
ChatGPT has become widely used amongst; students, professionals, curious minds and has been used as a framework for many people's daily life.


In fact, I even asked chatGPT this question to understand what it had to say;


"Language-learning models like ChatGPT significantly benefit written and technical works such as reports and software projects by generating content like text and code snippets, enhancing clarity through improved structure and readability suggestions, efficiently retrieving and summarising information for research and technical details, supporting translation tasks for multilingual documentation, automating routine writing tasks and report generation, aiding in code review and quality assurance processes, providing interactive support for software usage queries, and facilitating collaboration among team members." (chatGPT, 2024).


Now, I don't know about you - but that was a lot of information all at once and feels like a computer spat it out.


Although chatGPT brought up some great points; in a report done from January 2024 (Samala, A et al, 2024) explains that the advantages of language-learning tools like chatGPT is the capacity to provide personalised and adaptive learning whilst also having instant feedback and being accessible.
However, it can be noted that the drawbacks are the emotional intelligence, overreliance of the technology and privacy concerns; this also combined with the legal and ethical impacts on where the information is coming from and whether it is factual,
This will be covered in the next portion of this workbook.

##### References
Samala, Agariadne & Zhai, Xiaoming & Aoki, Kumiko & Bojic, Ljubisa & Zikic, Simona. (2024). An In-Depth Review of ChatGPT’s Pros and Cons for Learning and Teaching in Education. International Journal of Interactive Mobile Technologies (iJIM). 18. 96-117. 10.3991/ijim.v18i02.46509.


## Q10

#### Answer
As we have touched upon the uses, the benefits and the drawbacks of chatGPT, it is important to understand how this advanced piece of technology is growing in a way that may impact legal and ethical behaviours.


Again, before discussing this in depth; I wanted to see what chatGPT had to say in terms of what it thinks about how it itself has legal and ethical impacts.


chatGPT explains; "The use of language-learning models like ChatGPT in written and technical works presents legal challenges such as intellectual property rights, privacy concerns, liability for errors, and compliance with regulations. Ethical considerations include addressing biases in training data, ensuring transparency in AI use, accountability for AI decisions, managing impacts on employment, and respecting human rights in AI applications".


Once again, this information removed the human emotional intelligence and the nuances of the question that we are asking.


However, with chatGPT there is no way of understanding where they are referencing the information that they have provided - this leaves the user not able to know whether the information is biassed, whether it is spreading misinformation and how it handles the privacy and data.


Language-learning tools can have their own consequences - both positive and negative. Research that was regarding chatGPT in Higher Education (Hasanein AM, et al, 2023) shows that these tool show 6 positive and 6 negative consequences; "positive being time saving, reduced anxiety, improving language skills, self-confidence, punctual submission and non-academic support" (Hasanein AM, et al, 2023).
However, the negative consequences demonstrate that these tools create an area of concern when it comes to, "overreliance, the loss of academic integrity, lack of quality and accuracy, damaged learning outcomes, potential bias and deteriorated student skills sets" (Hasanein AM, et al, 2023).


In conclusion, these language learning tools are leading innovation technology, however it needs to be noted that it can come with its own legal and ethical impacts as well as positive and negative consequences.


##### Reference
Hasanein AM, Sobaih AEE. Drivers and Consequences of ChatGPT Use in Higher Education: Key Stakeholder Perspectives. Eur J Investig Health Psychol Educ. 2023 Nov 9;13(11):2599-2614. doi: 10.3390/ejihpe13110181. PMID: 37998071; PMCID: PMC10670526.


## Q11

- soft skills
- hard skills


#### Answer
It is important that someone coming into the software development workplace have a well rounded sense of skills, these being both soft and hard skills.


When we are talking about soft skills; these are more of your interpersonal skills that are defined by communication, patience, emotional intelligence and how you work in a team. These skills are also associated with one's personality which can be those who are more extroverted (10 Soft Skills Every Software Engineer Should Have - Trio, 2022).


With soft skills being your interpersonal skills, hard skills refer to the more technical side of your skills. Hard skills throughout a software development workplace would be testing and debugging, mobile development, cloud computing and security (Eilers, 2021).


##### Reference
10 Soft Skills Every Software Engineer Should Have - Trio. (2022, January 6). Trio.dev. https://trio.dev/software-engineer-soft-skills/


Eilers, C. (2021, March 4). 10 Hard and Soft Skills to Put On a Resume for Software Developer Jobs. Arc Talent Career Blog. https://arc.dev/talent-blog/skills-to-put-on-a-resume/


## Q12


#### Answer
Throughout most businesses, you will run into an array of different people, with different job roles - the main objective is to make your company as diverse as possible.


Amongst this array of roles, the following are the most noted;
- Software Developer:
   - This is a role that involves the front-end and the back-end, the role is primary to solve any emerging technical problems throughout the development cycle.


- Software Architect:
   - An expert-level software engineer who focuses on the software design decisions. This role is needed if you deal with complex requirements of legacy software - a big part of software architect is the decision making behind which services are needed and how integration should work.


- Product Owner:
   - At the beginning of creating something new and developing it or even expanding on the development of another product, there will be a product owner who will hold the responsibility for the vision and evolution of the product.
   This role balances the need of the business, market trends and they also define and shape business strategy.


- Business Analyst:
   - While the PO is the one that balances the need of the business through development of product, Business Analysts are the ones that dive deep into workflows and analyse stakeholder feedback; this inturn enriches the product development team.


   - BA and PO are similar with the key difference being BA is more focused on the projects and bridges the gap between customer and a team, however the PO is more customer-oriented and provides the vision of a product.
          
           -(Shashkina, 2022)


Throughout a software company, there are many other roles both on the engineering side as well as on the commercial and business side, it is important for both of these sides to come together and be homogenous.


##### References
Shashkina, V. (2022, August 31). Software Development Team Structure: Roles & Responsibilities. ITRex. https://itrexgroup.com/blog/software-development-team-structure/

