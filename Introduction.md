## Introduction

Startups are young companies which develop innovative products or services for people whose demand is not yet met by existing businesses. Globally there are 140,000 startups with a majority focussing on the internet and digital technologies. However, startups’ success rate is very small as 90% of them fail within a ten-year period (Startup Genome 2019, 19), primarily due to insufficient capital and a lack of market need (CB Insights 2021). Furthermore, CB Insights (2018) found that the odds of startups becoming unicorns, which are startups valued at $1 billion or more such as ride-hailing software company Uber, are only around 1%.

The rarity of unicorns raises questions about factors which contribute to driving up valuations. There are numerous factors ranging from the company’s sales and assets to the quality of the entrepreneur and of the venture capital (VC) firm (Gompers, et al. 2006, 18). This research will focus on three aspects. First is industry as certain industries have greater market opportunities for startups and also attract more investors than others. The second factor is geographical location which if supportive can provide startups with valuable networks of human capital and prospective investors. The third factor is investors whose role is significant given that starting up costs are high and it takes years for them to generate revenues from their innovation.

This research will examine whether unicorns are concentrated in certain industries or countries, and whether unicorns from different countries tend to specialise in different markets. Then, I will look at the top ten investors to check whether their investments specialise in particular industries or countries. Finally, I will investigate which industries have seen more or less growth in the number of unicorns in the recent years.


## Research  topic

### Background summary

Startups are more likely to succeed when operating in fast-expanding industries with growing customer segments. This aligns with how modern startups are mostly tech-centric as the IT revolution in the 1980s first led to innovations that gave us the Internet, then in the 2000s new companies began to create software programmes that “make up the content of the Internet”, connecting people for work, social and entertainment purposes (Grillo 2015, 40-1). Recently, health tech startups have also grown rapidly especially as the pandemic caused healthcare services to be overstretched. Furthermore, a startup’s industry significantly affects VC firms’ investment decisions (Gompers, et al 2020., 177), thereby making it an important factor of startups’ ability to grow and become billion-dollar companies.

Location can also be crucial when it provides a positive network effect, which means when environmental conditions supply startups with good connectivity to high quality research institutes, strong investor network and skilled labour such as the Silicon Valley (Bock and Hackober 2020, 977). In other words, innovation clusters support entrepreneurs and their ventures. But there seems to be variations among clusters as Bock and Hackober’s study didn’t find a statistically significant effect for Chinese clusters in Beijing and Shanghai. This may be due to Chinese clusters being relatively younger than Silicon Valley and thus not yet as developed. Nevertheless, startups in the US and China similarly face favourable conditions in terms of acquiring funds alternative to VCs (Jinzhi and Carrick 2019, 3379-80). The US has the Small Business Innovation Research grant programme, while in China government-backed investment programmes for startups at federal, provincial and local levels are available.

As a source of capital, investors play a major role in making sure that startups can remain in operation despite not receiving any earnings from their products yet. A survey found that most venture capital firms invested in three or more industries, but over 60% of them expressed specialising in a particular industry namely the IT and health industries (Gompers, et al. 2020, 174). Meanwhile, they were less likely to indicate focusing on a particular geography which suggests that most venture capitals invest in various geographies at once (ibid., 174). Since investors generally have preferences in terms of industry, they can further influence growth in the number of unicorns in certain industries apart from increasing the likelihood of startups becoming unicorns.

### Research questions

The following research questions will help indicate which industries have rapidly developing market opportunities and which countries are favourable to unicorns, whether countries and investors specialise in different markets, and also identify growth trends in the number of unicorns across industries.

1.	In which industries and countries are unicorns concentrated?
2.	Do countries vary in terms of their top industries with the most unicorns?
3.	Do investors specialise in particular industries or countries?
4.	What are the trends in the number of unicorns across different industries in 2014-2022?


## Data collection / Survey design

