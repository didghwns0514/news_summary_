# news_summary_
DBSCAN / cosine_similarity / wv vector to effiectively summarize news article in English  

# Results here
## Define a class using gensim



![output_2_1](https://user-images.githubusercontent.com/47662495/102862137-ffe41e80-4473-11eb-844d-dcda0e543fce.png)


    targEps : 0.006192422902081371
    length of whole paragraph : 20
    num_samp : 2
    elapsed for DBSCAN : 0:00:00.369022
    len of cluster : 6
    


![output_2_3](https://user-images.githubusercontent.com/47662495/102862140-007cb500-4474-11eb-8980-7ef55ae8d9d5.png)


    original : 
    
    Ad sales boost Time Warner profit
    
    Quarterly profits at US media giant TimeWarner jumped 76% to $1.13bn (Â£600m) for the three months to December, from $639m year-earlier.
    The firm, which is now one of the biggest investors in Google, benefited from sales of high-speed internet connections and higher advert sales.
    TimeWarner said fourth quarter sales rose 2% to $11.1bn from $10.9bn.
    Its profits were buoyed by one-off gains which offset a profit dip at Warner Bros, and less users for AOL.
    Time Warner said on Friday that it now owns 8% of search-engine Google.
    But its own internet business, AOL, had has mixed fortunes.
    It lost 464,000 subscribers in the fourth quarter profits were lower than in the preceding three quarters.
    However, the company said AOL's underlying profit before exceptional items rose 8% on the back of stronger internet advertising revenues.
    It hopes to increase subscribers by offering the online service free to TimeWarner internet customers and will try to sign up AOL's existing customers for high-speed broadband.
    TimeWarner also has to restate 2000 and 2003 results following a probe by the US Securities Exchange Commission (SEC), which is close to concluding.
    Time Warner's fourth quarter profits were slightly better than analysts' expectations.
    But its film division saw profits slump 27% to $284m, helped by box-office flops Alexander and Catwoman, a sharp contrast to year-earlier, when the third and final film in the Lord of the Rings trilogy boosted results.
    For the full-year, TimeWarner posted a profit of $3.36bn, up 27% from its 2003 performance, while revenues grew 6.4% to $42.09bn.
    "Our financial performance was strong, meeting or exceeding all of our full-year objectives and greatly enhancing our flexibility," chairman and chief executive Richard Parsons said.
    For 2005, TimeWarner is projecting operating earnings growth of around 5%, and also expects higher revenue and wider profit margins.
    TimeWarner is to restate its accounts as part of efforts to resolve an inquiry into AOL by US market regulators.
    It has already offered to pay $300m to settle charges, in a deal that is under review by the SEC.
    The company said it was unable to estimate the amount it needed to set aside for legal reserves, which it previously set at $500m.
    It intends to adjust the way it accounts for a deal with German music publisher Bertelsmann's purchase of a stake in AOL Europe, which it had reported as advertising revenue.
    It will now book the sale of its stake in AOL Europe as a loss on the value of that stake.
    
    reduced : 
    
    TimeWarner said fourth quarter sales rose 2% to $11.1bn from $10.9bn.
    Its profits were buoyed by one-off gains which offset a profit dip at Warner Bros, and less users for AOL.
    But its own internet business, AOL, had has mixed fortunes.
    Time Warner's fourth quarter profits were slightly better than analysts' expectations.
    For 2005, TimeWarner is projecting operating earnings growth of around 5%, and also expects higher revenue and wider profit margins.
    TimeWarner is to restate its accounts as part of efforts to resolve an inquiry into AOL by US market regulators.
    
    wc_list_cut - keyword : [('profit', 1.0), ('TimeWarner', 0.7777777777777778), ('AOL', 0.7777777777777778), ('sale', 0.5555555555555556), ('Warner', 0.4444444444444444)]
    iter next line..? x or X to exity
    


![output_2_5](https://user-images.githubusercontent.com/47662495/102862143-01154b80-4474-11eb-9973-14ee9bb32006.png)


    targEps : 0.004506656727537708
    length of whole paragraph : 15
    num_samp : 2
    elapsed for DBSCAN : 0:00:00.301230
    len of cluster : 5
    


![output_2_7](https://user-images.githubusercontent.com/47662495/102862146-01ade200-4474-11eb-9507-03e8524feefd.png)


    original : 
    
    Dollar gains on Greenspan speech
    
    The dollar has hit its highest level against the euro in almost three months after the Federal Reserve head said the US trade deficit is set to stabilise.
    And Alan Greenspan highlighted the US government's willingness to curb spending and rising household savings as factors which may help to reduce it.
    In late trading in New York, the dollar reached $1.2871 against the euro, from $1.2974 on Thursday.
    Market concerns about the deficit has hit the greenback in recent months.
    On Friday, Federal Reserve chairman Mr Greenspan's speech in London ahead of the meeting of G7 finance ministers sent the dollar higher after it had earlier tumbled on the back of worse-than-expected US jobs data.
    "I think the chairman's taking a much more sanguine view on the current account deficit than he's taken for some time," said Robert Sinche, head of currency strategy at Bank of America in New York.
    "He's taking a longer-term view, laying out a set of conditions under which the current account deficit can improve this year and next."
    Worries about the deficit concerns about China do, however, remain.
    China's currency remains pegged to the dollar and the US currency's sharp falls in recent months have therefore made Chinese export prices highly competitive.
    But calls for a shift in Beijing's policy have fallen on deaf ears, despite recent comments in a major Chinese newspaper that the "time is ripe" for a loosening of the peg.
    The G7 meeting is thought unlikely to produce any meaningful movement in Chinese policy.
    In the meantime, the US Federal Reserve's decision on 2 February to boost interest rates by a quarter of a point - the sixth such move in as many months - has opened up a differential with European rates.
    The half-point window, some believe, could be enough to keep US assets looking more attractive, and could help prop up the dollar.
    The recent falls have partly been the result of big budget deficits, as well as the US's yawning current account gap, both of which need to be funded by the buying of US bonds and assets by foreign firms and governments.
    The White House will announce its budget on Monday, and many commentators believe the deficit will remain at close to half a trillion dollars.
    
    reduced : 
    
    Dollar gains on Greenspan speech
    
    The dollar has hit its highest level against the euro in almost three months after the Federal Reserve head said the US trade deficit is set to stabilise.
    In late trading in New York, the dollar reached $1.2871 against the euro, from $1.2974 on Thursday.
    "He's taking a longer-term view, laying out a set of conditions under which the current account deficit can improve this year and next."
    But calls for a shift in Beijing's policy have fallen on deaf ears, despite recent comments in a major Chinese newspaper that the "time is ripe" for a loosening of the peg.
    The half-point window, some believe, could be enough to keep US assets looking more attractive, and could help prop up the dollar.
    
    wc_list_cut - keyword : [('US', 1.0), ('dollar', 0.875), ('deficit', 0.875), ('months', 0.5), ('Greenspan', 0.375)]
    iter next line..? x or X to exitx
    done...!
    


```python
print(f'starting !!  -> {datetime.datetime.now()}')
start_time = datetime.datetime.now()
model = Lang_ml()
print(f'elapsed time of loading model : {datetime.datetime.now() - start_time}')
```

    starting !!  -> 2020-12-22 15:17:29.938843
    self.wv_model successful loading!
    elapsed time of loading model : 0:01:10.863614
    

## Article 1
- Max Kozlov Dec 16, 2020
- https://www.the-scientist.com/news-opinion/new-sars-cov-2-variant-spreading-rapidly-in-uk-68292


```python
tmp_input = input('article content? : ')
model.paragraph_sentence(tmp_input)

```

    article content? : As public health officials worldwide mount vaccination campaigns against COVID-19, a new SARS-CoV-2 variant has rapidly taken hold in the UK, leading scientists to investigate if it carries any implications for the transmissibility of the virus, severity of infection, and success of a vaccine, though experts say it is unlikely to hamper vaccination efforts.   As of December 13, 1,108 COVID-19 cases with the new variant had been identified, predominantly in the south and east of England, says Public Health England in a statement on Monday (December 14). “High numbers of cases of the variant virus have been observed in some areas where there is also a high incidence of COVID-19,” the statement notes. “It is not yet known whether the variant is responsible for these increased numbers of cases.”  “We are still dealing with very thin evidence at the moment about this variant,” Sharon Peacock, the director of the UK COVID-19 Genomics Consortium (COG-UK), which randomly sequences positive COVID-19 samples around from the UK and discovered this variant, tells The Independent.   The group first identified the new variant in late September and began following its spread, but what surprised some experts was its sudden prevalence.  “This lineage came up quite rapidly,” Nick Loman, a professor of microbial genomics at the University of Birmingham and a contributor to COG-UK, tells The Washington Post, noting that there were a “striking” number of mutations in the new variant, compared to the one or two he’s seen in other strains. Still, he notes that there is no proof yet that this variant is spreading faster or causing more severe illness.  Scientists detected 17 mutations in the variant, which scientists have named “VUI – 202012/01,” most in the segment of the virus’s genome that codes for the spike protein that surrounds the virus and allows it to bind to cellular receptors and infiltrate cells.   Jeremy Farrar, the director of the Wellcome Trust biomedical research foundation, released a statement on Monday, calling the development “potentially serious,” though he cautioned that the implications for transmission of the virus and the efficacy of vaccines were still unclear.  “The pressure on the virus to evolve is increased by the fact that so many millions of people have now been infected,” he says. “Most of the mutations will not be significant or cause for concern, but some may give the virus an evolutionary advantage, which may lead to higher transmission or mean it is more harmful.”  COG-UK scientists stress that mutations are very common and that lineages arise and disappear quickly, according to a statement the group released on Monday.   There are few examples of the variant in other countries and it “does sort of seem to have come out of nowhere,” Loman tells The Independent.  This variant is not the first that scientists have detected in the novel coronavirus—the 614G variant that contains a spike protein mutation overtook the 614D variant in the spring. The mutation does not appear to cause more severe cases of COVID-19, but multiple studies indicate that it could be more contagious.  In the fall, another variant that scientists feared could be less sensitive to antibodies took hold in mink farms, leading several countries to call for the culling of millions of minks to prevent the variant from spreading to humans.  Even as the virus mutates, experts are quick to point out that it’s unlikely that it would mutate in such a way that would render a vaccine ineffective. “It seems hard to see that this virus is going to be able to evolve its way away from vaccine efficacy,” Egon Ozer, an infectious diseases expert at the Feinberg School of Medicine at Northwestern University, tells the Post.
    


![output_5_1](https://user-images.githubusercontent.com/47662495/102862148-01ade200-4474-11eb-9610-86aa1ac48769.png)


    targEps : 0.007088613653065706
    length of whole paragraph : 17
    num_samp : 2
    elapsed for DBSCAN : 0:00:00.314163
    len of cluster : 6
    


![output_5_3](https://user-images.githubusercontent.com/47662495/102862149-02467880-4474-11eb-918d-ecfababbd9a2.png)


    original : 
    
    As public health officials worldwide mount vaccination campaigns against COVID-19, a new SARS-CoV-2 variant has rapidly taken hold in the UK, leading scientists to investigate if it carries any implications for the transmissibility of the virus, severity of infection, and success of a vaccine, though experts say it is unlikely to hamper vaccination efforts.
    As of December 13, 1,108 COVID-19 cases with the new variant had been identified, predominantly in the south and east of England, says Public Health England in a statement on Monday (December 14).
    “High numbers of cases of the variant virus have been observed in some areas where there is also a high incidence of COVID-19,” the statement notes.
    “It is not yet known whether the variant is responsible for these increased numbers of cases.”  “We are still dealing with very thin evidence at the moment about this variant,” Sharon Peacock, the director of the UK COVID-19 Genomics Consortium (COG-UK), which randomly sequences positive COVID-19 samples around from the UK and discovered this variant, tells The Independent.
    The group first identified the new variant in late September and began following its spread, but what surprised some experts was its sudden prevalence.
    “This lineage came up quite rapidly,” Nick Loman, a professor of microbial genomics at the University of Birmingham and a contributor to COG-UK, tells The Washington Post, noting that there were a “striking” number of mutations in the new variant, compared to the one or two he’s seen in other strains.
    Still, he notes that there is no proof yet that this variant is spreading faster or causing more severe illness.
    Scientists detected 17 mutations in the variant, which scientists have named “VUI – 202012/01,” most in the segment of the virus’s genome that codes for the spike protein that surrounds the virus and allows it to bind to cellular receptors and infiltrate cells.
    Jeremy Farrar, the director of the Wellcome Trust biomedical research foundation, released a statement on Monday, calling the development “potentially serious,” though he cautioned that the implications for transmission of the virus and the efficacy of vaccines were still unclear.
    “The pressure on the virus to evolve is increased by the fact that so many millions of people have now been infected,” he says.
    “Most of the mutations will not be significant or cause for concern, but some may give the virus an evolutionary advantage, which may lead to higher transmission or mean it is more harmful.”  COG-UK scientists stress that mutations are very common and that lineages arise and disappear quickly, according to a statement the group released on Monday.
    There are few examples of the variant in other countries and it “does sort of seem to have come out of nowhere,” Loman tells The Independent.
    This variant is not the first that scientists have detected in the novel coronavirus—the 614G variant that contains a spike protein mutation overtook the 614D variant in the spring.
    The mutation does not appear to cause more severe cases of COVID-19, but multiple studies indicate that it could be more contagious.
    In the fall, another variant that scientists feared could be less sensitive to antibodies took hold in mink farms, leading several countries to call for the culling of millions of minks to prevent the variant from spreading to humans.
    Even as the virus mutates, experts are quick to point out that it’s unlikely that it would mutate in such a way that would render a vaccine ineffective.
    “It seems hard to see that this virus is going to be able to evolve its way away from vaccine efficacy,” Egon Ozer, an infectious diseases expert at the Feinberg School of Medicine at Northwestern University, tells the Post.
    
    reduced : 
    
    As of December 13, 1,108 COVID-19 cases with the new variant had been identified, predominantly in the south and east of England, says Public Health England in a statement on Monday (December 14).
    Still, he notes that there is no proof yet that this variant is spreading faster or causing more severe illness.
    Jeremy Farrar, the director of the Wellcome Trust biomedical research foundation, released a statement on Monday, calling the development “potentially serious,” though he cautioned that the implications for transmission of the virus and the efficacy of vaccines were still unclear.
    “The pressure on the virus to evolve is increased by the fact that so many millions of people have now been infected,” he says.
    There are few examples of the variant in other countries and it “does sort of seem to have come out of nowhere,” Loman tells The Independent.
    Even as the virus mutates, experts are quick to point out that it’s unlikely that it would mutate in such a way that would render a vaccine ineffective.
    
    wc_list_cut - keyword : [('variant', 1.0), ('virus', 0.5625), ('scientists', 0.375), ('mutation', 0.375), ('UK', 0.3125)]
    

## Article 2
- Martin Brueckner April 17, 2018 1.48pm AEST
- https://theconversation.com/not-so-fast-why-the-electric-vehicle-revolution-will-bring-problems-of-its-own-94980


```python
tmp_input = input('article content? : ')
model.paragraph_sentence(tmp_input)
```

    article content? : After years of being derided as a joke by car manufacturers and the public, interest in electric vehicles has increased sharply as governments around the world move to ban petrol and diesel cars.  We have seen a tremendous rise in availability, especially at the premium end of the market, where Tesla is giving established brands a run for their money. Electric cars are likely to penetrate the rest of the market quickly too. Prices should be on par with conventional cars by 2025.  Electric cars are praised as the answer to questions of green and clean mobility. But the overall sustainability of electric vehicles is far from clear. On closer examination, our entire transport paradigm may need to be rethought.  Compared with combustion engines, electric transport has obvious advantages for emissions and human health. Transport is responsible for around 23% of energy-related carbon dioxide emissions globally. This is expected to double by 2050.  Motor vehicles also put a burden on society, especially in urban environments where they are chiefly responsible for noise and air pollution. Avoiding these issues is why electric vehicles are considered a key technology in cleaning up the transport sector. However, electric cars come with problems of their own.  Dirt in the supply chain For one, electric vehicles have a concerning supply chain. Cobalt, a key component of the lithium-ion batteries in electric cars, is linked to reports of child labour. The nickel used in those same batteries is toxic to extract from the ground. And there are environmental concerns and land use conflicts connected with lithium mining in countries like Tibet and Bolivia.  The elements used in battery production are finite and in limited supply. This makes it impossible to electrify all of the world’s transport with current battery technology. Meanwhile, there is still no environmentally safe way of recycling lithium-ion batteries.  While electric cars produce no exhaust, there is concern about fine particle emissions. Electric cars are often heavier than conventional cars, and heavier vehicles are often accompanied by higher levels of non-exhaust emissions. The large torque of electric vehicles further adds to the fine dust problem, as it causes greater tyre wear and dispersion of dust particles.  Different motor, same problem Electric vehicles share many other issues with conventional cars too. Both require roads, parking areas and other infrastructure, which is especially a problem in cities. Roads divide communities and make access to essential services difficult for those without cars.  A shift in people’s reliance on combustion cars to electric cars also does little to address sedentary urban lifestyles, as it perpetuates our lack of physical activity.  Other problems relate to congestion. In Australia, the avoidable social cost of traffic congestion in 2015 was estimated at A$16.5 billion. This is expected to increase by 2% every year until 2030. Given trends in population growth and urbanisation globally and in Australia, electric cars – despite obvious advantages over fossil fuels – are unlikely to solve urban mobility and infrastructure-related problems.  Technology or regulation may solve these technical and environmental headaches. Improvements in recycling, innovation, and the greening of battery factories can go a long way towards reducing the impacts of battery production. Certification schemes, such as the one proposed in Sweden, could help deliver low-impact battery value chains and avoid conflict minerals and human rights violations in the industry.  A new transport paradigm Yet, while climate change concerns alone seem to warrant a speedy transition towards electric mobility, it may prove to be merely a transition technology. Electric cars will do little for urban mobility and liveability in the years to come. Established car makers such as Porsche are working on new modes of transportation, especially for congested and growing markets such as China.  Nevertheless, their vision is still one of personal vehicles – relying on electric cars coupled with smart traffic guidance systems to avoid urban road congestion. Instead of having fewer cars, as called for by transport experts, car makers continue to promote individualised transport, albeit a greener version.  With a growing population, a paradigm shift in transport may be needed – one that looks to urban design to solve transportation problems.  In Copenhagen, for example, bikes now outnumber cars in the city’s centre, which is primed to be car-free within the next ten years. Many other cities, including Oslo in Norway and Chengdu in China, are also on their way to being free of cars.  Experts are already devising new ways to design cities. They combine efficient public transport, as found in Curitiba, Brazil, with principles of walkability, as seen in Vauben, Germany. They feature mixed-use, mixed-income and transit-oriented developments, as seen in places like Fruitvale Village in Oakland, California.  These developments don’t just address transport-related environmental problems. They enhance liveability by reclaiming urban space for green developments. They reduce the cost of living by cutting commuting cost and time. They deliver health benefits, thanks to reduced pollution and more active lifestyles. They improve social cohesion, by fostering human interaction in urban streetscapes, and help to reduce crime. And of course, they improve economic performance by reducing the loss of productivity caused by congestion.  Electric cars are a quick-to-deploy technology fix that helps tackle climate change and improve urban air quality – at least to a point. But the sustainability endgame is to eliminate many of our daily travel needs altogether through smart design, while improving the parts of our lives we lost sight of during our decades-long dependence on cars.
    


![output_7_1](https://user-images.githubusercontent.com/47662495/102862151-02467880-4474-11eb-9627-14a93a700687.png)


    targEps : 0.00812093883383562
    length of whole paragraph : 53
    num_samp : 2
    elapsed for DBSCAN : 0:00:01.094087
    len of cluster : 11
    


![output_7_3](https://user-images.githubusercontent.com/47662495/102862152-02df0f00-4474-11eb-8624-e747a067b7a9.png)


    original : 
    
    After years of being derided as a joke by car manufacturers and the public, interest in electric vehicles has increased sharply as governments around the world move to ban petrol and diesel cars.
    We have seen a tremendous rise in availability, especially at the premium end of the market, where Tesla is giving established brands a run for their money.
    Electric cars are likely to penetrate the rest of the market quickly too.
    Prices should be on par with conventional cars by 2025.
    Electric cars are praised as the answer to questions of green and clean mobility.
    But the overall sustainability of electric vehicles is far from clear.
    On closer examination, our entire transport paradigm may need to be rethought.
    Compared with combustion engines, electric transport has obvious advantages for emissions and human health.
    Transport is responsible for around 23% of energy-related carbon dioxide emissions globally.
    This is expected to double by 2050.
    Motor vehicles also put a burden on society, especially in urban environments where they are chiefly responsible for noise and air pollution.
    Avoiding these issues is why electric vehicles are considered a key technology in cleaning up the transport sector.
    However, electric cars come with problems of their own.
    Dirt in the supply chain For one, electric vehicles have a concerning supply chain.
    Cobalt, a key component of the lithium-ion batteries in electric cars, is linked to reports of child labour.
    The nickel used in those same batteries is toxic to extract from the ground.
    And there are environmental concerns and land use conflicts connected with lithium mining in countries like Tibet and Bolivia.
    The elements used in battery production are finite and in limited supply.
    This makes it impossible to electrify all of the world’s transport with current battery technology.
    Meanwhile, there is still no environmentally safe way of recycling lithium-ion batteries.
    While electric cars produce no exhaust, there is concern about fine particle emissions.
    Electric cars are often heavier than conventional cars, and heavier vehicles are often accompanied by higher levels of non-exhaust emissions.
    The large torque of electric vehicles further adds to the fine dust problem, as it causes greater tyre wear and dispersion of dust particles.
    Different motor, same problem Electric vehicles share many other issues with conventional cars too.
    Both require roads, parking areas and other infrastructure, which is especially a problem in cities.
    Roads divide communities and make access to essential services difficult for those without cars.
    A shift in people’s reliance on combustion cars to electric cars also does little to address sedentary urban lifestyles, as it perpetuates our lack of physical activity.
    Other problems relate to congestion.
    In Australia, the avoidable social cost of traffic congestion in 2015 was estimated at A$16.5 billion.
    This is expected to increase by 2% every year until 2030.
    Given trends in population growth and urbanisation globally and in Australia, electric cars – despite obvious advantages over fossil fuels – are unlikely to solve urban mobility and infrastructure-related problems.
    Technology or regulation may solve these technical and environmental headaches.
    Improvements in recycling, innovation, and the greening of battery factories can go a long way towards reducing the impacts of battery production.
    Certification schemes, such as the one proposed in Sweden, could help deliver low-impact battery value chains and avoid conflict minerals and human rights violations in the industry.
    A new transport paradigm Yet, while climate change concerns alone seem to warrant a speedy transition towards electric mobility, it may prove to be merely a transition technology.
    Electric cars will do little for urban mobility and liveability in the years to come.
    Established car makers such as Porsche are working on new modes of transportation, especially for congested and growing markets such as China.
    Nevertheless, their vision is still one of personal vehicles – relying on electric cars coupled with smart traffic guidance systems to avoid urban road congestion.
    Instead of having fewer cars, as called for by transport experts, car makers continue to promote individualised transport, albeit a greener version.
    With a growing population, a paradigm shift in transport may be needed – one that looks to urban design to solve transportation problems.
    In Copenhagen, for example, bikes now outnumber cars in the city’s centre, which is primed to be car-free within the next ten years.
    Many other cities, including Oslo in Norway and Chengdu in China, are also on their way to being free of cars.
    Experts are already devising new ways to design cities.
    They combine efficient public transport, as found in Curitiba, Brazil, with principles of walkability, as seen in Vauben, Germany.
    They feature mixed-use, mixed-income and transit-oriented developments, as seen in places like Fruitvale Village in Oakland, California.
    These developments don’t just address transport-related environmental problems.
    They enhance liveability by reclaiming urban space for green developments.
    They reduce the cost of living by cutting commuting cost and time.
    They deliver health benefits, thanks to reduced pollution and more active lifestyles.
    They improve social cohesion, by fostering human interaction in urban streetscapes, and help to reduce crime.
    And of course, they improve economic performance by reducing the loss of productivity caused by congestion.
    Electric cars are a quick-to-deploy technology fix that helps tackle climate change and improve urban air quality – at least to a point.
    But the sustainability endgame is to eliminate many of our daily travel needs altogether through smart design, while improving the parts of our lives we lost sight of during our decades-long dependence on cars.
    
    reduced : 
    
    Compared with combustion engines, electric transport has obvious advantages for emissions and human health.
    This is expected to double by 2050.
    Cobalt, a key component of the lithium-ion batteries in electric cars, is linked to reports of child labour.
    The nickel used in those same batteries is toxic to extract from the ground.
    A shift in people’s reliance on combustion cars to electric cars also does little to address sedentary urban lifestyles, as it perpetuates our lack of physical activity.
    In Australia, the avoidable social cost of traffic congestion in 2015 was estimated at A$16.5 billion.
    A new transport paradigm Yet, while climate change concerns alone seem to warrant a speedy transition towards electric mobility, it may prove to be merely a transition technology.
    In Copenhagen, for example, bikes now outnumber cars in the city’s centre, which is primed to be car-free within the next ten years.
    Experts are already devising new ways to design cities.
    These developments don’t just address transport-related environmental problems.
    They enhance liveability by reclaiming urban space for green developments.
    
    wc_list_cut - keyword : [('car', 1.0), ('transport', 0.4166666666666667), ('vehicles', 0.375), ('problem', 0.3333333333333333), ('Electric', 0.25)]
    

## Article 3
- Martin Brueckner December, 22, 2020
- https://www.bbc.com/news/world-us-canada-55386947


```python
tmp_input = input('article content? : ')
model.paragraph_sentence(tmp_input)
```

    article content? : The cyber-security firm that identified the large-scale hacking of US government agencies says it "genuinely impacted" around 50 organisations.  Kevin Mandia, CEO of FireEye, said that while some 18,000 organisations had the malicious code in their networks, it was the 50 who suffered major breaches.  The US Treasury and departments of homeland security, state and defence are known to have been targeted.  US Secretary of State Mike Pompeo has blamed Russia for the hack.  So too have the chairs of the Senate and House of Representatives' intelligence committees.  However, President Trump cast doubt on Russia's role in two tweets on Saturday, hinting instead at Chinese involvement.  Mr Mandia told CBS News that the cyber attack "was very consistent" with what US officials know about the work of Russia's foreign intelligence agency, the SVR.  "I think these are folks that we've responded to in the '90s, in the early 2000s. It's a continuing game in cyberspace," he said.  He said the attack on the Texas-based SolarWinds Orion, the computer network tool at the source of the breach, had the "earliest evidences of being designed".  It started with a "dry run" in October 2019 when "innocuous code" was changed. "Then sometime in March, the operators behind this attack did put malicious code into the supply chain," he said, "injected it in there and that is the backdoor that impacted everybody".  Despite Russia's denials of the "baseless" claims, many in the US intelligence community suspect the Russian government is responsible.  Mr Pompeo said on Friday: "We can say pretty clearly that it was the Russians that engaged in this activity."  He said that Russia was trying to "undermine our way of life", and that Russian President Vladimir Putin "remains a real risk".  Mr Pompeo has taken a strong line against Russia before. In his time as secretary of state, the US has pulled out of a key nuclear treaty and the Open Skies Treaty on aerial surveillance flights.  The Republican Chair of the Senate intelligence committee, Marco Rubio, tweeted that it is "increasingly clear that Russian intelligence conducted the gravest cyber intrusion in our history". He said the response "must be proportional but significant".  Adam Schiff, Democrat chair of the House intelligence committee, echoed these views, saying on Sunday: "I don't think there's any question that it was Russia".  And he took a swipe at President Trump for his comments on the issue saying they were "just uniformly destructive and deceitful, and injurious ... to our national security."  The president has long been ambivalent towards Moscow, downplaying such incidents as allegations that Russia offered the Taliban bounties to kill US troops.  In his tweets on Saturday, Mr Trump again turned on what he labels the "fake news media" for exaggerating the matter.  He wrote: "The Cyber Hack is far greater in the Fake News Media than in actuality.  "I have been fully briefed and everything is well under control. Russia, Russia, Russia is the priority chant when anything happens because Lamestream is, for mostly financial reasons, petrified of discussing the possibility that it may be China (it may!)."  President-elect Joe Biden, who is due to be sworn in on 20 January, has vowed to make cyber-security a "top priority" of his administration.  "We need to disrupt and deter our adversaries from undertaking significant cyber-attacks in the first place," he said on Thursday.  "We will do that by, among other things, imposing substantial costs on those responsible for such malicious attacks, including in co-ordination with our allies and partners."  What do we know about the hacking campaign? Hackers managed to gain access to major organisations by compromising network management software developed by the Texas-based IT company SolarWinds.  The access could have allowed the hackers to take a high degree of control over the networks of organisations using that software, but appears to have been used to steal data rather than for any disruptive or destructive impact.  It is thought they targeted a narrow number of organisations in an attempt to steal national security, defence and other related information.  However, while software may have been downloaded, that does not necessarily mean data was taken.  SolarWinds Orion earlier said that 18,000 of its 300,000 customers might have been affected, but there is no indication that significant theft of customer or citizen data was an aim of the cyber-attack.  Researchers, who have named the hack Sunburst, say it could take years to fully comprehend it.  For more than three decades, hackers linked to Moscow are believed to have tried to steal US secrets online.  Several other organisations around the world, including in the UK, are understood to have been targeted by hackers using the same network management software.
    


![output_9_1](https://user-images.githubusercontent.com/47662495/102862154-0377a580-4474-11eb-9094-99625bdb453f.png)


    targEps : 0.0032759759270348868
    length of whole paragraph : 38
    num_samp : 2
    elapsed for DBSCAN : 0:00:00.696142
    len of cluster : 8
    


![output_9_3](https://user-images.githubusercontent.com/47662495/102862156-0377a580-4474-11eb-8555-780903a58c09.png)


    original : 
    
    The cyber-security firm that identified the large-scale hacking of US government agencies says it "genuinely impacted" around 50 organisations.
    Kevin Mandia, CEO of FireEye, said that while some 18,000 organisations had the malicious code in their networks, it was the 50 who suffered major breaches.
    The US Treasury and departments of homeland security, state and defence are known to have been targeted.
    US Secretary of State Mike Pompeo has blamed Russia for the hack.
    So too have the chairs of the Senate and House of Representatives' intelligence committees.
    However, President Trump cast doubt on Russia's role in two tweets on Saturday, hinting instead at Chinese involvement.
    Mr Mandia told CBS News that the cyber attack "was very consistent" with what US officials know about the work of Russia's foreign intelligence agency, the SVR.
    "I think these are folks that we've responded to in the '90s, in the early 2000s.
    It's a continuing game in cyberspace," he said.
    He said the attack on the Texas-based SolarWinds Orion, the computer network tool at the source of the breach, had the "earliest evidences of being designed".
    It started with a "dry run" in October 2019 when "innocuous code" was changed.
    "Then sometime in March, the operators behind this attack did put malicious code into the supply chain," he said, "injected it in there and that is the backdoor that impacted everybody".
    Despite Russia's denials of the "baseless" claims, many in the US intelligence community suspect the Russian government is responsible.
    Mr Pompeo said on Friday: "We can say pretty clearly that it was the Russians that engaged in this activity."
    He said that Russia was trying to "undermine our way of life", and that Russian President Vladimir Putin "remains a real risk".
    Mr Pompeo has taken a strong line against Russia before.
    In his time as secretary of state, the US has pulled out of a key nuclear treaty and the Open Skies Treaty on aerial surveillance flights.
    The Republican Chair of the Senate intelligence committee, Marco Rubio, tweeted that it is "increasingly clear that Russian intelligence conducted the gravest cyber intrusion in our history".
    He said the response "must be proportional but significant".
    Adam Schiff, Democrat chair of the House intelligence committee, echoed these views, saying on Sunday: "I don't think there's any question that it was Russia".
    And he took a swipe at President Trump for his comments on the issue saying they were "just uniformly destructive and deceitful, and injurious ... to our national security."
    The president has long been ambivalent towards Moscow, downplaying such incidents as allegations that Russia offered the Taliban bounties to kill US troops.
    In his tweets on Saturday, Mr Trump again turned on what he labels the "fake news media" for exaggerating the matter.
    He wrote: "The Cyber Hack is far greater in the Fake News Media than in actuality.
    "I have been fully briefed and everything is well under control.
    Russia, Russia, Russia is the priority chant when anything happens because Lamestream is, for mostly financial reasons, petrified of discussing the possibility that it may be China (it may!)."
    President-elect Joe Biden, who is due to be sworn in on 20 January, has vowed to make cyber-security a "top priority" of his administration.
    "We need to disrupt and deter our adversaries from undertaking significant cyber-attacks in the first place," he said on Thursday.
    "We will do that by, among other things, imposing substantial costs on those responsible for such malicious attacks, including in co-ordination with our allies and partners."
    What do we know about the hacking campaign?
    Hackers managed to gain access to major organisations by compromising network management software developed by the Texas-based IT company SolarWinds.
    The access could have allowed the hackers to take a high degree of control over the networks of organisations using that software, but appears to have been used to steal data rather than for any disruptive or destructive impact.
    It is thought they targeted a narrow number of organisations in an attempt to steal national security, defence and other related information.
    However, while software may have been downloaded, that does not necessarily mean data was taken.
    SolarWinds Orion earlier said that 18,000 of its 300,000 customers might have been affected, but there is no indication that significant theft of customer or citizen data was an aim of the cyber-attack.
    Researchers, who have named the hack Sunburst, say it could take years to fully comprehend it.
    For more than three decades, hackers linked to Moscow are believed to have tried to steal US secrets online.
    Several other organisations around the world, including in the UK, are understood to have been targeted by hackers using the same network management software.
    
    reduced : 
    
    The US Treasury and departments of homeland security, state and defence are known to have been targeted.
    So too have the chairs of the Senate and House of Representatives' intelligence committees.
    Mr Pompeo said on Friday: "We can say pretty clearly that it was the Russians that engaged in this activity."
    He said the response "must be proportional but significant".
    In his tweets on Saturday, Mr Trump again turned on what he labels the "fake news media" for exaggerating the matter.
    He wrote: "The Cyber Hack is far greater in the Fake News Media than in actuality.
    Hackers managed to gain access to major organisations by compromising network management software developed by the Texas-based IT company SolarWinds.
    Several other organisations around the world, including in the UK, are understood to have been targeted by hackers using the same network management software.
    
    wc_list_cut - keyword : [('Russia', 1.0), ('cyber', 0.6363636363636364), ('US', 0.6363636363636364), ('organisations', 0.5454545454545454), ('intelligence', 0.5454545454545454)]
    


```python

```











