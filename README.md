# T1A1 Workbook

## Q1. Identify and explain common and important components and concepts of web development markup languages


_MARKUP LANGUAGES_




When documents are created, notation methods are employed within the formatting framework, which allow one to delineate how each segment of a document is meant to be formatted. The term "markup" is derived from the practice of 'marking up' manuscripts during the editing process (Mendez, 2014). Within programming and web development exist a "standard text-encoding system" made up of symbols, which are used to define the structure and formatting of the document (Gregersen, 2024). Markup language is static, not dynamic; meaning this syntax is used to control the structure, but is not designed to be viewed in the exported document. This language uses tags, which are interpreted by operating systems to translate the document into how it should look when displayed on a monitor (Gregersen, 2024).




Here are some examples of some of the most commonly using markup languages within web development:




> HTML5 (Hypertext Markup Language)


HTML5, is the most widely used markup language and the backbone of web pages, consists of tags, attributes, elements, and a hierarchical document structure. Tags, enclosed in angle brackets, mark the beginning and end of elements. Attributes provide additional information within tags. Elements organize content and include headings denoting different importance levels. Hyperlinks, lists, and images are key components for navigation and visual presentation. Mastering these basics is crucial for creating well-structured web pages.




> XML (Extendable Markup Language)


XML, a data storage and transport language, comprises tags, attributes, elements, and hierarchical document structures. Tags define elements, attributes provide extra information, and elements can be nested to form hierarchies. XML documents can be validated against schemas, use namespaces to avoid conflicts, and must adhere to well-formedness rules.  The annotation and tagging methods mirror that of HTML, however, XML tags are _not_ predefined in the same manner as HTML tags: in this way, it's more malleable as it allows the user to create their own tags to describe their data (Inouye, 2022).


> SGML (Standard Generalized Markup Language)


SGML, the Standard Generalized Markup Language, emerged as an international standard for metalanguages, originating from developers at IBM with the goal of creating large, intricate documents that could be readily understood and broadly disseminated (Inouye, 2022). At its core, SGML comprises notations designed to articulate the purpose of a text segment and how it should be presented. Crucially, SGML is instrumental in crafting Document Type Definitions (DTDs), which delineate the necessary elements for a document, such as the obligatory presence of a < title > tag.




> SVG (Scalable Vector Graphics)


SVG, or Scalable Vector Graphics, serves as an XML-based markup language aimed at delineating two-dimensional vector graphics. As a text-centric open Web standard, SVG provides a framework for articulating images that can be rendered cleanly at varying sizes, specifically engineered to seamlessly integrate with other standard web markups like CSS and Javascript (Ferraiolo 2000). One of its primary strengths lies in its ability to adapt images to different dimensions without compromising their quality, ensuring a consistent visual experience across various display sizes. Moreover, SVG facilitates effortless localization by enabling straightforward updates to the embedded text within the graphics, further enhancing its versatility and utility in web development contexts.





## Q2. Define the features of the following technologies that are essential in terms of the development of the internet:
> packets
> IP addresses (IPv4 and IPv6)
> routers and routing
> domains and DNS


## Explain how each technology has contributed to the development of the internet.




> Packets


'Packets' or 'Network Packets' are single units of data communicated over a TCP/IP network. Devices utilising a TCP/IP network divide data into smaller pieces in order to accommodate various bandwidths. This will provide multiple potential routes for a destination and will allow for retransmission of pieces of data that get lost or interrupted. Packets were evolved due to the need for the internet to become wireless (Yasar et al., 2022).




> IP addresses


An Internet Protocol Address (or IP address) is a numeric label assigned to every device connected to the internet. They allow for the transfer of data between two connected devices, thus allowing different devices to be in communication with one another. Although many IP addresses are public (external), meaning they can be accessed via the internet from any computer in the world, they can also be private (internal), meaning they can only be reached by other devices on the same network. Furthermore, IP addresses can be either static or dynamic: Dynamic IP addresses have the ability to be changed, whereas static addresses will remain the same as long as the provider or server remain the same.




There are 2 versions of IP address:


>> _IPv4_
   IPv4 was launched in 1983 and was the very first version to be utilised. IPv4 uses a 32-bit address, providing almost 4.3 billion unique addresses. These addresses are composed solely of numbers.


