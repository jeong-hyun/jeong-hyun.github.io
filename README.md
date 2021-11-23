# Automated Software Testing

## Introduction
In this post, we are going to delve into a technology that is becoming more and more widely-used in today’s software industry, **Automated Software Testing**. 
As the use of software turned into an inseparable part of our modern society, the need to guarantee the quality of the software has never been greater. 
In the past, traditional manual testing was a popular methodology to ensure functionalities of software. 
However, this trend has been less dominant in today’s world due to its limitations below. 
1. **Slow and costly**: it is labor-intensive, thus, it takes an extensive amount of time and labor to write tests.  
2. **Lack of scalability**: as the target software becomes more and more complicated, writing tests for the software becomes exponentially more complex. 
3. **Prone to errors**: as manual testing is conducted by humans, errors and bugs are more likely to occur. 
Because of the above reasons, automated testing has gained more popularity over manual testing in today’s software industry. 
This post will encompass broad knowledge on automated testing, from the basics of automated testing and its strategy to advantages as well as disadvantages. 

## What is Automated Testing? 
Automated software testing is **_a method of implementing special software tools to automate a human-driven process of reviewing and validating a software application_**. 
(Rehkopf, "Automated software Testing") By automating repetitive and simple testing processes through automated testing, we can avoid the flaws that manual testing has 
as stated above. 

## What are the Advantages of Automated Testing? 
### It is time and cost efficient.
  * We live in an age where numerous multi-faceted software features get added in a highly fast-paced environment, therefore, traditional manual testing that incurs 
  a gross amount of time and labor cost over a long period of time may not be an ideal choice of testing methodology. 
  Once the automated testing environment is set up and testing procedures with a testing automation tool is figured out, the actual testing activities can be done 
  efficiently and the development team can save tremendous time and effort spent on validating newly added features.
### It provides better test coverage and accuracy.
  * Manual testing obviously imposes limitations on the number of tests one can create and verify. Automation testing, on the other hand, puts no such limits and 
  allows us to test all of the possible logic scenarios within the software, which is necessary to yield higher test coverage and testing accuracy. 
  * Automated tests are normally conducted by developers, who have a better understanding of software structures unlike manual testing, which is done by 
  quality assurance testers, who generally have limited knowledge. Thus, automated testing generates better thought-out test cases. This also adds another benefit of testing 
  activities being allowed to be integrated as part of the whole development cycle, streamlining the software product delivery process.   
  * Lastly, manual testing is done from start to finish by humans, which inevitably results in more errors. Automated testing, however, helps us to reduce these errors 
  significantly as it requires little to no intervention from humans.  
### It provides more features than just testing. 
  * Most of the software automation testing tools provide various features that can render the testing procedure more efficient and convenient. Many testing automation tools 
  can be integrated with testing management applications that offer various features that could eliminate the overhead cost of testing activities. 
  The features include the ease of managing test cases, generating test reports and metrics, and integrating with issue tracking tools. 

## What are the Disadvantages? 
Now we know automated testing offers great advantages over traditional manual testing. However, we also know as computer scientists that there is always a tradeoff in the world 
of software. What are the drawbacks of automated testing? 
### It requires proficiency to write automated tests. 
  * Automated testing is generally conducted by proficient individuals such as developers. It requires people with more in-depth knowledge on software development and technical 
skills, unlike manual testing, which can be done by anyone who has little to no knowledge or experience on software development. 
### It incurs more cost than manual testing initially. 
  * The overall cost of utilizing an automated testing tool may be cheaper than that of conducting manual testing in the long run, the initial cost of automation testing is 
  inevitably greater than that of its counterpart. Setting up the testing environment and learning to use the specific testing tool can pose great expense on the development team. 

## Automated Testing Strategy (Test Automation Pyramid)
![alt text](https://github.com/jeong-hyun/jeong-hyun.github.io/blob/master/The%20Test%20Automation%20Pyramid.jpg)

(Gregory and Crispin, "More Agile Testing: Learning Journeys for the Whole Team")

As automated testing is recognized to be a more efficient testing methodology over traditional manual testing, we have adopted a strategy to make transition from the existing 
manual testing processes. The Test Automation Pyramid was developed by Mike Cohn and it is said to be an innovative and efficient approach to automate tests. 
### Unit Tests/Component Tests
  * Unit tests are at the base of the pyramid. They are at the foundation of the pyramid as they comprise the largest portion of the tests. Unit tests mostly focus on 
  specific components or features within the software, making sure the functionality of each back-end component of the program works properly. Consequently, this requires 
  a more extensive number of tests.  
### Business Rules Functional Tests
Business rules functional tests are at the middle level of the pyramid. They do not require as much testing effort as unit tests in terms of the number of tests to be written, 
but this layer is crucial to ensure the program’s proper behavior. They are responsible for ensuring that responses from a component of software are returned appropriately 
according to user inputs. 
### Workflow Tests
  * Workflow tests are at the top layer of the pyramid, which indicates the number of tests required should be the least out of the three. They mostly focus on testing 
  functionality of the user interface. Writing such tests are not only highly redundant but also manual and time consuming, therefore, automated testing for the user interface 
  should be minimized. 

Testing is an arguably crucial phase in the development process as it is mainly responsible for ensuring the software product functions as expected. Manual testing was a popular testing method traditionally, but this trend has been transitioning as we have identified the downfalls that manual testing has. Automated testing has become an integral part in today’s software industry and it has added a tremendous amount of benefits to software developers. 

#### References Used:
  * "More Agile Testing: Learning Journeys for the Whole Team" (Janet Gregory, Lisa Crispin)
  * "Automated Software Testing" by Max Rehkopf (https://www.atlassian.com/continuous-delivery/software-testing/automated-testing)
  * "Manual Testing Vs. Automated Testing in Software Testing" by Rajkumar (https://www.softwaretestingmaterial.com/manual-testing-vs-automation-testing/#Manual-Testing-Pros-and-Cons) 
