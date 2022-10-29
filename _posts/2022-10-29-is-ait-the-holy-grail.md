---
layout: post
title: "Is Automation that supports testing (AiT) the holy grail?"
date: 2022-10-29
author: "John Kronenberg"
header-img: "img/enschede.jpg"
tags: [testautomation, AiT]
---

A while back I watched a presentation by Richard Bradshaw on YouTube that he gave at SeleniumConf in 2019. You can view the presentation for yourself here. 

<iframe width="1280" height="720" src="https://www.youtube.com/embed/uIDvGzQdoxc" title="Redefining test automation | Richard Bradshaw | #SeConfLondon" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The title of his presentation was 'Redefining Testautomation' and I probably watched this presentation because of this interesting title. In recent years I wrote a series of articles for TestNet about how I see the role of testers and test automation in our field for now and in the future ([1](https://www.testautomate-it.com/2022/10/23/goodtesters/)), ([2](https://www.testautomate-it.com/2022/10/25/give-software-developers-the-testautomation-role-within-projects/)), ([3](https://www.testautomate-it.com/2022/10/25/software-engineer-in-test/)) and I see a lot of same ideas in Richard Bradshaw's presentation and with how I look at test automation, now and in the future. For me a reason to delve into Richard's work. I would like to give you an introduction to Richard Bradshaw's thinking.

## Personal note
As you can read in my previous articles about test automation, I see myself as a Software Engineer in Test. A bit exaggerated: 'I am an experienced tester, but I find automating testing more fun and challenging'. What strikes me, however, is that my client is actually not looking for a Software Engineer in Test at all, but, once again, 'someone who can also automate testing, but still finds testing more fun and challenging'. So I spend a lot of my time testing. Time I can't (and don't have to) spend on test automation. My first reaction to the above is that I am looking for a different relationship between testing versus test automation in my role, because I find test automation more fun and challenging. After delving into Richard Bradshaw's ideas, I understand better that if you really want to make a difference as a test professional, the relationship between testing and test automation should be closer together. I can agree with the way Rob van Steenbergen recently expressed it in an interview on TestNetNieuws: 'The focus on test automation (in the market) is quite intense and is becoming a pitfall'. Can Automation In Testing (AiT) help us shift this focus?

## Automation in Testing
What does Richard Bradshaw mean by Automation in Testing? His site https://automationintesting.com states: 

>“Automation in Testing (AiT) is a mindset and namespace that promotes human-centric automation within the context of testing.” 

I read here that test automation must support the testing process and that people (read: the tester) must be central in the automation process.

Automation in Testing has the following six principles:

- Supporting testing about replicating testing
- Testability over automatability
- Testing expertise about coding expertise
- Problems about tools
- Focusing on risk over coverage
- Observability over understanding

The principles are pretty self-explanatory. The focus of the principles is clearly on supporting testing with test automation rather than test automation as the starting point. I believe this is the strength of AiT. Testing continues to be important. Test automation stands next to testing and should not attempt to replace testing.

It is more important to have a testable application than an automatable application. In other words, not being able to automate a test case isn't so bad, as long as you can run the test case manually. For me a valid statement.

According to Richard, testautomation engineers should therefore be testers in the first place. Being able to program step definitions in Java, for example, is of course desirable, but if the programming skills are not sufficient to work out such a step definition yourself, a developer can always help or take over that task entirely. I'm fine with that. Although I do think that a Software Engineer In Test who has a good mix of both skills, i.e. "the sheep with five legs", does add something extra to a project.

"To someone with a hammer, everything looks like a nail." That's the risk you run when you take a test automation tool as a starting point to solve a project's test automation challenges. Test automation must be customised. A framework / tool should be chosen based on the challenges specific to the project for which you want to set up a framework. Don't fall into the trap of focusing on the tool. Make choices based on the project problems.

Testing is about covering risks, based on the idea that you never have enough time and resources to cover your entire application. In practice, clients are too often asked to automate all test cases. As a result, many projects have a high degree of test automation, but not necessarily covered the most important risks. What a shame.

I also agree with Richard's statement that fully understanding the application is less relevant than being able to observe and explore the application.

## Conclusion
In itself, Automation in Testing is not new, of course. It is a good counterbalance to the desire of clients to automate all test cases. As a test professional, it can do no harm to regularly review the principles of AiT. Software testing is not dead. It is just as important as in the years when test automation was not yet used on such a large scale. Nice to read that in AiT.

---

This article is published earlier in the TestNet Nieuws with the title "[Is Automation that supports testing de holy grail](https://www.testnet.org/artikelen/is-automation-that-supports-testing-ait-de-holy-grail)". The article was published on 25 februari 2021.