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

Transitioning from our previous analysis of the average revenue and popularity among actors who have and have not collaborated with award-winning actors, we now advance to a time series analysis. This new phase focuses on scrutinizing the effects of collaborations between actors and award-winning peers on three specific aspects: box office revenue, popularity, and the likelihood of winning an award post-collaboration.

In this segment, we will closely examine how actors' careers are impacted before and after collaborating with award-winning actors. Our analysis will delve into whether such collaborations lead to a tangible increase in box office success, a boost in popularity, and an enhanced probability of winning awards. This targeted approach aims to provide a clearer understanding of the real value these prestigious collaborations bring to actors' careers.

## Assessing the Influence of Award-Winning Actors on the Careers of Their Peers: A Time Series Analysis

This time series approach will allow us to assess the cinematic success of actors who have worked with award-winning actors but have never won awards themselves, both before and after these collaborations

### Time Series Analysis of Actors: Comparing Box Office Revenues and Popularity Before and After Collaborating with Award-Winning Actors

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

As observed in our analysis, three key aspects - box office revenue, popularity, and the likelihood of winning an award post-collaboration - all show an increase following collaborations with award-winning actors

## Behind the Scenes Alchemy

In the fascinating world of cinema, where every movie is a unique blend of talent and creativity, we often ponder the role of those behind the camera in shaping the success of a film. Moving away from the glittering allure of star-studded casts, our focus turns to the often-unseen architects of film, the directors, writers and producers. In this chapter of our cinematic exploration, we delve into the nuanced impact of collaboration with acclaimed directors, writers and producers on an actor's career trajectory. We sought to understand how working with award-winning and nominated industry veterans influences an actor’s journey.

### The Catalyst of Tom Hardy's Career: A Prelude to Our Analysis

Before embarking on our comprehensive journey through the film industry's network, we turned our lens to a particularly illustrative case: the career transformation of Tom Hardy following his role in "Inception." This analysis was motivated by Hardy's remarkable ascent post his involvement in Christopher Nolan's masterpiece, which served as a pivotal moment in his career.

Our analysis took a deep dive into the tangible impact of "Inception" on Hardy's career. We specifically examined the change in box office revenues and movie ratings before and after this defining role. The results were striking: a noticeable elevation in both the commercial success and critical acclaim of his films post-"Inception."

![TomHardy-revenue](/img/TomHardy-revenue.png)

This case study of Tom Hardy stands as a vivid illustration of the transformative power of significant roles and collaborations in an actor's journey. It set the stage for our broader exploration, providing a lens through which we could examine similar patterns across the industry. Hardy's story is a testament to the impact that strategic collaborations and breakout roles can have, not just in diversifying an actor's portfolio, but in catapulting them to new levels of fame and success. As we delve into the wider analysis of how collaborations with acclaimed directors and producers shape careers, Tom Hardy's post-"Inception" journey serves as a beacon, highlighting the extraordinary potential of strategic partnerships in the cinematic world.

### Unraveling the Impact of Crew Accolades on Movie Success

We began by examining a compelling question: Do the awards and nominations of a film's crew influence its box office and critical success? Our initial statistical foray revealed intriguing correlations:

1. **Box Office Revenue**: A positive correlation emerged between the accolades of the crew (both awards won and nominations) and the financial performance of their movies.

2. **Movie Ratings**: We observed a similar trend linking crew awards to higher average ratings for their films.

These initial findings painted a picture where the recognition of a film's crew seems to be a harbinger of its success, both in commercial appeal and critical acclaim. This insight sets the stage for a deeper dive into the film industry's network, to further explore how the collective achievements of directors, writers, and producers intertwine with the stories they bring to life on screen. Motivated by these revelations, we embarked on a methodical quest, constructing an intricate network graph specifically designed to map the collaborative relationships between actors and the crews in the cinema industry. In this focused network, each node represented either an actor or a key crew member: directors, writers, and producers known for their award-winning and nominated work. The connections, or edges, between these nodes signified collaborations on various film projects. To further enrich our analysis, we showcased a subgraph highlighting the top nodes of the network. This subset offered an intriguing glimpse into the core of the industry's collaborative web, featuring prominent figures such as Robert DeNiro and influential entities like 20th Century Fox. The presence of these key players in the subgraph provided a fascinating perspective on the central, interconnected roles they play in shaping cinematic narratives.

Our aim was clear: to meticulously measure and analyze the impact of these specific collaborations between actors and their distinguished crews. We wanted to see how working with accomplished directors and producers influenced various aspects of an actor's success, ranging from critical acclaim and box office performance to audience reception and admiration. This tailored network analysis was poised to uncover the nuanced dynamics of how actors' careers are potentially shaped and transformed through their associations with award-recognized professionals in the film industry.