>> _IPv6_
   IPv6 is a newer version of IP that uses a 128-bit address format, and includes both numbers and letters within the address. It was initially developed by the Internet Engineering Task Force (IETF) in order to deal with the problem of IPv4 exhaustion and address depletion that was occurring. As well as providing increased address space, it also introduced improved header format, extension of protocol and additional functionalities.





> Routers and Routing


Routers are devices that mediate transmission routes of data packets over various communication networks. It works by directing incoming and outgoing internet traffic between connected devices and networks (Feamster, 2004). Similarly, the term "routing" refers to the process of selecting a path across one or several networks: the routers themselves are the hardware used to facilitate this process.





> Domains and DNS


The Domain Name System (DNS) translates "human-readable" domain names into "machine-readable" IP addresses: This means that every website can be allocated both an IP address and domain name, both of which can direct the user to the same web page (Mockapetris et al., 1988). This means that instead of having to remember a long, complex string of numbers to access a site, one can simply use a domain name like example.com to load the same resource: this will be translated by a DNS server into the corresponding IP address.






## Q3. Define the features of the following technologies that are essential in terms of the development of the internet:
> TCP
> HTTP and HTTPS
> web browsers (requests, rendering and developer tools)


## Explain how each technology has contributed to the development of client and server communication over the internet (50 - 150 words for each technology)


> TCP


TCP stands for Transmission Control Protocol and is one of the main protocols that make up the Internet protocol suite. The TCP/IP stack implements a series of protocol layers for networks, which in turn allow communication between any connected device. TCP is a communication-based protocol layer between the "Application" and "Network" layers of the stack, and aids in the exchanging of messages between devices over a common network. Before the introduction of TCP, UDP (User Datagram Protocol) was the alternative protocol option for sending data across a network: This is a connectionless protocol, devoid of error-checking or error recovery services (Gorlaski 2008). While UDP can often execute faster data transfer, it's at the cost of establishing a less firm connection and  forgoing congestion control and error support (Gorlaski 2008). In contrast, TCP is considered reliable in guaranteeing the delivery of data to the correct destination, as well as providing the advantage of flow control mechanism and retransmission of lost data packets (Gorlaski 2008). With the ever-increasing demand for widespread multimedia use, the connection-oriented and flexible nature of TCP has greatly contributed to providing more efficient, robust and safer client-server communication.




> HTTP and HTTPs


Similarly to TCP, the introduction of HTTP and HTTPs has revolutionised client-server communication by facilitating efficient and secure exchange of information over the internet. During the establishment of the WorldWideWeb project in 1990, Sir Tim Berners-Lee generated the first version of the Hypertext Transfer Protocol (Cox et al., 2012). Since then, HTTP has become a standardised protocol for client-server communication: its ability to support various types of content and interactive multimedia makes it a flexible and versatile option. Furthermore, its stateless communication makes it highly scalable, allowing servers to easily handle large numbers of concurrent requests (Cox et al., 2012). While HTTP is encoded, HTTPS provides a secure, encrypted version of this protocol; requiring authentication (SSL/TLS protocols) to ensure confidentiality and integrity of data exchanged over a secure network (Barlen & Blankertz, 2005). This encryption protects sensitive information, prevents data manipulation and provides a barrier to malicious hacking.




> Web browsers


Web browsers are software applications which retrieve information from remote servers and render the document to display on screen (Grosskurth 2006). Now the most widely used software application, web browsers, their mechanisms and their in-built features have revolutionised client-server communication over the internet.
Browsers implement a series of "subsystems" that have enhanced this communication:


1) The User Interface is the layer between the user and the engine, and outlines features such as toolbars, visual page-load progress, smart download handling, preferences and printing (Grosskurth 2006).


2) The Browser Engine is an embeddable element providing a high-level interface to the Rendering Engine. It loads the URI provided and facilitates “primitive browsing actions" (Grosskurth 2006).


3) The Rendering Engine is crucial in rendering the information provided by the URI and converting it into a visual display.Browsers use rendering engines such as Blink, Webkit or Gecko to interpret/display HTML, CSS + Javascript code received from servers. This subsystem is also responsible for calculating page layouts (Grosskurth 2006).


4) The Networking layer handles the data flow across networks and translates necessary characters. This feature manages the sending and fetching of HTTP requests from clients to servers to deliver web resources like HTML docs, images, scripts and stylesheets.


