---
title: "Resigned Rakuten Group"
date: 2022-07-11T00:00:00+09:00
draft: false
toc: false
images:
tags:
  - blog
  - resignation
---
I had retired in April 2022 from Rakuten Group, Inc. where I had joined as a new graduate in 2011. (At the time of joining the company, it was Rakuten, Inc. The company will be simply referred to as "Rakuten" hereafter.)

I had been working for the same company for more than 10 years. In fact, I have already been working for the next company. I decided to share my thoughts here mainly for the following reasons:

* I have been so busy recently that I thought it would be good to have a chance to stop and reflect on my life for a while.
* I had a feeling (no evicence though) that some might want to read these stories, although it doesn't seem like many.
* I wanted to write a so-called "retirement entry" at least once in my life.
* I set up a blog system based on Hugo and Github Pages, but I wanted something new to write and upload to it to see how the blog system's post management experience would be.


### What have I done in Rakuten?

I completed my master's degree in March 2011. Since I joined Rakuten as an application engineer as a new graduate the following month, I have managed to survive while occasionally avoiding fighting city hall, and occasionally finding interesting things to do on my own.

I have worked in various departments. One of them was an internal IT department, and another one of them was a department that provides membership management platforms to other development teams. From a primarily engineering perspective, the things I've done in-house include:

* Bug fixes and version upgrades and server relocations of services for small end users.
* System implementation and operation of Atlassian's collaboration tools (Jira, Confluence, etc.).
* A training trip to a subsidiary in Spain and database migration of an internal tool created there in Ruby on Rails.
* Design and implementation of a deployment pipeline in Jenkins.
* Management and operation of a Hive/Hadoop based data warehouse and ETL infrastructure (I think I actually did both roles, which would be called data engineer and data steward).

The above sounds kind of boring when written so succinctly, but I had the opportunity to do a lot of interesting things technically. For example, I took care of everything from installing middleware to running applications on a fresh CentOS server, set up Kubernetes and built a workflow engine on top of it, created a system to measure the SLO of the services we had in our department, and made sure it was tracked as a KPI for the team.

I started out working at the Tokyo headquarter (Rakuten Tower in Shinagawa Seaside and Rakuten Crimson House in Futakotamagawa since 2015), but after getting married and having a child, I wanted to work in my hometown (Kyoto) and was transferred to the Osaka office in 2019 with my job. （I am grateful to the company for accepting my request.)

### Was English no problem for you?

Rakuten is famous for the fact that English is the official language of the company. Although you were never forced to communicate in English when you were surrounded by only Japanese speakers, the personnel system was designed to put us at a great disadvantage if you could not speak English. There were a number of employees who left the company because they had difficulty with English.

Fortunately, in my case, I was not afraid of English, and I was able to get along with my work even in a team with only non-Japanese speakers. However, while speaking in English, I have the feeling that the content of what I want to talk about is 30% less than if I were speaking only Japanese...


### Why did I decide to change jobs?

The decisive reason was that Rakuten was no longer proactive about its employees working remotely.

The COVID-19 pandemic had begun in Japan in 2020, and Rakuten had followed suit by requiring employees to work from home in principle. Until then, I had to commute over an hour each way from Kyoto to Osaka, but that suddenly disappeared, allowing me to spend more time with their children and greatly improving their work-life balance.