<iframe src="./img/network_graph.html" height="500" width="100%"></iframe>

![selfie](/img/selfie.png)

### Exploring the Influence of Community Affiliation

In our quest to comprehend the intricate landscape of the film industry, we extended our analysis to examine the influence of community affiliation on various success metrics. Our ANOVA results revealed pronounced differences in average film ratings, box office revenues, vote counts, and neighbor centrality among different communities, suggesting that these groups possess distinct traits and advantages. This deeper dive, enhanced by geometric mean visualizations, brings to the forefront the significant impact of community dynamics on an actor's career trajectory. It prompts us to ponder: Does the essence of a community shape its members, or do the members define the community's character?

![ANOVA](/img/ANOVA.jpeg)

### The Interplay of Community Attributes and Success

Our community analysis delves into the distribution of awards, nominations, and the network centrality of crew members across various communities. We seek to unravel whether belonging to a particular community inherently bestows shared characteristics or influences these attributes. The emerging patterns from our visualizations and tests open up a realm of intriguing possibilities. Is the congruence observed within a community merely a reflection of shared experiences and opportunities, or does it indicate a deeper, more influential bond shaped by the community's collective identity?

This line of inquiry lays the groundwork for future explorations into the causative dynamics within the film industry's network. It challenges us to consider how the subtle forces of community affiliation might steer an individual's or a group's path towards success and influence within the cinematic domain. Our findings not only shed light on the present state of these communities but also invite further investigation into the evolving nature of these collaborative networks in shaping the narratives of success in the cinema industry. Motivated by these results, we utilized our network and identified communities to drive the regression analysis forward. This approach set the stage for an intriguing plot twist in our cinematic narrative. We uncovered a remarkable link: an actor's success, encapsulated in ratings, box office receipts, and audience votes of his movies, was intertwined with the stature of their professional network, particularly the crew they collaborated with. This narrative took a dramatic turn as we delved into a comparison of two distinct casts of actors: those who had collaborated with acclaimed crews and those who had not. The data unfurled an engrossing story:

![boxplotadam](/img/boxplotadam.jpeg)

- **Actors with Acclaimed Crew Connections** showcased significantly higher neighbor centrality in their networks, with median degrees reaching 4031, far surpassing their counterparts. This observation is crucial, as it reflects the influence and standing of the crews they work with. Given our regression analysis linking neighbor centrality to career success, this finding suggests a profound impact on the actors' career trajectories. Actors in this group, by virtue of their association with highly experienced and recognized crews, likely find themselves in a more advantageous position, accessing higher-quality projects and elevating their stature in the industry.

- **Actors Not Collaborating with Acclaimed Crew**, in contrast, were more on the fringes of the industry's network, potentially curtailing their pathways to high-profile projects and collaborations.

The convergence of these insights, from the regression analysis to the stark contrasts between the two groups, narrated a tale of opportunity and triumph. It hinted that an actor's career trajectory is not solely carved by their talent but is also significantly molded by the influence and acclaim of their professional network. 
Our data-driven journey through the complex network culminates in a nuanced understanding of the industry. Collaborations with esteemed crews were not mere entries on a resume; they were potential catalysts, propelling actors toward heightened acclaim, commercial success, and audience adoration.

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

## Careers Evolution

Within the dynamic evolution of an actor's career lies a fascinating journey marked by the genres they traverse—a trajectory that not only mirrors personal growth and evolving artistic inclinations but also mirrors the ever-shifting landscape of audience expectations and industry trends. As actors age, they may transition from one genre to another for various reasons. These shifts could be driven by a range of factors, including personal choice, typecasting, changes in the types of roles offered to them as they age, or even a strategic response to evolving trends within the film industry. In the early stages of their careers, actors might be more inclined to experiment with different genres or take on roles that challenge them in various ways. This period is often characterized by a quest for establishing a foothold in the industry, where versatility and a wide range of roles can be advantageous. As actors establish themselves, certain patterns might emerge, reflecting their strengths or audience preferences. For instance, an actor known for compelling dramatic performances might increasingly find themselves sought after for similar roles. Join us as we decipher the complex interplay between actors, genres, and the ever-evolving landscape of cinematic storytelling.

### Analysis of Movie Genres and Actor Age Distribution

