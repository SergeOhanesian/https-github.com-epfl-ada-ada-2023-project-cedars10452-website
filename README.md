# Unraveling the Dynamics of Star Power, Ethnicity, and Collaborative Influence in Film Success

## Abstract

The global film industry, estimated to be worth over $136 billion, represents an intricate tapestry of cultural, economic, and artistic elements. This project delves into the nuanced realms of actor success, movie performance, and the impact of ethnicity and collaboration in the industry.

Firstly, This research investigates how casting high-profile actors, influences a movie's success and the career trajectory of co-stars. Furthermore, the study explores the effects of an actor's ethnicity on both their personal success and the international reception of their films, considering the evolving global audience demographics. The influence of accolades, such as Oscars and Golden Globes, on an actor's subsequent roles and career longevity forms a critical aspect of this analysis. Additionally, collaboration with renowned directors and producers is scrutinized for its role in shaping an actor's career, akin to Leonardo DiCaprio's frequent partnerships with Martin Scorsese.

Using comprehensive databases like the CMU Movie Summary Corpus, as well as other sources, this research aims to decode patterns in the careers of successful actors and the evolution of their role choices

## Introduction

Step onto the grand stage of the global film industry, a captivating realm where creativity meets commerce, and individual talent intertwines with cultural dynamics. In this intricate tapestry of storytelling, economics, and artistry, the actors stand as central figures, their performances shaping not only the narratives but also the trajectory of entire cinematic experiences.

Imagine the electric charge that surges through a film when high-profile actors grace its cast—how their presence not only elevates the story but often sets in motion a ripple effect that touches the careers of their co-stars. Yet, beneath the glamour lies a deeper exploration awaiting us—one that examines the profound impact of an actor's ethnicity on their personal success and the reception of their films in an ever-evolving global landscape.

Join us on a journey that scrutinizes the complicated interplay between accolades such as Oscars and Golden Globes, and an actor's subsequent career choices, unlocking the doors to the realm of career longevity and role selection. But it doesn't stop there. This journey also delves into the symbiotic relationships actors form with renowned directors and producers, revealing how these collaborations sculpt and define careers.

Our voyage through the extensive databases of the CMU Movie Summary Corpus and other rich sources seeks to decipher the patterns ingrained in the careers of these eminent actors. From decoding the choices they make to understanding the evolution of their roles, this exploration aims to unravel the hidden threads that weave the fabric of success in the realm of cinema.

So, embark with us as we unravel the enigmatic paths that successful actors tread, unveiling the profound impact of their choices, their collaborations, and the ever-shifting dynamics of the global cinematic landscape.

### Unveiling the Influence: the Career Trajectory of Non-Award-Winning Peers due to the Collaboration with Award-Winning Actors

In the dynamic realm of cinema, the partnership between actors within a film isn't merely a collaboration—it's a convergence of talent, influence, and potential career trajectories. Within this tapestry of artistic synergy, the spotlight often shines brightly on those adorned with accolades, but what happens when their paths intersect with those who haven't yet claimed the industry's highest honors?

This section unravels a compelling facet of the film industry, exploring the profound impact experienced by actors who, despite not holding prestigious awards themselves, find themselves participating in projects alongside revered, award-winning peers. The focus isn't solely on the film itself but on the intricate dynamics that unfold when these two worlds collide.

Imagine the resonance created when the prowess of an award-winning actor intertwines with the potential of their non-awarded co-star. It's here that we delve into the very essence of influence—scrutinizing how such collaborations sculpt not just the dynamics within a movie but the career trajectories of all involved.

Join us as we dissect these cinematic partnerships, unveiling the hidden layers of influence and opportunity that arise when the acclaimed and the aspiring share the screen. From dissecting the dynamics of these collaborations to understanding the subsequent career paths taken, this exploration sheds light on the impact of participating in a film alongside an award-winning counterpart.

Prepare to embark on a journey that transcends the boundaries of awards and accolades, revealing the intricate dance of talent and opportunity that defines the ever-evolving landscape of the film industry.

#### A first look at the collaboration situation

The histogram below displays the frequency of actors' participation alongside award-winning counterparts. Beyond the glitz of accolades, this visualization unveils the patterns and trends that emerge when actors collaborate with esteemed peers who have claimed prestigious awards. Each bar represents the frequency of an actor's engagements in projects alongside award-winning actors, shedding light on the prevalence and impact of such collaborations on career trajectories. Explore this histogram to uncover the intriguing relationships and their potential influence on the careers within the cinematic realm.