6. Web Storing and Caching - "Browsers support various mechanisms for storing data locally, such as cookies, localStorage, and sessionStorage. These storage mechanisms enable web applications to cache resources, store user preferences, and maintain session state, enhancing performance and providing offline capabilities."


Although there are more subsystems, these are 4 general categories that provide insight into the complexities of web browsers and the interplay of these features in order to provide us with efficient client-server communications. There are other in-built features that, as software developers, can aid us: For example, most modern browsers have in-built developer tools that provide the user with full breakdown of the code elements, network requests and performance metrics. The accessibility of these tools have empowered developers globally with their own debugging and leading to the creation of more complex web applications.


Some other browser features that have enhanced client-server communication are cross-origin sharing, asynchronous request handling, web caching/cookies and the introduction of push notifications.






## Q4. Describe the features of interpreters and compilers and how they are different.




When communicating with one another in human languages, two individuals attempting to communicate in different languages require an interpreter in order to make sense of the conversation. Similarly, programming languages are human-readable languages which require a translator in order to properly communicate with a computer. Both interpreters and compilers are features designed to convert source code into object code (Agarwal, 2009).


> Compilers

Compilers translate high-level language into low-level machine or assembly languages so that the computer can understand the instructions. Compilers work by looking at the source code in its entirety (Agarwal, 2009). Despite this process, it operates quicker than an interpreter and it is advantageous in its in-built debugging tools; thus, obtaining the ability to correct syntax and semantic errors easily. From a client perspective, it's a convenient option in that it doesn't require third party installation in order to be launched (ref). Despite this potential advantage, this could also lead to system compatibility issues. Furthermore, the way in which it goes through the entire program results in a longer run-time and occupies more memory in comparison to interpreters (Agarwal, 2009).




> Interpreters

Conversely, interpreters work by translating and executing each line of source code one at a time, consecutively. This fact means that overall debugging is easier, as it can identify errors immediately (BasuMallick, 2023). Interpreters run spontaneously, are more flexible and avoid occupying additional memory space (BasuMallick, 2023). However, this feature also has its drawbacks; for example, should an interruption occur during the process, the mechanism will cause the interpreter to reset and start again from the beginning (ref). Furthermore, an individual seeking to access the source code will require installation of an interpreter in order to retrieve and execute the code (BasuMallick, 2023). Lastly, it's not as secure.






## Q5. Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.




_1. Python_



> Advantages


1. Beginner Friendly
   The simple syntax makes this language suitable for programming beginners to understand, write and debug (Gavrilova, 2023). This feature also makes it versatile, meaning it can be used in an array of different applications and disciplines; such as web development, data science or bioinformatics.


2. Highly Scalable + in-built libraries
   Python can handle large amounts of data and can support distributed computing across multiple machines, making it highly scalable. With its extensive in-built frameworks and libraries, the processing and analysis of sizable datasets can be executed efficiently (Gavrilova, 2023). The accessibility of the extensive library of in-built modules and packages provide easily-integratable pre-written code; resulting in significant time saved for programmers and developers (Gavrilova, 2023).


3. Embeddable
   Python is highly integrable, allowing it to be used in conjunction with other programming languages. This is convenient to developers seeking to add functionality to existing software programs or to build custom applications; for example, it can be embedded into C++ applications by using Boost.Python library (Gavrilova, 2023).




> Disadvantages


1. Slower than compiled languages
   As an interpreted language, each line of code is executed in succession, line by line. As explained in a previous question, this tends to make the processing of the program sluggish as opposed to compiled languages (Gavrilova, 2023).


2. Less secure
   Due to the fact that it's dynamically typed/interpreted, data types are determined at runtime rather than at compile time. This can leave the code vulnerable to malicious hacking. Furthermore, while the simplicity of the language/use makes it a popular option, it means programs written in Python are at a higher risk of exploitation if not comprehensively vetted (Gavrilova, 2023). Java and C++ are considered significantly more secure.


3. Bad memory consumption + garbage collection
   Python is infamous for higher memory consumption, which can ultimately be obstructive or problematic in resource-constrained environments. For example, it can use up to x10 the RAM of an alternative programming language. Furthermore, the automatic garbage collection feature can ultimately be counterproductive in that it can impact performance and cause unpredictable behaviour (Gavrilova, 2023).


