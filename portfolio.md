---
layout: page
title: Portfolio
permalink: /portfolio/
---

## Open Energy Platform 

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/energyscreen.png){: .center-image }

Open Energy is an energy platform that allows consumers to efficiently trade energy at a consumer level – allowing them to save money and improve the sustainability of the grid. The project began with a blockchain implementation in IBM's Hyperledger technology during a hackathon in the Netherlands. Our team of three took home the 5000 euro grand prize for prototyping the marketplace. After the hackathon I opted to pursue the project further after speaking with Engie and Shell, two utilities.

 The next iteration occured at UltraHacks a hackathon in Helsinki, Finland. I decided to port the blockchain component to Ethereum as it became the standard. The Ethereum platform had a more active community and abundant resources to leverage. 

 The most recent iteration boasts a classic database that allows for more throughput and quicker development cycles compared to its blockchain peer. With the help of Iowa State University the project was accepted as a  senior design capstone project

There is [evidence](http://www.solarcity.com/sites/default/files/SolarCity_Distributed_Grid-021016.pdf) that a distributed grid has a net positive benefit for society. The issue arises in that there is little incentive to implement this system. The incentive is spread out over the masses while the few parties that benefit from the current model lobby to keep it with a strong presence. 

The mission for Open Energy is to break down these barriers, by creating an environment for peer to peer energy transactions. In certain locations there are solar or wind installations that produce energy at a cost cheaper than the grid. By allowing individuals the opportunity to buy this energy you 1. incentivize the producer to purchase more clean energy installations and 2. save money for the consumer. There a myriad of other benefits including lower transmission costs, infrastructure, and a reduction in energy buffers for a utility.

To follow along, or contribute, fork [this repo](https://github.com/bgeils/open-energy).

* [Press](http://brendongeils.com/energy/)
* [Demo Customer Interface](http://www.myopenenergy.com)

## Quantum Visualization -- Harvard's Hackathon

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/qcviz.gif){: .center-image }

As quantum hardware is progressing there is a future where a programmer would execute certain portions of their programs on a quantum computer. To assist in the paradigm shift that software and hardware are going through in the quantum realm, our team built a quantum VM and visualization tool. The best case scenario is a future where this tool becomes the Code Academy for the quantum programmers. After researching optical and ion based quantum implementations I joined a team at Harvard to address the software angle of quantum. 

Using the quantum properties of superposition and entanglement certain problems within computer science have exponential speeds ups. Factoring problems and unordered search are two common applications. Our initial design used Regetti's quantum API to process the programs we wrote in QUIL, what we dub the assembly language of quantum computers. After Regetti's server went down we were forced into implementing our own quantum virtual machine. The basic gates we needed to implement in a universal gate set were X, Y, Z and CNOT. 

*Want to try the visualizer out yourself? [Here you go.](http://qchackers.com)*

Code snippet to try out
```js
X 0 
X 0
MEASURE 0 [1]
```
The X Gate performs a rotation of pi around the x axis.


## Future Founders Fellowship

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/futurefounders.jpeg){: .center-image }

One of 17 entrepreneurs selected to join a 12-month program to assist in their ventures through high caliber mentors, resources, and a strong peer group. Representing 15 schools in nine states the program is nationwide. The represented industries include agriculture, consumer products, food and tech.

Throughout the fellowship I was able to grow Sodima Solutions by expanding into our first product, Atlas Fitness, while building communication technology for multiple start ups, Terva & Structurely. At the conclusion of the fellowship I was invited to the follow-on Alumni Fellowship to continue with the program -- with a select number of fellow.

* [Release Link](https://www.prnewswire.com/news-releases/future-founders-names-2017-fellows-17-entrepreneurs-you-should-know-300388639.html)
* [ISU Press](http://www.ece.iastate.edu/files/2011/02/Summer-2017-Connections-Web.pdf)


## Sodima Solutions -- Co-Founder/CEO

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/sodima.jpg){: .center-image }

* 2015 - 2016 -- Miami, FL

Sodima had its humble beginnings in Miami, FL during Florida International University's Spring Hackathon. I met my co-founder Marcellus G. during the event, where we immediately clicked. The following months we spend working as a pair with a focus on web services and digital marketing. As we grew into the communication space we had the opportunity to work heavily with two startups, Structurely & Terva, bringing their ideas to an MVP and product release. During the 20 months at Sodima Solutions our company secured revenue of ~100k and equity in multiple startups.

During the web development phase of the business I interviewed clients, build solutions, and maintained them. Marcellus would find and make the sale, passing off the client to me. We built the majority of our web services in wordpress or other highly managed systems. This allowed us to easily maintain the project and hand it off to our client upon completion. This taught me basic web technologies -- HTML, CSS, JS -- and more importantly how to work with our clients. Adjacent to the technology stack I grew into the finance and legal role. I drafted all our contracts prior to having professional review -- a decision that saved us big time. The finances were fairly straight forward while operating in a consulting business allowing cashflow to rarely be an issue. 

Given the competitive landscape in web services we began to position ourselves to take on larger web applications and more specifically communciation technology.

* Revenue: +$100K
* Products: Atlas Fitness
* Major Clients: Terva, Structurely
* +15 web development clients
* NewCo Helsinki Accelerator -- Finland
* StartUp FIU Accelerator -- Florida International Unviersity
* Sodima Solutions owns equity in the following two companies: 
	* [Structurely](https://structurely.com) 5%
	* [Terva](https://terva.ag) 4% 

#### Sodima in the News
* [Pitch Competition](http://www.iowastatedaily.com/news/academics/article_8c6e0d9e-0480-11e7-b610-1f042f982db0.html)
* [Chatbot landscape](https://blog.botmakers.net/chatbot-developers-landscape-130-development-agencies-powering-the-future-of-chatbots-industry-5cec2e1eeb34)

## Atlas Fitness - Owned by Sodima Solutions

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/atlas.png){: .center-image }

Atlas was the first product Sodima released. Atlas Fitness is a chatbot for helping people to consistently get to the gym. The technology also featured products and workouts that our clients could configure. In three months we grew to ~1k users and seven clients including gyms in NYC and Miami. During the release Atlas was named the #1 fitness chatbot and #3 health chatbot by botlist.

Tech Stack: MongoDB, API.AI, Meteor.js, Node, nginx, AWS, Python3, NLTK

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/atlas_customer.png){: .center-image }

*Pictured above is the customer interface to Atlas Fitness. Our clients log into this system to identify their audience and cater content accordingly.*


### Structurely 

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/struct.png){: .center-image }

One of Sodima's first contracts was for Structurely. We had been tasked to build an artificially intelligent chat technology for their real estate company. The project was a finalist for Inman's Most Innovative Technology in real estate in 2016. Our company had the opportunity to build three iterations of this technology. The first iteration was selected to demo at Facebook's HQ. Additionally, Sodima was hired to build a full database system, API, and front end customer portal. Today over 3,500 agents from across 39 states are using this technology to help with their job of selling the right home to people. 

Tech Stack: React, Redux, GraphQL, Node, Meteor, PSQL, AWS, Digital Ocean, nginx, python ML kits, API.AI, Flask.

[Link to Structurely's homepage](https://structurely.com)

#### Days to Sell

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/daystosell.png){: .center-image }

At an SF hackathon our team designed an algorithm for picking a price to sell your home given the number of days you are willing to wait. The algorithm is patent pending. During this hackathon I learned various clustering algorithms and various data visualization techniques. Also, this was the first time I was introduced to Jupyter notebooks, I haven't looked back since.

### Terva 

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/terva.jpeg){: .center-image }

Another client for Sodima was Terva, a craigslist for farmland. The company was tasked with building a web application the allowed users to search for land for sale and interact with it accordingly. Our system incorporated a database with millions of documents that were served over in GeoJSON to visualize. 

Tech Stack: Meteor, Digital Ocean, Flask, Python, Mapbox/Leaflet, MongoDB

[Link to Terva's homepage](http://landing.terva.ag/)


## Moralit.ai -- Princeton's Hackathon

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/moralit.png){: .center-image }


Moralit.ai is an artificially intelligent personal assistant which uses natural language processing and machine learning to perform moral decision making. By adhering to deontological principles surrounding murder, suffering, adultery, and deception, moralit.it determines the ethical permissibility of performing action requests from the user. My role was to build the machine learning processor to use general consensus sentiment on a subject to make a decision. Over time this system would self correct. 


Tech Stack: Node.js, Express, mySQL, NLP models

## Palantir -- Deployment Strategist Internship

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/palantir.jpg){: .center-image-small }

* Summer 2017 -- London, UK
* Summer 2016 -- New York City, NY

• Assisted in building and deploying cybersecurity web based software for Fortune 500 company users
• Data ingestion of 100GB+/day in cyber security logs from the client
• Client point of contact and developer intermediary for feature selection and product deployments


## SpaceX -- Instrumentation & RangeOps Internship

* Spring 2016 -- Cape Canaveral, FL

As an instrumentation and comm intern my focus was on designing and implementing systems for ground control to reliably launch Falcon 9 rockets. During my time at the Cape I helped launch and, fingers crossed, land five Falcon 9 rockets at LC-40 and SLC-39A. The majority of my time was spend on 39A projects. This is the same space launch complex as the Apollo missions from '63 to '72. Part of the 39A work was associated with pad completion for Falcon Heavy. I also worked with the payload and Dragon install implementing an end-to-end hazard-safe communication system for pre-flight operations. 


![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/waterlanding.gif){: .center-image }

*Video Source: Youtube @spacexchannel*

*Landing the first rocket on water, during the internship.*

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/waterfall.gif){: .center-image }

*Video Source: Youtube @spacexchannel*

*We had a few of these too... but practice makes perfect.*

## Research Assistant -- Iowa State University

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/isu.png){: .center-image-small }

* 2015 - 2016

• Insider threat analysis through anomaly detection, flagging malicious behavior in enterprise systems
• Data analysis in underrepresented minority student enrollment and graduation within STEM majors
 
## Procter & Gamble -- Power Controls & Information Systems Engineering Internship

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/pg.jpg){: .center-image }

