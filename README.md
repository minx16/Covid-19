As of August 28, 2020, the COVID-19 pandemic has resulted in more than 24 million cases, with more than 0.8 million deaths worldwide (Johns Hopkins University 2020). Among all countries, the United States of America has the highest number of infections (more than 5.9 million cases) and fatalities (over 0.18 million deaths). The situation has drastically changed and disrupted people’s daily lives, with millions of jobs lost. Since the start of the outbreak, we have seen hundreds and thousands of businesses temporarily shut down, schools temporarily closed, travel plans canceled, and entertainment put on hold. Still, many employees work from home, and students take courses online. Every person and organization is anxious to know when the situation will end, or, at least, what the near future will be like.

To answer these questions, having a reliable prediction tool to forecast future cases and deaths of COVID-19 is of foremost importance. Motivated by this, our paper titled 
[“A Geotemporal Clustering Model for COVID-19 Projection”](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3686506)
proposes a clustering based algorithm to predict the state-level COVID-19 cases in the United States, using the state-level population and historical COVID-19 case data as input. Our algorithm has two novel features. First, we treat a (state, date) pair as one observation in the COVID-19 case data, summarize features from the data, and classify similar observations using k-means clustering. Second, we use the similarity between the observations in the same cluster to capture the similarity of future trajectory of cases. Thus, when predicting the number of cases in a state in the future, we first map the pair of this state and the current date to a corresponding cluster, then take the observable future of older observations in this cluster as potential samples. Using mean absolute percentage error (MAPE) as the performance metric, we demonstrate that our algorithm provides reliable results for prediction periods ranging from 1 to 20 days. Our algorithm achieves the highest 7-day prediction accuracy both at the state and the national levels compared to three existing models and one intuitive baseline model. Our results indicate that in the next 20 days, states may be in starkly different situations if there are no interventions. While some states are getting better, the cases in others are still trending upward.

Below are prediction results in state-level updated on September 5, 2020.
The solid blue line is historical daily cases.
The dash blue line is daily cases predictions. The daily cases are smoothed as 7-day average. 
The solid red line is historical cumulative cases. The dash red line is cumulative cases predictions.

