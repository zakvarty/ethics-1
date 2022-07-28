# Foundations of Ethical AI {#ch-foundations}

## Introduction {-}

Welcome to the first week of this unique course.

This will likely be different to any other course you have taken before if you come from a scientific or engineering background. We will often spend a few days without seeing any equation, and we will be asked to think carefully about the real-world implications of our work.

Having said that, rest assured that there will be plenty of technical and mathematical content in the course, and any content that is purely conceptual will be immediately relevant to your life as a professional data scientist.

This is not a course in moral philosophy, but I really hope it will encourage you to take one. And with that, let's get started.

This week, we'll spend our time getting to understand precisely what we mean by harm, what we mean by data science itself, what moral frameworks and codes of conduct are already in place, and finally codify them in a set of five principles that we can use as guardrails for our own work as professional data scientists.

Although the term AI is not in the course title, I will sometimes collectively refer to our subject as ethical AI. That's not necessarily very accurate. There is a tendency these days to label even simple data analysis as AI and that can be misleading. Also, there are flavours of AI that do not use any data or learning. However, the literature and regulation around the topic of professional ethics is increasingly consolidating under the term ethical AI, so I will use that as short cut.

You can safely assume that whenever I use the term AI, I am referring to statistical machine learning and data science, which is the focus of the program you're attending.

All right. Disclaimers aside, this week we will cover a huge amount of conceptual ground.

It will also be the only week in this entire course that does not have mathematical or programming content, so sit back and enjoy.

## Do No Harm 

### AI for good

#### Go

It is hard to open a news website these days and not come across a headline that celebrates the incredible achievements of AI algorithms. Millions of people held their breath while DeepMind's neural network AlphaGo played a game of Go, the world's most challenging strategy board game, against the world champion, Eventually landing a victory and ushering in the era of AI supremacy in yet another frontier of human intelligence.

What makes this moment dramatic is that once a computer becomes a world champion at a certain game, say chess or go, it means that the basic algorithmic design, allowing it to learn how to play that game is finally in place.

And given year-on-year increases in computational power, the computer can get better and better at a much faster pace than a human can. Put differently,
a human will never again manage to out compete state-of-the-art AI in chess or go.

A common criticism of AI used to be that it can only outperform humans in toy
domains or games which, though fascinating, does not really help humanity. We also used to criticise AI systems for being very narrow, for example, only able to deal with one task at a time. Now, that era seems to be over.

####  Protein folding

DeepMind recently demonstrated that an algorithm architecturally similar to AlphaGo was able to solve a riddle in biochemistry that holds the promise of
revolutionising drug discovery. This is known as protein folding, and
it is the task of predicting the 3D shape of a protein on the basis of the sequence of amino acids that it is made of.

Proteins are very complex twisty things and the way they fold depends on a number of spontaneous interactions between different parts of their amino acids. So it is a very hard computational
problem to solve exactly.

AI researchers have instead opted for predictive modeling using a large database of known structures as a training data set and then predicting what the likely shape of new proteins will be.

#### Arrhythmia 

AI is now reaching superhuman performance not only in games and scientific problems in the lab, but also in everyday real-world tasks that currently require
a well-trained professional.

For example, cardiologists can detect arrhythmia by inspecting the echocardiogram of a patient. That's a graph of the electrical
activity of the heart.

Recent work by Andrew Ng and others demonstrated that an AI algorithm is able to perform that task with similar performance but can do so in milliseconds everywhere in the world, just as reliably.

The implications for remote health care or care of patients in countries without robust health care systems and absence of specialist doctors are mind-blowing. And yet, increasingly we also hear news stories about AI getting it wrong.

### AI can cause harm

#### Self-driving

Self-driving cars are a particularly interesting example of ethical AI.

That is because driving is a relatively easy task for humans; we learn how to do it in a matter of months and most of us can do it reasonably well. Yet, to an Artificial Intelligence system, driving is much harder than chess.

It requires very advanced computer vision, planning and movement forecasting.
These are all things that humans and most animals excel at because we evolved
over millions of years to move while avoiding objects under various conditions,
including rain, low visibility in a range of different physical environments.

Similarly, driving safely requires knowing that a dog is more unpredictable than,
say, a pedestrian or that an elderly man typically walks slower than a teenager. We didn't learn any of those facts during driving lessons. To know how to drive
a car, we need to understand much more than just cars, roads, and roadsides.