I thought I would be happy if I could continue this way of working even after COVID settled down, but as [this Yahoo News article](https://news.yahoo.co.jp/articles/04e5a9014af621eb440233c7ff4d5f37b6db0fec) explains, Rakuten's final thought was that employees would, in principle, have to come into the office four times a week.

I was, at the moment this policy was shared with me last November, I thought,
**"NO WAY😇"**,
so I decided to contact an agent and begin my job search.


### Job Search

#### What kind of company would I like to work for? 🤔

I first thought about what kind of company I would like to work for when looking for a new job, and the following criteria came up:

* **Full remote work or an obligation to come to work less than about once a week (and a commute load less than the same as my current position).** Fully remote was preferred, but I was willing to commute to the office on a low frequency basis as long as the office was within about the same distance from my home as my current position.

* **The management of the company must have the value that doing business globally.** I was aware of the issue, "As Japan's economic presence in the world declines, will we have no choice but to taper off if our business is confined to Japan?" I worried whether I could share this awareness with the company's management team.
* **Having a culture similar to that of the incumbent company.** Although I had not yet successfully verbalized the requirements for this culture during my job search, I avoided so-called JTC (Japanese traditional companies) because I thought they would not be a good fit for me.


#### What should I sell myself? 🤔

I know big data, I know infrastructure, I know DevOps, I can write backend applications, I've done some engineering lead work. I can perform tasks in English with no problem. I can get agreement with people in the company appropriately and work on projects that go beyond the boundaries of the team.

I thought that sounds great, but I was probably more of a half-baked person. I thought that **"you can do everything" is same as "you can do nothing"**.

I had the sense that most of the jobs that appeared in the recruitment postings of the stiff companies, which were looking for someone with as many years of experience as I had, were usually looking for a **tough senior black mage** who could fire a lot of Thundagas and contribute a lot to defeating Omega. Never a **mid-career red mage** who can manage to shoot both Cairra and Fira in a real fight... (on par with FF5)

#### Results

Am I alright? Is there a job out there like this? 🤔 and I was worried at first.

Nevertheless, after about three months of job hunting, I finally received two offers for data engineering-related positions and one as an SRE. All of them were miraculous positions that met all three of the above conditions! After much deliberation, I decided to accept one of the offers, as a **Data Manager** at **Merpay Corporation**.

I joined the company in May and have been with the company for a little over two months now, and so far I am enjoying my work.

### What was good and not so good about Rakuten?
I'm sure a good percentage of you reading this article are considering seeking jobs at Rakuten. Perhaps this is the kind of information you would like to know, so let me share it with you here.

#### Good points

  * **They have a strong will to do business and win in the world.** The will of this company was repeatedly communicated within the company. It was easy to do because it fit with my ideas I explained in the job search chapter.
  * **Even if something is not looking good, attempts to involve everyone to improve is welcomed and appreciated. There is a climate in which such improvements can happen on an ongoing basis.** To give you an example, the desktop PC I was provided when I joined the company in 2011 had a Pentium 4 and 1GB of memory. The specs were already about 4 years old, and it took 30 minutes from the time I turned it on to complete Outlook startup. I thought, **"the company thinks it's enough for engineers to work with this level of PC... How inhumane...😮‍💨"** But after a few months, high-spec PCs were provided to those who wanted them, and from then on, PCs with resonable spec were deployed.
  * **I was allowed to do what I wanted to do.** I think this depends on the department, but I was welcomed to challenge new technologies and systems. I did a lot of things such as testing and using popular technologies by myself.
  * **The annual salary was probably not bad.** Especially in the last few years, it is said that the demand for software engineers is far exceeding the supply, and annual salaries are on the rise worldwide. To keep up with this trend, the company was raising salaries of employees. I was happy to see my annual salary go up along with it, although it was probably partly due to the fact that I was producing good results.


#### No-good points.

  * **The company does not seem to be good at communicating with its employees.**
  When the company says, "We are going to change the personnel system," employees are never asked for their opinions before the change is made. The process of discussion leading up to important decisions involving the entire company is rarely made public. The decision to restrict remote working, which was the reason for my job change, was simply stated as a decision in an article that suddenly appeared on the company intranet, without any explanation of the background or reasons for the decision.

### Conclusion

I left Rakuten because remote working becomes more difficult there. But even though there were some minor issues, I don't think there was anything else that I fatally disliked about the company. If you are a person who can fit in with Rakuten's culture and the above mentioned negative points are not a problem for you, I can still say that Rakuten is a good company to work.
