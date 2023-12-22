# Unraveling the Dynamics of Star Power, Ethnicity, and Collaborative Influence in Film Success

Hey there! Let's dive into a world where the glamour of Hollywood meets the grind of research. We're setting out on an adventure, not just to crunch numbers and browse through databases, but to unravel some of the most intriguing mysteries of the film world. Think of it as our own cinematic quest, where we’re not just spectators but active explorers in the vibrant universe of movies.

In our journey, we're asking some pretty cool questions. Ever wondered if sharing the screen with big stars can give an actor's career a turbo boost? Or how about the way an actor's background and ethnicity play into their stardom and the global charm of the movies they're in? We're also curious about the glitter of awards – do those shiny Oscars and Golden Globes really open doors to new realms of roles and opportunities? Just look at Tom Hardy, whose career skyrocketed to new heights with each collaboration with award-winning directors. Then there's the dynamic journey of Robert De Niro, seamlessly shifting from gripping dramas, such as Goodfellas or Casino to heartwarming comedies, such as The Intern – a perfect example of how adaptability and strategic collaborations can sculpt an actor's career path.

## Introduction

Picture this: the film industry, a radiant mosaic of stories, dreams, and big bucks. At its heart are actors, the stars who bring these tales to life. Our mission? To peek behind the curtain and see what makes these stars shine. We'll explore the star-studded impact of acting alongside Hollywood giants, the diverse colors of ethnicity and their role in an actor's rise to fame, and the gleaming allure of awards and their afterglow on careers. We're also keen to uncover the secret sauce in those power-packed collaborations between actors and top-notch filmmakers.
Why are we doing all this, you ask? Picture a young actor, stepping onto the red carpet for the first time, eyes wide with dreams. Through our research, we want to map the roads they might travel, the hurdles they could face, and the triumphs that await. It’s a journey of discovery, to understand not just the 'what' but the 'why' behind the curtains of cinema. Let’s roll! 🎬

## Cultural Canvases on the Global Screen

As we delve deeper into the film industry's intricate world, our next stop is the role of an actor's ethnicity in the success and appeal of movies. This isn't just about star power; it's an exploration of how cultural diversity influences global audience connections.

### A First Look at the Current Actors' Ethnicities

Up next, we'll showcase intriguing data, starting with some graphs that offer a real glimpse into the diversity of the cinematic universe.

![assem1](/img/assem1.jpeg)

The bar chart presents a clustered distribution of ethnicities among actors, indicating a nuanced overlap that suggests the need for a more refined categorization to accurately reflect the diversity within the industry.

### Average Movie Revenue per Actor per Ethnicity 

Next, we turn our attention to an analysis of the average revenue per actor, categorized by ethnicity and normalized for accuracy. 

![assem4](/img/assem4.jpg)

This examination reveals a noteworthy pattern: certain ethnic groups appear to outperform others in terms of revenue. However, this observation requires a nuanced understanding. The apparent overperformance may be attributed to a relatively smaller number of actors within these ethnicities, potentially skewing the results. To ensure a more representative analysis, we refine our focus to include only those ethnic groups represented by more than 10 actors. This step is vital to gain a clearer perspective on the financial implications of ethnic diversity in film casting.

Understanding the commercial impact of casting actors from various ethnic backgrounds is essential. It provides insights into the potential financial benefits or challenges associated with diversity in casting. However, while these initial visualizations offer valuable observations, they are preliminary and not definitive. Therefore, we intend to employ linear regression analysis to delve deeper. This method will enable us to examine the data more rigorously, allowing for a thorough and controlled exploration of the underlying trends and relationships.
The dominance of certain ethnicities in our initial findings further underscores the importance of grouping them into broader, more representative world regions for a clearer understanding and a more meaningful analysis. 

### Ethnicity's Role in Box Office Performance

Now, moving on to our more formal and in-depth analysis, we aim to run a linear regression model. For this purpose, we tried to come up with some variables that will allow us to explain the role that actor ethnicity plays in movie success. 

Our analysis takes a creative turn here. How? By examining an actor’s position in the movie credits. The closer to the top, the more significant their role, allowing us to calculate the influence of their ethnic background on the film's box office performance.
And there's more to our story. We've introduced a 'main actor match' variable – it lights up when the ethnicity of the lead actor aligns perfectly with the movie's primary release region.