Despite these huge challenges, self-driving cars remain an incredibly valuable business proposition. Therefore, many tech companies and car manufacturers are competing in this space. 

Inevitably, a self-driving car will occasionally enter into an accident and
some of these will be fatal. This is not a statement about the relative
safety of self-driving AI versus human driving. Current statistics suggest that
existing self-driving cars are much safer than humans on a scale of number of accidents per mile drive, and that trend is likely to persist.

And yet, when a fatal accident does happen, who is to blame? Could it have been avoided?

Is the data scientist that worked on the algorithm to blame?

Is it the model's fault or the data's fault? If not, then who or what is to blame?

These are hard and important questions that we have never had to ask before. There are also other subtler but equally important ways in which AI can cause harm.

As AI is increasingly used in our daily lives, it will make mistakes and without care, these mistakes may disproportionately affect minorities, vulnerable populations or groups that have been the subject
of historic discrimination.

####  Facial recognition

Facial recognition is one particular example where a combination of poor quality data and poor governance have led to headline grabbing failures. 

These news articles (and the academic articles on which they were based) draw attention to the fact that these algorithms reliably perform worse on faces of people of colour. 

These mistakes can be hurtful and perpetuate historic racism. They can also lead to real-world discrimination in cases where the algorithms are used, for example by the police. 

So here, we are at a crossroad of sorts. After decades of broken promises,
AI is starting to be powerful enough to solve real-world problems and even outperform humans in a number of valuable tasks. However, as adoption of these technologies increases so does the risk of them doing harm.

Whereas before, AI researchers were playing harmlessly with toy examples 
in university labs, they are now increasingly holding lives and livelihoods in their hands.

This is not the first time this happens. In fact, it happens with nearly
every powerful emerging technology.

### Technological Adoption Requires Public Trust

#### Nuclear Power

One particular example of this that we'll come back to is nuclear power.

Before the nuclear bomb, theoretical physicists were completely
protected in their academic ivory towers, both unwilling and unable to affect
the mess that is the real world.

Suddenly, the right set of equations and a wartime effort to make use of
them changed all that. Iconic names like Richard Feynman and Albert Einstein suddenly got thrown into one of the most heated moral debates of the century. 

Even putting aside the question of nuclear weapons, nuclear power has struggled to secure public trust even when used for peaceful purposes like energy production. At a time of climate and energy crisis, nuclear power is one of the few truly sustainable sources of energy we have, but it comes with a very considerable safety problem.

Although, nuclear disasters are few, when they do occur, they can be
devastating and particularly terrifying, and they do not only happen
in struggling economies where failures might be attributed to poor practices.
They can even happen in technologically advanced economies like Japan.

Trust is hard to earn and easy to lose, and each such headline makes
widespread adoption of nuclear power exponentially harder. A similar future might await AI unless we act now.

So, whose responsibility is it to ensure AI fares better than that? Well, we would expect the physicists and engineers to carry the burden of responsibility of explaining exactly how safe a nuclear reactor is, and how it needs to be maintained for it to remain safe, because they're the only
ones that understand it well enough.

#### Taking responsibility

Similarly, data scientists like yourselves are the first line of defence against
harmful AI because you are the ones that understand these systems well enough to anticipate what might go wrong with them.

Just like theoretical physicists in the early 20th century, data scientists before the onset of big data did not have to worry about this as their work had limited impact and only in very specific conditions.

Now with data science in AI increasingly becoming a part of the very fabric
of society and the economy, we all do carry a burden to demonstrate its safety.
As data scientists, we not alone in this; many other professions carry a similar
burden of responsibility and have to abide by strict codes of conduct and are legally liable for the outcomes of their work.

###  Learning from other professions

Doctors and drug design researchers are one example, which is very prominent in a pandemic era. There are also other,more quotidian, examples that we rarely think about including lawyers and the engineers that build the infrastructure
we use on a daily basis like the houses we live in, the power network, the transport network, and the bridges that we hope don't fall.

All of these professions know that lives depend on them getting things right and they hence adopt a safety-first approach to risk-management. This is what we are inviting you to adopt in your own work.

Doctors are a particularly interesting example in that, from antiquity, they have been very explicit about their moral obligations. 

#### Hippocratic Oath

As early as 2,500 years ago, doctors would swear by the Hippocratic oath,
which among other things included a commitment to medical confidentiality and non-maleficence, or as it is commonly known, "do no harm".