This researches uses a CB Insights’ database covering 1191 unicorn companies which was last updated on 7th October 2022. The database is in table form and contains the following variables:
i.	Company
ii.	Valuation in billion dollars
iii.	Date joined
iv.	Country
v.	City
vi.	Industry
vii.	Select investors

It is worth noting that the database is incomplete considering that there were over 1200 unicorns by the end of 2022, and that FTX, a cryptocurrency exchange company which went bankrupt in November 2022, is still in the database. Regardless, it holds a sufficiently large amount of data which allows for appropriate use. 

# #total number of countries in the list - 47
# df['Country'].describe()

# #total number of cities in the list - 280
# df['City'].describe()

# #total number of industries in the list - 15
# df['Industry'].describe()

# #find min, max and average of valuation - 1, 14, 3.2
# df['Valuation'].describe()

# #the proportion of unicorns with the lowest valuation - 23 percent
# (df.loc[df['Valuation']==1.0].count()/1190)*100

# #the highest valued unicorn - bytedance
# df.loc[df['Valuation']==df['Valuation'].max()]

# #the first unicorn in the list - veepee
# df.loc[df['Date']==df['Date'].min()]

# #the latest unicorn in the list - equashield
# df.loc[df['Date']==df['Date'].max()]

There are 1190 unicorns distributed across 47 countries, 280 cities, and 15 industrial categories. The unicorns in the data have an average valuation of $3.2 billion. 23% of unicorns have the lowest valuation of 1 billion, whereas Chinese company Bytedance, which owns TikTok, is the highest valued at 140 billion. The oldest unicorn is French e-commerce company Veepee which joined in July 2007, and US health firm Equashield is the latest to join in October 2022. Finally, the total number of investors is 1356.

## Analysis and results

### RQ1: In which industries and countries are unicorns concentrated?

More than half (55%) of unicorns are located in the US with a total of 644 companies followed by China, India, the UK and Germany. Four of the top five cities with the most unicorns are also in the US and China. San Francisco, which has Silicon Valley, is ranked first with 169 firms. New York places second (114), then Beijing (62), Shanghai (44), and fifth, London (34). Meanwhile, 205 companies, or 18% of the world’s unicorns, are spread across the remaining 42 countries excluded from the top five list.

When looking at the top five countries, it appears that unicorns tend to concentrate in particular geographies. For example, 644 US unicorns are distributed across 135 cities, but over 40% of them are based in San Francisco and New York. In China, more than one-third of unicorns are located in Beijing alone. But the most notable geographical concentration is in the UK with 78% of their unicorns based in London.

Fintech is the top industry with the most unicorns (21%). The highest valued fintech unicorn at $95 billion is US-based Stripe which offers online payment solutions. Nearly half of the world’s unicorns are in the top three industries including internet software & services and e-commerce & direct-to-consumer. The highest valued unicorns in the two latter groups are Australia’s graphic design platform Canva and China’s online fashion retailer SHEIN.

Health and artificial intelligence (AI) are fourth and fifth. They are industries which seem to have growing market opportunities for startups. This is against the background of rising demand for healthcare services and accessing healthcare benefits, and that machine learning technologies have made significant progress in recent years. Startups that develop technologies which enable self-driving cars or real-time analysis of consumer behaviour have greater potential growth compared with startups that sell, for instance, electronic cigarettes. This explains why health and AI industries have more unicorns than bottom industries such as consumer & retail and travel.

### RQ2: Do countries vary in terms of their top industries with the most unicorns?

The analysis here is narrowed down to the top five countries with the most unicorns because countries with relatively small number of unicorns do not have a reasonably sufficient number of unicorn representations across multiple industries.