Through comprehensive regressions, we're not only isolating these variables but also considering crucial factors like budget and movie ratings. It's essential for a complete picture, ensuring we don't miss any hidden details that could affect our understanding of what truly makes a movie successful.


We only report the final regression: 

| Dependent Variable                   | Coefficient       | P-value |
|:-------------------------------------|:------------------|:--------|
| Intercept                            | -0.3545           |  0.000  |
| Average Rating                       | +0.0921           |  0.000  |
| Popularity                           | +0.2480           |  0.000  |
| Budget                               | +0.3451           |  0.000  |
| Weighted Average Ethnicity Match     | +0.0086           |  0.000  |

As you can see, our linear regression model brings into focus the subtle yet significant role of ethnicity in a movie's box office draw. The 'weighted average ethnicity match' emerges with a positive coefficient, indicating that an alignment between the actors' ethnicities and the movie's release region does resonate with revenue generation, even though more quietly than its co-stars in the model. This variable, while significant, does not command the stage alone. It shares the spotlight with heavy hitters like budget and popularity, which hold sway with larger coefficients, underscoring their more pronounced influence on a film's financial outcome.

This piece of the puzzle is just the start. We're now ready to dig into other areas that might influence a movie's success. Next up, we'll look at the shiny world of awards and the creative partnerships between directors and actors. We expect these areas to shed new light on what really makes a movie a hit.

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

### Assessing the Influence of Award-Winning Actors on the Careers of Their Peers: A Time Series Analysis

To further evaluate the impact of collaborating with an award-winning actor, we will now transition to a time series approach. This will allow us to assess the cinematic success of actors who have worked with award-winning actors but have never won awards themselves, both before and after these collaborations

In this section, we will perform a time series analysis for each participating actor, comparing their average box office revenues and popularity before and after their first collaboration with an award-winning actor.

To test for statistical significance in the changes in revenues and popularity, we will use the t-test, as done previously. At a 95% confidence level, the t-test for revenue change before and after participation yielded a t-statistic of -27.68. This result leads us to reject the null hypothesis that the mean average revenue per actor before collaborating with an award winner is greater than or equal to the average revenue after such collaboration.

Similarly, the t-test for changes in popularity before and after participation, also conducted at a 95% confidence level, yielded a t-statistic of -17.93. This indicates that we reject the null hypothesis that the mean average popularity per actor before participating with an award winner is greater than or equal to the average popularity after participating

The mean revenues and popularity before and after participation can be resumed in these box plots.

![boxplotstimeseriesrevs](/img/boxplotstimeseriesrevs.png)

![boxplotstimeseriespop](/img/boxplotstimeseriespop.png)

The findings reveal a statistically significant rise in both the average popularity and revenue of actors following their collaborations with award-winning actors. This pattern distinctly demonstrates the beneficial effect that working alongside award-winning actors has on the professional trajectories of their fellow actors.

### Exploring the Pre-Award Collaborations of Award-Winning Actors

Our focus now shifts to examining the projects in which award-winning actors participated before achieving their own accolades.

We define a "beneficial collaboration" between two actors as occurring when one of them had already been recognized with an award prior to the collaboration, while the other had not yet received any awards. This type of collaboration is viewed as potentially advantageous for the yet-to-be-awarded actor.

The histogram below displays the count of actors against the number of their beneficial collaborations. A notable finding is that only 22 out of the 463 award-winning actors in our dataset had won an award before engaging in any collaboration with other award-winning actors.

![histogrambeneficialcollabs](/img/histogrambeneficialcollabs.png)

Furthermore, the results, as illustrated in the pie chart below, indicate that over 97.4% of award-winning actors had already worked with other award-winning actors before securing their own awards.

![piechartbeneficialcollab](/img/piechartbeneficialcollab.png)

In conclusion, the importance of collaborating with award-winning actors cannot be overstated. These partnerships seem to not only enhance the immediate visibility and credibility of actors but also play a pivotal role in paving their path towards receiving accolades in the future. This trend highlights the interconnected nature of success in the film industry, where the collaboration and mentorship of established professionals can have a lasting impact on the careers of up-and-coming actors.

