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

## Unveiling the Influence: the Career Trajectory of Non-Award-Winning Peers due to the Collaboration with Award-Winning Actors

In the dynamic realm of cinema, the partnership between actors within a film isn't merely a collaboration—it's a convergence of talent, influence, and potential career trajectories. Within this tapestry of artistic synergy, the spotlight often shines brightly on those adorned with accolades, but what happens when their paths intersect with those who haven't yet claimed the industry's highest honors?

This section unravels a compelling facet of the film industry, exploring the profound impact experienced by actors who, despite not holding prestigious awards themselves, find themselves participating in projects alongside revered, award-winning peers. The focus isn't solely on the film itself but on the intricate dynamics that unfold when these two worlds collide.

Imagine the resonance created when the prowess of an award-winning actor intertwines with the potential of their non-awarded co-star. It's here that we delve into the very essence of influence—scrutinizing how such collaborations sculpt not just the dynamics within a movie but the career trajectories of all involved.

Join us as we dissect these cinematic partnerships, unveiling the hidden layers of influence and opportunity that arise when the acclaimed and the aspiring share the screen. From dissecting the dynamics of these collaborations to understanding the subsequent career paths taken, this exploration sheds light on the impact of participating in a film alongside an award-winning counterpart.

Prepare to embark on a journey that transcends the boundaries of awards and accolades, revealing the intricate dance of talent and opportunity that defines the ever-evolving landscape of the film industry.

### A first look at the collaboration situation

The histogram below displays the frequency of actors' participation alongside award-winning counterparts. Beyond the glitz of accolades, this visualization unveils the patterns and trends that emerge when actors collaborate with esteemed peers who have claimed prestigious awards. Each bar represents the frequency of an actor's engagements in projects alongside award-winning actors, shedding light on the prevalence and impact of such collaborations on career trajectories. Explore this histogram to uncover the intriguing relationships and their potential influence on the careers within the cinematic realm.

![Wactor-NWactor_frequency](/img/Wactor-NWactor_frequency.png)

In order to get some numerical figures, we divided our actors to two groups:
*   Actors that never participated with award winning actors
*   Actors that participated at least once with award winning actors

After counting the number of people in these two groups, we see that the Number of actors that did not participate with award winning actors(98730) is 2.7 times larger than the number of actors that participated(36226), which seems reasonable.

### Measuring Cinematic Success: Box Office Revenue and Popularity of Movies

Success is often measured not just by critical acclaim but by the commercial impact and audience reception of the movies themselves. In this section, we embark on a journey to evaluate the success of actors within the film industry, employing two pivotal metrics: box office revenue and popularity of the movies. These metrics serve as the initial benchmarks, illuminating the impact and resonance of movies in which actors have participated. By delving into the box office revenue and gauging the popularity of these films, we unveil a comprehensive framework to rank and assess the success of actors. This exploration sets the stage for a deeper understanding of how an actor's roles and collaborations correlate with the commercial and audience-driven triumphs that define their careers in the cinematic world.

Upon analyzing the dataset, intriguing trends emerged, highlighting that actors engaged in projects alongside award-winning peers tend to showcase higher average and median box office revenue as well as heightened popularity metrics. This observation aligns logically with the increased exposure garnered by actors through collaborations with esteemed award-winning individuals. To validate and solidify these initial insights, rigorous statistical methods were employed. Utilizing t-tests and visual aids like box plots, we meticulously confirmed these observed differences. This comprehensive analysis not only fortifies our initial observations but also underscores the potential impact of collaborations with award-winning actors on the commercial success and audience appeal of the movies in which actors participate.

#### Statistical and visual Validation: T-Test Analysis and Box Plots

As the metric for this study is box office revenues and popularity of movies, we will be conducting two seperate t-tests that will allow us to statistically verify our findings. We define the first t-test using the following null and alternative hypotheses:

> H<sub>0</sub>: μ<sub>1</sub> - μ<sub>2</sub> = 0  AND  H<sub>1</sub>: μ<sub>1</sub> - μ<sub>2</sub> < 0

