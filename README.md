# How big companies are using Kubernetes

## ```Kubernetes’ increased adoption is showcased by a number of influential companies which have integrated the technology into their services. Let us take a look at how some of the biggest companies of our time are successfully using Kubernetes.```

![image](https://user-images.githubusercontent.com/61896468/103122676-479ebc00-46a7-11eb-85ae-f68b29e6ca98.png)

## *The Docker or other container technology adoption is still growing exponentially, more and more companies have started using it in Production. It is important to use an orchestration platform to scale & manage your containers.*

## -->> Imagine a situation where you have been using Docker for a little while, and have deployed on a few different servers. Your application starts getting massive traffic, and you need to scale up fast, how will you go from 3 servers to 40 servers that you may require? And how will you decide which container should go where? How would you monitor all these containers and make sure they are restarted if they exit?

# ```This is where Kubernetes comes in.```

![image](https://user-images.githubusercontent.com/61896468/103122769-aebc7080-46a7-11eb-80b3-d48046e8770a.png)

## Kubernetes’ increased adoption is showcased by a number of influential companies which have integrated the technology into their services.

# `Let us take a look at how some of the most successful companies of our time are successfully using Kubernetes.`

# Tinder’s move to Kubernetes
Due to high traffic volume, Tinder’s engineering team faced challenges of scale and stability. What did they do?

Kubernetes – Yes, the answer is Kubernetes.

Tinder’s engineering team solved interesting challenges to migrate 200 services and run a Kubernetes cluster at scale totaling 1,000 nodes, 15,000 pods, and 48,000 running containers.

Was that easy? No ways. However, they had to do it for the smooth business operations going further. One of their Engineering leaders said, “As we onboarded more and more services to Kubernetes, we found ourselves running a DNS service that was answering 250,000 requests per second.” Fantastic culture, Tinder’s entire engineering organization now has knowledge and experience on how to containerize and deploy their applications on Kubernetes.

Read this fascinating case study [Here].

[Here]: https://medium.com/tinder-engineering/tinders-move-to-kubernetes-cda2a6372f44

Reddit’s Kubernetes story
Reddit is one of the top busiest sites in the world. Kubernetes forms the core of Reddit’s internal Infrastructure.

From many years, the Reddit infrastructure team followed traditional ways of provisioning and configuring. However, this didn’t go long until they saw some huge drawbacks and failures happening while doing the things the old way. They moved to ‘Kubernetes.’

![image](https://user-images.githubusercontent.com/61896468/103123216-951c2880-46a9-11eb-9659-e4c259cb3fb5.png)

See this [video] where their infrastructure release engineering manager describes the Kubernetes story at Reddit.

[video]: https://www.youtube.com/watch?v=z7TIzCAEo0M

The New York Times Journey to Kubernetes
Today the majority of their customer-facing applications are running on Kubernetes. What an amazing story:) The biggest impact has been to speed up deployment and productivity. Legacy deployments that took up to 45 minutes are now pushed in just a few. It’s also given developers more freedom and fewer bottlenecks. The New York Times has gone from a ticket-based system for requesting resources and weekly deploy schedules to allowing developers to push updates independently.

Check out the evolution & the fascinating story of The New York Times tech stack [Here].

[Here]: https://stackshare.io/posts/evolution-of-new-york-times-tech-stack

Airbnb’s Kubernetes story
Airbnb’s transition from a monolithic to a microservices architecture is pretty amazing. They needed to scale continuous delivery horizontally, and the goal was to make continuous delivery available to the company’s 1000 or so engineers so they could add new services. Airbnb adopted to support over 1000 engineers concurrently configuring and deploying over 250 critical services to Kubernetes (at a frequency of about 500 deploys per day on average). I want you to see this excellent presentation from [Melanie Cebula], the infrastructure engineer at Airbnb.

[Melanie Cebula]: https://twitter.com/MelanieCebula

![image](https://user-images.githubusercontent.com/61896468/103123438-5e92dd80-46aa-11eb-91a1-97b9359b919a.png)


Read more about this story here.

Pinterest’s Kubernetes story
With over 250 million monthly active users and serving over 10 billion recommendations every single day, that is huge. (The numbers might have changed now) As they knew these numbers are going to grow day by day, they began to realize the pain of scalability and performance issues.

Their initial strategy was to move their workload from EC2 instances to Docker containers; hence they first moved their services to Docker to free up engineering time spent on Puppet and to have an immutable infrastructure.

And then the next strategy was to move to Kubernetes:) Now they can take ideas from ideation to production in a matter of minutes whereas earlier they used to take hours or even days. They have cut down so much of overhead cost by utilizing Kubernetes and have removed a lot of manual work without making engineers worry about the underlying infrastructure.

Read the Pinterest Kubernetes story on their website ‘[Pinterest Case Study]’

[Pinterest Case Study]: https://kubernetes.io/case-studies/pinterest/

# Pokemon Go’s Kubernetes story
## How was ‘Pokemon Go’ able to scale so efficiently & became so successful? The answer is Kubernetes. Pokemon Go was developed and published by Niantic Inc. 500+ million downloads and 20+ million daily active users.

## ```Pokemon Go engineers never thought their user base would increase exponentially surpassing the expectations within a short time, they were not ready for it, and even the servers couldn’t handle this much traffic.```

![image](https://user-images.githubusercontent.com/61896468/103123605-ee388c00-46aa-11eb-9dfb-d7700097dde7.png)


# The challenge
## ``The horizontal scaling on one side but Pokemon Go also faced a severe challenge when it came to vertical scaling because of the real-time activity by millions of users worldwide. Niantic was not prepared for this.``

# The solution
## *The magic of containers. The application logic for the game ran on Google Container Engine (GKE) powered by the open source Kubernetes project. Niantic chose GKE for its ability to orchestrate their container cluster at planetary-scale, freeing its team to focus on deploying live changes for their players. In this way, Niantic used Google Cloud to turn Pokémon GO into a service for millions of players, continuously adapting and improving. This got them more time to concentrate on building the game’s application logic and new features rather than worrying about the scaling part.*



# `Impressive, isn’t it? Read the complete case study shared on [Google Cloud].`

[Google Cloud]: https://cloud.google.com/blog/products/gcp/bringing-pokemon-go-to-life-on-google-cloud

# Conclusion
## `Around the world, many CIO’s and technologists have chosen to use Kubernetes, and it is expected to evolve much more in the years to come.`

## ```<u><b>Containers are becoming more and more popular in the software world and Kubernetes has become the industry standard for deploying containers in production. We will expect a high growth rate of Kubernetes this year too.</b></u>```