The chart below illustrates the share of unicorns across different industries in the UK, India, Germany, the US and China. As mentioned previously, the fintech industry has the most unicorns, and it is apparent that fintech is among the top three industries in all countries except for China. The UK, in particular, has an exceptionally high share of unicorns in fintech at 59% and other industries are much less represented in comparison. This is mainly due to the country’s strong fintech ecosystem. London is a global financial centre with a high concentration of large pools of capital and skilled labour, making it one of the top three fintech hubs globally. According to a 2020 report, UK financial services spent nearly £100 billion on technology (Kimber 2021). UK fintechs mostly specialise in banking, payment technology, and wealth technology such as trading and investment platforms (Deloitte 2021).

Surprisingly, fintech unicorns only account for 4.7% in China. Its largest unicorn industry is e-commerce & direct-to-consumer at 16%. Compared with other countries, China also has about even distribution of unicorns across various industries. Other strong industries in China include AI, hardware and auto & transportation. This can in part be attributed to greater adoption of advanced technologies by other industries which require AI-operated programmes such as in developing autonomous cars, and in other part to government push for expansion in AI such as the state council’s conception of the New Generation Artificial Intelligence Development Plan in 2017 (GMI Research 2021). Additionally, China’s electric vehicle (EV) market is the world’s largest (McKerracher 2022).

In the US, the top industry is in the internet software & services industry (25%), followed by fintech and health. The US’ dominance in internet startups is likely due to the country’s history of being a pioneer in developing the Internet. Moreover, tech giants like Microsoft and Alphabet were conceived there. Its digital health industry is also rapidly expanding not only because the pandemic has increased the use of digital technologies for resource management and patient monitoring in the healthcare sector, but also due to its ageing population with a higher incidence of chronic illnesses (Great Market Insights 2021). Unlike other countries, cybersecurity is also a strong industry for the US with 45 unicorns, whereas China only has one and others none. Generally, it is a newly rising industry as the digitisation of the economy has created greater demand for protection of data and against cyberattacks.

Meanwhile, India and Germany similarly share fintech, e-commerce & direct-to-consumer and internet software & services as their top three industries. India is advantaged by having the world’s second highest number of internet users and also a large pool of skilled IT workers. In Germany, the tech startup scene is growing in Berlin which managed to raise $13 billion in venture capital funding in the first three quarters of 2021 (Hodgson 2021).

Based on the data, there are variations in the distribution of unicorns across different industries among the top five countries. Variations are caused by a combination of multiple factors from market opportunities and government initiatives to the presence of supportive economic or innovative clusters. This can lead to countries specialising in different industries.

### RQ3: Do investors specialise in particular industries or countries?

The analysis here will focus on the top ten investors identified as those making the highest number of investments. Their investments account for 424 unique unicorns, or 35% of the total number of firms in the database, spread out across 33 countries. Table 1 shows that on average they invest in 10 countries and 12 out of 15 industries.

The top five countries where the ten investors make their investments are similar to the top five countries with the most unicorns. The US is ranked first followed by China, India, then the UK. The only difference is that Israel makes the top five instead of Germany.

Majority of their investments are also in the top three industries with the most unicorns. However, while the fintech industry has the highest number of unicorns, the above shows that the top ten investors make the most frequent investments in internet startups. Apart from that, cybersecurity is ranked above health and AI. There are 37 cybersecurity unicorns where the top ten investors invest in – 26 in the US and 8 in Israel, which explains Israel’s top fifth position. Israel has one of the largest clusters for cybersecurity innovation which managed to acquire venture capital funding of $8.8 billion in 2021. Israel’s economy also has a special focus on national defence, and it has experienced an increasing number of cyberattacks in the last couple of years (Jaghory 2022).

Table 2 shows that half of their investments are generally spread out across two different industries. This suggests that even if specialisation takes place, it occurs over more than one industry.

A great majority also heavily invest in the US by having over half of their investments there, except for SoftBank Group and Sequoia Capital China, which is the only VC with a high share of investment in China. The second most preferred location appears to be India or alternatively Israel.

