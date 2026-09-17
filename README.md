# AI Study Buddy

Building AI course project

## Summary

AI Study Buddy is an app that helps students focus on the right things. It follows what the student is doing and suggests tasks where they are weakest. The idea is to make studying more efficient so time isn't wasted on things already learned.

## Background

As a student myself, I know it's hard to know what to study next. You might spend hours on things you already know, while weaker areas get less attention. This can be frustrating.

This app is especially for you if learning difficult topics feels hard. Some subjects just don't click right away, and it's easy to avoid them. But avoiding them only makes things harder later.

The app can be really fun for middle school and high school students, but also for upper secondary school students. The game-like features and social studying make it feel less like boring homework and more like something you actually want to do. It motivates you to study more and more.

Teachers don't have time to follow every student's progress either.

Problems:
* Student doesn't know where they are weak
* Time is wasted on things already learned
* Weak areas can stay weak and cause bigger problems later
* Teacher can't help everyone personally



## How is it used?

A student logs in and creates their own profile. The profile shows their progress, strengths, and areas that need practice. It also has levels, like in a game. When the student completes tasks and practices weak areas, they earn points and move up to the next level.

AI Buddy is very encouraging. It notices both strengths and weaknesses, and it keeps cheering you on during tasks. It doesn't just tell you what's wrong,  it also says what you did well. This helps you stay positive and keep going.

The app watches how the student is doing and notices if some topic is difficult. Then it suggests more practice for those specific areas.

When the app suggests a new topic or exercise, it also explains it in a very simple way so the student can understand it as well as possible. The explanations are short, clear, and use easy examples. If you want to go deeper into a topic, there are also short videos you can watch.

Sometimes you might not feel like reading. Maybe you're tired or just want to listen. That's why AI Buddy can also speak. If you want, it can read the explanation out loud for a specific topic.

The app also has a feature for studying with a friend. Students can pair up and discuss specific topics or themes together. The app can suggest themes to talk about and give simple questions to help the conversation.

The teacher sees a summary of how the group is doing and can step in early.

Users:
* Students
* Teachers
* Parents

Example: A student is studying history. The app notices that the causes of World War I are hard to remember. AI Buddy gives a simple explanation and encourages the student: "Good job, you already know the years! Let's practice the causes a bit more." The student earns points and levels up. If they want, they can watch a short video or listen to the explanation instead of reading. Later, they can invite a friend to discuss the topic together.

## Data sources and AI methods

Data comes through the app: student answers, task difficulty levels, and topics. At first, ready-made materials like Khan Academy could also be used.

AI methods that could be used:
* Decision trees – to spot weak areas
* K-means – to group similar learners
* Bayes – to update the estimate of skill level
* Recommender systems – to suggest next tasks and discussion themes
* Text-to-speech – to read explanations out loud

| Method | What for |
| ------ | -------- |
| Decision trees | Finding weaknesses |
| K-means | Grouping learners |
| Bayes | Updating skill level |
| Text-to-speech | Listening instead of reading |

## Challenges

This doesn't solve everything. It doesn't replace a teacher or motivate the student by itself.

Challenges:
* Need enough data, otherwise suggestions are bad
* Student data is sensitive
* If data is biased, the model can discriminate
* Must not label students unfairly
* Social features need moderation so discussions stay friendly
* Levels and points should not make students feel bad if they progress slowly
* Text-to-speech must sound clear and natural
* Videos must be short and relevant

## What next?

In the future:
* Connect to Moodle or Google Classroom
* Mobile app
* Multilingual
* More gamification features like badges and challenges
* Work with teachers

I need help especially with collecting data and designing the user interface.

## Acknowledgments

* Inspiration: Khan Academy, Duolingo
* Course: Building AI (Reaktor & University of Helsinki)
* Images and code: made by me or under open source licenses
