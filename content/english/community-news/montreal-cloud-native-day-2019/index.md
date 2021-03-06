---
title: "Montreal Cloud Native Day 2019"
date: "2018-06-21"
author: "CloudOps"
description: Montreal’s first Cloud Native Day was last Tuesday. The event brought together Kubernetes and cloud native communities from across Eastern Canada and featured a full day of talks.
resources:
- name: "thumbnail"
  src: "CDN.png"
class_name: "blog post"
aliases:
    - /2019/06/montreal-cloud-native-day-2019/
    - /montreal-cloud-native-day-2019/
keywords: [montreal cloud native day 2019, cloud native day, eastern canada devops, kubernetes]
tags:
---

<p>Montreal’s first Cloud Native Day was last Tuesday. The event brought together Kubernetes and cloud native communities from across Eastern Canada and featured a full day of talks. The event was attended by over 200 cloud native enthusiasts and culminated the Kubernetes and cloud native meetups run by CloudOps in Montreal, Toronto, Ottawa, Kitchener-Waterloo, and Quebec City.</p>

<p>Luc Perkins from the CNCF and Vicky Brasseur from Juniper Networks began the day with a keynote called ‘A well-grounded Cloud: Exploring the foundations of cloud native.’ Cloud native architectures have become the default for software today, but merit isn’t the only factor that leads to its success. Cloud native architectures require solid foundations in order to reach for the skies.</p>

<div class="wp-block-image"><img style="width: 50%; float: left; margin: 5px 20px 20px 0;" src="/images/blog/post/original.png"></div>

<p>Following Luc and Vicky, Ian Crosby from Container Solutions presented ‘<a href="https://www.slideshare.net/CloudOps2005/kubernetes-crossing-the-chasm">Kubernetes: Crossing the Chasm</a>.’ The chasm between early market and mainstream market adoption can be difficult to cross but is essential for projects to evolve from having minimum feature sets and being whole product solutions. Ian Crosby from Container Solutions presented how Kubernetes crossed this chasm and what that means for the future of cloud native applications.</p>

<p>After a break, CloudOps’ own Syed Ahmed presented ‘The Containerization of Machine Learning: Kubeflow.’ Kubeflow assimilates Tensorflow, JupyterHub, and other ML tools into a complete stack that can be deployed alongside Kubernetes in multi-cloud environments. It helps ML algorithms become as portable and scalable as Kubernetes. Syed then gave a demo to help community members get their hands dirty with ML.</p>

<p>Viktor Gamov from Confluent gave a talk called ‘<a href="https://www.slideshare.net/CloudOps2005/kafka-on-kubernetes">Streams must flow: developing fault-tolerant stream processing application with Kafka Streams and Kubernetes</a>.’ Kafka Streams is Apache Kafka’s stream processing library. It lets developers build and deploy sophisticated stream processing applications in multi-cloud environments. Viktor explained the essentials of dynamic scaling and state migration in Kafka Streams and performed a demo of how a Kafka Streams application can be run in a Docker container and scaled with Kubernetes. This can help developers deal with ever-changing data at low latency.</p>

<p>Morgan Martinet and Marc Khouzam then gave Cloud Native Day a fully Canadian spin with a talk discussing <a href="https://www.slideshare.net/CloudOps2005/plateformes-et-infrastructure-infonuagique-natif-de-ville-de-montrall">the City of Montreal’s software development life cycles</a>. They described how an architecture was put in place for microservices to develop in NodeJS and execute in Kubernetes. Jenkins was used to develop a DSL that would simplify adoption and operations. Morgan and Marc demonstrated all the steps taken from the creation of a new API project to deployment in production.</p>

<p>Raymond Maika and Moh Ahmed then presented ‘<a href="https://www.slideshare.net/CloudOps2005/using-rook-to-manage-kubernetes-storage-with-ceph">Using Rook to Manage Kubernetes Storage with Ceph.</a>’ They demonstrated a running Rook cluster that uses Ceph as its backend. They upgraded Ceph in the cluster to exhibit more independence between the operator and its storage backends.</p>

