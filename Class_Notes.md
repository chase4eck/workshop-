# [Return to Home](https://chase4eck.github.io/workshop-/)

# Class Notes

## What is human development?
- It is development OF the people, FOR the people, and BY the people.
  - First said by Lincoln at Gettysburg.
- The focus of human development must change from income to bettering living conditions.
- Highlights the concept of choice.
- Crown jewel of human development: the HDI.
  - It is essentially a measure of human development
  -  Cannot completely measure human development though; this is not really possible
- 2 types of measures of human development: breadth measure and focus measure.
  - Focus measure is more of the descriptive factor.

## HDR 2015 Discussion
- Discussing volunteer work, family work, and jobs/employment together.
  - Also includes artistic work: contributes to social cohesion.


## Debunking Myths About the Third World
- "Who are 'we' and 'them'?"
  - 'Them' being the 3rd world countries.
- As fertility rate (or family size) increases, lifespan decreases.
  - The study done w/ the smartest students from Sweden; occurred because of preconceived notions.
- On the topic of world distribution of income, Rosling showed how the "hump" (when looking at the Asian population) travelled from entirely in poverty to mostly middle class.
  - The data also predicts that in the future, the vast majority of the population will end up in the middle.
- Child survivability is directly proportional to income.
  - Rosling then splits Africa up into its countries; they reveal how there are some countries in Africa that seek aid, while others are a vacation destination.
- A country can develop much faster if it is healthy first than if it is wealthy first.
- Rosling also splits up countries into their classes; this shows a large distribution of both low and high income/ child survivability.
- "The improvement of the world must be highly contextualized." - 14:44
  - Need more detail on a regional level.
- Gapminder: used to connect big data/ databases to visual representations for public access.


## High Resolution Global Gridded Data for Use in Population Studies
- Using non-spatial population data to transfer census data into grid-cell data
  - GRUMP uses this data along w/ satellite info to build its dataset
- There are four ‘base’ standardised 100 m tiled datasets and 30 arc-second global mosaic derivations
  - 30 arc-second global mosaic derivations = 1km datasets
- Some useful info:
  - Base dataset creation involves processing raster topography data with vector country boundary data using a Geographical Information System (GIS) and other geospatial software. Raster images consist of a grid of pixels of particular size (spatial resolution), each pixel having a discrete (x,y) location and value. Raster images are commonly used in GIS applications, where they can represent digital elevation or terrain models of the Earth’s surface (i.e., topography). Vector datasets represent data slightly differently, utilising points (or nodes), and (in turn) lines and polygons, to represent (x,y) positions in space. Vector data can be assigned attribute information where required, and are well suited to representing boundary data.
- Four 100 m resolution datasets form the basis of the archive:
  1. Topography
  2. Standardised
  3. Gridded
  4. Clipped to country coastal boundaries
  - These create a resolution of 1 km and tiles of 100 m
#### There's a lot of math and computing involved in transferring this data into grid cells that I do not understand
- Each grid can be separated into a stack of layers to better understand how the data is making up that tile
- Some examples of layers:
  - Precipitation, land-slope, nightlights, population count, population density, water, land cover
- These layers come from a multitude of data-sites
  - For example, OSM (open street map) provides the majority of info about streets, waterways, railroads, and airports



## Development as Freedom (Amartya Sen)
- Development: the process of expanding peoples' freedoms
  - Similarly, development requires the removal sources of 'unfreedom'
    - Such as tyranny, poverty, intolerance, repression, etc.
- 2 reasons freedom is central to the process of development
  - The evaluative reason: progress should be considered the enhancement of freedoms
  - The effectiveness reason: achievement of development is thoroughly based on the free agency of the people
- The freedom to interchange words, gifts, and goods leads to a free market
  - This freedom "has a basic role in social living" (Sen 7).
  - Anectdote about Kader Mia emphasizes how his economic unfreedom lead to his death.
    - Went looking for work in a hostile area; knifed in the back
  - "Economic unfreedom can breed social unfreedom" (Sen 8).