> where μ<sub>1</sub> = mean of average revenue of movies per actor who have no collaborated with an award-winning actor.

> and μ<sub>2</sub> = mean of average revenue of movies per actor who have collaborated with an award-winning actor.


By running this test, a significant result emerged with a t-statistic of -42.98 and a calculated p-value of 0.000. This compelling outcome leads to a pivotal finding: the rejection of the null hypothesis that the mean of average revenue of movies per actor not participating with an award winner actor is equal to the mean of average revenue of movies per actor participating with an award winning actor in favor of the alternative that the mean average revenue of movies per actor who has participated with an award-winning counterpart is greater. At a 5% significance level, this outcome underscores the substantial impact that collaborations with award-winning actors have on an actor's average revenue, emphasizing the potential influence of such partnerships within the cinematic landscape.

Following the same idea and using the same methodology we set up the second t-test using the following null and alternative hypotheses:

> H<sub>0</sub>: μ<sub>1</sub> - μ<sub>2</sub> = 0  AND  H<sub>1</sub>: μ<sub>1</sub> - μ<sub>2</sub> < 0

> where μ<sub>1</sub> = mean of average popularity of movies per actor who have not collaborated with an award-winning actor.

> and μ<sub>2</sub> = mean of average popularity of movies per actor who have collaborated with an award-winning actor.

By running this test, a significant result emerged with a t-statistic of -22.10 and a calculated p-value of 0.000. This compelling outcome leads to the following finding: the rejection of the null hypothesis that the mean of popularity of movies per actor not participating with an award winner actor is equal to the mean of popularity of movies per actor participating with an award winning actor in favor of the alternative that the mean of average popularity of movies per actor who has participated with an award-winning counterpart is greater. At a 5% significance level, this outcome matches the outcome of the first t-test, further solidifying our analysis.

In our pursuit of elucidating the influence of collaborations with award-winning actors on the financial success within the film industry, we employed box plots as a visual tool to complement our statistical analysis. These graphical representations vividly portray the distribution of average revenue per actor, offering a compelling visual narrative that aligns with our earlier statistical findings. The box plots exhibit a stark distinction between actors who have engaged in projects with award-winning counterparts and those who haven't. Notably, the median and distribution of average revenue per actor who participated in films with award-winning peers visibly outshine their counterparts who haven't had such collaborations.

![boxplotpart1a](/img/boxplotpart1a.png)

![boxplotpart1b](/img/boxplotpart1b.png)

The t-tests and box plots confirm the results obtained previously when we analyzed the dataframes. Both the popularity and the box office revenues are statistically significantly higher for actors who have participated with award-winning actors. These results seem logical; collaborating with award-winning actors, who possess proven talents, likely increases the popularity of the movies. At the same time, these movies may also reach a broader audience, which could be a reason for the higher box office revenues. After all these results provide a starting point to answering the research questions treating the impact of co-starring with high-profile actors.

## Spotlight to Stardom: The Ripple Effect of Awards on Actors' Careers

In this part we embark on a journey through the captivating realm of cinematic stardom, where accolades serve as milestones in the careers of actors, illuminating their trajectory within the ever-evolving landscape of the film industry. This section, delves into the profound influence that awards have on the paths and achievements of these on-screen luminaries. From dissecting the transformative impact of awards on an actor's career trajectory to unraveling the resonance of accolades within the cinematic sphere, this exploration unveils the nuanced dynamics and far-reaching consequences of industry recognition. Join us as we explore the profound ripple effect that awards create, shaping the destinies of those who stand under their luminous spotlight.

### A First Look at the Actors' Stardom Situation

The following histograms serve as a portal into the realm of recognition within the film industry, portraying the nominations and victories amassed by actors on their quest for acclaim. Our exploration navigates through the flow of recognition, delving into the patterns and frequencies that dictate an actor's journey toward industry acclaim. From analyzing the frequency of nominations to unraveling the moments of triumph on award nights, this visual journey offers a comprehensive view into the landscape of accolades and the current state of the industry.

