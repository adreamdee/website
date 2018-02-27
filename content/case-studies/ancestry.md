---
title: Ancestry Case Study
date: "2015-10-10T13:07:31+02:00"
tags: ["ipsum"]
type: "case-studies"
categories: ["lorem"]
banner: "img/banners/banner-5.jpg"
---

<div class="banner1">
  <h1> CASE STUDY:<img src="http://c.mfcreative.com/i/logo/ancestry-on-dark.svg" width="22%" style="margin-bottom:-12px;margin-left:3px;"><br> <div class="subhead">Digging Into the Past With New Technology</div></h1>
</div>

<div class="details">
  Company &nbsp;<b>Ancestry</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Location &nbsp;<b>Lehi, Utah</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Industry &nbsp;<b>Internet Company, Online Services</b>
</div>

<hr>

<section class="section1">
<div class="cols">
<div class="col1">

<h2>Challenge</h2>
Ancestry, the global leader in family history and consumer genomics, uses sophisticated engineering and technology to help everyone, everywhere discover the story of what led to them. The company has spent more than 30 years innovating and building products and technologies that at their core, result in real and emotional human responses. <a href="https://www.ancestry.com">Ancestry</a> currently serves more than 2.6 million paying subscribers, holds 20 billion historical records, 90 million family trees and more than four million people are in its AncestryDNA network, making it the largest consumer genomics DNA network in the world. The company's popular website, <a href="https://www.ancestry.com">ancestry.com</a>, has been working with big data long before the term was popularized. The site was built on hundreds of services, technologies and a traditional deployment methodology. "It's worked well for us in the past," says Paul MacKay, software engineer and architect at Ancestry, "but had become quite cumbersome in its processing and is time-consuming. As a primarily online service, we are constantly looking for ways to accelerate to be more agile in delivering our solutions and our&nbsp;products."

<br>

</div>

<div class="col2">
  <h2>Solution</h2>

  The company is transitioning to cloud native infrastructure, using <a href="https://www.docker.com">Docker</a> containerization, <a href="https://kubernetes.io">Kubernetes</a> orchestration and <a href="https://prometheus.io">Prometheus</a> for cluster monitoring.<br>
<br>
<h2>Impact</h2>
  "Every single product, every decision we make at Ancestry, focuses on delighting our customers with intimate, sometimes life-changing discoveries about themselves and their families," says MacKay. "As the company continues to grow, the increased productivity gains from using Kubernetes has helped Ancestry make customer discoveries faster. With the move to Dockerization for example, instead of taking between 20 to 50 minutes to deploy a new piece of code, we can now deploy in under a minute for much of our code. We’ve truly experienced significant time savings in addition to the various features and benefits from cloud native and Kubernetes-type technologies."
</div>
</div>
</section>

<div class="banner2">
  <div class="banner2text">
    "At a certain point, you have to step back if you're going to push a new technology and get key thought leaders with engineers within the organization to become your champions for new technology adoption. At training sessions, the development teams were always the ones that were saying, 'Kubernetes saved our time tremendously; it's an enabler. It really is incredible.'"<br><br><span style="font-size:16px">- PAUL MACKAY, SOFTWARE ENGINEER AND ARCHITECT AT ANCESTRY</span>
  </div>
</div>