- 5 types of freedoms:
1. Political freedoms
2. Economic facilities
3. Social opportunities
4. Transparency guarentees
5. Protective security
  - Each of these serve to increase the general capabilities of the people
  - These freedoms must be considered together, as a group
- "Wealth is evidently not the good we are seeking; for it is merely useful and for the sake of something else." (Aristotle)
  - Economic growth can not be treated as an end; development is more about expanding our freedoms
- There is a very evident connection between authoritarian rule and famine
  - Example with North Korean & Sudan being "famine-leauge"
- When talking about freedom, we must consider both the processes that allow freedom and the opportunities that people have.
- Sen highlights the importance of having the freedom to do things that one values in order to have valuable outcomes.
  - Freedom allows people to have a greater impact on society & even the world
- Sen uses the term agent as someone who brings about change and who has their own set of values and objectives that they strive to achieve
- Sen considers how unemployment is not just the loss of income; it's also social exclusion, loss of self-reliance & self-confidence, and psychological/ physical health
  - Inhibiting agency
- There is a large variation between the survival rates of white males in the US and black males in the US.
  - Black males in the US suffer from 'relative' deprivation, compared to the white males
- Economic deprivations occur when the people lose what the market has to offer, such as lucrative opportunities
- Individual freedoms are a social product; they are a relation between social arrangements to expand individual freedoms and 
  - On top of these ideas, Sen highlights the importance of participation
- This also plays into the idea of participation in tradition, which leads to the discussion of mandatory participation vs. freedom
- There are 2 general attitudes concerning development
  1. Development as a 'fierce' process - w/ blood, sweat, and tears
  2. Development as a 'friendly' process - w/ focus on beneficial exchanges (social safety nets, political liberties, etc.)
- Primary end of development: expansion of freedoms
  - This is also the principle mean of development
  - Constitutive role: freedom enriching one's life; avoiding basic deprivations (ex. starvation); also primary end
  - Instrumental role: principal means
- Instrumental freedoms play an instrumental role in advancing the economy
1. Political freedoms: giving the people power in politics
2. Economic facilities: opportunities of the people to use economic resources
3. Social opportunities: arrangements that society makes for education, health care, etc.
4. Transparency guarentees: the openness of the people; a general trust throughout the society
5. Protective security: social safety net (ex. collecting unemployment)
- Each of these instrumental freedoms complement each other and lead to development (as the increase of freedoms)
  - Many also lead to economic growth indirectly
- Sen explains how economic growth does NOT equal development; he backs this up with data that shows no correlation between life expectancy and GNP per capita
- China v. India
  - China is ahead of India in terms of using the market economy
    - Began focusing on literacy and other social reforms
    - Though they did experience famine, unlike India, since India was a democracy
- Two world wars lead to a more nurturing economy in Britain; led to mortality reduction



## Spatially Disaggregated Population Estimates
- Accurate population data at the local level is essential for government & nongovernmental organizations
  - Ironically, those places that could benefit the most from this info are the regions that lack the ability to collect this data
- One recent solution is the use of high-spatial resolution estimates of population data (i.e. using satellites)
- Top-down census disaggregation -> grid cells
  - These grid cells are only as accurate as the census data they're based off of
    - This data is not accurate in regions of vast migration
    - It also takes stability and a large amount of resources for a census
- There are many examples of countries that have not had a census since the 70's due to political instability or civil unrest
  - For example, both Madagascar and the Democratic Republic of Congo continues to postpone a much needed census
- Some countries are implementing "microcensus surveys" which are then linked with spatial data to provide a much cheaper alternative to a full-country census
  - This is considered bottom-up style
  - To improve the accuracy of this data, other sources of info are being incorporated, such as satellite imaging, weather patterns, age of community, distance to roads, etc.
  - Makes use of georeferencing of the areas where population data has been aquired
- Though this data is rarely validated, many people make use of R^2 values in order to indicate the precision & accuracy of the data collected
- Bottom-up population estimation is the future of population data: it provides a cheaper alternative to a full-on census
  - For countries in Africa, it was estimated that a census costs about $1-$2 per person
  - Nigeria & Afghanistan used the bottom-up approach and estimated the cost to be about $0.03-$0.15 per person