![nominations-awards](/img/nominations-awards.png)

### Initial Observation: Award Influence Analysis

Analyzing movie metrics before and after an actor wins an award can reveal insights into the award's influence on their career and the success of the films they participate in. This comprehensive analysis transcends mere statistics. It's a journey that delves into the transformative impact of accolades on an actor's career and the cinematic resonance of the films they inhabit. By scrutinizing the movie metrics, ranging from box office revenue to critical acclaim before and after an actor's momentous win, we discover pivotal insights into the award's influence. This exploration not only illuminates the immediate ripple effect on an actor's subsequent roles and career choices but also unravels the enduring legacy left on the films themselves. Prepare to witness the metamorphosis sparked by an actor's triumph, as we navigate through the before-and-after landscape, uncovering the indelible imprint of awards on the individual.

#### Revenue Increase Post Awards

The below plot indicates a potential increase in box office revenue following an award win, hinting at a noteworthy surge in box office revenue subsequent to an actor's triumph at prestigious awards. This telling pattern underscores the pivotal role that accolades play in not only elevating an actor's profile but also in amplifying the commercial viability of the films they grace. The observed upturn in box office figures serves as a testament to the enhanced marketability wielded by actors post-award wins, signifying a newfound allure that resonates with audiences and potentially draws wider attention to their cinematic endeavors. This correlation between an actor's accolades and the subsequent financial performance of their films hints at a symbiotic relationship, where industry recognition amplifies an actor's star power, consequently bolstering the financial success and market appeal of the movies they inhabit. This insight unveils a fascinating dynamic within the film industry, illustrating the far-reaching implications of awards beyond mere recognition, as they intricately weave into the fabric of commercial success and market reception for these cinematic ventures.

![awards-revenue](/img/awards-revenue.png)

#### Increased Voter Participation and Change in Rating Quality

The first part of the below plot presents an intriguing discovery: a surge in audience participation in voting for movie ratings on IMDb subsequent to an actor's accolade. This surge signifies a palpable spike in audience engagement, reflecting a heightened interest and involvement spurred by an actor's triumph at prestigious awards. The resonance of an award win reverberates beyond the ceremonies, resonating deeply with audiences who seem excited to voice their opinions and contribute to the cinematic discourse. This surge in voting participation underscores the profound impact of awards on audience engagement, suggesting that industry recognition not only influences critical acclaim but also catalyzes a deeper connection between audiences and the films they adore. This heightened engagement on platforms like IMDb paints a vivid picture of the amplified interest and emotional investment that follows an actor's triumph, highlighting the pivotal role that awards play in fostering a more vibrant, participative cinematic community. It's a testament to the enduring power of awards in not just honoring talent but in fostering a stronger, more interactive relationship between cinema and its diverse audience base.

The intriguing revelation from the second part of the below plot unveils a thought-provoking dynamic within the realm of audience perception and expectations. Contrary to the anticipated rise in ratings following an actor's accolade, the data hints at a surprising downturn in average ratings post-award. This unexpected trend prompts a deeper exploration into the intricate psyche of audiences and their evolving perceptions of movies featuring award-winning actors. This shift could signify a fascinating paradox where heightened acclaim and recognition place movies under a more scrutinizing lens. The decrease in average ratings might be indicative of heightened audience expectations, influenced by the elevated prestige associated with award-winning actors. It's conceivable that audiences, anticipating extraordinary cinematic experiences, hold these films to higher standards, resulting in more critical assessments. This trend results in a raise of the bar for films, prompting audiences to appraise them with a more discerning eye. This unexpected downturn in ratings, offers a fascinating insight into the complexities of audience perception and their evolving standards.

![awards-votes](/img/awards-votes.png)

#### Popularity Surge