<p>Kharthik Prabhakar from Tigera then presented ‘Identity, AuthN and AuthZ for Zero Trust Workload Security,’ where he discussed how they can be enabled within Kubernetes and service meshes. He shared some emerging patterns that can be seen from operationalizing interconnected Kubernetes services with Istio Citadel, Envoy, and Calico. He then performed a demo that showed how they can be connected to enable zero-trust security. Security is important for cloud native applications.</p>

<p>Cloud Native Day continued with James Munelly from JetStack presenting ‘Cert manager: using Kubernetes as an automated x509 management platform.’ Cert-manager is often used to secure websites using Let’s Encrypt TLS certificates, but it can also used for advanced PKI management. James walked through how Issuers and Certificates can be used as building blocks for complex PKIs to secure user applications, ingresses, Kubernetes system components and webhooks, and external systems.</p>

<p>Nicolas Seigneur from IDStacks gave a talk called ‘Compliance and Security in a Cloud Native World.’ DevSecOps is becoming essential for securing cloud native applications. He discussed how IDStacks’ DevSecOps implements security with tools including Comply, Jira, Hashicorp &nbsp;Vault, and Twistlock. This helps build a highly secure platform that can meet requirements for compliance. He provided an overview of key topics for cloud native security, such as vulnerability scanning, image admission, compliance patching strategy, CI/CD integration, network security, intrusion detection, and runtime protection.</p>

<p>Following Nicolas, Don Bowman of Agilicus presented <a href="https://www.slideshare.net/CloudOps2005/defense-in-depth-securing-your-new-kubernetes-cluster-from-the-challenges-that-lurk-within">‘Defense in Depth: Securing your new Kubernetes cluster from the challenges that lurk within.</a>’ Containers themselves are not a strong security barrier. His talk assumed that threats have already entered your environment, and offered steps that can be taken to mitigate any damage. This includes looking at the service mesh, logging, network policy, reduction in privilege, rbac, roles, and filesystems amongst other things. He showed a checklist of activities to include in your DevOps cycles that will help shift security left and automate as much as possible.</p>

<p>Ian Rae, founder of CloudOps, concluded Cloud Native Day by speaking about the importance of cloud native in <a href="https://www.slideshare.net/CloudOps2005/own-your-destiny-in-the-cloud-ian-rae-cloud-native-day-montreal-2019">owning one’s destiny in the cloud</a>. Open source software can be at the heart of this, especially as the landscape of cloud native technologies has exploded in the past few years and can be difficult to navigate. Lean, agile, and DevOps methodologies will help teams make the most of open source solutions as they will break down the wall of confusion that pits the developer’s need for change against the operator’s need for stability. Security must be integrated into DevOps pipelines, and technical upskilling requires cultural change. Ultimately, it’s all about the people and what they learn, not only from trainings but also from community.</p>

<div class="wp-block-image"><img style="width: 50%; float: right; margin: 5px 0 20px 20px;" src="/images/blog/post/medium.png" alt="" class="wp-image-9197" width="332" height="186"></div>

<p>It was great seeing local communities from across Eastern Canada get together. Thank you to all attendees and all speakers. Thank you Pizzeria Bros for an awesome lunch. Thank you to Instana, GitHub, Rancher, Aqua Security, Elastic, Container Solutions, Red Hat, HashiCorp, cloud.ca, OneSpan, Cloudbees, MayaData, and Citrix for sponsoring the event.</p>

<p>Become a part of this growing community by joining the <a href="http://k8scanadaslack.herokuapp.com">Canadian Kubernetes Slack channel</a> or the pages for the local meetups in <a href="https://www.meetup.com/Kubernetes-Quebec/">Quebec City</a>, <a href="https://www.meetup.com/Kubernetes-Ottawa/">Ottawa</a>, <a href="https://www.meetup.com/Kubernetes-Montreal/">Montreal</a>, <a href="https://www.meetup.com/Kubernetes-Kitchener-Waterloo/">Kitchener-Waterloo</a>, and <a href="https://www.meetup.com/Kubernetes-Toronto/">Toronto</a>. DevOpsDays Montreal will take place on November 5th and 6th, so stay tuned for this next event where community members will get together to learn, grow, and meet like-minded individuals.</p>

<p><iframe width="560" height="315" src="https://www.youtube.com/embed/mBQIJ23TMWI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe></p>