4. Higher incidence of runtime errors
   Also due to the dynamic typing of this language, there are reportedly higher runtime errors when using Python in comparison to other languages. Therefore, rigorous testing is required before finalising a project (Novotny, 2024).




_2. Java_



> Advantages


1. Beginner friendly
   Much like Python, Java is a high-level language suitable for beginners in that it's easy to comprehend and write. This language is devoid of all the pointers, structures and unions that make languages such as C and C++ considered more complex.


2. Object-Oriented
   The advantage to object-oriented programming languages is that they're more secure, easy to implement and break down large blocks of code into more digestible fragments.


3. Economical
   Java is inexpensive and easy to develop and maintain due to its simple build (Team, 2024). It is compatible with all machines regardless of the hardware, making it a flexible option and inexpensive to run.


4. Platform-independent
   As alluded to above, Java is platform-independent, meaning that it can be run on any other system with Java in it, independent of hardware or operating systems (Team, 2024). This makes it a highly portable and compatible language.




> Disadvantages



1. Slow / Higher Memory Connsumption
   In comparison to native programming languages such as C + C++, Java is significantly slower and consumes more memory (Team, 2024). While automatic data collection is a convenient feature, having it continuously running the backend tends to hinder the performance speed (Team, 2024).


2. Poor GUI
   Its GUI builder is inadequate for constructing complex UIs, despite the availability of multiple frameworks such as Swing, SWT, JavaFX, and JSF. These frameworks still fall short in comparison to the superior GUI builders found in modern languages like Python, R, and C# (Team, 2024).


3. Lack of Backup Functionality:
    Java lacks any built-in features for backing up user data. While it excels in data storage, it does not offer any built-in backup solutions to safeguard user data (Team, 2024).


5. Verbosity and Complexity in Code:
    Java is known for its verbose and complex syntax, making it challenging for programmers to remember all the intricate details. Many developers opt for languages like Python or C++ due to their simpler syntax and structure, avoiding the complexities associated with Java (Team, 2024).






## Q6. A hypothetical client has sent you an email (shown in the Q6 Email section), asking for you to build them a website. Write an appropriate, professional email response that shows your understanding of the client’s needs for the website, as well as an understanding of appropriate technologies or tools needed to build the website yourself.




_Hello there!_


_My name is Alex, and I’m the director of the Super Awesome Museum (SAM). We display a variety of interesting artefacts, objects, and paraphernalia about all sorts of things from all over the world._


_I’m writing to you because the SAM needs a website. The museum is new in the city, we’re fully funded and don’t sell our items but we just need to encourage people to visit the museum._


_We would need a website that showcases some of our interesting exhibits and items, helps people find their way to the museum, and helps people contact the museum._


_We don’t know much about this website stuff - does this sound like something that you can do?_


_Looking forward to hearing from you,_


_Alex_


_Director_


_Super Awesome Museum_





Dear Alex,


Thank you for getting in contact regarding this project. I appreciate the opportunity to discuss the museum's online presence and how we can assist you in achieving your goals.


After reviewing your requirements, I certainly believe that we can help you in your endeavour to build your website in a way that showcases the uniqueness features of your museum and aligns with your brand. See below for a brief of how we can approach the project:


1. Foregrounding of Exhibits and Artefacts:


   We will design the website to prominently feature your museum's pivotal and most captivating exhibits and artefacts. This will include  high-quality images, detailed descriptions, and interactive multimedia to engage visitors and pique their curiosity.


1. Visibility of Visitor Information and Directions:


   An obviously crucial aspect, your audience needs to know how to get there! We can integrate interactive maps and clear directions to make this as seamless as possible for individuals of all ages.


3. Contact and Communication:


   We understand the importance of providing visitors with a streamlined avenue of communication with the museum for inquiries, feedback, or other means. We can also incorporate a user-friendly contact form as well as relevant contact details for direct communication.




As for the technical aspects, our team will implement current web development technologies and frameworks to create an aesthetic, accessible, interactive and user-friendly website. This will ensure compatibility across various devices and browsers, providing an optimal experience for all visitors.


To proceed further, I suggest scheduling a meeting to delve deeper into your requirements, discuss any specific features or design preferences, and outline the project timeline and budget. Please let me know a convenient time for you, and I'll be happy to arrange it accordingly. I also would be happy to provide examples of some of our past projects upon request.