The below plot highlights an increase in the popularity score after an award win, aligning with the notion that awards boost an actor's public visibility and appeal. This is an indication of a public fascination and appeal. The observed increase in popularity scores paints a vivid picture of the ripple effect sparked by an actor's triumph that extends to their broader appeal among audiences. Awards act as beacons, casting a luminous spotlight on an actor and their body of work, thereby fostering a more profound connection with the public. This surge in popularity scores underscores the pervasive influence of awards in amplifying an actor's charisma, resonance, and relatability among diverse audiences.

![awards-popularity](/img/awards-popularity.png)

### Further Observation: Statistical Analysis

The revelations from our initial observations present an intriguing narrative that hints at the interplay between awards, an actor's career trajectory, and the performance of their films. However, these observations, while compelling, serve as a foundation for deeper exploration. In this section we embark on a more robust statistical analysis to solidify and unveil the underlying causal relationships. Through rigorous statistical tests, our aim is to traverse beyond correlations and establish a more concrete understanding of the cause-and-effect dynamics between awards, an actor's professional success, and the subsequent performance of their films.

## Cultural Canvases on the Global Screen

In the global film industry, an actor's ethnicity weaves an intricate thread within the fabric of success and audience reception. The influence of an actor's ethnicity on their trajectory within the industry and the international resonance of their films stands as a multifaceted terrain waiting to be explored. This exploration delves beyond the performances themselves, seeking to unravel the nuanced interplay between an actor's cultural background and their journey towards success. How does an actor's ethnicity affect their success and the international reception of their films? This research question serves as a gateway into understanding the different ways in which an actor's ethnicity functions as both a defining factor and a dynamic force within the global cinematic panorama. Join us as we navigate this compelling terrain, dissecting the profound impact of ethnicity on an actor's journey to success and the resonant echoes it creates within global audiences.

### A First Look at the Current Actors' Ethnicities

Before delving deeper into our analysis, let's take an initial glimpse into the diverse landscape of current actors. This section offers a panoramic view, highlighting the representation and distribution of actors across various ethnic groups within the cinematic sphere. By examining the numbers and proportions within each ethnic category, we unveil a preliminary understanding of the industry's diversity. This initial overview lays the groundwork for our exploration into how these diverse ethnicities navigate the pathways of success and influence the reception of their films on the global stage. The below barplot displays the top 10 ethnicities in terms of number of actors.

![top10ethnicities](/img/top10ethnicities.png)

### Average Movie Revenue per Actor per Ethnicity 

This section sheds light on the fascinating correlation between an actor's ethnicity and the average movie revenue they generate. By dissecting these revenue metrics across various ethnicities, we uncover nuanced insights into the economic impact and opportunities experienced within the cinematic realm. This initial glimpse offers a compelling narrative, providing a preliminary understanding of how an actor's ethnicity may intersect with financial success within the dynamic and diverse landscape of film. However, this is a preliminary analysis of whether an actor's ethnicity influences a movie's box office success. By comparing average revenues of movies featuring actors from different ethnicities and then adjusting these averages based on the number of actors in each group, we aim to see whether some ethnicities are associated with higher revenues in a more equitable and representative way. The below barplot displays the top 10 average movie revenues generated per actor by ethnicity.

![top10revenue-ethnicities](/img/top10revenue-ethnicities.png)

But we notice that the actor counts for some of these ethnicities are very low (<10). Therefore, we will introduce a cut-off point. We will require at least 10 actors from one ethnicity for the ethnicity to be considered in this part of our analysis. After applying the changes required we got the following results displayed in the below barchart.

![top10revenue-ethnicities-2](/img/top10revenue-ethnicities-2.png)

- These graphs above are a comparison of average movie revenue per actor before and after applying a filter for a minimum of ten actors per ethnicity. It's important to study this because it helps us understand the commercial impact of having actors of different ethnicities in movies. From the first to the second graph, we see a change in which ethnicities appear, suggesting that some groups have fewer actors but still a significant impact on revenue (probably irrelevant due to sample size). 
- However, because the analysis is not highly conclusive, it's a starting point that indicates the need for a more in-depth look at diversity in film and its economic implications. It shows a glimpse of the potential market performance of movies with diverse casts but requires further study to draw strong conclusions, which we will delve deep into as we proceed.

