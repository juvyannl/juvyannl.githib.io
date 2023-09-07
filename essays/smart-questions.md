---
layout: essay
type: essay
title: "Am I Asking The Right Questions?"
# All dates must be YYYY-MM-DD format!
date: 2023-09-07
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/smart-questions/rtfm.png">

We all know that learning a programming language is not an easy thing to do. It takes time and practice to be the best at it. Not everyone knows the answer to everything nor well documented. 

## Is there really such thing as a stupid question?

I mean I guess so... [Stack Overflow](https://stackoverflow.com) itself even has a own article to help users learn [how to ask a good question](https://stackoverflow.com/help/how-to-ask). The article has a guideline to follow that will make sure you're asking a good question. The question needs to be on-topic and have a title that sums up the problem. 

Example:

Bad: JavaScript Confusion

Good: Why does str == "value" evaluate to false when str is set to "value"?

This article "[why i'm getting this error in rust? while running cargo in terminal](https://stackoverflow.com/questions/59102067/why-im-getting-this-error-in-rust-while-running-cargo-in-terminal)" did not do well on asking the question. The author should have done more research before posting a question. It was marked as a duplicate or showed that there was any research effort.

## What’s a smart question?

Stack Overflow, a question and answer site for programmers, is a great resource for anyone who may have issues with code or who may simply want to learn new or different methods of doing something. There I found examples of good questions and bad questions, which could probably be improved. In the following example, the title is clear and succint. Granted, it’s a relatively easy question to answer. But perhaps it is only easy to answer because it is phrased well. Following the good question, the user continues with an example of what they’ve tried.

A question from Richard Garside asked the community: [var functionName = function() {} vs function functionName() {}](https://stackoverflow.com/questions/336859/var-functionname-function-vs-function-functionname)

I've recently started maintaining someone else's JavaScript code. I'm fixing bugs, adding features and also trying to tidy up the code and make it more consistent.

The previous developer used two ways of declaring functions and I can't work out if there is a reason behind it or not.

The two ways are:
```
var functionOne = function() {
    // Some code
};
```
And,
```
function functionTwo() {
    // Some code
}
```
What are the reasons for using these two different methods and what are the pros and cons of each? Is there anything that can be done with one method that can't be done with the other?


While the heading of his question could be better, it does convey what he’s trying to figure out. Usually something as brief as “python date of previous month” is what other users would enter in as search terms on Google, making it easily found. Another good thing about the question is that it’s not just a question. The asker shows what he or she has done and that he or she has put in some effort to answer the question. And while it may not be as important as the question itself, the asker shows courtesy, which does increase the chance of getting an answer.

The asker received forty-one possible answers, and they were successful in inciting discussion from multiple users. The answers themselves were clear and were devoid of the rumored sarcasm and hostility of “hackers.” Since I myself have referenced this page and found it useful, I can confidently say that it is a good question.

## The foolproof way to get ignored.

While there are decent questions that benefit everyone, there are those one can ask to create an entirely different effect. In the following example, a user asks how he would, in short, create a desktop application with Facebook.

```
Q: Facebook Desktop Notifier
I am a beginner programmer that have never used anything other than what's included in a language.
I am trying to create a desktop application that notifies me anytime I get an update onfacebook. 
How should go about doing this? Thanks in advance.
edit Sorry I was not clear. Is there any way to make a DESKTOP application with facebook?
```

A simple “yes” would have answered the question, but we know that’s not the sort of answer he or she is looking for. Fortunately, someone kindly responded with a link to Facebook’s developer website. The asker should have done more research on his or her potential project. Then further down the road, he or she could have asked more specific and detailed questions that wouldn’t require a thousand-paged response for a sufficient answer.

## Conclusion

When we rely on others’ generosity and expertise to provide answers to our questions, it should hold that the question we ask should be one that leads to efficient and effective help that not only benefits us, but also the people we ask and others who might ask the same question in the future. Thus, if you have a question… make it a smart one! Asking questions may not always get you the best answer, but asking them in a way that will make others want to answer them will increase the success of finding a good solution and make it a positive experience on all sides.