Thank you again for considering us for this project. I would be delighted at the opportunity to collaborate with the Super Awesome Museum team and believe we could help you elevate your online engagement.


Don’t hesitate to contact me with any further questions in the meantime.




Looking forward to hearing from you,




Kind regards,




Hannah Scaife
Software Developer
Nebulous Faux Company
Ph: 0412345678
1/2 Anywhere Street,
Any City, NSW 3232







## Q7. Think back to a scenario or situation in your own software development projects or work.
## Explain how you would do things differently if you had a chance to go through that scenario again, using an appropriate reflective cycle or reflection technique.



In a recent personal project, I developed a personal portfolio website to be utilised as a platform to showcase my professional experience, career aspirations and personal values. Upon reflection, there are several things I would do differently given the chance.


Firstly, despite creating a sitemap and wireframe to provide clarity in mapping out the aesthetic and functionality of the project, I neglected to effectively use an agile project management tool from the beginning of my project to organise and visualise my task list. At times, I found myself feeling stressed and assuming I had more to do than I did in reality. Although I did use occasional task lists in a notebook, upon reflection I believe that the use of a Kanban or Trello AGM tool from the very beginning of my project would have greatly aided in providing clarity and aiding in time management. Moving forward, I plan to incorporate these tools during the planning process prior to commencing order to provide clarity of tasks and improve time management; a crucial soft skill required for when I'm ultimately working in a team of developers.


Secondly, there was another significant issue with the launch of this project that ended up costing me a lot of marks as it was catastrophic to the functionality of the overall product. Within the project, I employed a series of external CSS stylesheets to add styling to the HTML document, with the intention of executing a common colour theme, image styling and interactive animated features to increase user engagement. Due to the assignment requirements, I had to create specifically named directories and move all of the documents into their various files. I knew that this would disrupt the styling of the website without also revising and changing the tags on each page to ensure all of the stylesheets were connected to the HTML document and adequately recognised. I therefore meticulously raked through the documents, changing the tags and double checking the functionality via the styling on the deployed website. In this way, I did the right thing and triple checked the functionality of the deployed website. However, when I copied the documents into a zip file for submission, I changed all of the file locations to match the exact instructions on the assignment brief without understanding that this file was what was going to be opened and marked, as opposed to just a collection of documents to be viewed individually. This meant that although the functionality worked perfectly on the deployed website, I had inadvertently destroyed the functionality of the styling within the zip file that was to be marked. Within this scenario, my lack of attention to detail and inability to clarify this detail with my educators lead me to a significant mistake. Upon reflection, I realise that had this been for a client, it would have been a catastrophic error that may compromise my professional integrity. Moving forward, I will ensure to clarify these finer details with my team in order to ensure I'm delivering a functional and aesthetic product.


Ultimately both of these scenarios were important opportunities for reflection. They each shed light on areas of improvement, and allowed me to reflect on how they could have potentially affected my entire team in the future if repeated or gone unaddressed.






## Q8. A large part of career growth as an information technology professional happens through networking and workshops, often found at online or in-person events or workshops.
## Create an action plan that identifies several relevant networking opportunities for you to participate in or attend, and add some information about what you expect to gain or grow through each item in the action plan.




Particularly today when the field of software development and computer science fields are arguably "over-saturated", it's more important than ever to actively participate in networking and meet contact in-person. So far, this is my action plan in order to propel my budding career in software development.


There are several websites such as Eventbrite, STEM women and Meetup that I've subscribed to for events with relevant filters in situ; for example, pending tech events, hiring events and software dev/engineer grad events. So far I've already signed up to attend a couple of events. This coming week, I've bought tickets for an event titled "DevOps and Cloud Engineer Career Development”: The itinerary for this event outlines a networking and meet-and-greet with industry experts, DevOps specialists and AI enthusiasts. Furthermore, it outlines a panel discussion and skill-building workshop. These are exactly the type of networking events I will continue to go to, as not only are they opportunities to learn from industry leaders and build my skills, they're most importantly an opportunity to network with professionals in the field. Within these scenarios, I will have an opportunity to discuss my experience, skill and interests. I will also use this opportunity to assess which companies align with my values and have the resources to accommodate my ongoing professional development.