### Average Movie Rating by Ethnicity

This section unveils an intriguing exploration into the average movie ratings across various ethnicities, offering insights into the intersection between an actor's ethnic background and the critical acclaim their films receive. By analyzing these ratings, we embark on a journey that navigates the subtle interplay between ethnicity and audience perceptions, painting a preliminary picture of how diverse cultural backgrounds may influence the cinematic narratives' reception. This overview serves as a gateway into understanding the dynamic relationship between an actor's ethnicity and the audience's appraisal, providing a nuanced glimpse into the multifaceted dimensions of film appreciation. The below barplot displays the top 10 average movie rating by ethnicity.

![top10rating-ethnicities](/img/top10rating-ethnicities.png)

- The graph shows movie ratings linked to actors' ethnicities. This simple plot indicates that films with Czech actors get the best ratings, but other ethnicities are not far behind. This means people are enjoying movies with actors from different backgrounds in general.
- It is noteworthy to mention that we used a logarithmic scale on the y-axis because the ratings are very close to each other and the plot doesn't really show any value otherwise.

### Temporal Trends

Within the ever-evolving landscape of cinema, the representation of diverse ethnicities stands as a mirror reflecting societal shifts and evolving narratives. This section embarks on a temporal journey, exploring the dynamic flux in ethnicity representation across cinematic epochs. Through a captivating visual narrative, we unveil the changing landscape of ethnic diversity within movies over time. The below plot serves as a lens through which we witness the flow of representation, observing the evolving strides, setbacks, and the nuanced patterns that shape the portrayal of diverse ethnicities across different eras of cinematic storytelling. 

![temporaltrends-ethnicities](/img/temporaltrends-ethnicities.png)

- We analyze the ethnicity representation in movies over time to track the progress of diversity and inclusivity in the film industry. It offers a visual insight into how the portrayal of various ethnic groups has changed, potentially reflecting shifts in societal attitudes and stereotypes. The chart indicates a trend towards greater diversity in recent decades, suggesting a response to increased awareness and demand for representation, which makes sense. 
- It is very important to note that the ethnicities given from the dataset can be clustered into more compact and inclusive ethnicities for better analysis, which we will conduct in the following sections.

### Ethnicity Clustering: Unifying Diversity for Deeper Insights

Immediately we notice a huge overlap between some of the ethnicities (for example white people and White Americans). This will be tackled by clustering these ethnicities into more extensive ones.

In our pursuit of comprehensively understanding the nuanced landscape of ethnic representation within the film industry, we encounter a fascinating convergence of ethnicities that often share substantial similarities. This section ventures into the realm of _Ethnicity Clustering_,which gives a strategic approach aimed at combining overlapping ethnicities into more expansive and cohesive groups. By clustering these ethnicities, we aspire to create a more comprehensive and nuanced lens through which to analyze and interpret the diversity landscape within films. This process is poised to  offer a more holistic understanding of how these collective ethnic representations shape the cinematic narrative. Join us as we embark on this journey of consolidation, seeking to merge similar threads and enrich our exploration of diversity within the captivating world of film.

## Behind the Scenes Alchemy

Within the intricate ecosystem of the film industry, the collaborations forged between actors and esteemed directors or producers stand as pivotal milestones in shaping not just careers, but the very essence of cinematic storytelling. This section ventures into the profound impact of these collaborations, spotlighting how partnerships with acclaimed directors and producers serve as transformative catalysts within an actor's career trajectory. Beyond mere collaborations, these alliances offer more than just roles, they provide a gateway to heightened visibility, diverse and demanding characters, and often, an amplified resonance at the box office. Join us in unraveling the symbiotic relationship between actors and the luminaries behind the camera, as we explore how these collaborations carve the pathways to success, prestige, and enduring cinematic legacies.

### Exploring the Interplay: Nominations/Awards Won and Box Office Revenue/Vote Average Correlation