<section class="section2">
<div class="fullcol">
<h2>It started with a Shaky Leaf.</h2>

    Since its introduction a decade ago, the Shaky Leaf icon has become one of Ancestry's signature features, which signals to users that there's a helpful hint you can use to find out more about your family tree.<br><br>
    So when the company decided to begin moving its infrastructure to cloud native technology, the first service that was launched on <a href="https://kubernetes.io">Kubernetes</a>, the open source platform for managing application containers across clusters of hosts, was this hint system. Think of it as Amazon's recommended products, but instead of recommending products the company recommends records, stories, or familial connections. "It was a very important part of the site," says Ancestry software engineer and architect Paul MacKay, "but also small enough for a pilot project that we knew we could handle in a very appropriate, secure way."<br><br>
    And when it went live smoothly in early 2016, "our deployment time for this service literally was cut down from 50 minutes to 2 or 5 minutes," MacKay adds. "The development team was just thrilled because we're focused on supplying a great experience for our customers. And that means features, it means stability, it means all those things that we need for a first-in-class type operation."<br><br>
    The stability of that Shaky Leaf was a signal for MacKay and his team that their decision to embrace cloud native technologies was the right one for the company. With a private data center, Ancestry built its website (which launched in 1996) on hundreds of services and technologies and a traditional deployment methodology. "It worked well for us in the past, but the sum of the legacy systems became quite cumbersome in its processing and was time-consuming," says MacKay. "We were looking for other ways to accelerate, to be more agile in delivering our solutions and our products."
</div>
</section>

<div class="banner3">
  <div class="banner3text">
"And when it [Kubernetes] went live smoothly in early 2016, 'our deployment time for this service literally was cut down from 50 minutes to 2 or 5 minutes,' MacKay adds. 'The development team was just thrilled because we're focused on supplying a great experience for our customers. And that means features, it means stability, it means all those things that we need for a first-in-class type operation.'"
  </div>
</div>

<section class="section3">
<div class="fullcol">
  That need led them in 2015 to explore containerization. Ancestry engineers had already been using technology like <a href="https://www.java.com/en/">Java</a> and <a href="https://www.python.org">Python</a> on Linux, so part of the decision was about making the infrastructure more Linux-friendly. They quickly decided that they wanted to go with Docker for containerization, "but it always comes down to the orchestration part of it to make it really work," says MacKay.<br><br>
  His team looked at orchestration platforms offered by <a href="https://docs.docker.com/compose/">Docker Compose</a>, <a href="http://mesos.apache.org">Mesos</a> and <a href="https://www.openstack.org/software/">OpenStack</a>, and even started to prototype some homegrown solutions. And then they started hearing rumblings of the imminent release of Kubernetes v1.0. "At the forefront, we were looking at the secret store, so we didn't have to manage that all ourselves, the config maps, the methodology of seamless deployment strategy," he says. "We found that how Kubernetes had done their resources, their types, their labels and just their interface was so much further advanced than the other things we had seen. It was a feature fit."<br><br>
  <div class="quote">
  Plus, MacKay says, "I just believed in the confidence that comes with the history that Google has with containerization. So we started out right on the leading edge of it. And we haven't looked back since."</div><br>
  Which is not to say that adopting a new technology hasn't come with some challenges. "Change is hard," says MacKay. "Not because the technology is hard or that the technology is not good. It's just that people like to do things like they had done [before]. You have the early adopters and you have those who are coming in later. It was a learning experience on both sides."<br><br>
  Figuring out the best deployment operations for Ancestry was a big part of the work it took to adopt cloud native infrastructure. "We want to make sure the process is easy and also controlled in the manner that allows us the highest degree of security that we demand and our customers demand," says MacKay. "With Kubernetes and other products, there are some good solutions, but a little bit of glue is needed to bring it into corporate processes and governances. It's like having a set of gloves that are generic, but when you really do want to grab something you have to make it so it's customized to you. That's what we had to do."<br><br>
  Their best practices include allowing their developers to deploy into development stage and production, but then controlling the aspects that need governance and auditing, such as secrets. They found that having one namespace per service is useful for achieving that containment of secrets and config maps. And for their needs, having one container per pod makes it easier to manage and to have a smaller unit of deployment.
<br><br>
</div>
</section>

<div class="banner4">
<div class="banner4text">

"The success of Ancestry's first deployment of the hint system on Kubernetes helped create momentum for greater adoption of the technology."

</div>
</div>

