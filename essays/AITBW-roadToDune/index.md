# Dr. Strangelove or: How I handled my stubbornness to become a web developer

Becoming a developer can be a pretty underwhelming task these days, especially if you delve into the [JavaScript](https://hackernoon.com/how-it-feels-to-learn-javascript-in-2016-d3a717dd577f) land, where _the new kid on the block_ can be thrown into obscurity in a matter of days.

I faced a completely different situation back when I began college in 2010, which is the story I'd like to tell you today.

I enrolled in college around mid/late 2010 under an "Information Engineer" undergrad, which is mostly focused in the importance/value of data and how we can take advantage of IT systems to make the most out of it.

When I began college, one of my biggest weaknesses from high school were maths. My education had a very high standard but I just couldn't make sense out of them —as a matter of fact: I struggled with maths during **all** of my high school education.

You must be asking: Then why did you went for Engineering?

1. I love a good challenge
2. I didn't see myself in the future as anything other than an Engineer

So there I went.

My first real programming course was "Programación I" or "Programming 101", which was taught using C#.

> I failed.

Even though we were developing really basic CLI applications, I had a hard time grasping all these new concepts. (Fun enough: I did grasp the `arrays start at 0` concept from start)

[arrays_start_at_one](./images/arrays_start_at_one.jpg)

But I thought it was normal to fail on your first-ever programming course if you had no prior programming experience. Few months later, I had to take three (3) new programming-related courses: "Design tools" (Basic HTML/CSS along with PHP), "Programming II" (C# with Windows Forms) and "Databases" (Modeling, normalization, SQL, relationships, MySQL/SQL Server)

Of the three, I failed the first and the second one —and even approving "Databases", I used to thought (until a few years ago) that I knew shit about them.

"Design tools" was the most frustrating of all 3, because CSS positioning seemed so hard to get right. (This was in 2011 and while we had Bootstrap, we didn't had cool stuff like Flexbox and CSSGrid; I must also add that _CSS positioning_ is **really** hard, as demonstrated by the GIF below)

[css_positioning](./images/css_positioning.gif)

We also were taught how to use Dreamweaver —so I had to deal with, not only CSS issues, but also had to fight any issues that came up when installing DW and don't get me started on the hell that was installing WAMP.

> Years later I realized that most of my issues when I started college were born because of the tools my teachers taught me to get me into programming.

Two and a half years into college, I faced somehow of a career crisis (which is way more common that you would think) and questioned myself if I had chosen the right path for me. One of my closest, dearest friends told me during that time that _we weren't supposed to become programmers; we're studying Engineering to become Engineers, not workers on a construction site_ and in someway he was right, but something inside me told me I needed to understand programming if I wanted to become a great Engineer.

That was around mid 2012 and nothing really relevant happened after that until late 2014 where I got interested into programming again —decided to get it right this time and began researching about (programming) languages others than the ones I had learned in college.

Besides C# and PHP, I learned Java. (Along with Classic ASP (yep) and JSP). I despised all 3 of them.

* PHP is an abomination from hell. My thoughts about it are all backed on my own experiences and this incredible [article](https://eev.ee/blog/2012/04/09/php-a-fractal-of-bad-design/)

* Java is extremely verbose, bloated and Oracle is not the most FOSS-friendly enterprises of them all. (This "hate" made me aware of Scala which I find beautiful and expressive without all the bad stuff Java has; I plan to get into it in the future)

[scala_vs_java](./images/scala_vs_java.png)

* C# is the better of this pack and some pretty cool stuff comes with it but I just can't stand Windows for development —Don't get me wrong: I use Windows a lot for gaming, photography and audio-related stuff but for development is just "meh" (WSL wasn't even close back then, not even in our [wildest dreams](https://www.youtube.com/watch?v=IdneKLhsWOQ))

So after spending a few weeks researching about programming languages I wasn't aware of (Haskell and Clojure were the highlights of that research), I found Ruby and I immediately fell in love because of its syntax and how easy it was to get stuff done in a few lines of code and I couldn't wait to get into a project where my new found knowledge could be used.

Right before New Years' Eve (2 days before, if I recall correctly), I landed an internship (a requirement to opt for the Engineering degree) that began on January 2015 from April 2015, as a _Backend Developer_ on a government-backed company, here on my hometown.

I was assigned, along with a friend, the task to develop a web-based system for the company. «Sure thing», I said and also proposed «Can we do this on Ruby? I just found about it and seemed like a great choice for this project», but the manager asked for it on PHP since they had their stack on PHP.

I wasn't too happy about it but I needed the internship —plus, I could work from home.

> What I thought was going to be a terrible experience, happen to became a turning point in my career as a developer

During this time I also retook "Programming 101" (again with C#) but this time, somehow, everything made sense. C# became my best friend during that quarter. It was beautiful and I knew there was a lot more to discover. And this time I killed it by getting one of the highest grades.

Three months later, my friend and I finished our internship and with it, the project that was assigned to us. We handed our dissertation and right after, signed up to begin our theses (individually; the thesis is the last requirement needed to get a degree in most colleges in my country)

I grew fond of the project I developed for my internship but I despised the way I tackled it (not my fault since I had no saying in the stack but you know how this is), so I thought: «Hey, that experience was pretty rad but I know there must be a hassle-free, painless way to develop web applications»

During those 4 months, I was also studying Ruby (Shoutout to [LRTHW](https://learnrubythehardway.org/)
and [The Well-grounded Rubyist](https://www.goodreads.com/book/show/3892688-the-well-grounded-rubyist); incredible resources to get your feet up-and-running with Ruby in no time) and a dear friend of mine ([@stefanmaric](https://github.com/stefanmaric/)) made me aware of [Sinatra](http://sinatrarb.com/) and the [Sequel ORM](http://sequel.jeremyevans.net/), so I decided developing a web application with Ruby as my undergrad thesis would be great (spoiler alert: it was one of the best decisions I took)

I began the development of my thesis as soon as was possible and jumped into the Linux/Ubuntu ship to up my skills. My friends had also told me about Git and considering the hell it was to keep files synchronized with my friend during the internship using Dropbox (yes, Dropbox), I said: «It can't be that hard» (P.S.: It is not)

So off I went with Ruby, Sinatra, Git and Ubuntu to develop my thesis.

I know what you must be thinking right now: Why didn't you picked up Ruby on Rails?

Honestly, I didn't researched a lot back then and Sinatra seemed pretty cool but it's worth noting that I modeled a lot of my application to be Rails-esque, so I managed to grasp **a lot** of Rails magic unconsciously. Controllers, routing, I18n, layouts, asset management, authentication, authorization, you name it —I had to implement most of this stuff from scratch, which one hell of a exercise (not in futility, of course); I look back at it and I'm glad to say I recognize most of the mistakes, something fundamental in order to know you've actually grown up as a developer, but I also loved what I did the way I did it, which was the main objective.

(If you're interested, the whole thing is open-sourced and you can find it [here](https://github.com/aitbw/af_maracay) —I plan to restart development later this year)

Fast forward one year, I handed my thesis and presented it against a committee and they couldn't be more happier, they loved both the end-product and the presentation. I attained a final score of 98.22 points over 100 and my thesis received several honours, between them an "honorific mention" because of said score, "absolute quality" for fulfilling all the standards set by my college within regards to dissertations and a «ground-breaking technology usage» honour for developing my thesis with technologies not included within the degree's program.

After that, I kept on studying, reading a lot and took a position as a "Software Development Leader» on one of my college projects where I taught students about, well, software development. Fast forward one year, I was done with college and began looking out for my first, out-of-college job and on September '17, I landed my first gig as a _Ruby on Rails Developer_ @ M2C Consulting, a Madrid-based IT consulting company
