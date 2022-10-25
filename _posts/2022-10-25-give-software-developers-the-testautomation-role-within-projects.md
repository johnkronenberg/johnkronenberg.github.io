---
layout: post
title: "give software developers the testautomation role within projects"
subtitle: "A threat or an opportunity?"
date: 2022-10-25
author: "John Kronenberg"
header-img: "img/post-bg-2015.jpg"
tags: [SDET, testautomation, TestNet]
---

I published two articles here last year. After my [first](https://www.testautomate-it.com/2022/10/23/goodtesters/) article, where I argueed for the tester with sufficient technical knowledge, I devoted a [second](https://www.testautomate-it.com/2022/10/25/software-engineer-in-test/) article to the role I recently performed for my clients: Software Engineer in Test. A logical follow-up to these two articles is to consider testautomation from the developer's point of view. More and more I see 'in the field' that developers take on the testautomation within projects. This article answers whether we, testers or testautomation engineers, should see that as a threat or as an opportunity.

## Argumentation
Let me immediately share my answer with you. When software developers take the testautomation role within our projects, it is generally a blessing for our field. I have the following arguments for this statement:

**It empowers testers and developers.**

In the previous articles I have already indicated that in my opinion testautomation is a form of software development. In general, testautomation engineers, or Software Engineers in Test, are more developers than testers. What I see in the market is that there is a scarcity of good testautomation engineers in the Netherlands. Don't get me wrong, there are plenty of good technical testers in the Netherlands, but many of them are not good in testautomation and/or don't really want to automate test. Developers, on the other hand, have programming in their DNA and, if the test framework is chosen wisely, they can develop the testautomation components in the programming language they already work on in the project. In my current project, the testautomation was set up in Cucumber, with the step definitions developed in Java. In my absence on the project, these components could have been developed just fine by the developers. This in turn creates space for the testers to do what they are good at: demonstrating the quality of the software.

**Testautomation done by developers supports the whole team approach.**

The strength of my current team is that we try to make good quality software together. As a team we came to the conclusion that we would like to be able to run our tests in parallel instead of sequentially. The sequential running ensured that our tests had a turnaround time of over an hour. As a result, it took the team far too long before we could make a statement about the quality of the delivered software. In order to enable parallel test execution, in addition to a software adjustment, two step definitions also had to be adjusted. As a team, we concluded that these adjustments in the step definitions could just as easily be done by a developer. Now that our developers have also helped set up the testautomation, I notice every day that the testautomation solution is also supported by the developers.

**The quality of the test automation is generally better if the developer has automated the tests than if the tester has automated the tests.**

Every tester who works with testautomation knows already that you don't have to be senior to be able to work as testautomation engineer, in the programming language in which the tests are programmed. The reason for this is quite simple. For example, to automate a GUI or an API you only need to master a relatively small part of the programming language. While in order to build this GUI or the API in this programming language, you will need to have a relatively huge knowledge level of the programming language. Providers of books and courses about test automation respond to this by, for example, publishing a 'Java for testers' book or offering a course of the same name. The above undoubtedly meets a need among testers. I support the premise that testers need to have sufficient, but not necessarily too much, knowledge of the programming language of the testing tool to be used. This does have the side effect that the testautomation will not have as good a quality as if the developer has set up the testautomation. The developer will set up the test automation using the same principles as he develops software (for example using clean code principles). As a result, you generally get more maintainable and transferable test automation.

## Conclusion
I conclude that it is an opportunity for the team if the developer helps with the testautomation. If you have a Software Engineer in Test in the team, you can of course make him/her responsible for the testautomation framework, but that does not alter the fact that the developer should also be able to help develop testautomation components in such a team set-up. If there are only technical testers on the team, it is a good idea to give the developer(s) responsibility for the testautomation framework. Testers then do not have to develop the testautomation components, but they can invest their time to design test scenarios in, for example, Cucumber.

---

This article is previously published in the [TestNet Nieuws](https://www.testnet.org/nieuwsmagazine/) with the title [Developers inzetten als testautomatiseerders. Een bedreiging of een kans?](https://www.testnet.org/artikelen/developers-inzetten-als-testautomatiseerders-een-bedreiging-of-een-kans) on 26 February 2020.