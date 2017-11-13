# Introduction

With the rise of interest in using Containers specially Docker as an industry standard for application containerization, the idea is that you should be able to deploy your application in any environment. Also, with the attention around building Microservices, and people breaking up their systems into smaller components to be able to be more reactive againts fast technology changes, we are seeing the fact that, each system, that in earlier days used to be just few components, if you ask some one for an architecture today, you will end up with a hand full of components, and you would even hear that the architect would like to have multiple instance of each running at the same time, for performance, zero-down-time, scalability and other reasons.

So, the good news is, with Docker and Containerization, it is so easy. We just have an image ready, and we just "run" them. Now imagine so many of these running in our infrastructure, and if one fails, or if we want to update a few of them! Then it becomes really challenging. 

Here is where the Orchestrators come into play, where they would help up better manage our army of containerized applications.



