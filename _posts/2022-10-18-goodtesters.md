---
layout:       post
title:        "Good testers are not good testautomation engineers"
subtitle:     "So what?"
author:       "John Kronenberg"
date:       2022-10-23 10:00:00
header-img: "img/post-bg-2015.jpg"
catalog:      true
tags:
    - testautomation
    - SDET
---

Over the past decade, the role of the tester has changed drastically, dramatically for many. In addition to testing skills, today's tester must also be very technically savvy. Today's tester must also be able to set up test automation and, for example, be able to program fixtures in Java, develop Selenium Webdriver scripts or maintain Cucumber step definitions.

At my current client, I am in a position to review resumes for new employees. What strikes me about the resumes is that many of the applicants, with a rock-solid testing background, have written test automation in their resumes, because that was the job offer or because otherwise he/she would never be hired for a test role again. But not because they have the ambition and personal qualities to become good at test automation. Test automation and testing are two different roles. A good baker is generally not a good butcher, this also applies to a tester versus a testautomation engineer. The question I want to answer in this blogpost is whether that is a bad thing. Shouldn't we just let (technical) testers be good (technical) testers? Isn't there room on current projects for good (technical) testers as well as good test automation engineers/developers?

## What is test automation?

Before I try to make my point, I want to first describe what I mean by test automation. In fact, the word test automation doesn't accurately cover what this blog post is about at all. Automated testing is a better term. In my opinion, the following definition covers it:

>'Automated testing is the act of conducting specific tests via automation (i.e., a set of regression tests) as opposed to conducting them manually, while test automation refers to automating the process of tracking and managing the different tests.'

If you look at it this way, only a small part of test automation is the automation and automated execution of regression tests, whereby test automation itself is also a small part of another container term: [Continuous Testing](https://en.wikipedia.org/wiki/Continuous_testing). What a senior test engineer is skilled at is essentially only a small part of what the field currently expects a good tester to be able to do. A testautomation engineer is skilled in implementing a test automation framework, in which test artefacts have a place, and programming the code (Java, Python, Javascript, etc.) to automatically execute these test artefacts. If someone asks me what my role is for customers, I say that I am a [Software Engineer in Test](https://blog.testproject.io/2018/11/06/the-software-engineer-in-test/#:~:text=What%20is%20a%20Software%20Engineer,running%20tests%20quickly%20and%20repeatedly.), I automate tests.

To take BDD as an example. Creating feature files, setting up test scenarios and defining test steps can easily be done by a tester, or in a Three Amigo's setting. A testautomation engineer can be made responsible for translating these test steps in test automation code (step definitions).

## Good testers are still needed

I believe that there are (should be) a lot of opportunities for well-trained, modern testers, with a healthy portion of technical knowledge, but without knowledge of and affinity with creating test automation code. Test automation is a specialist role that can be performed by a skilled test engineer or a developer. The skills to be a good tester are not the skills to be a good testautomation engineer and it shouldn't be a big deal. In my opinion, the role that a tester should take is to support the testautomation engineer or developer. He can maintain test automation code, he helps create Jenkins jobs and conducts exploratory testing sessions, has a lot of technical knowledge, understands what web services and APIs are. In addition to test automation, projects still need good testers. It is a nice bonus that testers can also take care of the test automation role, but in my opinion this is not necessary.

## Conclusion

When I started my career as a test automation engineer, [TestFrame](https://nl.wikipedia.org/wiki/TestFrame) was very hot. Within TestFrame there was a clear delineation of the roles of tester and testautomation engineer. The tester ("testanalist") was responsible for creating the Excel sheets with action words and the test engineer ("testnavigator") was programming the action words. This is a very powerful division of roles. I wish the field would realize that, while with sufficient understanding of the work of testautomation engineers, testers should be doing what they have become good at, testing, and not be forced to take on a role that doesn't fit well for them. That is to the benefit of the entire testing community. Both testing and test automation as a profession are then taken seriously (again).

---

This article is also published in Dutch in the TestNetNieuws from the Dutch Association for Testers, TestNet, on 10th July 2019.
 
[https://www.testnet.org/artikelen/goede-testers-zijn-geen-goede-testautomatiseerders-so-what/](https://www.testnet.org/artikelen/goede-testers-zijn-geen-goede-testautomatiseerders-so-what/)