*Pictured outside Procter & Gamble HQ in Cincinnati, Ohio*

* Summer 2015 - Iowa City, IA
* Summer 2014 - Iowa City, IA

• Led 10 projects in vision systems, VBA programming, software training, system installations & upgrades
• Provided a global P&G software solution for PLC revision DBs saving 20 hours/month per site
• Utilized statistical analysis and data integrity for enterprise data systems

## Wakefield Entertainment

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/wakefield.jpg){: .center-image }

*Left to Right: Brendon Geils, Adam Horn*

During my third year in high school I co-founded a sound and lighting entertainment company. At Wakefield I managed company finances, marketing, and web development. I also organized our event planning for over 100 events and 60+ clients in two states. We grew yearly revenue to $25,000 organically in two years – Sold January, 2015. From an early age Wakefield taught me how to manage a business and organize a group of individuals to seamlessly pull off a wedding night or prom. 

### General 

[[Get to know]](http://www.isupjcenter.org/2017/02/get-to-know-brendon-geils/)

Events:
* Collegiate Entrepreneur Organization Conference - Orlando, FL
* Forbes Under 30 Summit - Boston, MA
* Okoboji Entrepreneurial Institute - Okoboji, IA
* NewCo Business Accelerator - Helsinki, Finland
* Slush - Helsinki, Finland


## Defining Experiences

To better understand my personality, what makes me tick and some more impressionable moments in my life I've put together my most defining experiences. While working in teams I belive it is important to be vulnerable and open. The most effective way that I can be open with a new team is to understand their experiences and have them understand mine. 

#### Almost Abroad

As a studying electrical engineer the computer science field was always very interesting to me, but I felt I never had a chance to break into the market given my "path" was set in electrical engineering. The tipping point came when I was two weeks out from study abroad semester of lax living and reluctant studying in Spain. I knew this trip would be an eye opening cultural experience, but I would neglect my growing interest in computer science. 

After weighing my options, I canceled the trip. This was a turning point in my life. I spent the subsequent months absorbing as much as I could in order to at the time get the "Google" dream job. This goal overtime faded as I understood the potential I had within the field. Studying computer science for those three months I learned something more important than the most efficient way to traverse a binary tree, but how I could change effect global systems such as quantum computing and energy markets. The following year I did just that. I worked at SpaceX, Palantir, and a company I co-founded, Sodima Solutions.

Having reviewed the companies attending my university's career fair I booked a flight to UCLA to attend theirs with a focus on gettin a technology internship. While boarding the flight I recieved the email from UCLA's career staff stating I was not to attend the fair less I was an enrolled UCLA student. The wheels sputtered up and I was on my way to California from small town Iowa. With a bit of luck I was able to get into the fair and landed interviews over the next few months with Palantir, Google, Microsoft, American Express, IBM, SpaceX and Bloomberg. 

I wrote a blog post shortly after [here](http://brendongeils.com/Following-passions/).

#### Hackathons

Having only attended my first hackathon during my third year of college I was behind the curve when it came to these events. I quickly 

15 on-site hackathons including:

* Hack ISU – Iowa State University
* HackIllinois - University of Illinois at Urbana-Champaign
* Hack Princeton, Princeton University
* Hack Harvard, Harvard University
* Code 4 Good, JP Morgan Chase – Boston, MA
* MadHacks - University of Wisconsin at Madison
* Hack4Energy – Gronigen, Netherlands
* UltraHack – Helsinki, Finland
* Mango Hacks, Florida International University - Miami, FL
* Hack Riddle - Embry-Riddle Aeronautical University
* Intern Hacks – San Francisco