<section class="section4">
<div class="fullcol">
  With that process established, the time spent on deployment was cut down to under a minute for some services. "As programmers, we have what's called REPL: read, evaluate, print, and loop, but with Kubernetes, we have CDEL: compile, deploy, execute, and loop," says MacKay. "It's a very quick loop back and a great benefit to understand that when our services are deployed in production, they're the same as what we tested in the pre-production environments. The approach of cloud native for Ancestry provides us a better ability to scale and to accommodate the business needs as work loads occur."<br><br>
  The success of Ancestry's first deployment of the hint system on Kubernetes helped create momentum for greater adoption of the technology. "Engineers like to code, they like to do features, they don't like to sit around waiting for things to be deployed and worrying about scaling up and out and down," says MacKay. "After a while the engineers became our champions. At training sessions, the development teams were always the ones saying, 'Kubernetes saved our time tremendously; it's an enabler; it really is incredible.' Over time, we were able to convince our management that this was a transition that the industry is making and that we needed to be a part of it."<br><br>
  A year later, Ancestry has transitioned a good number of applications to Kubernetes. "We have many different services that make up the rich environment that [the website] has from both the DNA side and the family history side," says MacKay. "We have front-end stacks, back-end stacks and back-end processing type stacks that are in the cluster."<br><br>
  The company continues to weigh which services it will move forward to Kubernetes, which ones will be kept as is, and which will be replaced in the future and thus don't have to be moved over. MacKay estimates that the company is "approaching halfway on those features that are going forward. We don't have to do a lot of convincing anymore. It's more of an issue of timing with getting product management and engineering staff the knowledge and information that they need."
</div>
</section>

<div class="banner5">
  <div class="banner5text">
    "... 'I believe in Kubernetes. I believe in containerization. I think
    if we can get there and establish ourselves in that world, we will be further along and far better off being agile and all the things we talk about,
    and it'll&nbsp;go&nbsp;forward.'"
  </div>
</div>

<section class="section5">
<div class="fullcol">


Looking ahead, MacKay sees Ancestry maximizing the benefits of Kubernetes in 2017. "We're very close to having everything that should be or could be in a Linux-friendly world in Kubernetes by the end of the year," he says, adding that he's looking forward to features such as federation and horizontal pod autoscaling that are currently in the works. "Kubernetes has been very wonderful for us and we continue to ride the wave."<br><br>
That wave, he points out, has everything to do with the vibrant Kubernetes community, which has grown by leaps and bounds since Ancestry joined it as an early adopter. "This is just a very rough way of judging it, but on Slack in June 2015, there were maybe 500 on there," MacKay says. "The last time I looked there were maybe 8,500 just on the Slack channel. There are so many major companies and different kinds of companies involved now. It's the variety of contributors, the number of contributors, the incredibly competent and friendly community."<br><br>
As much as he and his team at Ancestry have benefited from what he calls "the goodness and the technical abilities of many" in the community, they've also contributed information about best practices, logged bug issues and participated in the open source conversation. And they've been active in attending <a href="https://www.meetup.com/Utah-Kubernetes-Meetup/">meetups</a> to help educate and give back to the local tech community in Utah. Says MacKay: "We're trying to give back as far as our experience goes, rather than just code."
<br><br>When he meets with companies considering adopting cloud native infrastructure, the best advice he has to give from Ancestry's Kubernetes journey is this: "Start small, but with hard problems," he says. And "you need a patron who understands the vision of containerization, to help you tackle the political as well as other technical roadblocks that can occur when change is needed."<br><br>
With the changes that MacKay's team has led over the past year and a half, cloud native will be part of Ancestry's technological genealogy for years to come. MacKay has been such a champion of the technology that he says people have jokingly accused him of having a Kubernetes tattoo.<br><br>
"I really don't," he says with a laugh. "But I'm passionate. I'm not exclusive to any technology; I use whatever I need that's out there that makes us great. If it's something else, I'll use it. But right now I believe in Kubernetes. I believe in containerization. I think if we can get there and establish ourselves in that world, we will be further along and far better off being agile and all the things we talk about, and it'll go forward."<br><br>
He pauses. "So, yeah, I guess you can say I'm an evangelist for Kubernetes," he says. "But I'm not getting a tattoo!"


</div>
</section>