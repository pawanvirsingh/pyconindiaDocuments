# Pyconindia -2017 
# Documents

# 1
Today i Attendend the pycon in delhi so it is good experience to be there .
in this repo i am just collecting the links(including slides and url for documents in talk)

Setting the scene
Issues with Indian Budget Documents
Extracting Tables with boundaries.
Detecting Table Boundaries using OpenCV
Leveraging Open Source Tools like “Tabula”
What about tables without boundaries ?
Extracting information from tables without boundaries
Geometrical features using OpenCV library
Textual features using “pdf to text” poppler’s version
Building a pipeline to detect table components
Headers
Number Cells
Text Based Cells / Groupings
Detecting Table layout
Detecting rows
Detecting columns
Where each component lies
Extracting tables split across Pages
Building a base for machine learning models while doing so.
Open Research using Jupyter Notebooks
How you can contribute ?
Prerequisites:

  Python 2.7
  pandas
  numpy
Basic Image Manipulation using OpenCV
Content URLs:
  Repo: https://github.com/heaven00/pycon_delhi_2017 
  Slides: https://heaven00.github.io/pycon_delhi_2017
  https://github.com/cbgaindia/parsers
  https://github.com/cbgaindia/scrapers
  https://github.com/heaven00
  
# 2
Prerequisites:

Intermediate level knowledge of Python is beneficial, however the concepts are language agnostic .
Knowledge of NLTK , spaCy and scikit-learn is a plus.
Content URLs:

Talk presentation link : https://prezi.com/view/m2Fe65t1RTuQK2s1LZrC/

Speaker Info:

I am Dhruv Pathak, a python enthusiast. I currently work at Goibibo as VP of Engineering, where we ship many evolving and high scale products using Python.

Speaker Links:

https://stackoverflow.com/users/533399/dhruvpathak
https://www.linkedin.com/in/dhruvpathak
https://github.com/dhruvpathak  




# 3:
Building microservices with firefly
 Nabarun Pal (~palnabarun) |  


Description:

firefly is an open source micro framework to deploy Python functions as web services. firefly was created with the aim of simplifying the deployment Machine Learning models as RESTful API. But as fate would have it, it became our favourite tool for building microservices. firefly takes care of processing the HTTP requests, forwarding the data to the python functions and encoding the result back to a HTTP request. It also has data validation, authentication support, transfering any type of file. You can also define a configuration file specifying the URL resource structure resulting in an elegant RESTful API.

It comes with a client library that makes calling remote functions calling as easy as calling functions present locally. It is a WSGI application and can be deployed and scaled through any WSGI server like gunicorn. There are many other features in the pipeline like multiple authentication modes through the plugin system.

This talk will focus on introducing firefly, it's notable features like plugin support, building microservices efficiently with various examples.

Prerequisites:

The participants should have a basic notion of making web services and RESTful API's.

Content URLs:

Slides outline:

About me
Microservices Architecture
Comparison with monolithic architecture
Design Patterns
Forces in Action
Solution
Examples
Benfits
When to use?
Who uses?
Firefly to the rescue
What is firefly?
Why use firefly?
Code
Run
Deploy
Use (Client)
Authentication
Data Validation
Canonical URL's
Plugins
Github: https://github.com/rorodata/firefly
Documentation: https://firefly-python.readthedocs.io/

Speaker Info:

The speaker is Nabarun Pal, a final year undergraduate student at Indian Institute of Technology Roorkee. Currently, he is working for rorodata which aims at providing data scientists a platform to build and deploy their models without the need of worrying about infrastructure, scalability, and performance. He is working on an Open Source Functions as a Service framework called firefly.

He is passionate about software development. He can also talk about Internet of Things, Electronics, Robotics with equal spirit. His journey with the field of software and robotics started in his schooling days. He represents the college in various Robotics competitions and was involved in projects related to the above domains, brief of which can be found here. He actively participates in conducting open lectures for students in the domains of Introductory Robotics, Control, AI and ML through a curated community of around 2000 members. He is also speaking at PyData Delhi 2017.

Speaker Links:

Homepage: https://nabarun.in
LinkedIn: https://www.linkedin.com/in/nabarunpal/
Github: https://github.com/palnabarun



# 4:

Do you know in the current micro services world, how to spot the critical parts of a monolith and replace them with modern efficient technologies? Have you ever wondered how Google or Netflix scale their traffic? For all these questions you should know how you can boost your web applications using Protocol Buffers and GRPC. Protocol Buffer is the data format that allows you to efficiently compose and read messages in binary format over HTTP/2. GRPC is a transport mechanism which delivers the protocol buffers over the wire. In the recent days, businesses may integrate with third party systems. For that to be smooth, any system can implement a micro service and others can consume it and vice versa.

Prerequisites:

Knowledge of JSON based REST services. Others will be covered in the talk.

Content URLs:

Talk's preliminary slides are here:

https://goo.gl/bb1RDh

Speaker Info:

enter image description here

Naren Arya, currently working as Software Engineer 2 at Citrix R&D, India. He is a Pythonista from the beginning. Currently joined the cloud services team in Citrix in a full stack development role. He is well known with his Python blog Impythonist. Gave many conference talks and presentations before. He is willing to share his knowledge of building micro services with Protocol Buffers & GRPC. Naren previously worked at few innovative startups like Knowlarity Cloud Telephony for integrating many different platforms using Django & BackboneJS.

He loves blogging on open source because it is the simplest way to explain things to the loving community. Apart from Python, he loves web development overall, best practices of scaling etc.

Speaker Links:

https://github.com/narenaryan

https://www.linkedin.com/in/narenarya/

https://impythonist.wordpress.com/

https://www.youtube.com/watch?v=NAwFrYcAY8Y

https://medium.com/@narenarya