## Spotlight to Stardom: The Ripple Effect of Awards on Actors' Careers

In the grand narrative of Hollywood, winning an award isn't just a moment of glory; it's a chapter that heralds a new era in an actor's career. Our exploration into the film industry's starlit realm reveals a fascinating story: the impact of awards on an actor's trajectory. It's like a subtle yet potent spell cast upon their journey, bringing a noticeable shift in the landscape of their success.

Envision the scenario: in the wake of receiving an award or a nomination, there’s a tangible change in the box office world. Over the next five years, an actor's movies begin to paint a different picture on the box office canvas, charting a course higher than before. It's as if the award adds a new dimension to their appeal, resonating through ticket booths and industry buzz.

![boxoffice](/img/boxoffice.png)

Parallel to this box office tale is the narrative of popularity and acclaim. In the year of the award, there's a crescendo of attention, a peak where the movie’s charm shines brightest in the public eye and on platforms like IMDb. It seems that the allure of critically acclaimed films extends beyond the jury, touching the hearts of the audience and critics alike.

![mergedvote-pop](/img/mergedvote-pop.jpeg)

As we map out these trajectories of fame and success, what emerges is a story of transformation. Awards are more than just accolades; they are catalysts that propel actors into new orbits of recognition and commercial success. Each statuette and each nomination mark not just a victory but a stepping stone to a future rich with potential and promise. In the cinema's grand theatre, this is but one of the many tales of how glories on stage can turn into triumphs on the silver screen. 

But the methods we’ve used so far were naïve. As we venture deeper into our exploration of Hollywood's landscape, we adopt a more nuanced approach, one that acknowledges the complex interplay of factors that shape an actor's journey. Our analysis now shifts to a more structured stage, where we categorize our cast into two distinct groups, each offering unique insights into the dynamics of film industry success.

### Structuring the Cast

#### Treatment Group: The Award Spotlight

In this group, we gather actors who have stepped into the limelight of award recognition. These are the individuals whose talents have been formally acknowledged, be it through nominations or wins. They are our focal point, the characters whose post-award trajectories we're keen to dissect and understand.

#### Control Group: The Unacknowledged Talent

Contrasting our treatment group, here lies the pool of actors who have yet to receive such accolades. Crucially, this isn't just a static backdrop; these actors appear multiple times, representing various chapters of their careers. This group forms our baseline, allowing us to draw comparisons and observe the nuanced effects of award recognition.

#### Crafting the Narrative: Matching and Analysis

With our cast in place, our next act involves a meticulous matching process. Actors in the limelight are paired with their counterparts in the shadows, aligned by their years in the industry, the volume of their filmography, and the genres they've adorned. This methodical pairing is akin to creating a mirror image, where each reflection offers a chance to see what might have been.

In our pursuit of a fair and balanced narrative, we also introduce a crucial directorial decision: focusing solely on movies made in the USA post-1990. This choice isn't arbitrary; it anchors our story in a realm where box office figures are comparable, and the influence of cultural and industrial shifts is acknowledged. It's a conscious effort to control our storyline, ensuring that the spotlight shines evenly, allowing us to discern the true impact of those glittering awards.

The results of our t-test shed a clear, empirical light on the influence of award recognition in Hollywood. With a mean box office revenue of approximately $94.6 million for the treatment group, who have been honored with Oscars or Golden Globes, the contrast is stark against the control group's $39 million. This significant difference, underscored by a t-test statistic of 34.71 and a strikingly low p-value (5.51e-252), points to a clear conclusion: awards do have a tangible impact.

The statistical analysis confirms that actors recognized at major award ceremonies like the Oscars or Golden Globes experience a substantial increase in their box office performance in the five years following their accolade. This isn't just a marginal boost; it's a substantial elevation that sets these actors apart from their counterparts.

What these numbers reveal is a deeper story within the film industry. Awards are not merely tokens of artistic merit; they are markers of commercial viability and appeal. They seem to open doors to more lucrative roles and projects, elevating an actor's marketability significantly compared to those who haven't received similar recognition.

In summary, this data-driven exploration into the world of cinema underscores the powerful role of accolades in shaping an actor's career, not just in terms of artistic acknowledgment but also in driving box office success.

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

<iframe src="./img/network_graph.html" height="500" width="100%"></iframe>