## Mapping road network communities for guiding disease surveillance and control strategies
- Global transportation has reached a dangerous point of a development that allows for the spread of disease with ease.
  - It has also helped lead to more global drug resistance
- Consider how the following factors can affect the spread of disease:
  - Population density, amount of road connections, public transportation
- African Road Network (ARN) is the more complete source of data for Africa, rather than one of the open sources (such as OSM)
- Hubs have plenty of nodes connected to them



## The End of Theory: The Data Deluge Makes the Scientific Method Obsolete
- The "petabyte age": the futuristic time period where big data will be measured in petabytes (1 petabyte = 1024 terabytes)
  - This massive level of info will be stored in the cloud
- "For instance, Google conquered the advertising world with nothing more than applied mathematics. It didn't pretend to know anything about the culture and conventions of advertising — it just assumed that better data, with better analytical tools, would win the day. And Google was right" (Chris Anderson).
- Currently, scientists use the scientific method (hypotheses, experiment) as well as considering how correlation is NOT causation
  - However, some hypotheses are unable to be put to the test without a ridiculous amount of computing power
    - Though this may soon change with the development of quantum computing
- This same shift is occuring in the world of biology: new hypothese are made that are unable to be tested due to cost
- Now, with the use of petabytes of data, we can say "Correlation is enough".
- J. Craig Venter has been making use of supercomputers and big data to discover tons of new life-forms by sequencing the genes found in the air around the ocean.
  - The evidence of these new life forms is simply a "statistical blip", however this is enough
- In conclusion, by using the same science that Google uses, we can make more discoveries


## Big Data, New Epistemologies and Paradigm Shifts
- One classic problem w/ big data is that these large quantities of data sometimes cannot be fit into one spreadsheet, or even into one computer
  - Think about this: 1 petabyte of data is 1024 terabytes is 1 x10^6 gigabytes. Most computers have between 500 gb to one tb of storage.
- There are other problems with big data nowadays: it's high in velocity, diverse in variety, and it's exhaustive by covering entire populations
- Big data is also *continuously* being collected (e.g. website clicks, retail sales, transactions, phone records)
  - Walmart collected 2.5 petabytes of data every *hour* in 2012; this number is likely even larger today
- "The challenge of analysing Big Data is coping with abundance, exhaustivity and variety, timeliness and dynamism, messiness and uncertainty, high relationality, and the fact that much of what is generated has no specific question in mind or is a by-product of another activity," (Rob Kitchin).
  - Machine learning is one modern-day solution, through the use of computing power to discover
- Modern day paradigm: exploratory science, data-intensive; statistical exploration and data mining
- "Correlation supersedes causation, and science can advance even without coherent models, unified theories, or really any mechanistic explanation at all," (Kitchin).
- The beauty of this new approach is that scientists no longer need to devise a hypothesis before collecting data; the data itself tends to reveal new information (that often the scientists did not even know they were looking for)
- Example: Amazon uses its large computing power to discover patterns in online shopping; this is why their "other recommendations" are typically pretty spot-on
  - Another strength that comes from this approach is that the computer may recognize a pattern that a human observer could not
- Abductive logic: starts w/ an observation, tries to find a way to explain it
- Empiricial logic: conducting an investigation that relies upon experimentation and systematic observation rather than theoretical speculation
- Data-driven science will lead to the integration of many sources of data to create a real-time picture of the situation
  - A scientist may look at a plethora of sources at once and discover a connection between all
- One problem w/ this new method is that pieces of literature cannot accurately convey the messages from literature as raw data
  - Big data has trouble encapsulating and measuring the value of all forms of art
  - In the same way, it's nearly impossible to define a society through data/ numbers
    - Sometimes a quantitative approach is simply not appropriate
  - Humans are too complex to be reduced to a set of numbers, no matter the size of the data
- Post-positivism: theories, background, knowledge and values of the researcher can influence what is observed



## A spatial database of health facilities managed by the public health sector in sub Saharan Africa
- The location of health facilities is crucial to developing a solid health system
  - These life-saving facilities must be accesible to all corners of society