Unlike other top VC firms, Sequoia Capital China and General Catalyst also uniquely make considerable investments in AI and health respectively. This may be due to strong China’s AI development and growing digital health industry in the US.

### RQ4: What are the trends in the number of unicorns across different industries in 2014-2022?

Generally, 2021 saw the highest number of startups joining the unicorn club across industries. In total, 529 startups became unicorns in 2021, up from 106 in 2020. This is largely due to the sudden rise in funding sources as nontraditional investors like private equity firms becoming more willing to invest in early-stage startups lately. Crossover investors, who invest in both public and private markets, have also injected more capital in the latter. Additionally, fewer companies are going public before reaching a billion-dollar valuation to allow “crossover investors to take stakes in these private companies and secure for themselves an opportunity to further increase their position when an IPO occurs” (PitchBook 2021, 29-30).

The rise in the number of unicorns has been the most notable in fintech and internet software & services. They remain the top industries producing the most unicorns even though the significant rise in unicorns has come down to just over 230 companies joining in 2022 with 60 fintech and 50 internet startups. 

There are five other promising industries specifically health, e-commerce & direct-to-consumer, supply chain, logistics & delivery, AI, and cybersecurity as highlighted in the figure below. The number of unicorns produced in each of these five industries ranged from 27 to 41 in 2021. In 2022, each contributed over 10 which is lower than the previous year but still higher than any other years before 2021.

As mentioned earlier, digital health is a growing industry largely due to the pandemic changing the delivery of healthcare services. E-commerce has also boomed since the pandemic when retail stores closed and people were confined to their homes. Growth in the number of mobile device users, online marketplaces and integration with social media, for example, sellers promoting their products on Instagram, are also driving forces of growth in e-commerce. Furthermore, the pandemic has changed people’s mobile behaviour. This has created growth opportunities in the logistics & delivery industry such as grocery or medicine delivery or even meeting the delivery needs of sellers on e-commerce platforms (Eckert 2022, 10). Meanwhile, the cybersecurity industry is particularly expanding in the US and Israel as demand for data protection and online security increases. Finally, AI is flourishing as technological adoption in other industries require the development of sophisticated machine learning programmes whether for developing new vaccines or for operating autonomous cars.

## Conclusions

This research has shown that unicorns are mostly concentrated in the US and China with 70% of the world’s unicorns collectively. These unicorns are also concentrated in economic or innovation clusters namely the Silicon Valley in San Francisco, New York, Beijing, Shanghai and London. These clusters can provide positive network effect for entrepreneurs. Most unicorns are in fintech, internet and e-commerce. However, there are variations across countries which suggest industry specialisation. For example, the UK specialising in fintech, the US in internet software and health technology, and China in e-commerce and AI.

This research further found that the top ten investors’ cumulative investments are broad covering at least 10 industries and up to 15 countries. But they appear to favour internet and fintech startups, except for three VC firms that prefer health, e-commerce or AI companies. Regardless, they do not specialise in a single industry and substantially invest in more than one industry simultaneously instead. Since all of them predominantly invest in US unicorns, except one China-based VC, this indicates geographical specialisation to some extent despite their willingness to invest broadly globally.

Lastly, health, e-commerce, mobility, AI and cybersecurity industries are demonstrating rapidly growing market opportunities which may produce even more unicorns in the future. Besides increasing capital inflow from VCs, the driving forces of growth in those industries include newly developed clusters with a special industrial focus, COVID-19-related changing consumer behaviour, government initiatives, and demand for technological advancements as a result of linkages among industries.

## References

Bock, Carolin, and Christian Hackober. 2020. "Unicorns—What Drives Multibillion-Dollar Valuations?" Business Research 13: 949-984.

CB Insights. 2022. “The Complete List of Unicorn Companies.” CB Insights. Accessed December 28, 2022. https://www.cbinsights.com/research-unicorn-companies

—. 2021. The Top 12 Reasons Startups Fail. August 3. Accessed January 3, 2023. https://www.cbinsights.com/research/report/startup-failure-reasons-top/.