In this section, we embark on a captivating exploration into the intricate interplay between nominations and awards won and the cinematic metrics of box office revenue and vote average. This analysis seeks to unveil the nuanced correlations that exist between the industry accolades a movie crew receives and the commercial success or critical reception of their films. By delving into this intersection, we aim to decode how an director's recognition in the form of nominations and awards intertwines with the financial performance and audience appreciation of the movies they inhabit. Join us in deciphering this complex relationship, as we unravel the potential influences and connections that underpin the dynamic landscape of awards recognition and cinematic acclaim. In order to understand these correlations, we make use of two statistical methods: the Pearson correlation and the Spearman correlations. We ran both of these tests on each scenario we are trying to study, and obtained the following results:

1. ***Total movie crew member nominations and movie box office revenues***

> Pearson correlation:  PearsonRResult(statistic=0.29, pvalue=1.4e-149)

> Spearman correlation:  SignificanceResult(statistic=0.24, pvalue=4.75e-103)

> The Pearson correlation is significant.

> The Spearman correlation is significant.

1. ***Total movie crew member awards won and movie box office revenues***

> Pearson correlation:  PearsonRResult(statistic=0.28, pvalue=8.27e-139)

> Spearman correlation:  SignificanceResult(statistic=0.16, pvalue=1.47e-47)

> The Pearson correlation is significant.

> The Spearman correlation is significant.

1. ***Total movie crew member nominations and vote average***

> Pearson correlation:  PearsonRResult(statistic=0.30, pvalue=4.35e-167)

> Spearman correlation:  SignificanceResult(statistic=0.39, pvalue=2.90e-275)

> The Pearson correlation is significant.

> The Spearman correlation is significant.

1. ***Total movie crew member awards won and vote average***

> Pearson correlation:  PearsonRResult(statistic=0.21, pvalue=3.10e-78)

> Spearman correlation:  SignificanceResult(statistic=0.27, pvalue=1.63e-134)

> The Pearson correlation is significant.

> The Spearman correlation is significant.

### Tom Hardy's Career Post-"Inception"

In this section we study the case of Tom Hardy which will serve as a compelling situation illustrating the transformative power of collaborations and breakout roles. Following his standout performance in Christopher Nolan's Inception, Hardy's journey catapulted into a realm of high-profile projects, setting a stage for a career trajectory marked by versatility and acclaim. Some of the notable works of Tom Hardy post-Inception are: 

- **"The Dark Knight Rises":**
  - Hardy's role as the formidable Bane showcased his versatility and cemented his status as a leading actor in Hollywood.

- **"Mad Max: Fury Road":**
  - A lead role in this film marked a critical and commercial success, demonstrating Hardy's range and mass appeal.

- **"Venom"** in the Superhero Genre:
  - His portrayal in "Venom" solidified Hardy's capability to anchor a blockbuster film with his dynamic performance.

- **"Peaky Blinders" - A Critically Acclaimed Series:**
  - Although not in our dataset as it is a TV series, Hardy's involvement in Peaky Blinders highlighted his skill in long-form storytelling, adding a significant layer to his acting portfolio.

This analysis of Hardy's career stands as a beacon, illuminating the potential ripple effect that breakout roles and collaborations with esteemed directors can have on an actor's path. As we delve deeper into the industry landscape, this case becomes a cornerstone for extrapolating and understanding similar phenomena that shape the journeys of actors within the cinematic sphere.

The graphs below display the difference in movie box office revenues and vote average before and after Tom Hardy's appearence in the Inception. This serves as a prime example of how strategic collaborations with notable directors and producers can not only diversify an actor's portfolio but also significantly boost their marketability and box office draw. This pattern is a testament to the power of strategic collaborations in the film industry to propel an actor's career to new heights.

![TomHardy-revenue](/img/TomHardy-revenue.png)

![TomHardy-vote](/img/TomHardy-vote.png)

## Careers Evolution