- Sub Saharan Africa lacks the data that is typically used to make these facilities the most accessible
  - This relates to the optimization of health care
  - This data would also make the management of epidemics much easier
- To fix this problem, this group of data scientists gathered some data to be applied to this problem
  - They collected public data, cleaned said data, geocoded it, and validated said data with other technology
  - Some data was unable to be reached through technology, and so they had to rely on in-country contacts and personal communication
  - Some countries had *no* data whatsoever
- Due to the difficulty of data collection about the private sector of health care, they were forced to rely on their data collected about the public health care sector
  - "In total, 98,745 public health facilities were assembled for 50 countries in sub Saharan Africa."
- The process of "data cleaning" involved the removal of duplicates, addition of missing entries, and just overall revisions/edits that were necessary to complete the full picture



## An African Elections: Ghana's Democracy in Action
- NDC (National Democratic Congress)(progressive) vs. NPP (New Patriotic Party)(conservative)
- Jobs are often offered by political affiliation
  - One Ghanian recounts having to show his "party card" in order to get his job
- Multi-party democracy was reinstated in 1992; this is the 5th election
- This election focused on security, employment, and the accessibility of education
- Nana Addo -> NPP; Atta Mills -> NDC
- NDC is affiliated with the past 
- Ghana was the first country to become an independent country in Africa
- 3 previous republics, 5 previous military regimes
- NPP ran on the basis of providing free education
- "Are we going forward, or are we coming back?" - Nana Addo
- A gold miner in Ghana makes significantly less than a gold miner in the USA
- The people do not believe that the candidates will maintain their promises
- Rawlings: a previous President of Ghana, NDC. He carries a certain military conscience that follows in suite of how he came about as president-- through the barrel of a gun
  - He was initially a junior officer, revolted against the senior officer -> coup
  - However, Rawlings did set the foundation for democracy in Ghana
  - His VP was Atta Mills, who ran for president once Rawlings' term came to an end
- Runs in '92,
- In 2000, the NDC John Atta Mills lost to the NPP John Kufuor -> 1st time power shifted due to an election
  - NDC fears that if they lose this (2008) election, their party may come to an end
  - 2004 NPP wins again
- Ghanians have to wait hours in line to vote -> this discourages them from voting and needs to change
- Each vote is counted in public at the polling station, where the citizens can witness
  - Then, each of these numbers are aggregated into the total votes
- During the election, the government needs about 11,000 officials for the 21,000 polling stations
  - It is impossible to vouch for 11,000 people's neutrality, though they are recruited carefully
    - Instead, Ghana attempts to build integrity into the system
- "Figures don't lie."
- Both parties claim on TV that they have won the election before the results have been revealed/ counted
  - This infuriates and confuses the public, and they begin to lose trust in the election
- Since neither candidate received more than 50%, there is another election that takes place -> "runoff election"
  - Candidate must receive 50 percent plus one majority vote
  - Results of first election: Nana Addo (NPP): 49.13%; Atta Mills (NDC): 47.92%
- Both parties begin campaigning again for the next election
- Danger in Ghana: no impeachment, the president is essentially immune until the next election, which they can also control (to some extent)
- Rawlings has a fear that the NPP will resort to violence or fraud to win the runoff election
  - He even uses a call-to-action with the public, to "protect your ballot boxes" as if they were your family
- Nana Addo also addresses his followers, saying that the NDC will use violence to win the election
- "Macho men" use their appearance to scare the public away and control the voting booths
- In the past, citizens have used motorbikes to steal ballot boxes
  - Some NPP followers were stationed near the ballot boxes, causing much anxiety on top of the macho men
  - Some boxes were claimed to be stolen and could not be found, leading to chaos
    - This may not be true, and may be a political tool
- NDC Atta Mills "won" the election
  - There seems to be some interference with the results however
  - There is much tension in the strong room
  - Results were declared, then new results came in putting Nana Addo ahead