—. 2018. Venture Capital Funnel Shows Odds Of Becoming A Unicorn Are About 1%. September 6. Accessed January 3, 2023. https://www.cbinsights.com/research/venture-capital-funnel-2/.

Deloitte. 2021. The UK FinTech Landscape. Accessed January 3, 2023. https://www2.deloitte.com/uk/en/pages/financial-services/articles/uk-fintech-landscape.html.

Eckert, Huff Vicki. 2022. "Unicorns in Digital Economy: 5 Emerging Trends." pwc. January 17. Accessed January 3, 2023. https://www.pwc.com/gx/en/issues/reinventing-the-future/take-on-tomorrow/download/sbpwc-2022-01-17-World-of-unicorns.pdf.

Global Market Insights. 2022. "Digital Health Market Size & Share | Trends Report, 2022-2030." Global Market Insights. September. Accessed January 3, 2023. https://www.gminsights.com/industry-analysis/digital-health-market.

GMI Research. 2021. "China AI Market Opportunities & Forecast 2021-2028." GMI Research. January. Accessed January 3, 2023. https://www.gmiresearch.com/report/china-ai-market/.

Gompers, Paul, Anna Kovner, Josh Lerner, and David Scharfstein. 2006. “Skill vs Luck in Entrepreneurship and Venture Capital: Evidence from Serial Entrepreneurs.” NBER Working Paper 12592, National Bureau of Economic Research, Cambridge. http://www.nber.org/papers/w12592 

Gompers, Paul, Will Gornall, Steven Kaplan, and Ilya Strebulaev. 2020. "How Do Venture Capitalists Make Decisions?" Journal of Financial Economics 135: 169-190.

Grillo, Edoardo. 2015. An Investigation on the Economics of Unicorns and Their Valuations as a Signal of a New Technological Bubble. Thesis, Rome: LUISS. https://tesi.luiss.it/18497/1/668061_GRILLO_EDOARDO.pdf

Hodgson, Leah. 2021. How Foreign Investors Are Tapping into Germany’s Late-Stage VC Boom. November 25. Accessed January 3, 2023. https://pitchbook.com/news/articles/foreign-investors-tapping-into-germanys-late-stage-vc-boom.

Jaghory, Dillon. 2022. Cybersecurity in Israel: Fortifying Digital Defenses Amid Elevated Risks. July 14. Accessed January 3, 2023. https://www.nasdaq.com/articles/cybersecurity-in-israel%3A-fortifying-digital-defenses-amid-elevated-risks.

Jinzhi, Zhai, and Jon Carrick. 2019. "The Rise of the Chinese Unicorn: An Exploratory Study of Unicorn Companies in China." Emerging Markets Finance and Trade 55 (15): 3371-3385.

Kimber, Anita. 2021. Why Fintech Is Core to the UK's Future Success. April 16. Accessed January 3, 2023. https://www.ey.com/en_uk/financial-services/why-fintech-is-core-to-the-uk-future-success.

McKerracher, Colin. 2022. China Has Shot at Seizing 60% Share of Global EV Sales This Year . November 15. Accessed January 3, 2023. https://www.bloomberg.com/news/articles/2022-11-15/china-has-shot-at-seizing-60-share-of-global-ev-sales-this-year.

PitchBook. 2021. "PitchBook-NVCA Venture Monitor Q3 2021." PitchBook. October 13. Accessed January 3, 2023. https://files.pitchbook.com/website/files/pdf/Q3_2021_PitchBook-NVCA_Venture_Monitor.pdf.

Startup Genome. 2019. Global Startup Ecosystem Report 2019. Startup Genome. https://startupgenome.com/reports/global-startup-ecosystem-report-2019

Startup Ranking. 2022. Countries - With the Top Startups Worldwide. Accessed January 3, 2023. https://www.startupranking.com/countries.