![Wactor-NWactor_frequency](https://github.com/SergeOhanesian/https-github.com-epfl-ada-ada-2023-project-cedars10452-website/blob/master/img/Wactor-NWactor_frequency.png)

In order to get some numerical figures, we divided our actors to two groups:
*   Actors that never participated with award winning actors
*   Actors that participated at least once with award winning actors

After counting the number of people in these two groups, we see that the Number of actors that did not participate with award winning actors(98730) is 2.7 times larger than the number of actors that participated(36226), which seems reasonable.

#### Measuring Cinematic Success: Box Office Revenue and Popularity of Movies

Success is often measured not just by critical acclaim but by the commercial impact and audience reception of the movies themselves. In this section, we embark on a journey to evaluate the success of actors within the film industry, employing two pivotal metrics: box office revenue and popularity of the movies. These metrics serve as the initial benchmarks, illuminating the impact and resonance of movies in which actors have participated. By delving into the box office revenue and gauging the popularity of these films, we unveil a comprehensive framework to rank and assess the success of actors. This exploration sets the stage for a deeper understanding of how an actor's roles and collaborations correlate with the commercial and audience-driven triumphs that define their careers in the cinematic world.

Upon analyzing the dataset, intriguing trends emerged, highlighting that actors engaged in projects alongside award-winning peers tend to showcase higher average and median box office revenue as well as heightened popularity metrics. This observation aligns logically with the increased exposure garnered by actors through collaborations with esteemed award-winning individuals. To validate and solidify these initial insights, rigorous statistical methods were employed. Utilizing t-tests and visual aids like box plots, we meticulously confirmed these observed differences. This comprehensive analysis not only fortifies our initial observations but also underscores the potential impact of collaborations with award-winning actors on the commercial success and audience appeal of the movies in which actors participate.

##### Statistical and visual Validation: T-Test Analysis and Box Plots

As the metric for this study is box office revenues and popularity of movies, we will be conducting two seperate t-tests that will allow us to statistically verify our findings. We define the first t-test using the following null and alternative hypotheses:

> H<sub>0</sub>: μ<sub>1</sub> - μ<sub>2</sub> = 0  AND  H<sub>1</sub> = μ<sub>1</sub> - μ<sub>2</sub> < 0

> where μ<sub>1</sub> = mean of average revenue of movies per actor who have no collaborated with an award-winning actor.

> and μ<sub>2</sub> = mean of average revenue of movies per actor who have collaborated with an award-winning actor.


By running this test, a significant result emerged with a t-statistic of -42.98 and a calculated p-value of 0.000. This compelling outcome leads to a pivotal finding: the rejection of the null hypothesis that the mean of average revenue of movies per actor not participating with an award winner actor is equal to the mean of average revenue of movies per actor participating with an award winning actor in favor of the alternative that the mean average revenue of movies per actor who has participated with an award-winning counterpart is greater. At a 5% significance level, this outcome underscores the substantial impact that collaborations with award-winning actors have on an actor's average revenue, emphasizing the potential influence of such partnerships within the cinematic landscape.

Following the same idea and using the same methodology we set up the second t-test using the following null and alternative hypotheses:

> H<sub>0</sub>: μ<sub>1</sub> - μ<sub>2</sub> = 0  AND  H<sub>1</sub>: μ<sub>1</sub> - μ<sub>2</sub> < 0

> where μ<sub>1</sub> = mean of average popularity of movies per actor who have not collaborated with an award-winning actor.

> and μ<sub>2</sub> = mean of average popularity of movies per actor who have collaborated with an award-winning actor.

By running this test, a significant result emerged with a t-statistic of -22.10 and a calculated p-value of 0.000. This compelling outcome leads to the following finding: the rejection of the null hypothesis that the mean of popularity of movies per actor not participating with an award winner actor is equal to the mean of popularity of movies per actor participating with an award winning actor in favor of the alternative that the mean of average popularity of movies per actor who has participated with an award-winning counterpart is greater. At a 5% significance level, this outcome matches the outcome of the first t-test, further solidifying our analysis.

In our pursuit of elucidating the influence of collaborations with award-winning actors on the financial success within the film industry, we employed box plots as a visual tool to complement our statistical analysis. These graphical representations vividly portray the distribution of average revenue per actor, offering a compelling visual narrative that aligns with our earlier statistical findings. The box plots exhibit a stark distinction between actors who have engaged in projects with award-winning counterparts and those who haven't. Notably, the median and distribution of average revenue per actor who participated in films with award-winning peers visibly outshine their counterparts who haven't had such collaborations.

![boxplotpart1a](https://github.com/SergeOhanesian/https-github.com-epfl-ada-ada-2023-project-cedars10452-website/blob/master/img/boxplotpart1a.png)

![boxplotpart1b](https://github.com/SergeOhanesian/https-github.com-epfl-ada-ada-2023-project-cedars10452-website/blob/master/img/boxplotpart1b.png)

The t-tests and box plots confirm the results obtained previously when we analyzed the dataframes. Both the popularity and the box office revenues are statistically significantly higher for actors who have participated with award-winning actors. These results seem logical; collaborating with award-winning actors, who possess proven talents, likely increases the popularity of the movies. At the same time, these movies may also reach a broader audience, which could be a reason for the higher box office revenues. After all these results provide a starting point to answering the research questions treating the impact of co-starring with high-profile actors.