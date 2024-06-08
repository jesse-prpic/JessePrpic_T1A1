# Jesse Prpic Term 1 Assignment 1 - Workbook

## Q1
### Identify and explain common and important components and concepts of web development markup language

#### Answer


##### Reference


## Q2
### Define the features of the following technologies that are essential in terms of the development of the internet:
- Packets
- IP addresses (IPv4 and IPv6)
- routes and routing
- domains and DNS

Explain how each technology has contributed to the development of the internet.

#### Answer
Packets
A packet is a small chunk of segments (around 1500 bytes) which is from a larger message, these chunks of segments consist of two portions, the header and the payload. Header contains information such as its origin aand destination IP address and the payload refers to the actual data.
Once the payload reaches its destination it will recombine.

An analogy of this I found useful is;
"Suppose Alice is writing a letter to Bob, but Bob's mail slot is only wide enough to accept envelopes the size of a small index card. Instead of writing her letter on normal paper and then trying to stuff it through the mail slot, Alice divides her letter into much shorter sections, each a few words long, and writes these sections out on index cards. She delivers the group of cards to Bob, who puts them in order to read the whole message" (https://www.cloudflare.com/en-au/learning/network-layer/what-is-a-packet/, 2024).

Packet and packet swtiching is a way to allow data to be sent securely, the worlds first computer network was produced in 1969 and is the basis on which the internet still works today.

##### Reference
https://www.cloudflare.com/en-au/learning/network-layer/what-is-a-packet/

A short history of the internet | National Science and Media Museum. (n.d.). Www.scienceandmediamuseum.org.uk. https://www.scienceandmediamuseum.org.uk/objects-and-stories/short-history-internet#:~:text=The%20packet%20switching%20method%20is

IP addresses (IPv4 and IPv6)
Internet Protocol or more commonly known as IP addresses is a unique identification number, which is assigned to all computers, however is not created randomly but through math. 
Whether it is through a computer, laptop, tablets, toys etc every device with an internet connection will have this IP address associated to it and there are reasons for this with the most common task is to have the IP to identify the host or a network, or identifying the particular location of the device (A Brief Introduction to the World of IP Addresses | Tripwire, n.d.).

The difference between IPv4 and IPv6 is the age and capability of each, the IPv4 is the older of the two and has space up to 4 billion IP addresses, whereas the IPv6 holds space for trillions - ultimately replacing IPv4. This is due to IPv6 addresses being able to have the capacity of 8 sets of 4 character (32 total, letters and numerals) separated by a colon, meanwhile IPv4 is at most 4 sets of 3 (12 numbers only) separated by a period.

The main purpose of IP addresses is to map the web and send data to the right place, without this the internet would not be able to fulful your data requests - you would not even be able to use social media, check your emails or browse the internet without it (What Is an IP Address and How Does It Work?, n.d.)

If you want to find your IP address, you can simply type "What's my IP" into Google and it will display it amongst the top search results.

##### Reference
A Brief Introduction to the World of IP Addresses | Tripwire. (n.d.). Www.tripwire.com. https://www.tripwire.com/state-of-security/brief-introduction-world-ip-addresses

What Is an IP Address and How Does It Work? (n.d.). What Is an IP Address and How Does It Work? https://www.avg.com/en/signal/what-is-an-ip-address

Routes and routing
So far we have spoken about Packets or packet-switching and Internet Protocols (IP's), these are both needing to be used when we are talking about routes and routing. When packet-switching, routing selects the parths for IP packts to travel from their origin to the destination - these decisions are made through specialisd pieces of network hardware called routers (cloudflare.com, n.d).

The importance of this comes does the efficiency and how this impacts the network communication, without routing network communications you will find yourself with network failures, website pages not loading and sever crashed as it can't handle the large number of users (AWS, 2023) - ever tried to get on ticketek to get Taylor Swift tickets, this is a result of an overloaded network.

The way that this technology has evolved over the decades since its innovation is due to the creation of cloud infrastructures, involving computing resources and hardware hosted by third-party cloud providers. By having this cloud infrastructure in place you are connected virtually and the business is able to use this resource to host and run applications, which many organizations now have a hybrid approach when it comes to these networks - both on premises networks with internal hardware and cloud networks (AWS, 2023).

##### Reference
https://www.cloudflare.com/en-au/learning/network-layer/what-is-routing/

AWS. (2023). What is Routing - Beginner’s Guide to Network Routing - AWS. Amazon Web Services, Inc. https://aws.amazon.com/what-is/routing/

Domains and DNS
The Domain Name Systems or more commonly known as DNS is the phonebook of the internet. Domain names such as coderacademy.com.au or facebook.com are an example of this, however do not get this mixed up with URL's which is a string of the website https://coderacademy.edu.au/web-development/bootcamp. DNS uses IP addresses to translate these domain names so browsers can load internet sources.
As we spoke about regarding IP addresses and the multitude of IP addresses that are possible (trillions), DNS removes the need for humans to memorise IP addresses (Cloudflare, n.d.).

(expand

##### References
https://www.cloudflare.com/en-au/learning/dns/glossary/what-is-a-domain-name/

## Q3
### Define and features of the following technologies that are essential in terms of the development of the internet:
- TCP
- HTTP and HTTPS
- Web Browsers (requests, rendering and developer tools)

Explain how each technology has contributed to the development of client and server communication over the internet (50 - 150 words for each technology)

#### Answer
TCP
Transmission Control Protocol or TCP for short is designed to send packets across the internet, enabling programs and devices to exchange messages over a network - this ensures the successful delivery of data and messages. This method of TCP is one of the most commonly used protocols within digital networks communications and end-to-end data delivery.

TCP and IP's have a similar relationship, where IP addresses send packets of informations and ensures that these arrive at their destination, TCP however is more of the assembler aspect of this relationship where it assembles all of the packets together in the right order as well as asks for missing parts of the message to be resent(cloudflare, n.d).

(expand

##### Reference
https://www.cloudflare.com/en-au/learning/ddos/glossary/tcp-ip/

HTTP and HTTPS

##### Reference

Web Browsers (requests, rendering and developer tools)

##### Reference

## Q4
### Describe the features of "interpreters" and "compilers" and how they are different.

#### Answer
Before understanding what the key differences are between "interpreters" and compilers", we should understand what they are.

These concepts are both language processors and are used to convert codes written in high-level lanuage into machine language codes, this is basically stating that it interprets lanuage understood by humans and is converted into what the machine understand which is 0's and 1's, however these are translated differently - compiler is translated into machine code before the program runs, whilst interpreter translates into machine code line by line as the code runs.

The key differences involved between interpreters and compilers is; firstly the programming languages, where programs languages that use interpreters are JavaScript, Python, Ruby whereas C, C++, Java use compilers.
Another major key difference to consider is that it takes a lesser amount of time to analyze the source code using interpreters, though the overall execution is comparatively slower; this is opposite of a compiler where it it would analyze the source code taking a larger amount of time, however it would be comparatively faster than interpreters (Sassi, 2023).

Another difference to note is the types of Interpreters and Compilers there are; interpreters have 4 common types, whereas compilers have 10.

The reasons why these concepts and processors are important is compilers help catch syntax and semantic errors before we run the code, this inturn saves times and prevents crashes; interpreters on the other hand help clarify misunderstandings, interpret expressions and ensure the correct and intended message is accurately transformed and conveyed.

#### Reference
What Is a Compiler? (Definition, How It Works) | Built In. (n.d.). Builtin.com. Retrieved June 6, 2024, from https://builtin.com/software-engineering-perspectives/compiler#

Do I need an Interpreter? 7 Ways you can benefit from Interpreting Services. (n.d.). Www.globalinterpretingservices.com. https://www.globalinterpretingservices.com/blog/do-i-need-an-interpreter#:~:text=They%20can%20help%20to%20clarify

Sassi, R. B. (2023, April 24). Compiler vs. Interpreter in Programming | Built in. Builtin.com. https://builtin.com/software-engineering-perspectives/compiler-vs-interpreter


## Q5
### Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.

#### Answer
In 2022 the latest survey report from Statista highlighted the programming lanugages most preferred by developers. Out of the 700+ lanugages that there are, two of the most common lanuages I will be speaking about today will be;
- JavaScript: at 65.36% preference, this is a high-level, object-oriented programming lanugage built mostly for apps and follows the ECMAScript protocols.
- Python: at 48.07% preference amongst developers, this is a high-level and general purpose programming language which includes structured, functional and object-oriented paradigms.

The benefits and drawbacks of each is as follows;

JavaScript is comparatively fast and smmooth allowing you to render with consistent results across all browsers. Due to the ease of the implementation and learning aspect of JavaScript this has also created a large support community.
Although there are some great benefits with JavaScript, it has drawbacks including; A single error in JavaScript code can stop rendering the entire website, each browser interprets JavaScript differently as well as the code is visibile and accessible to to everyone.

However, although there may be some drawbacks, it still reamins the most popular and demanded programming lanuage with over 40% of recruiters across the globe were seeking to hire.

Python is known to be the best programmming language for any beginners that are starting in the Software Development space, this is because of its simple and easy syntax. Other reasons developers may to choose Python, is due to how it is easily readable and faciliates dynamic coding, however the main benefit when it comes to python is how it follows a step-by-step debugging process - what this means is that the execution stops as soon as an error occurs, not allowing this to pass to the console. Though this is a great benefit, Python may not be able to challenge the developers in a way that will positively impact their skills due to Python being more intuitive than most other lanugages. Those that do use Python experience it being slower than other lanuages like C or C++ and experience testing to be complex and tedious with its Runtime errors.

Similar to JavaScript, Python has its deal of benefits and drawbacks, however it still has a 38% demand amongst recruiters through the top software development companies world wide.

##### Reference
Chavda, S. (2023, January 17). The pro’s and con’s of different programming languages and frameworks. Whitelotus Corporation. https://www.whitelotuscorporation.com/pros-and-cons-of-different-programming-languages-and-frameworks/


## Q6
### A hypothetical client has sent you an email (shown in the Q6 Email section), asking for you to build them a website. Write an appropriate, professional email response that shows your understanding of the client’s needs for the website, as well as an understanding of appropriate technologies or tools needed to build the website yourself.	

## Hypothetical Client
Hello there

My name is Alex, and I’m the director of the Super Awesome Museum (SAM). We display a variety of interesting artefacts, objects, and paraphernalia about all sorts of things from all over the world.

I’m writing to you because the SAM needs a website. The museum is new in the city, we’re fully funded and don’t sell our items but we just need to encourage people to visit the museum.

We would need a website that showcases some of our interesting exhibits and items, helps people find their way to the museum, and helps people contact the museum.

We don’t know much about this website stuff - does this sound like something that you can do? 

Looking forward to hearing from you,

Alex

Director

Super Awesome Museum  

## Q7
### Think back to a scenario or situation in your own software development projects or work.
### Explain how you would do things differently if you had a chance to go through that scenario again, using an appropriate reflective cycle or reflection technique.
It is important to reflect on your past, whether that is something you had worked on, experienced or simply how you handled a situations. Although you are unable to change this from the past, you are able to reflect and understand how you would approach this scenario next time if and/or when you are faced with it.

The scenario I am bringing up is from the first project we have done, which was building the website portfolio with HTML/CSS. As mentioned, this was my first project and really my first sense of what coding is; so I had dealt with imposter syndrome and also a sense of not trusting my decision making.
Due to this, I made multiple changes throughout the project based on the appearance of the website, but the visual and coding aspect and got stuck on this for a long time.
However, if I were to go over this again I would create a reflection technique from what I could have improved on and what I would keep.

Using the Gibbs Cycle we will go through 5 steps; Description, Feelings, Evaluation, Conclusions and Action (Mind Tools Content Team, 2022).

Step 1: Description - What Happened
As mentioned, this is due to the project where we built the website portfolio with HTML/CSS having 2 weeks to complete and submit, this project had to have a variety of requirements including media queries for different devices, be visually appealing and also documentation in terms of a README.md file.

Step 2: Feelings - Thought during
Throughout the project and throughout the course in general, I have had strong feelings of being overwhelmed and also a sense of imposter syndrome - however, I understand that these things are normal when you are trying something new.
During this time, I was indecisive of my choices throughout the project and changed the course of the project a few times, which ultimately led me to being behind.

Step 3: Evaluation - What approaches worked
Going into this project, even though overwhelmed and unsre of myself I was able to move forward as I know that I wouldn't be this way if this didn't mean something to me. Yes, these feelings crop up time and time and perhaps even while I am writing this sentence, however my approach was if something fails, understand why and apply what you learnt for the next time.
After a while of experimenting with new code and concepts like animation, keyframes and media queries it came easier and more enjoyable.
However, at the end of the day I was unfortunately still behind in my project and missed adding all of the media queries to the project.

Step 4: Conclusions - Whats been collected
I think in life we get in our heads and feelings surrounding the negative and what we could have done better; however, we should focus on the 9/10 things we did correct and are happy with. I am disappointed that the media queries weren't done in full and how I wanted them, however I am absolutely happy about how I was able to build a working and functioning website after only 3 weeks of going the course.
If I was faced with the same situation again, I would be focusing on the aspects that are necessary to be done and not focus on how pretty that website needs to be, media queries would be something to work on in the earlier stages of the project.

Step 5: Action - A plan
There is no point going through a reflective cycle if we do not put in place actions and an action plan moving forward. 
If I were to do this project again, I would plan from start to finish on what I want the project to be and how this is going to be possible and stick with this as if a client or employer were to ask something a certain way we would deliver it with those requirements.

##### References
Mind Tools Content Team. (2022). Gibbs Reflective Cycle. Www.mindtools.com; Mind Tools Content Team. https://www.mindtools.com/ano9qiu/gibbs-reflective-cycle

## Q8
### A large part of career growth as an information technology professional happens through networking and workshops, often found at online or in-person events or workshops. 

### Create an action plan that identifies several relevant networking opportunities for you to participate in or attend, and add some information about what you expect to gain or grow through each item in the action plan.

## Q9
### Explain the uses of language-learning model technologies (such as ChatGPT) on written and technical works, such as reports and software projects.	

## Q10
### Explain the legal and ethical impacts of the usage of language-learning model technologies (such as ChatGPT) in written and technical works, such as reports and software projects.

## Q11
### Explain multiple skills from each of the categories below, and how they're useful to a software development workplace
- soft skills
- hard skills

## Q12
### Explain multiple roles or job positions that would be found in a medium-sized software development company