With these objectives in mind, I will also attempt to network via online communities and forums. I plan on using the portfolio website that we created as our first Coder Academy project as a professional platform with which I can connect with prospective employers and extend to relevant professional connections. Within my action plan, I intend to display the link to this website on my Linkedin, Github and other social media platforms. Connecting these platforms will provide potential prospective employers with insight into my experience, aspirations and personal values. Furthermore, Linkedin is a pivotal platform in creating and fostering these professional connections. I will strive to be active on this platform by providing relevant information and connecting with relevant industry figures. Furthermore, I've subscribed to platforms such as Medium and Substack in order to obtain valuable technical and hiring advice from fellow developers and those experienced in the field.


In the meantime, I intend to continue my own professional development in a manner that will make me an exceptional candidate in an ostensibly over-saturated market. I intend to do this by continuously practising Leetcode and Hackerrank challenges in order to adequately prepare for the technical aspect of a job interview, as well as just advancing my skills and familiarity with the mechanisms of complex programming languages so that I can excel when I inevitably secure a position. I will also attempt to participate in coding competitions and hackathon events, which are not only fantastic opportunities for advancing coding skills but can also double as hiring/networking events. Furthermore, I plan to create as many personal projects as I can; it's my understanding that building a portfolio of professional work and personal projects is arguably the most important aspect of this process. Without it, I won't have anything to showcase at networking events and will likely squander these opportunities.






## Q9. Explain the uses of language-learning model technologies (such as ChatGPT) on written and technical works, such as reports and software projects.



There are several ways in which language-learning models (LLMs) can be used to aid written and technical works:


1. Condensing reports
   > LLMs such as ChatGPT have the ability to condense lengthy reports into short, concise summaries. This can be a useful time-saving method, enhancing overall productivity and efficiency.


2. Language translation
   > LLMs can be used for translating written reports into different languages, which could be extremely useful in the context of communicating with international colleagues.


3. Technical writing assistance
   > LLMs can be used as an editing tool to improve style, grammar and format of written and technical reports. Despite this being useful in theory, the limitations of these models should be taken into consideration; these are outlined in the next question.

4. Contextual Assistance
    > LLMs are able to offer contextual assistance and guidance within software development environments, providing suggestions, code examples, or documentation references based on the current context of the user's work.

5. Debugging code
    > LLMs can aid in code debugging by spotting errors, explaining code functionality, proposing refactoring ideas, assisting in documentation creation, and giving troubleshooting advice. Nonetheless, they should complement traditional debugging tools rather than replace them, as developers need to combine various methods for effective debugging.





## Q10. Explain the legal and ethical impacts of the usage of language-learning model technologies (such as ChatGPT) in written and technical works, such as reports and software projects.




There are many potential legal and ethical implications that could arise with the introduction of language-learning model (LLM) technology into social and professional settings. Content produced by LLMs remains an ethical grey-area for a myriad of reasons; firstly, they have the ability to inherit biases based on the training data (Liyanage et al., 2023). By using unfiltered content produced by LLMs in written reports, the user is at risk of inadvertently propagating harmful or discriminatory prejudices. Admittedly, this is not likely in the setting of a technical software report, however, should still be considered.


More importantly, the intellectual property rights of the data produced by LLMs are a legal grey-area (Liyanage et al., 2023); if the LLM is trained on copyright text or data, publishing this content under a personal or company name could potentially leave either party liable to copyright infringement and subsequent legal action. Similarly, the content produced by this technology has the potential to be misused, intentionally or inadvertently, to replicate existing content. Within the context of a written professional report, this could lead to damaging outcomes, as the company could be held accountable for plagiarism.


Furthermore, the fledgling nature of these technologies means they are still ongoing adjustments and don't always produce reliable technical data. LLMs such as ChatGPT have the potential to be extremely useful learning tools in many areas, however, there have also been many cases involving the production of inaccurate technical data; for example, inaccurate code or algorithms. In a recent study evaluating the performance of LLMs on Technical Language Processing tasks, the data suggested that, by design, these models are "not outputting accurate information but convincing text in the language(s) of training", stating that "although LLMs have shown promise in information retrieval (IR) tasks, their information retrieval capabilities are accidental and not by design" (Kernycky et al., 2024). In this way, relying on this technology for technical information without critical evaluation of the responses could ultimately lead to the production of bugs and broken code.