![Alabama](https://user-images.githubusercontent.com/67207788/93020157-a4b7ab80-f5a9-11ea-8379-8d678bfbb7ce.png)
![Alaska](https://user-images.githubusercontent.com/67207788/93020160-a84b3280-f5a9-11ea-8c1e-466bfe6bb0b5.png)
![Arizona](https://user-images.githubusercontent.com/67207788/93020161-aaad8c80-f5a9-11ea-877c-e4dad0ea6bec.png)
![Arkansas](https://user-images.githubusercontent.com/67207788/93020162-ad0fe680-f5a9-11ea-8bd2-6c3e9f5ec49c.png)
![California](https://user-images.githubusercontent.com/67207788/93020164-aed9aa00-f5a9-11ea-8344-eb60ef62fff1.png)
![Colorado](https://user-images.githubusercontent.com/67207788/93020166-b0a36d80-f5a9-11ea-950f-7e69ba80f666.png)
![Connecticut](https://user-images.githubusercontent.com/67207788/93020168-b305c780-f5a9-11ea-8dbc-6e69d5022c6b.png)
![Delaware](https://user-images.githubusercontent.com/67207788/93020170-b436f480-f5a9-11ea-9221-32ae2b1f747c.png)
![District of Columbia](https://user-images.githubusercontent.com/67207788/93020172-b5682180-f5a9-11ea-8fc2-a1f8a3c5f5a7.png)
![Florida](https://user-images.githubusercontent.com/67207788/93020173-b600b800-f5a9-11ea-9ff8-9f78918375ff.png)
![Georgia](https://user-images.githubusercontent.com/67207788/93020175-b731e500-f5a9-11ea-879a-91897040d2e5.png)
![Hawaii](https://user-images.githubusercontent.com/67207788/93020176-b7ca7b80-f5a9-11ea-9752-ea7b64807391.png)
![Idaho](https://user-images.githubusercontent.com/67207788/93020178-b8631200-f5a9-11ea-85fd-2c6bde92e5e2.png)
![Illinois](https://user-images.githubusercontent.com/67207788/93020179-b8fba880-f5a9-11ea-8cef-a939807c215e.png)
![Indiana](https://user-images.githubusercontent.com/67207788/93020180-bbf69900-f5a9-11ea-8e8f-1606a2ac2b9f.png)
![Iowa](https://user-images.githubusercontent.com/67207788/93020182-bd27c600-f5a9-11ea-8850-2c0cec1c4463.png)
![Kansas](https://user-images.githubusercontent.com/67207788/93020183-be58f300-f5a9-11ea-8df7-59bf0350761b.png)
![Kentucky](https://user-images.githubusercontent.com/67207788/93020184-bef18980-f5a9-11ea-99bb-9e229957e196.png)
![Louisiana](https://user-images.githubusercontent.com/67207788/93020186-c0bb4d00-f5a9-11ea-9878-28240fecbae3.png)
![Maine](https://user-images.githubusercontent.com/67207788/93020188-c1ec7a00-f5a9-11ea-97a3-518dc75bdeb1.png)
![Maryland](https://user-images.githubusercontent.com/67207788/93020191-c31da700-f5a9-11ea-8566-970142e34346.png)
![Massachusetts](https://user-images.githubusercontent.com/67207788/93020192-c4e76a80-f5a9-11ea-9e8f-5dc10d02bebd.png)
![Michigan](https://user-images.githubusercontent.com/67207788/93020193-c6189780-f5a9-11ea-92a2-2dedf54f73e5.png)
![Minnesota](https://user-images.githubusercontent.com/67207788/93020195-c7e25b00-f5a9-11ea-9876-5d44c83c5046.png)
![Mississippi](https://user-images.githubusercontent.com/67207788/93020196-c87af180-f5a9-11ea-9c66-3adfa95f773f.png)
![Missouri](https://user-images.githubusercontent.com/67207788/93020197-c9138800-f5a9-11ea-9348-b8fdbecb774a.png)
![Montana](https://user-images.githubusercontent.com/67207788/93020199-ca44b500-f5a9-11ea-8556-1efd96199bdb.png)
![Nebraska](https://user-images.githubusercontent.com/67207788/93020200-cb75e200-f5a9-11ea-808d-9dde27829ee7.png)
![Nevada](https://user-images.githubusercontent.com/67207788/93020201-cc0e7880-f5a9-11ea-8148-8bb8d9e33963.png)
![New Hampshire](https://user-images.githubusercontent.com/67207788/93020202-cd3fa580-f5a9-11ea-90f7-db17f624e3e3.png)
![New Jersey](https://user-images.githubusercontent.com/67207788/93020203-cdd83c00-f5a9-11ea-9b16-8b85d5c371f8.png)
![New Mexico](https://user-images.githubusercontent.com/67207788/93020205-cf096900-f5a9-11ea-829c-0617e3db6dc2.png)
![New York](https://user-images.githubusercontent.com/67207788/93020206-cfa1ff80-f5a9-11ea-83ff-05e99d0ccdda.png)
![North Carolina](https://user-images.githubusercontent.com/67207788/93020208-d0d32c80-f5a9-11ea-84cc-601d079fae59.png)
![North Dakota](https://user-images.githubusercontent.com/67207788/93020211-d2045980-f5a9-11ea-8326-9db7147b7c58.png)
![Ohio](https://user-images.githubusercontent.com/67207788/93020213-d3358680-f5a9-11ea-80b7-3c177168acc2.png)
![Oklahoma](https://user-images.githubusercontent.com/67207788/93020215-d466b380-f5a9-11ea-92e0-6946d2f28e6a.png)
![Oregon](https://user-images.githubusercontent.com/67207788/93020218-d9c3fe00-f5a9-11ea-8516-0990e6acb018.png)
![Pennsylvania](https://user-images.githubusercontent.com/67207788/93020221-ddf01b80-f5a9-11ea-82c7-a6a119c4aa2d.png)
![Rhode Island](https://user-images.githubusercontent.com/67207788/93020222-dfb9df00-f5a9-11ea-9b6a-0a3dac0f06cb.png)
![South Carolina](https://user-images.githubusercontent.com/67207788/93020225-e183a280-f5a9-11ea-9ab6-c0a7a1e7fe5c.png)
![South Dakota](https://user-images.githubusercontent.com/67207788/93020234-e47e9300-f5a9-11ea-8fbb-73ef822c1984.png)
![Tennessee](https://user-images.githubusercontent.com/67207788/93020238-e7798380-f5a9-11ea-8731-c5cf2f06322c.png)
![Texas](https://user-images.githubusercontent.com/67207788/93020239-e8aab080-f5a9-11ea-9e70-8cf6c64a6092.png)
![Utah](https://user-images.githubusercontent.com/67207788/93020240-e9dbdd80-f5a9-11ea-89d6-554543798e5f.png)
![Vermont](https://user-images.githubusercontent.com/67207788/93020243-eb0d0a80-f5a9-11ea-87bb-c636cbfae6b5.png)
![Virginia](https://user-images.githubusercontent.com/67207788/93020245-eba5a100-f5a9-11ea-9710-29748e2fa2b0.png)
![Washington](https://user-images.githubusercontent.com/67207788/93020247-ed6f6480-f5a9-11ea-9787-de427b8cadfe.png)
![West Virginia](https://user-images.githubusercontent.com/67207788/93020249-efd1be80-f5a9-11ea-80fa-3ec05696fd10.png)
![Wisconsin](https://user-images.githubusercontent.com/67207788/93020256-f8c29000-f5a9-11ea-9204-e897c8181b14.png)
![Wyoming](https://user-images.githubusercontent.com/67207788/93020259-f9f3bd00-f5a9-11ea-9112-dc1396ebd7ef.png)
