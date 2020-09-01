# CSC 510 Software Engineering -- Homework 3 submission
## Method:
### Here lies the detailed description on how to conduct tests for homework 3.

### 1. Get people to sign up for your experiment.
We get around 10 participants for the experiment and give them keys that they will use from here on, as a placeholder for their identity with respect to this task. 

For example, they will use these keys on the forms pertaining to this experiment instead of their names or email IDs . This way they are anonymous. This gives them the power to freely participate in the test without any fear or feeling of being judged.

### 2. Ask participants to fill the [pre-debugging survey](https://docs.google.com/forms/d/e/1FAIpQLSdFWBKKwtmoXGe220kCVoX_K859VLqQrK5XGpPASdzAoOuPww/viewform?usp=sf_link) google form.
A `pre-debugging survey` form is a google form that aims to know more about the participants and their initial feelings about the languages used.

We first ask them about their familiarity with the respective languages. The answer for this can be used for understanding the prior knowledge of the participants; which can be used for various inferences. One of them can be that if the language was already famous with the majority of people, it may become the easiest debugged language of all given programming languages in question. Hence, such a result is less indicative of the apparent ease that comes with using that particular language but more with the participants already knowing about the language.

Next, we can show them a famous snippet from the languages in question (for example Fibonacci or matrix multiplication) or a snippet from our `Game of Life` code and ask them their instinct about the apparent ease of debugging the language. This will aim to see what language "seems" easy to debug.

At last, we ask them about the languages they already know. The answer would not be restricted and will include every language in the world. This can be used to find any correlation between the language that the participant may find easy to debug and the languages they already knew.

### 3. The debugging task.
The participants will be invited to a 30-minute zoom call, based on a mutually decided time. 

They will be sent the `pre-debugging survey` google form prior to the task and a `post-debugging survey` google form will be sent after the task. 

Again, the participants will be asked to conceal their identity, by any means the technology allows. For example, they can change their names before the call, and also they can talk to us via chat only and no audio.

About the task:
1. It will be proctored by one of the group members. 
2. The participant will be sent a link with instructions on how to access and debug the code. 
3. The audio from the group member conducting the task will be on and they will narrate, communicate, and direct the participants about the technical aspects. 
4. The participant will be asked to share the screen. But they can mute their audio and communicate only via chat.
5. The participant will be aware of the number of bugs and can shift between languages however they want. 
6. They will be free to use any resource on the internet, except for the GitHub repository of the testing group.

### 4. Ask participants to fill the [post-debugging survey](https://docs.google.com/forms/d/e/1FAIpQLSeaNjVP7B2jWqTIE4jHouHyiM7rJ4r7Y3KSnu1K3DbI8t2Yrw/viewform?usp=sf_link) google form.

This survey will aim to get to know about their performance during the debugging task and their experience.

We first ask them about the number of bugs that they found in each language. The purpose of this is self-explanatory.

Next, we ask them about how their rating for each language based on the difficulty of debugging during the task. This gives us their experience with each of the languages.

We also ask them to rank the languages based on the difficulty of debugging it. This is to get the relative difficulty of the languages with each other. This question will have an open-ended follow-up, asking them for their reasons for the rankings.

At last, we ask them if they felt the code was difficult to understand because of the way the author wrote it. This question will also have an open-ended follow-up, asking them to give some suggestions on how to improve our methods of testing and coding.

>NOTE: The google forms will only allow you to access it if you're logged in with NCSU ID.





## Materials
We would need the following entities:
1. Buggy codes for the Game of Life in 3 languages. For this experiment, the languages are Ruby, Julia and Go.
2. A virtual meeting rooms. For our purpose, a zoom meeting is ideal.
3. Stable internet connection throughout the virtual meeting.
4. Atleast 10 participants to test upon.
5. Two google forms. 
6. Online editor for each language.





## Observations

### Ruby:
![Ruby Pre 1](https://github.com/ssp4all/csc-510-hw-03/blob/master/src/images/Ruby-Pre_1.PNG)
![Ruby Pre 2](https://github.com/ssp4all/csc-510-hw-03/blob/master/src/images/Ruby-Pre_2.PNG)
![Ruby Post 1](https://github.com/ssp4all/csc-510-hw-03/blob/master/src/images/Ruby-Post_1.PNG)
![Ruby Post 2](https://github.com/ssp4all/csc-510-hw-03/blob/master/src/images/Ruby-Post_2.PNG)

None of the participants had Ruby extensively before. Around 70% of the participants rated their familarity with Ruby as 1 out 5, meanwhile only one person marked their familarity as 4 out of 5; which was the highest rated familarity reported. 

It is safe to say that Ruby is obscure for most of the participants. But still, when shown a snippet of Ruby code; all of them felt debugging a Ruby code was of easy or moderate difficulty. It seems participants felt Ruby was easier to read and understand despite not using Ruby a lot prior to this.

During the debugging, most of the participants were able to find all the bugs in the code, while all of them being able to find atleast one bug in it. After debugging the code, most of the participants felt more or less the same about the difficulty of debugging Ruby as when they saw the snippet of code before the test, with only one of the participant thinking it was hard.

The team members who were observers during the task found that most of the participants were unable to understand what the error message was about and 
were put-off by the way ranges work in Ruby. But except that, most of them quickly understood what was the error in the code. 




## Conclusions

## Threats to validity