Exploring the relationship between an actor's age and the distribution of movie genres they participate in unveils an intriguing tapestry of patterns within the film industry. This section ventures into the captivating intersection where an actor's age intersects with the diverse array of movie genres they inhabit at the time of release. By dissecting this correlation, we unravel the nuanced patterns that emerge, shedding light on how an actor's age potentially influences the genres they gravitate towards or are offered. These insights offer a glimpse into the complex dynamics that shape an actor's choices, the industry's preferences, and the audience expectations, encapsulating a mosaic of factors that interplay in defining the cinematic landscape across different age brackets. As a first step, we plotted the distribution of movie genres against the age of actors at the time of release. The plot below shows the distribution of movie genres across different actor age buckets.

![genre-agebracket](/img/genre-agebracket.png)

From this plot we can take away some interesting observations:

### The Evolution of Genres in an Actor's Career

#### The Depth of Drama

As actors mature, there's a noticeable gravitation towards drama. This genre, rich in complexity, seems to align well with the depth of experience that comes with age. Seasoned actors, armed with a nuanced understanding of life's intricacies, often find a resonant match in the dramatic roles that demand such depth. It's where their journey through life enriches their portrayal on screen, lending authenticity and weight to the narrative.

#### The Wisdom in Fantasy

Fantasy films, too, often see an uptick in participation from older actors. Here, age brings with it a sense of wisdom, a crucial ingredient for roles like the venerable wizard or the sage elder. Older actors, with their air of lived wisdom, breathe life into these fantastical characters, making them believable anchors in a world of imagination.

#### The Lightness of Comedy

Conversely, comedy tends to be a younger actor's playground. Perhaps it's the physicality of comedic roles or the genre's ever-evolving nature, resonating more with younger audiences and their experiences. As actors age, their presence in comedy seems to wane, possibly a reflection of the genre’s demanding nature or the shifting landscape of humor and cultural references.

These genre trends weave a tapestry that speaks to more than just personal choice. They reflect broader patterns in the industry and audience preferences, painting a picture of how actors navigate the changing seas of cinematic demand and opportunity.

### Genre Evolution: The Example of Robert De Niro

Take Robert De Niro, for instance. His early career was defined by intense drama and iconic roles in the underworld of crime cinema. His performances in "Taxi Driver" and "Raging Bull" showcased a raw intensity, while "Goodfellas" and "The Godfather II" solidified his standing in the gangster genre. Yet, as his career progressed, De Niro displayed a remarkable pivot. He began to embrace the lighter, more humorous side of cinema. This transition, evident in the "Meet the Parents" series and "The Intern," suggests an exploration of different facets of his talent or perhaps an adaptation to the evolving landscape of audience preferences and industry trends. In sum, an actor's genre journey is more than a series of roles. It's a narrative of adaptation, growth, and response to the ever-changing world of cinema. As we delve deeper, we uncover not just the stories they tell on screen but the underlying story of their artistic evolution.

The plot below displays the distribution of movie genres against the age of Robert De Niro at the time of release. 

![age-DeNiro](/img/age-DeNiro.png)

## Employing Topic Modeling to Characterize Movie Genres

In the dynamic world of cinema, classifying and understanding movie genres has always sparked both artistic and analytical interest. With advanced data analysis techniques coming to the fore, we've embraced new methods to explore the subtleties of film genres more deeply. Utilizing LDA (Latent Dirichlet Allocation) for topic modeling, we've been able to generate distinct topic distributions for each movie in our dataset.

The topics we identified are as follows:

Topic 0: "Action/Adventure/Sci-Fi"

Topic 1: "Horror/Thriller"

Topic 2: "Drama"

Topic 3: "Comedy"

Topic 4: "Other"

Topic 5: "Romance"

Utilizing these topics, we crafted plots illustrating 'Average Box Office Revenue by Age Group and Dominant Topic' and 'Average Popularity by Age Group and Dominant Topic'.

![borevstopic](/img/boprevstopic.png)

![poprevstopic](/img/poprevstopic.png)

Our analysis of these plots revealed that comedy, overall, enjoys the highest popularity and revenue across various age groups. This is in line with general expectations, given that comedy films often cater to a broad audience and are typically family-friendly. On the other hand, horror films have shown to be particularly profitable, even among actors in older age groups. This could be a reflection of the limited number of actors who are inclined to take on roles in horror movies. Overall, our findings do not suggest a significant shift in genre preference among actors based on the popularity or financial success of different genres across age groups. This indicates that other factors, perhaps related to the appropriateness of roles or specific actor profiling, might play a more pivotal role in guiding genre choices throughout an actor's career.

![merrychristmas](/img/merrychristmas.png)