---
layout: page
title: Portfolio
permalink: /portfolio/
---
## Open Energy Platform 
![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/energyscreen.png){: .center-image }

*[Open Energy Landing Page](http://myopenenergy.com)*

Open Energy is an energy platform that allows consumers to efficiently trade energy at a consumer level – allowing them to save money and improve the sustainability of the grid. The project began with a blockchain implementation in IBM's Hyperledger technology during a hackathon in the Netherlands. Our team of three took home the 5000 euro grand prize for prototyping the marketplace. After the hackathon I opted to pursue the project further after speaking with Engie and Shell, two utilities.

 The next iteration occured at UltraHacks a hackathon in Helsinki, Finland. I decided to port the blockchain component to Ethereum as it became the standard in blockchain. The Ethereum platform had a more active community and abundant resources to leverage. 

 The most recent iteration boasts a classic database that allows for more throughput and quicker development cycles compared to its blockchain peer. With the help of Iowa State University the project was accepted as a senior design capstone project.

There is [evidence](http://www.solarcity.com/sites/default/files/SolarCity_Distributed_Grid-021016.pdf) that a distributed grid has a net positive benefit for society. The issue arises in that there is little incentive to implement this system. The incentive is spread out over the masses while the few parties that benefit from the current model lobby to keep it. 

The mission for Open Energy is to break down these barriers, by creating an environment for peer to peer energy transactions. In certain locations there are solar or wind installations that produce energy cheaper than the grid. By allowing individuals the opportunity to purchase this energy you 1. incentivize the producer to purchase more clean energy installations and 2. save money for the buyer. There are a myriad of other benefits including lower transmission costs, stable infrastructure, and a reduction in energy buffers for a utility. As we are collecting data we can help enable grids to provide real time billing a system that has reduced energy consumption (5-7%) in many areas by informing the consumer energy prices throughout the day.

Our energy platform requires a smart meter to log consumption data (energy the consumer uses from the grid) and production data (energy the user produces from energy generation sources). Below is the block diagram for the system. Using two transducers we can non-invasively measure the energy flow at both the consumption and production ties. This is sent to our microprocessor for filtering and passed to the communication module. To date we have ethernet and wifi capabilities for the communication module. The comm module uses TCP/IP to hit a Flask endpoint for database entry.

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/hardwareschem.png){: .center-image }

To get around the political barriers many municipalities have in regards to energy trading protocol I've turned our efforts to the private sector for prompt implementation. A Chicago developer is now collaborating to allow our smart meter and trading technology to be installed within their development zoning. By going direct to the developer we don't need municipality approval to share energy as the grid is owned and maintained by the developer within their zoning. 

After proving the benefits from distributed generation, storage, trading, and energy transparency at the developer spectrum we plan to expand our product offerings to a wider audience. 

To follow along, or contribute, fork [this repo](https://github.com/bgeils/open-energy).

* [Press](http://brendongeils.com/energy/)
* [Demo Customer Interface](http://www.myopenenergy.com)

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

#### Sodima in the News
* [Pitch Competition](http://www.iowastatedaily.com/news/academics/article_8c6e0d9e-0480-11e7-b610-1f042f982db0.html)
* [Chatbot landscape](https://blog.botmakers.net/chatbot-developers-landscape-130-development-agencies-powering-the-future-of-chatbots-industry-5cec2e1eeb34)

## Atlas Fitness - Owned by Sodima Solutions

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/atlasconvo.png){: .center-image }

*Sample customer interaction. Our servers directly respond to fitness queries.*

Atlas was the first product Sodima released. Atlas Fitness is a chatbot for helping people to consistently get to the gym. The technology also featured products and workouts that our clients could configure. In three months we grew to ~1k users and seven clients including gyms in NYC and Miami. During the release Atlas was named the #1 fitness chatbot and #3 health chatbot by botlist.

Tech Stack: MongoDB, API.AI, Meteor.js, Node, nginx, AWS, Python3, NLTK

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/atlas_customer.png){: .center-image }

*Customer interface to Atlas Fitness. Our clients log into this system to identify their audience and cater content accordingly.*

### Structurely 

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/struct_convo.png){: .center-image }

One of Sodima's first contracts was for Structurely. We had been tasked to build an artificially intelligent chat technology for their real estate company. The project was a finalist for Inman's Most Innovative Technology in real estate in 2016. Our company had the opportunity to build three iterations of this technology. The first iteration was selected to demo at Facebook's HQ. Additionally, Sodima was hired to build a full database system, API, and front end customer portal. Today over 3,500 agents from across 39 states are using this technology to help with their job of selling the right home to people. 

My role was interviewing and distilling the client's requests, creating system designs and helping our team implement the solutions across the stack. As Structurely grew I turned focused our engineering efforts on creating front ends backed by JSON to allow our clients to make on-the-fly edits to configurations. This allowed our development team to focus on core features and allow the content team to build conversational components separately. 

Tech Stack: React, Redux, GraphQL, Node, Meteor, PSQL, AWS, Digital Ocean, nginx, python ML kits, API.AI, Flask, humans (when the convo goes astray)

[Link to Structurely's homepage](https://structurely.com)

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/daystosell.png){: .center-image }

*The Structurely Team + Brendon*

I was invited to join the Structurely team at an SF hackathon to design an algorithm for picking a price to sell your home given the number of days you are willing to wait. The system is patent pending. During this hackathon I learned various clustering algorithms and data visualization techniques. Also, this was the first time I was introduced to Jupyter notebooks, I haven't looked back since.

### Terva 

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/terva.jpeg){: .center-image }

Another client for Sodima was Terva, a craigslist for farmland. The company was tasked with building a web application the allowed users to search for land for sale and interact with it accordingly. Our system incorporated a database with millions of documents that were served over in GeoJSON to visualize. 

The theme in designing and deploying technology at Terva was scale. From the start we knew the data was going to be large and messy. The users were also accessing a heavy application and weren't the most technically savvy. The user experience solved a number of these issues. Having loading menus with tips and messages made the application feel faster. Using contrasting colors and industry standards helped direct the users eye and more easily digest the content.  

Tech Stack: Meteor, Digital Ocean, Flask, Python, Mapbox/Leaflet, MongoDB

[Link to Terva's homepage](http://landing.terva.ag/)

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/tervaviz.png){: .center-image }

*Iowa farmland for sale.*

## Quantum Visualization -- Harvard's Hackathon

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/qcviz.gif){: .center-image }

*Two bloch spheres, one has an X gate applied to it.*

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

## SpaceX -- Instrumentation & RangeOps Internship

* Spring 2016 -- Cape Canaveral, FL

As an instrumentation and comm intern my focus was on designing and implementing systems for ground control to reliably launch Falcon 9 rockets. During my time at the Cape I helped launch and, fingers crossed, land five Falcon 9 rockets at LC-40 and SLC-39A. The majority of my time was spend on 39A projects. This is the same space launch complex as the Apollo missions from '63 to '72. Part of the 39A work was associated with pad completion for Falcon Heavy. I also worked with the payload and Dragon install implementing an end-to-end hazard-safe communication system for pre-flight operations. 


![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/waterlanding.gif){: .center-image }

*Video Source: Youtube @spacexchannel*

*Landing the first rocket on water, during the internship.*

![alt text](https://raw.githubusercontent.com/bgeils/bgeils.github.io/master/images/waterfall.gif){: .center-image }

*Video Source: Youtube @spacexchannel*

*We had a few of these too... but practice makes perfect.*

### General 

* [Get to know](http://www.isupjcenter.org/2017/02/get-to-know-brendon-geils/)
* [Future Founders Release](https://www.prnewswire.com/news-releases/future-founders-names-2017-fellows-17-entrepreneurs-you-should-know-300388639.html)
* [ISU Press](http://www.ece.iastate.edu/files/2011/02/Summer-2017-Connections-Web.pdf)

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

After weighing my options, I canceled the trip. This was a turning point in my life. I spent the subsequent months absorbing as much as I could in order to at the time get the "Google" dream job. This goal overtime faded as I understood the potential I had within the field. Studying computer science for those three months I learned something more important than the most efficient way to traverse a binary tree, but how I could effect global systems such as energy markets. The following year I did just that. I worked at SpaceX, Palantir, and a company I co-founded, Sodima Solutions.

Having reviewed the companies attending my university's career fair I booked a flight to UCLA to attend theirs with a focus on gettin a technology internship. While boarding the flight I recieved the email from UCLA's career staff stating I was not to attend the fair less I was an enrolled UCLA student. The wheels sputtered up and I was on my way to California from small town Iowa. With a bit of luck I was able to get into the fair and landed interviews over the next few months with Palantir, Google, Microsoft, American Express, IBM, SpaceX and Bloomberg. 

I wrote a blog post shortly after [here](http://brendongeils.com/Following-passions/).

#### Hackathons

Each hackathon has offered me something I would never expect. I met my co-founder, my first two clients and landed an internship from going to hackathons. The energy and mentality kept me coming back. Open Energy was another hackathon-born project that I would never have been exposed to otherwise.

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