This leads into the issue of the ethical risk the use of LLMs pose to the overall workforce in regards to development of professional skills. In a recent study evaluating the performance of LLMs on Technical Language Processing Tasks, the data found that "participants with less experience and knowledge in FCC-related topics are more likely to be more confident in the answers provided by these models, even when these answers are inaccurate or off-topic" (Kernycky et al., 2024). In this way, one can see that concerns regarding the over-reliance of LLMs while attempting to master technical disciplines such as software development can not only lead to unreliable outcomes, but overall degradation to the development skills within professional fields. While LLMs should be considered a useful learning tool to assist human learning, users should be advised to acknowledge the limitations of these technologies and not rely on them to replace human skills.





## Q11. Explain multiple skills from each of the categories below, and how they’re useful to a software development workplace.




> Soft skills


   1. Communication/Team Work


       This is an imperative skill within a software development context as software engineers and developers are required to engage in collaboration with each other, other relevant teams and their product manager in order to be able to produce a functional and satisfactory product.


   2. Time Management
      
       In software development, there are inflexible deadlines and product launch dates set in advance and required to be met promptly. Time management is imperative to meet these deadlines. Furthermore, an inability to properly manage your time can cause obstruction to the work of colleagues.


   3. Accountability
      
       Remaining accountable for one's actions and mistakes is crucial in maintaining professional integrity, regardless of your profession. When developers are accountable for their work, they are more likely to thoroughly test their code, adhere to coding standards, and strive for high-quality outcomes.


   4. Problem solving/critical thinking


       Good problem solving skills are the cornerstone to developing quality software. Software developers often encounter complex problems that require creative solutions; requiring analysis of issues, identification of root causes, and ability to devise effective strategies to address them.


   5. Discipline/interest in ongoing education and professional development
       Within the field of computer science and software development, technologies and languages are ever-evolving. Motivation to engage in continuous study of these emerging developments within the tech world is an imperative soft skill.




> Hard skills


   1. Programming languages
       This is an obvious hard skill required in the field of software development. Depending on the project requirements and technology stack, developers will need to be proficient in programming languages such as Java, Python, React, JavaScript, C#, C++, or SQL, to name a few.


   2. Version Control Systems
       An understanding of Version Control Systems (VCS) such as Git or Subversion (SVN) is crucial; VCSs are used universally within development teams to track, debug and collaborate work within a project/story.


   3. Familiarity with Development Tools
       From code editors to in-built web development tools, one must have an understanding of how to use these universally used programs in order to perform a software development or engineering role.\\
  
   4. Testing and debugging
       Under the umbrella of programming languages, an understanding unit and program testing is a large contingent of the job. Without knowledge of testing or debugging, one can easily cause an entire project to fail.


   5. Software Development Methodologies
       Methodologies such as Agile, Scrum and Waterfall are important in the role, particularly whether cross-collaborating with other teams in the company.






## Q12. Explain multiple roles or job positions that would be found in a medium-sized software development company.


1. Software Engineer/Developer


   > Software Engineers or developers are responsible for developing, testing and maintaining software applications/systems according to the project requirements. They apply their knowledge of engineering principles, programming languages and systems architecture to build software solutions. It is not only their job to write and test code, but also to optimise software for speed and scalability. Furthermore, this role involves dynamic collaboration with other engineers, clients, security specialists and stakeholders in order to produce end user satisfaction.




2. UX/UI Designer


   > These roles fall under the category of web design. UX Design involves the process of creating products and services which provide meaningful experience for the users; such as branding, usability, function, and design. UI Design refers to the interfaces with which the users engage og web pages such as interactive elements, animation and transitions by incorporation of buttons, images, widgets and visual effects. Often web designers have experience in both types of design.


3. Product Manager


   > The Product Manager oversees and manages the vision, strategy and roadmap for projects. This involves guiding the all cross-functional teams, prioritising requirements, revising strategy and responsibility for the final product launch. It is their role to essentially coordinate all moving parts of a project.




4. Data Scientist/Analyst


   > Data Scientists collate and analyse all relevant data to derive insights and inform future decision making. They generate algorithms and perform statistical analysis of data in order to identify trends, patterns and opportunities for optimization or improvement.





## REFERENCES


