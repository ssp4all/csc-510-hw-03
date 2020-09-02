# CSC 510 Software Engineering -- Homework 3 submission
## Method:
### Here lies the detailed description on how we conducted tests for homework 3.

### 1. Got people to sign up for the experiment.
We got 10 participants for the experiment and gave them keys that they will use from here on, as a placeholder for their for this task. 

For example, they used these keys on the forms pertaining to this experiment instead of their names or email IDs . This way they were anonymous. This gave them the power to freely participate in the test without any fear or feeling of being judged.

### 2. Asked participants to fill the [pre-debugging survey](https://docs.google.com/forms/d/e/1FAIpQLSdFWBKKwtmoXGe220kCVoX_K859VLqQrK5XGpPASdzAoOuPww/viewform?usp=sf_link) google form.
A `pre-debugging survey` form was a google form that aimed to know more about the participants and their initial feelings about the languages used.

We first asked them about their familiarity with the respective languages. The answer for this was used for understanding the prior knowledge of the participants; which was used for various inferences. One of them was that if the language was already famous with the majority of people, it would become the easiest debugged language of all given programming languages in question. Hence, such a result is less indicative of the apparent ease that comes with using that particular language but more with the participants already knowing about the language.

Next, we showed them a famous snippet from the languages in question (for example Fibonacci or matrix multiplication) or a snippet from our `Game of Life` code and asked them their instinct about the apparent ease of debugging the language. This aimed to see what language "seems" easy to debug.

At last, we asked them about the languages they already knew. The answer was restricted and included every language in the world. This was used to find any correlation between the language that the participant may find easy to debug and the languages they already knew.

### 3. The debugging task.
The participants were invited to a 30-minute zoom call, based on a mutually decided time. 

They were sent the `pre-debugging survey` google form prior to the task and a `post-debugging survey` google form was sent after the task. 

Again, the participants were asked to conceal their identity, by any means the technology allows. For example, they changed their names before the call, and also they spoke to us via chat only and no audio.

About the task:
1. It was proctored by one of the group members. 
2. The participant was sent a link with instructions on how to access and debug the code. 
3. The audio from the group member conducting the task was on and they narrated, communicated, and directed the participants about the technical aspects. 
4. The participant were asked to share the screen. But they could mute their audio and communicate only via chat.
5. The participant were aware of the number of bugs and could shift between languages however they wanted. 
6. They were free to use any resource on the internet, except for the GitHub repository of the testing group.

### 4. Asked participants to fill the [post-debugging survey](https://docs.google.com/forms/d/e/1FAIpQLSeaNjVP7B2jWqTIE4jHouHyiM7rJ4r7Y3KSnu1K3DbI8t2Yrw/viewform?usp=sf_link) google form.

This survey aimed to get to know about their performance during the debugging task and their experience.

We first asked them about the number of bugs that they found in each language. The purpose of this is self-explanatory.

Next, we asked them about how their rating for each language based on the difficulty of debugging during the task. This gave us their experience with each of the languages.

We also asked them to rank the languages based on the difficulty of debugging it. This was to get the relative difficulty of the languages with each other. This question was an open-ended follow-up, asking them for their reasons for the rankings.

At last, we asked them if they felt the code was difficult to understand because of the way the author wrote it. This question has an open-ended follow-up, asking them to give some suggestions on how to improve our methods of testing and coding.

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

During the debugging, most of the participants were able to find all the bugs in the code, while all of them being able to find atleast one bug in it. But after debugging the code, there was a significant shift in their opinion regarding the difficulty of debugging this code. While the people finding Ruby "easy" dropped from 60% to 30%, while 60% of the participants now found the code to be of moderate difficulty, which is jump up from 40%, with only one of the participant thinking it was hard. Previously, no one had felt it was hard.

The team members who were observers during the task found that most of the participants were unable to understand what the error message was about and 
were put-off by the way ranges work in Ruby. But except that, most of them quickly understood what was the error in the code. 

### Go:
![Go Pre 1](https://github.com/ssp4all/csc-510-hw-03/blob/master/src/images/Go-Pre_1.png)
![Go Pre 2](https://github.com/ssp4all/csc-510-hw-03/blob/master/src/images/Go-Pre_2.png)
![Go Post 1](https://github.com/ssp4all/csc-510-hw-03/blob/master/src/images/Go-Post-1.png)
![Go Post 2](https://github.com/ssp4all/csc-510-hw-03/blob/master/src/images/Go-Post_2.png)

None of the participants had used Go as their primary language before. 7 out of 10 participants rated themselves as a Novice(1/5), only 2 of them considered them to be a bit familiar (2/5) and only a solitary person marked themselves as 3/5.

It is safe to assume that Go was relatively obscure for most of the participants. When a snippet of Go code was shown, most of them felt debugging a Go code was of easy or moderate difficulty. However, 2 out of the 10 participants felt that it would be hard for them to debug.

Most of the respondents were able to find all the bugs in the Go code. Only 1 person was unable to find a single bug in the code. This was not surprsing since most of the people felt that debugging the code would be moderate to easy. 

The team members who were observers during the task found that most of the participants were unable to understand what the error message was about and  were put-off by some syntax nuances of Go. But except that, most of them quickly understood what was the error in the code. 

## Conclusions

## Threats to validity

### 1. Too many bugs:
Much of the feedback we received was that there were too many bugs. We were asking them to find 9 bugs in 30 minutes, which we later understood was too many.

### 2. Dependency of bugs:
The bugs were dependent on each other. This means if someone does not get the first bug it means they would also won't find all of the next. If this is true for most of the people, the data would be invalid. Also, there were inconsistencies in the type of bugs(syntax / logical) across all 3 languages.

### 3. No feedback on execution:
As we used repl.it - an online IDE that allows execution of single file, every time the participant found a bug in the code, the observer had to manually point out that "You have found a bug at this point". This could've been done better by using a print statement "Correct or Incorrect" at the end of the program depending on the case.

### 4. Automation of time keeping:
While testing the participants, we kept manual records of the amount of time they take for each bug for all three languages. It could be easily automated by creating a log file storing execution result information for each language.

### 5. No diversity in dataset:
We tested a total of 10 participation, all of them pursuing Masters in Computer Science. The collected data could have some bias because of non-diverse nature of participants. A solution to this problem could be that we can perform this test on a large scale using a simple webapp which records all the required parameters.

### 6. The code is not written by a regular user of that language.
The authors of these codes were also new to these languages. Although they do had more time to write it and to test it; a "good" code in a particular language will most probably come from a person who had more experience in that particular language. 

![Validity 6](https://github.com/ssp4all/csc-510-hw-03/blob/master/src/images/Validity_6.PNG)

Here, we see that 2/10 people thought that the author could have structured the code better, so this threat to validity is not that far off.