The idea is that a doctor should not take unnecessary risks when considering
treatment options for a patient. This simple command has had tremendous
influence throughout the centuries in our understanding of professional ethics.
It may even lie at the core of recent corporate mission statements, such as the famous motto, "don't be evil", that google used to have as the opening statement of its internal code of conduct. This was later rephrased to "you
can make money without being evil", but in both cases captures the aspiration
that companies should strive to not hurt society or the users of their
products, even as they try to make profit.

This dual allegiance is a theme we will return to in this course and a core objective of professional codes of conduct. What we are seeking is something like a Hippocratic oath for data scientists.

#### Hippocratic Oath for Data Scientists

Doctors start thinking about medical ethics very early in their training and literally stand in front of a crowd taking an oath not to hurt their patients to
protect their privacy, amongst other things.

A profession with as broad an impact as data science ought to have a similar process, as Cathy O'Neil argued  in her 2016 book _Weapons of Math Destruction_.

I haven't yet quite decided whether we should all take an oath together when
the course is completed, but that is definitely the idea.

So I've invited you to think about using AI for good and ensuring it is safe.
But how easy is that, really? 

### Doing the right thing is neither obvious nor is it easy 

It turns out that doing the right thing is neither obvious nor easy.

We will often lack context or lack an understanding of the group which is most at risk. Unless advocates representing that group are consulted, our ignorance might be dangerous.

Moreover, even when we have the necessary facts, humans are often hampered by cognitive biases and bad habits. Processes need to be in place to
overcome such sources of error. Even in cases where we know
what the right thing is, it might be difficult to do it unless the right incentive structures are in place.

If it is not safe to raise a certain concern in the company or if it is likely to negatively impact your career progression, fewer people will have the courage and determination to do it.

We should build organisations in which you don't have to be a hero to do
the right thing. In certain situations, even when both the knowledge and
the will to do the right thing are present, we will be faced with moral dilemmas where one harm must be balanced against another. Given all this, it is easy to give up. Just because the problem is too big to fix immediately, that does not mean you can't make progress. 

Finally, despite our best efforts, our technology can sometimes have unanticipated consequences. A humble attitude where we learn from our mistakes is needed to at least ensure that no accident happens twice.

Having said all that, we should clarify that we won't attempt to define
what is right in this course. That's too hard, and this is not a course in moral philosophy. After all, your instructors are both mathematicians, not social scientists or philosophers. We will mostly take certain values as a given, as you will see later in this week. 

You can maybe think of this course as an attempt to change your default perspective on your work. Where you might be used to focusing on success stories and the likely positive impact of your work, you will now start to think about near-misses: things that could have gone wrong and anticipate harm they might have caused.

Where before you might focus on how to access more data, you will now start to think about whether you have permission to use the data in a certain way.

Where before, you might have been committed to do good and not evil, but this making it emotionally difficult to admit that some of your work will necessarily entail risk of harm. Now, you might start to humbly accept that risk and commit to doing the best you can to mitigate against it.

Where before, you might not even have thought it was part of your job as a data scientist to worry about such things. Going forward, as a specialist in the field, you will see it as your responsibility to raise the bar. 

Where you would see unsolvable moral dilemmas, now you will seek to explicitly
quantify these trade-offs so as to have an informed conversation about the right balance.

Where you might have hoped that eventually technology will solve its own problems, and we should just focus on doing more research; now, you will approach the problem more pragmatically, acknowledging that not all problems can be solved with technology and in any case we cannot afford to wait.

Whereas before you'd be obsessed with your model's performance, you will now start to monitor other things that we care about, such as the degree to which it protects privacy or treats people fairly.

And finally, where before you might have preferred to only discuss these things with your fellow engineers and scientists, you will now feel confident to engage
in conversation with broader society.

### Conclusion 

To sum up, we have established that with power comes responsibility and that you, as a trained professional, are best placed to be a driver for positive change.

We have argued at the core of safe and benevolent AI is the ability to anticipate
harm, to minimise it (even if we can't eliminate it altogether) and to communicate it transparently to the public.

We have also showed how it is important to think about the humans who are impacted by a technology, putting the human in the centre of the design and
not just talking about the technology itself.

In what follows, we will pause to better define what data scientists actually build, so that we can be specific in tying potential harm to different components of a data science pipeline.

We will then discuss the progress that has been made to date by way of codifying the ethics of data science and AI, and conclude the week by offering our own codification of this problem area into five major principles.

These five principles will also serve as the backbone of the rest of the course.

Thank you and welcome aboard.
