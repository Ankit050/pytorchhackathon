# BeyondVision.ai - PyTorch Summer Hackathon

## Inspiration
Wildfires are one of the biggest recurring problems faced in California today. They cause loss of life and property and are extremely expensive. In the US, there are 4.5 million homes at risk of being affected by wildfires, with 2 million being in California. Over the past 10 years, losses from wildfires have gone beyond $5.1 billion. Being students in Berkeley, this affects us dearly and we wanted to use our technical skills to combat the problem. When we got to know about drones flying over wildfire affected regions, we realized that creating a system to help first responders would be beneficial in terms of time and cost, and would help people that have already been through a lot of suffering.

Another aspect of wildfires is the reason that they are caused. When we got to know about last year's fires being caused due to vegetation impacting utility cables, we sought to look at prevention aspect as well, so as to have a well rounded solution. Most utility infrastructure is very old and requires regular maintenance. However, it is hard to prioritize which infrastructure to inspect first, since the process is extremely manual and individuals are required to drive down and look at the affected poles/cables. As drones get adopted to fly over these poles and cables for inspection, they generate a lot of images which have to be manually looked through. This takes time and effort, and has also been inaccurate over time because of fatigue. To combat this problem, we wanted to create a first level solution that could categorize images in categories and reduce the number to be looked at, so as to speed up the decision making process, and thus prevent wildfires by timely maintenance.

We wanted to use the Computer Vision capabilities of drones and the resources provided by PyTorch to create a positive impact on businesses (like PG&E) and people by protecting them and even helping them recover after a disaster.

## Demo Video on Youtube
https://youtu.be/3ry-XFrLBKE

## Live Demo
https://beyondvision-ai.onrender.com

## Running on localhost
You can run the application locally by installing Docker and using the following command:
```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```