Within the dynamic evolution of an actor's career lies a fascinating journey marked by the genres they traverse—a trajectory that not only mirrors personal growth and evolving artistic inclinations but also mirrors the ever-shifting landscape of audience expectations and industry trends. As actors age, they may transition from one genre to another for various reasons. These shifts could be driven by a range of factors, including personal choice, typecasting, changes in the types of roles offered to them as they age, or even a strategic response to evolving trends within the film industry. In the early stages of their careers, actors might be more inclined to experiment with different genres or take on roles that challenge them in various ways. This period is often characterized by a quest for establishing a foothold in the industry, where versatility and a wide range of roles can be advantageous. As actors establish themselves, certain patterns might emerge, reflecting their strengths or audience preferences. For instance, an actor known for compelling dramatic performances might increasingly find themselves sought after for similar roles. Join us as we decipher the complex interplay between actors, genres, and the ever-evolving landscape of cinematic storytelling.

### Analysis of Movie Genres and Actor Age Distribution

Exploring the relationship between an actor's age and the distribution of movie genres they participate in unveils an intriguing tapestry of patterns within the film industry. This section ventures into the captivating intersection where an actor's age intersects with the diverse array of movie genres they inhabit at the time of release. By dissecting this correlation, we unravel the nuanced patterns that emerge, shedding light on how an actor's age potentially influences the genres they gravitate towards or are offered. These insights offer a glimpse into the complex dynamics that shape an actor's choices, the industry's preferences, and the audience expectations, encapsulating a mosaic of factors that interplay in defining the cinematic landscape across different age brackets. As a first step, we plotted the distribution of movie genres against the age of actors at the time of release. The plot below shows the distribution of movie genres across different actor age buckets.

![genre-agebracket](/img/genre-agebracket.png)

From this plot we can take away some interesting observations:

**Drama Movies**
For drama movies, there's an observable increase in participation with the age of the actors. This trend might stem from the depth and complexity of dramatic roles, which older actors, with their wealth of experience and nuanced understanding of human emotions, are often more adept at portraying. Their life experience lends authenticity and gravitas to these roles, making them particularly effective in dramatic narratives.

**Fantasy Films**
In fantasy films, a similar increase is noted with older actors. This could be attributed to the fact that many fantasy narratives require seasoned, wise characters, like wizards or elders. Roles exemplified by Dumbledore in "Harry Potter" or Gandalf in "The Lord of the Rings" are prime examples. Older actors bring a believable sense of wisdom and historical depth to these characters, enhancing the storytelling.

**Comedy Films**
On the other hand, comedy films show a decrease in participation by older actors. This might be due to the physical demands of physical comedy, or the themes and situations in comedies that often resonate more with a younger demographic. Additionally, as the comedy genre evolves with changing cultural references and styles, younger actors may be perceived as more relatable to the target audience.

These trends highlight not just individual actor choices, but also broader industry practices and audience expectations, reflecting the dynamic interplay between career trajectories, industry trends, and cultural shifts. For the purpose of readability, in the above plot, we tried to only include some of the most prominent genres in the film industry. The database contains a substantial amount of very detailed genres, which we will try to group as we proceed.

### Genre Evolution: The Example of Robert De Niro

Investigating the career trajectories of high-profile actors offers valuable insights into how genre preferences evolve over time. A prime example is Robert De Niro, whose early career was marked by intense drama movies and iconic gangster roles. His performances in films like "Taxi Driver" and "Raging Bull" showcased his ability to bring depth and intensity to complex characters, while his roles in "Goodfellas" and "The Godfather II" cemented his reputation as a formidable presence in the gangster genre.

However, in his later career, De Niro exhibited a notable shift in the types of roles he chose. He began to appear more frequently in comedies and lighter genres, a departure from the intense, often brooding characters of his earlier years. This transition can be seen in films like the "Meet the Parents" trilogy and "The Intern," where he embraced more comedic, approachable characters. This evolution in De Niro's career could be indicative of a desire to explore different facets of his acting abilities or possibly a response to changing audience expectations and industry trends.

The plot below displays the distribution of movie genres against the age of Robert De Niro at the time of release. 

![age-DeNiro](/img/age-DeNiro.png)

![network_graph](/img/network_graph.html)