- NDC is furious and ready to revolt
- The election committee must do the right thing, otherwise there will be a coup
- The government is afraid of the people taking to the streets, leading to a state of emergency
- The Tain region could not participate in the runoff election due to "irregularities in voting"
  - However, the election was close enough that these votes may have mattered
  - Therefore, the election will take place in Tain; as of that moment, Atta Mills is in the lead
- NDC Atta Mills once again is the winner of the election
- Ghanians were able to come to a decision rather than leading to a civil war
  - This sets a good democratic role model for the rest of Africa





## Examining the correlates and drivers of human population distributions across low- and middle-income countries
- Humans can make a new environment both more or less suitable to live in.
  - Creating more roads, developing jobs; polluting the surrounding area, desertification.
- Africa & Asia currently experiencing a large push for urbanization: huge amounts of internal migration taking place.
  - Demographic shifts like this will change population densities greatly.
- Studying the different factors that may influence population density to understand it better.
  - (i) What datasets, representing drivers and associated landscapes of population distribution, are the most informative for accurately mapping populations at global scales?
  - (ii) What are the differences, in terms of relative importance of these datasets, between countries, between regions of countries and within regions of countries?
- Random Forest models - machine learning technique combines weaker learners into strong learners; don't require much specification.
- Also used census data to create a baseline for population numbers.
- Predictive covariates: intensity of night time lights, energy productivity of plants, topographic elevation adn slope, climatic factors, land cover, roads, water features, human settlements, urban areas, protected areas, points of interest, and facilities.
  - Used these factors to find a weighted importance rank (WIR)= within country ranked importance/total # country covariates
    - 0 is highest importance, 1 is lowest
- "The five most important covariate classes, in descending order of median importance, were urban/suburban extents (0.32), built environment and urban/suburban proxies (0.35), climatic/environmental variables (0.37), populated place covariates (0.42) and transportation networks (0.50)."
- The majority of population growth is expected in these low and middle-income countries.
- Estimated that 54% of the population lives in urbanized regions
- Another important covariate is climate as well as elevation: population density tends to be higher at resource-rich, low elevation locations, where society can thrive.
  - Also, it is seen that typically regions with a steep slope are not inhabited as much as other regions, likely due to the difficulty of building facilities on said slope.
- One major problem with this reliance on covariate data is the unreliability of a census; the quality of a census drastically changes from country to country.



## City of God
- Synopsis: Based on the novel by Paolo Lin about gangland violence in the slums of Rio in the 1960s and '70s. Shifting alliances result in a brutal gang war, which is documented on film by an amateur photographer.
- "In the City of God, if you run, they get you, and if you stay, they get you too."
- Rocket is the main character, brother is Goose.
- "The Tender Trio" : Shaggy, Clipper, and Goose. (and Li'l Dice, Benny).
  - Attempting to sell gas @ high prices, cops show up, hide back in soccer game.
- Homeless were sent to the city of god
- Tender Trio robs motel-> Li'l Dice's idea, he's put on watch for the cops, doesn't show up when it's time to leave
  - They crash the car into a bar, leave on foot; one stays behind to distract cops
    - Shorty gives up their location: in the woods.
  - Cops come to close to them in woods, run back to town when they hear shots fired
  - Shaggy hides in a friend's place
- Clipper doesn't want to die a gangster so he comes back to town, heads to the church
- The motel heist was a bloody one; each hoodlum went down their own path.
  - Goose was in his (and Rocket's) father's hands, Clipper went back to God, Shaggy stayed with Bernice.
- After the heist, constant police raids; people were constantly taken to jail, though no one gave up the tender trio.
  - Apparently there were deaths at the motel.
- Bernice decides to leave, offers Shaggy to come with.
- Goose started hanging with Shorty's wife
  - They sleep together, shorty catches them; Goose dips and the cops take Rocket.
  - Cops raid Rocket's house, Goose leaves home.
  - Shorty kills buries his wife alive.
- Cops see Shaggy as he tries to escape in stolen car, doesn't make it into the car; Bernice dips.
  - Shaggy gets shot and killed (rip).
- Li'l Dice -> Li'l Ze, a notorious, respected hoodlum who had a thirst to kill




