Agarwal, B.B., Gupta, M. and Tayal, S.P., 2009. Software engineering and testing. Jones & Bartlett Publishers.


Atlas, S., 2023. ChatGPT for higher education and professional development: A guide to conversational AI.


BasuMallick, C. (2023) Compiler and interpreter critical differences - spiceworks, Spiceworks Inc. Available at: https://www.spiceworks.com/tech/tech-general/articles/compiler-vs-interpreter-12-critical-differences-to-know/ (Accessed: 20 April 2024). 


Barlen, T. and Blankertz, W. (2005) IBM HTTP Server (powered by Apache) an integrated solution for IBM eServer iSeries servers. San Jose, CA: IBM, International Technical Support Organization. 


Cox, J., Jones, N. and Szumski, J. (2012) Professional IOS network programming: Connecting the enterprise to the iPhone and iPad, ProQuest. Indianapolis, IN: Wiley. Available at: https://ebookcentral.proquest.com/lib/redhill-ebooks/detail.action?docID=947567 (Accessed: 17 April 2024). 


Erik Gregersen (2024) "Markup language", Encyclopædia Britannica. Available at: https://www.britannica.com/technology/markup-language (Accessed: 18 April 2024).


Feamster, N., Balakrishnan, H., Rexford, J., Shaikh, A. and Van Der Merwe, J., 2004, August. The case for separating routing from routers. In Proceedings of the ACM SIGCOMM workshop on Future directions in network architecture (pp. 5-12).

Ferraiolo, J., Jun, F. and Jackson, D., 2000. Scalable vector graphics (SVG) 1.0 specification. Bloomington: iuniverse.


Gavrilova, Y. (2023) Pros and cons of python programming language, Pros and Cons of Python. Available at: https://serokell.io/blog/python-pros-and-cons (Accessed: 20 April 2024). 


Gorlaski, W. (2008) The Illustrated Network : How TCP/IP Works in a Modern Network. 1st edn, ProQuest. 1st edn. Elsevier Science & Technology. Available at: https://ebookcentral.proquest.com/lib/redhill-ebooks/detail.action?docID=405967 (Accessed: 16 April 2024).


Grosskurth, A. and Godfrey, M.W., 2006. Architecture and evolution of the modern web browser. University of Waterloo in Canada, 24.


Inouye, J. (2022) What is a markup language? definition, history, features and applications, Hackr.io. Available at: https://hackr.io/blog/what-is-markup-language#the-most-popular-markup-languages (Accessed: 18 March 2024). 


Kernycky, A., Coleman, D., Spence, C. and Das, U. (2024). Evaluating the Performance of LLMs on Technical Language Processing tasks. arXiv preprint arXiv:2403.15503. (Accessed: 18 April 2024)


Liyanage, U. P. and Ranaweera, N. D. (2023) “Ethical Considerations and Potential Risks in the Deployment of Large Language Models in Diverse Societal Contexts”, Journal of Computational Social Dynamics, 8(11), pp. 15–25. Available at: https://vectoral.org/index.php/JCSD/article/view/49 (Accessed: 17 April 2024).


Mendez, M. (2014) Chapter 7: Markup languages, The Missing Link. Available at: https://milnepublishing.geneseo.edu/themissinglink/chapter/chapter-7-markup-languages/ (Accessed: 20 March 2024).


Mockapetris, P. and Dunlap, K.J., 1988, August. Development of the domain name system. In Symposium proceedings on Communications architectures and protocols (pp. 123-133).


Novotny, J. (2024) A programmers’ guide to python: Advantages & disadvantages, Akamai. Available at: https://www.linode.com/docs/guides/pros-and-cons-of-python/ (Accessed: 20 April 2024).


Private and Public IP Addresses (no date) Teltonika. Available at: https://wiki.teltonika-networks.com/view/Private_and_Public_IP_Addresses (Accessed: 20 April 2024).


Team, D. (2024) Pros and cons of java: Advantages and disadvantages of Java, DataFlair. Available at: https://data-flair.training/blogs/pros-and-cons-of-java/ (Accessed: 21 April 2024). 


Yasar, K. and Zola, A. (2022) What are network packets and how do they work?, Networking. Available at: https://www.techtarget.com/searchnetworking/definition/packet (Accessed: 20 April 2024). 



