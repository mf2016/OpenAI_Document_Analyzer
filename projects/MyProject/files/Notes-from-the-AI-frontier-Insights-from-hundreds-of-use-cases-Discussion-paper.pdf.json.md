## MCKINSEY ANALYTICS

Mckinsey&Company

MCKINSEY GLOBAL INSTITUTE NOTES FROM THE AI FRONTIER INSIGHTS FROM HUNDREDS OF USE CASES

DISCUSSION PAPER APRIL 2018

Michael Chui | San Francisco James Manyika | San Francisco Mehdi Miremadi | Chicago Nicolaus Henke | London Rita Chung | Silicon Valley Pieter Nel | New York Sankalp Malhotra | New York

MCKINSEY GLOBAL INSTITUTE

Since its founding in 1990, the Mckinsey Global Institute (MGI) has sought to develop a deeper understanding of the evolving global economy. As the business and economics research arm of Mckinsey & Company, MGI aims to provide leaders in the commercial, public, and social sectors with the facts and insights on which to base management and policy decisions.

MGI research combines the disciplines of economics and management, employing the analytical tools of economics with the insights of business leaders. Our "micro-to-macro" methodology examines microeconomic industry trends to better understand the broad macroeconomic forces affecting business strategy and public policy. MGI's in-depth reports have covered more than 20 countries and 30 industries. Current research focuses on six themes: productivity and growth, natural resources, labor markets, the evolution of global financial markets, the economic impact of technology and innovation, and urbanization. Recent reports have assessed the digital economy, the impact of Al and automation on employment, income inequality, the productivity puzzle, the economic benefits of tackling gender inequality, a new era of global competition, Chinese innovation, and digital and financial globalization.

MGI is led by three Mckinsey & Company senior partners: Jacques Bughin, Jonathan Woetzel, and James Manyika, who also serves as the chairman of MGI. Michael Chui, Susan Lund, Anu Madgavkar, Jan Mischke, Sree Ramaswamy, and Jaana Remes are MGI partners, and Mekala Krishnan and Jeongmin Seong are MGI senior fellows.

Project teams are led by the MGI partners and a group of senior fellows, and include consultants from Mckinsey offices around the world. These teams draw on Mckinsey's global network of partners and industry and management experts. Advice and input to MGI research are provided by the MGI Council, members of which are also involved in MGI's research. MGI Council members are drawn from around the world and from various sectors and include Andrés Cadena, Sandrine Devillard, Richard Dobbs, Tarek Elmasry, Katy George, Rajat Gupta, Eric Hazan, Eric Labaye, Acha Leke, Scott Nyquist, Gary Pinkus, Sven Smit, Oliver Tonby, and Eckart Windhagen. In addition, leading economists, including Nobel laureates, act as research advisers to MGI research.

The partners of Mckinsey fund MGI's research; it is not commissioned by any business, government, or other institution. For further information about MGI and to download reports, please visit www.mckinsey.com/mgi.

Mckinsey Analytics helps clients achieve better performance through data. We work together with clients to build analytics-driven organizations, helping them develop the strategies, operations, and capabilities to derive rapid and sustained impact from analytics. Over the past five years, we have worked with more than 2,000 clients across every industry and business function. Mckinsey Analytics is led globally by Nicolaus Henke and Noshir Kaka, together with an executive committee comprised of 40 Mckinsey senior partners representing all regions and practices. Today, McKinsey Analytics brings together more than 1,900 advanced analytics and Al experts and spans more than 125 domains (industry- and function-specific teams with people, data, and tools focused on unique applications of analytics). Mckinsey Analytics includes several acquired companies such as QuantumBlack, a leading advanced analytics firm that Mckinsey acquired in 2015.

Learn more at www.mckinsey.com/business-functions/mckinsey-analytics/our-insights.

Copyright @ Mckinsey & Company 2018

IN BRIEF

NOTES FROM THE AI FRONTIER: INSIGHTS FROM HUNDREDS OF USE CASES

For this discussion paper, part of our ongoing research into evolving technologies and their effect on business, economies, and society, we mapped traditional analytics and newer "deep learning" techniques and the problems they can solve to more than 400 specific use cases in companies and organizations. Drawing on MGI research and the applied experience with artificial intelligence (Al) of Mckinsey Analytics, we assess both the practical applications and the economic potential of advanced Al techniques across industries and business functions. We continue to study these Al techniques and additional use cases. For now, here are our key findings:

· Al, which for the purposes of this paper we characterize as "deep learning" techniques using artificial neural networks, can be used to solve a variety of problems. Techniques that address classification, estimation, and clustering problems are currently the most widely applicable in the use cases we have identified, reflecting the problems whose solutions drive value across the range of sectors.

The greatest potential for Al we have found is to create value in use cases in which more established analytical techniques such as regression and classification techniques can already be used, but where neural network techniques could provide higher performance or generate additional insights and applications. This is true for 69 percent of the Al use cases identified in our study. In only 16 percent of use cases did we find a "greenfield" Al solution that was applicable where other analytics methods would not be effective.

Because of the wide applicability of Al across the economy, the types of use cases with the greatest value potential vary by sector. These variations primarily result from the relative importance of different drivers of value within each sector. They are also affected by the availability of data, its suitability for available techniques, and the applicability of various techniques and algorithmic solutions. In consumer-facing industries such as retail, for example, marketing and sales is the area with the most value. In industries such as advanced manufacturing, in which operational performance drives corporate performance, the greatest potential is in supply chain, logistics, and manufacturing.

· The deep learning techniques on which we focused - feed forward neural networks, recurrent neural networks, and convolutional neural networks-account for about 40 percent of the annual value potentially created by all analytics techniques. These three techniques together can potentially enable the creation of between $3.5 trillion and $5.8 trillion in value annually. Within industries, that is the equivalent of 1 to 9 percent of 2016 revenue.

· Capturing the potential impact of these techniques requires solving multiple problems. Technical limitations include the need for a large volume and variety of often labeled training data, although continued advances are already helping address these. Tougher perhaps may be the readiness and capability challenges for some organizations. Societal concern and regulation, for example about privacy and use of personal data, can also constrain Al use in banking, insurance, health care, and pharmaceutical and medical products, as well as in the public and social sectors, if these issues are not properly addressed.

· The scale of the potential economic and societal impact creates an imperative for all the participants-Al innovators, Al-using companies and policy-makers-to ensure a vibrant Al environment that can effectively and safely capture the economic and societal benefits.

INTRODUCTION

Artificial intelligence (Al) stands out as a transformational technology of our digital age. Questions about what it is, what it can already do-and what it has the potential to become- cut across technology, psychology, politics, economics, science fiction, law, and ethics. Al is the subject of countless discussions and articles, from treatises about technical advances to tabloid headlines about its effects. Even as the debate continues, the technologies underpinning Al continue to move forward, enabling applications from facial recognition in smartphones to consumer apps that use Al algorithms to detect diabetes and hypertension with increasing accuracy.1 Indeed, while much of the public discussion of Al focuses on science fiction-like Al realization such as robots, the number of less-noticed practical applications for Al throughout the economy is growing apace and permeating our lives.

This discussion paper seeks to contribute to the body of knowledge about Al by mapping Al techniques to the types of problems they can help solve and then mapping these problem types to more than 400 practical use cases Acknowledgments Page 31 and applications in businesses across 19 industries, from aerospace and defense to travel and the public sector, and nine business functions ranging from marketing and sales and supply-chain management to product development and human resources.2 Drawing on a wide variety of public and proprietary data sources, including the experiences of our Mckinsey & Company colleagues, we also assess the potential economic value of the latest generations of Al technologies. The Al techniques we focus on are deep learning techniques based on artificial neural networks, which we see as generating as much as 40 percent of the total potential value that all analytics techniques could provide.

What's inside Introduction Page 1

1. Mapping Al techniques to problem types Page 2

2. Insights from use cases Page 7

3. Sizing the potential value of Al Page 17

4. The road to impact and value Page 26

Our findings highlight the substantial potential of applying deep learning techniques to use cases across the economy; these techniques can provide an incremental lift beyond that from more traditional analytics techniques. We identify the industries and business functions in which there is value to be captured, and we estimate how large that value could be globally. For all the potential, much work needs to be done to overcome a range of limitations and obstacles to Al application. We conclude with a brief discussion of these obstacles and of future opportunities as the technologies continue their advance. Ultimately, the value of Al is not to be found in the models themselves, but in organizations' abilities to harness them. Business leaders will need to prioritize and make careful choices about how, when, and where to deploy them.

This paper is part of our continuing research into analytics, automation, and Al technologies, and their effect on business, the economy, and society.3 It is not intended to serve as a comprehensive guide to deploying Al; for example, we identify but do not elaborate on issues of data strategy, data engineering, governance, or change management and culture

1 Geoffrey H. Tison et al., "Cardiovascular risk stratification using off-the-shelf wearables and a multi-mask deep learning algorithm," Circulation, volume 136, supplement 1, November 14, 2017.

2 We do not identify the companies by name or country, for reasons of client confidentiality.

3 Previous Mckinsey Global Institute reports on these issues include The age of analytics: Competing in a data- driven world, December 2016; A future that works: Automation, employment and productivity, January 2017; and Artificial intelligence: The next digital frontier? June 2017. See a list of our related research at the end of this paper.

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

1

that are vital for companies seeking to capture value from Al and analytics.4 The use cases we examined are not exhaustive; indeed, we continue to identify and examine others, and we may update our findings in due course. Nonetheless, we believe that this research can make a useful contribution to our understanding of what Al can and can't (yet) do, and how much value could be derived from its use. It is important to highlight that, even as we see economic potential in the use of Al techniques, the use of data must always take into account concerns including data security, privacy, and potential issues of bias, issues we have addressed elsewhere.5

## 1. MAPPING AI TECHNIQUES TO PROBLEM TYPES

As artificial intelligence technologies advance, so does the definition of which techniques constitute Al (see Box 1, "Deep learning's origins and pioneers").6 For the purposes of this paper, we use Al as shorthand specifically to refer to deep learning techniques that use artificial neural networks. In this section, we define a range of Al and advanced analytics techniques as well as key problem types to which these techniques can be applied.

NEURAL NETWORKS AND OTHER MACHINE LEARNING TECHNIQUES We looked at the value potential of a range of analytics techniques. The focus of our research was on methods using artificial neural networks for deep learning, which we collectively refer to as Al in this paper, understanding that in different times and contexts, other techniques can and have been included in Al. We also examined other machine learning techniques and traditional analytics techniques (Exhibit 1). We focused on specific potential applications of Al in business and the public sector (sometimes described as "artificial narrow Al") rather than the longer-term possibility of an "artificial general intelligence" that could potentially perform any intellectual task a human being is capable of.

Exhibit 1

Artificial intelligence, machine learning, and other analytics techniques that we examined for this research

Techniques

:selected:

Considered Al for our research

Likelihood to be used in Al applications

:unselected: Less

:selected: More

Transfer learning

Deep learning neural networks (e.g., feed forward neural networks, CNNs, RNNs, GANs)

Advanced techniques

Reinforcement learning

Dimensionality reduction (e.g., PCA, tSNE) Decision tree learning

Instance based (e.g., KNN)

Ensemble learning (e.g., random forest, gradient boosting)

Monte Carlo methods

Linear classifiers (e.g., Fisher's linear discriminant, SVM)

Clustering (e.g., k-means, tree based, db scan)

Statistical inference (e.g.,

Markov process (e.g., Markov chain)

Bayesian inference, ANOVA)

Descriptive statistics (e.g., confidence interval)

Regression Analysis (e.g., linear, logistic, lasso)

Naive Bayes classifier

## Traditional techniques

SOURCE: McKinsey Global Institute analysis

4 See Jacques Bughin, Brian McCarthy, and Michael Chui, "A survey of 3,000 executives reveals how businesses succeed with Al," Harvard Business Review, August 28, 2017.

5 Michael Chui, James Manyika, and Mehdi Miremadi, "What Al can and can't do (yet) for your business," Mckinsey Quarterly, January 2018.

6 For a detailed look at Al techniques, see An executive's guide to Al, Mckinsey Analytics, January 2018. https://www.mckinsey.com/business-functions/mckinsey-analytics/our-insights/an-executives-guide-to-ai

2

Mckinsey Global Institute

1. Mapping Al techniques to problem types

It is too early to write a full history of deep learning-and some of the details are contested-but we can already trace an admittedly incomplete outline of its origins and identify some of the pioneers. They include Warren McCulloch and Walter Pitts, who as early as 1943 proposed an artificial neuron, a computational model of the "nerve net" in the brain.1 Bernard Widrow and Ted Hoff at Stanford University, developed a neural network application by reducing noise in phone lines in the late 1950s.2 Around the same time, Frank Rosenblatt, an American psychologist, introduced the idea of a device called the Perceptron, which mimicked the neural structure of the brain and showed an ability to learn.3 MIT's Marvin Minsky and Seymour Papert then put a damper on this research in their 1969 book "Perceptrons", by showing mathematically that the Perceptron could only perform very basic tasks.4 Their book also discussed the difficulty of training multi-layer neural networks. In 1986, Geoffrey Hinton at the University of Toronto, along with colleagues David Rumelhart and Ronald Williams, solved this training problem with the publication of a now famous back propagation training algorithm- although some practitioners point to a Finnish mathematician, Seppo Linnainmaa, as having invented back propagation already in the 1960s.5 Yann LeCun at NYU pioneered the use of neural networks on image recognition tasks and his 1998 paper defined the concept of convolutional neural networks, which mimic the human visual cortex.6 In parallel, John Hopfield popularized the "Hopfield" network which was the first recurrent neural network.7 This was subsequently expanded upon by Jurgen Schmidhuber and Sepp Hochreiter in 1997 with the introduction of the long short-term memory (LSTM), greatly improving the efficiency and practicality of recurrent neural networks.8 Hinton and two of his students in 2012 highlighted the power of deep learning when they obtained significant results in the well-known ImageNet competition, based on a dataset collated by Fei-Fei Li and others.9 At the same time, Jeffrey Dean and Andrew Ng were doing breakthrough work on large scale image recognition at Google Brain.10 Deep learning also enhanced the existing field of reinforcement learning, led by researchers such as Richard Sutton, leading to the game-playing successes of systems developed by DeepMind.11 In 2014, lan Goodfellow published his paper on generative adversarial networks, which along with reinforcement learning has become the focus of much of the recent research in the field.12 Continuing advances in Al capabilities have led to Stanford University's One Hundred Year Study on Artificial Intelligence, founded by Eric Horvitz, building on the long-standing research he and his colleagues have led at Microsoft Research. We have benefited from the input and guidance of many of these pioneers in our research over the past few years.

## Box 1: Deep learning's origins and pioneers

Warren McCulloch and Walter Pitts, "A logical calculus of the ideas immanent in nervous activity," Bulletin of Mathematical Biophysics, volume 5, 1943.

2 Andrew Goldstein, "Bernard Widrow oral history," IEEE Global History Network, 1997.

3 Frank Rosenblatt, "The Perceptron: A probabilistic model for information storage and organization in the brain," Psychological review, volume 65, number 6, 1958.

4 Marvin Minsky and Seymour A. Papert, Perceptrons: An introduction to computational geometry, MIT Press, January 1969.

5 David E. Rumelhart, Geoffrey E. Hinton, and Ronald J. Williams, "Learning representations by back-propagating errors," Nature, volume 323, October 1986; for a discussion of Linnainmaa's role see Juergen Schmidhuber, Who invented backpropagation?, Blog post http://people.idsia.ch/~juergen/who-invented-backpropagation.html, 2014.

6 Yann LeCun, Patrick Haffner, Leon Botton, and Yoshua Bengio, Object recognition with gradient-based learning, Proceedings of the IEEE, November 1998.

7 John Hopfield, Neural networkds and physical systems with emergent collective computational abilities, PNAS,

April 1982.

8 Sepp Hochreiter and Juergen Schmidhuber, "Long short-term memory," Neural Computation, volume 9, number 8, December 1997.

9 Alex Krizhevsky, Ilya Sutskever, and Geoffrey E. Hinton, ImageNet classification with deep convolutional neural networks, NIPS 12 proceedings of the 25th International Conference on Neural Information Processing Systems, December 2012.

10 Jeffrey Dean et al., Large scale distributed deep networks, NIPS 2012.

11 Richard S. Sutton and Andrew G. Barto, Reinforcement learning: An introduction, MIT Press, 1998.

12 lan J. Goodfellow, Generative adversarial networks, ArXiv, June 2014.

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

3

Neural networks are a subset of machine learning techniques. Essentially, they are Al systems based on simulating connected "neural units," loosely modeling the way that neurons interact in the brain. Computational models inspired by neural connections have been studied since the 1940s and have returned to prominence as computer processing power has increased and large training data sets have been used to successfully analyze input data such as images, video, and speech. Al practitioners refer to these techniques as "deep learning," since neural networks have many ("deep") layers of simulated interconnected neurons. Before deep learning, neural networks often had only three to five layers and dozens of neurons; deep learning networks can have seven to ten or more layers, with simulated neurons numbering into the millions.

In this paper, we analyzed the applications and value of three neural network techniques:

Feed forward neural networks. One of the most common types of artificial neural network. In this architecture, information moves in only one direction, forward, from the input layer, through the "hidden" layers, to the output layer. There are no loops in the network. The first single-neuron network was proposed in 1958 by Al pioneer Frank Rosenblatt. While the idea is not new, advances in computing power, training algorithms, and available data led to higher levels of performance than previously possible.

Recurrent neural networks (RNNs). Artificial neural networks whose connections between neurons include loops, well-suited for processing sequences of inputs, which makes them highly effective in a wide range of applications, from handwriting, to texts, to speech recognition. In November 2016, Oxford University researchers reported that a system based on recurrent neural networks (and convolutional neural networks) had achieved 95 percent accuracy in reading lips, outperforming experienced human lip readers, who tested at 52 percent accuracy.

Convolutional neural networks (CNNs). Artificial neural networks in which the connections between neural layers are inspired by the organization of the animal visual cortex, the portion of the brain that processes images, well suited for visual perception tasks.

We estimated the potential of those three deep neural network techniques to create value, as well as other machine learning techniques such as tree-based ensemble learning, classifiers, and clustering, and traditional analytics such as dimensionality reduction and regression.

For our use cases, we also considered two other techniques-generative adversarial networks (GANs) and reinforcement learning-but did not include them in our potential value assessment of Al, since they remain nascent techniques that are not yet widely applied in business contexts. However, as we note in the concluding section of this paper, they may have considerable relevance in the future.

· Generative adversarial networks (GANs). These usually use two neural networks contesting each other in a zero-sum game framework (thus "adversarial"). GANs can learn to mimic various distributions of data (for example text, speech, and images) and are therefore valuable in generating test datasets when these are not readily available.

" Reinforcement learning. This is a subfield of machine learning in which systems are trained by receiving virtual "rewards" or "punishments," essentially learning by trial and error. Google DeepMind has used reinforcement learning to develop systems that can play games, including video games and board games such as Go, better than human champions.

4

Mckinsey Global Institute

1. Mapping Al techniques to problem types

PROBLEM TYPES AND THE ANALYTIC TECHNIQUES THAT CAN BE APPLIED TO SOLVE THEM

In a business setting, those analytic techniques can be applied to solve real-life problems. For this research, we created a taxonomy of high-level problem types, characterized by the inputs, outputs, and purpose of each. A corresponding set of analytic techniques can be applied to solve these problems. These problem types include:

· Classification. Based on a set of training data, categorize new inputs as belonging to one of a set of categories. An example of classification is identifying whether an image contains a specific type of object, such as a truck or a car, or a product of acceptable quality coming from a manufacturing line.

Continuous estimation. Based on a set of training data, estimate the next numeric value in a sequence. This type of problem is sometimes described as "prediction," particularly when it is applied to time series data. One example of continuous estimation is forecasting the sales demand for a product, based on a set of input data such as previous sales figures, consumer sentiment, and weather. Another example is predicting the price of real estate, such as a building, using data describing the property combined with photos of it.

· Clustering. These problems require a system to create a set of categories, for which individual data instances have a set of common or similar characteristics. An example of clustering is creating a set of consumer segments based on data about individual consumers, including demographics, preferences, and buyer behavior.

All other optimization. These problems require a system to generate a set of outputs that optimize outcomes for a specific objective function (some of the other problem types can be considered types of optimization, so we describe these as "all other" optimization). Generating a route for a vehicle that creates the optimum combination of time and fuel use is an example of optimization.

Anomaly detection. Given a training set of data, determine whether specific inputs are out of the ordinary. For instance, a system could be trained on a set of historical vibration data associated with the performance of an operating piece of machinery, and then determine whether a new vibration reading suggests that the machine is not operating normally. Note that anomaly detection can be considered a subcategory of classification.

· Ranking. Ranking algorithms are used most often in information retrieval problems in which the results of a query or request needs to be ordered by some criterion. Recommendation systems suggesting next product to buy use these types of algorithms as a final step, sorting suggestions by relevance, before presenting the results to the user.

· Recommendations. These systems provide recommendations, based on a set of training data. A common example of recommendations are systems that suggest the "next product to buy" for a customer, based on the buying patterns of similar individuals, and the observed behavior of the specific person.

· Data generation. These problems require a system to generate appropriately novel data based on training data. For instance, a music composition system might be used to generate new pieces of music in a particular style, after having been trained on pieces of music in that style.

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

5

Exhibit 2 illustrates the relative total value of these problem types across our database of use cases, along with some of the sample analytics techniques that can be used to solve each problem type. The most prevalent problem types are classification, continuous estimation, and clustering, suggesting that meeting the requirements and developing the capabilities in associated techniques could have the widest benefit. Some of the problem types that rank lower can be viewed as subcategories of other problem types-for example, anomaly detection is a special case of classification, while recommendations can be considered a type of optimization problem-and thus their associated capabilities could be even more relevant.

## Problem types Sample techniques

:selected: Essential

:selected: Relevant

% total Al value potential that could be unlocked by problem types as essential vs. relevant to use cases

Classification

CNNs, logistic regression

Continuous

Feed forward neural networks, linear

estimation

44

29

72

regression

37

29

66

Clustering K-means, affinity propagation

All other

optimization Genetic algorithms

Anomaly One-class support vector machines,

detection k-nearest neighbors, neural networks

16

39

55

17

21

37

Ranking Ranking support vector machines, neural networks 9

Recommender

systems Collaborative filtering

Data

generation

19

6

24

8

17

14

1 15

Generative adversarial networks (GANs), hidden Markov models

0 7

7

NOTE: Sample techniques include traditional analytical techniques, machine learning, and the deep learning techniques we describe in this paper as Al. Numbers may not sum due to rounding.

SOURCE: Mckinsey Global Institute analysis

6

Mckinsey Global Institute

1. Mapping Al techniques to problem types

## 2. INSIGHTS FROM USE CASES

We collated and analyzed more than 400 use cases across 19 industries and nine business functions for this research (see Box 2, "Our Al use cases"). They provided considerable insight into the areas within specific sectors where deep neural networks can potentially create the most value, the incremental performance lift that these neural networks can generate compared with more traditional analytics, and the voracious data requirements-in terms of volume, variety, and velocity-that must be met for this potential to be realized.

Examples of where Al can be used to improve the performance of existing use cases include:

Predictive maintenance: the power of machine learning to detect anomalies. Some existing predictive maintenance systems have analyzed time series data from Internet of Things (loT) sensors, such as those monitoring temperature or vibration, in order to detect anomalies or make forecasts on the remaining useful life of components. Deep learning's capacity to analyze very large amounts of high dimensional data can take this to a new level. By layering in additional data, such as audio and image data, from other sensors-including relatively cheap ones such as microphones and cameras-neural networks can enhance and possibly replace more traditional methods. Al's ability to predict failures and allow planned interventions can be used to reduce downtime and operating costs while improving production yield. In some industry examples we studied,

## Box 2. Our Al use cases

We define a "use case" as a targeted application of digital technologies to a specific business challenge, with a measurable outcome. We recognize that use cases can be described at different levels of granularity. The use cases we analyzed for this paper correspond to descriptions of specific business challenges which practitioners in the industries and sectors we studied acknowledged as meaningful. For example, recommending the "next product to buy" for e-commerce in the retail industry was considered a use case, whereas "marketing and sales" was not sufficiently granular to be considered a use case, even though it is a relevant business function. We also collated similar use cases across sectors into "domains" (see related section below).

For this research we built a library of use cases across the economy that is as comprehensive as possible. The cases that we identified come from a variety of sources, including thousands of engagements by Mckinsey Analytics with clients around the globe. The data incorporate findings from real-life examples of companies and public-sector organizations using a range of analytics techniques, both Al and more traditional approaches, as well as the potential application of these techniques in situations similar to those in which they have already been successfully deployed. For example, where we found a use case in one sector, such as a pricing promotion use case in travel, we looked to see if it could be applied in

other sectors, for example in retail. Where possible, we identified and analyzed multiple instances of individual use cases.

For each use case, we estimated the annual value potential of applying Al and other analytics across the entire economy. This value potential could be captured by companies and organizations themselves, in the form of increased profits, or by their customers, in the form of lower prices or higher quality. For use cases that involve increasing revenue, such as those in sales and marketing, we estimated the economy-wide value potential in terms of the increased potential productivity of sales and marketing expenditures, assuming that overall annual spend in the economy is fixed in a given year (rather than estimating the impact of higher revenues, which would have assumed that overall spending would increase). Our estimates are based on the structure of the global economy in 2016. We did not estimate the value potential of creating entirely new product or service categories, such as autonomous driving.

Our library of use cases, while extensive, is not exhaustive, and thus it may overstate or understate the potential for certain sectors. We realize it may also contain some biases based on the business profile of clients. Our library of examples is a living one and we will continue refining and adding to it.

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

7

using remote on-board diagnostics to anticipate the need for service could theoretically generate value of 1 to 2 percent of total sales. In a case involving cargo aircraft, Al can extend the life of the plane beyond what is possible using traditional analytic techniques by combining plane model data, maintenance history, loT sensor data such as anomaly detection on engine vibration data, and images and video of engine condition.

Al-driven logistics optimization can reduce costs through real-time forecasts and behavioral coaching. Application of Al techniques such as continuous estimation to logistics can add substantial value across many sectors. Al can optimize routing of delivery traffic, thereby improving fuel efficiency and reducing delivery times. One European trucking company has reduced fuel costs by 15 percent, for example. By using sensors that monitor both vehicle performance and driver behavior, drivers receive real-time coaching, including when to speed up or slow down, optimizing fuel consumption and reducing maintenance costs. In another example, an airline uses Al to predict congestion and weather-related problems in order to avoid costly cancellations. For an airline with 100,000 flights per day, a 1 percent reduction in cancellations can make a material difference

Al can be a valuable tool for customer service management and personalized marketing. Improved speech recognition in call center management and call routing by applying Al techniques allow a more seamless experience for customers-and more efficient processing. The capabilities go beyond words alone. For example, deep learning analysis of audio allows systems to assess customers' emotional tone; if a customer is responding negatively to an automated system, the call can be rerouted to human operators and managers. In other areas of marketing and sales, Al techniques can also have a significant impact. "Next product to buy" recommendations that target individual customers-as companies such as Amazon and Netflix have successfully implemented-can lead to a substantial increase in the rate of sales conversions. Individual pricing and promotion also has a broad application across sectors. For example, in auto insurance, premiums can be customized based on data about driving patterns and distances driven. In one use case, a travel company that micro-segmented customers built a 360-degree customer view and offered additional services, such as hotels and airlines, using a recommender system algorithm trained on product and customer data. This led to a 10 to 15 percent increase in ancillary revenue. In retail, Al can use SKU-performance data to optimize weekly and thematic product promotions, including giving daily promotional recommendations.

## MAPPING ANALYTICS TECHNIQUES TO USE CASES

For each use case, we catalogued the specific analytical techniques that could be applied, including traditional analytics techniques, and various forms of machine learning, including deep learning. We found that the applicability of different techniques varied across sectors and business functions. Exhibits 3 and 4 are heatmaps that show the extent to which applicable techniques can be used by industry and function, based on our library of use cases. A select set of traditional techniques, including clustering, regression, and tree- based models, are broadly applicable across many industries and functions. Similarly, the more advanced Al techniques, such as RNNs, CNNs, and feed forward neural networks, are relevant in many of the same industries and functions. The variations in the heat maps relate to the different types of problems to be solved in the use cases, and the most applicable techniques with which to do that.

8

Mckinsey Global Institute

2. Insights from use cases

Exhibit 3



||Focus of report|||||||||Traditional analytics techniques|||||||||
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
||Reinforcement|learning|Feed forward
networks|Recurrent neural
networks||Convolutional neural
networks||Generative|adversarial networks|Tree-based ensemble
learning|Dimensionality
reduction|Classifiers|Clustering|Regression analysis|Statistical inference|Monte Carlo|Markov processes|Other optimization|
|Advanced electronics/ semiconductors|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|:unselected:|:unselected:|:unselected:||:unselected:|:unselected:|||
|Aerospace and defense|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|||
|Agriculture|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|||
|Automotive and assembly|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:||
|Banking|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:||
|Basic materials|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:||
|Chemicals|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:||
|Consumer packaged goods|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:||
|Health-care systems and services|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:||
|High tech|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:||||:unselected:|:unselected:|:unselected:|:unselected:||
|Insurance|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:||:unselected:||:unselected:|:unselected:|:unselected:|:unselected:||
|Media and entertainment|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:||:unselected:||:unselected:|:unselected:|:unselected:|:unselected:||
|Oil and gas|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|||||:unselected:|:unselected:|:unselected:||
|Pharmaceuticals and medical products|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|||||:unselected:|:unselected:|:unselected:||
|Public and social sector|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:||||||:unselected:|||
|Retail|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|||||||||
|Telecommunications|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|||||||||
|Transport and logistics|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|||||||||
|Travel|:unselected:||:unselected:||:unselected:|:unselected:|||:unselected:|:unselected:|||||||||


## Heat map: Technique relevance to industries

Number of use cases

Low

High

Exhibit 4



||Focus of report|||||Traditional analytics techniques|||||||||
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
||Reinforcement
learning|Feed forward
networks|Recurrent neural
networks|Convolutional neural
networks|adversarial networks
Generative|Tree-based ensemble
learning|Dimensionality
reduction|Classifiers|Clustering|Regression analysis|Statistical inference|Monte Carlo|Markov processes|Other optimization|
|Finance and IT|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|
|Human resources|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|
|Marketing and sales|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|
|Other operations|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|
|Product development|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|
|Risk|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|
|Service operations|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|
|Strategy and corporate finance|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|
|Supply-chain manage- ment and manufacturing|:unselected:|:selected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:|


## Heat map: Technique relevance to functions

Number of use cases

Low

High

10

Mckinsey Global Institute

2. Insights from use cases

We have also collected individual use cases into broader "domains" that address closely related problems. For example, the predictive maintenance domain aggregates use cases from across multiple sectors and types of machinery in which the use of analytics and Al can help to identify when repairs can be made to prevent a piece of equipment from breaking down (Exhibit 5).

Overall, a deep understanding of use cases and how they are associated with particular problem types, analytical techniques, and data types can help guide organizations regarding where to invest in the technical capabilities and data that will provide the greatest impact.

## Use case mapping to data types

Number of use cases

Low

High



|Use case domains|Structured/ semi- structured|Time series|Text|Audio|Video|Image|
|---|---|---|---|---|---|---|
|Analytics-driven accounting and IT|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:||
|Analytics-driven hiring and retention|:unselected:|:unselected:|:unselected:|:unselected:|:unselected:||
|Channel management|:unselected:|:unselected:|||||
|Churn reduction|:unselected:|:unselected:|||||
|Customer acquisition/lead generation|:unselected:|:unselected:|||||
|Customer service management|:unselected:|:unselected:|||||
|Fraud and debt analytics|:unselected:||||||
|Inventory and parts optimization|:unselected:|:unselected:|||||
|Logistics network and warehouse optimization|:unselected:||||||
|Marketing budget allocation|:unselected:||||||
|Next product to buy/individualized offering|:unselected:||||||
|Predictive maintenance|:unselected:||||||
|Predictive service/intervention|||||||
|Pricing and promotion|:unselected:||||||
|Procurement and spend analytics|:unselected:||||||
|Product development cycle optimization|:unselected:||||||
|Product feature optimization|:unselected:||||||
|Risk modeling|:unselected:||||||
|Sales and demand forecasting|:unselected:||||||
|Smart capital expenditures|:unselected:||||||
|Task automation|:unselected:||||||
|Workforce productivity and efficiency|:unselected:||||||
|Yield optimization|:unselected:||||||


TWO-THIRDS OF THE OPPORTUNITIES TO USE AI ARE IN IMPROVING THE PERFORMANCE OF EXISTING ANALYTICS USE CASES

In 69 percent of the use cases we studied, deep neural networks can be used to improve performance beyond that provided by other analytic techniques. Cases in which only neural networks can be used, which we refer to here as "greenfield" cases, constituted just 16 percent of the total. For the remaining 15 percent, artificial neural networks provided limited additional performance over other analytics techniques, among other reasons because of data limitations that made these cases unsuitable for deep learning.

Greenfield Al solutions are prevalent in business areas such as customer service management, as well as among some industries in which the data are rich and voluminous and at times integrate human reactions. A key differentiator that often underpins higher Al value potential is the possibility of applying large amounts of audio, video, image, and text data to these problems. Among industries, we found many greenfield use cases in health care, in particular. Some of these cases involve disease diagnosis and improved care, and rely on rich data sets incorporating image and video inputs, including from MRIs.

On average, our use cases suggest that modern deep learning Al techniques have the potential to provide a boost in value above and beyond traditional analytics techniques ranging from 30 percent to 128 percent, depending on industry (Exhibit 6).

In many of our use cases, however, traditional analytics and machine learning techniques continue to underpin a large percentage of the value creation potential in industries including insurance, pharmaceuticals and medical products, and telecommunications, with the potential of Al limited in certain contexts. In part this is due to the way data are used by those industries and to regulatory issues, as we discuss later in this paper.

DATA REQUIREMENTS FOR DEEP LEARNING ARE SUBSTANTIALLY GREATER THAN FOR OTHER ANALYTICS, IN TERMS OF BOTH VOLUME AND VARIETY

Making effective use of neural networks in most applications requires large labeled training data sets alongside access to sufficient computing infrastructure. As the size of the training data set increases, the performance of traditional techniques tends to plateau in many cases. However, the performance of advanced Al techniques using deep neural networks, configured and trained effectively, tends to increase. Furthermore, these deep learning techniques are particularly powerful in extracting patterns from complex, multi-dimensional data types such as images, video, and audio or speech. The data will need to be collected in a way that addresses society's concerns about issues of privacy.

## Data volume is essential for neural networks to achieve a high level of accuracy in training algorithms

Deep learning methods require thousands of data records for models to become relatively good at classification tasks and, in some cases, millions for them to perform at the level of humans. By one estimate, a supervised deep-learning algorithm will generally achieve acceptable performance with around 5,000 labeled examples per category and will match or exceed human level performance when trained with a data set containing at least 10 million labeled examples.7 In some cases in which advanced analytics is currently used, so much data are available-millions or even billions of rows per data set-that Al usage is the most appropriate technique. However, if a threshold of data volume is not reached, Al may not add value to traditional analytics techniques.

7 lan Goodfellow, Yoshua Bengio, and Aaron Courville, Deep learning, MIT Press, 2016.

12

Mckinsey Global Institute

2. Insights from use cases

Exhibit 6

## In more than two-thirds of our use cases, Al can improve performance beyond that provided by other analytics techniques

%

Breakdown of use cases by applicable techniques

Full value can be captured using non-Al techniques

15

Al necessary to capture value ("greenfield")

16

Al can improve performance over that provided by other analytics techniques

69

## Potential incremental value from Al over other analytics techniques

Travel

67



|Transport and logistics||
|---|---|
|Retail||
|Automotive and assembly||
|High tech||
|Oil and gas||
|Chemicals||
|Media and entertainment|57|
|Basic materials|56|
|Consumer packaged goods|55|
|Agriculture|55|
|Banking|50|
|Healthcare systems and services|44|
|Public and social sector|44|
|Telecommunications|44|
|Pharmaceuticals and medical products|39|
|Insurance|38|
|Advanced electronics/ semiconductors|36|
|Aerospace and defense|30|


128

89

87

85

85

79

Average = 62

NOTE: Numbers may not sum due to rounding.

SOURCE: McKinsey Global Institute analysis

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

13

These massive data sets can be difficult to obtain or create for many business use cases, and labeling remains a challenge. For example, teaching an autonomous vehicle to navigate urban traffic requires enormous image data sets in which all critical objects (other vehicles of all types, traffic signs, pedestrians, road markings, and so on) are labeled under all weather and lighting conditions. Most current Al models are trained through "supervised learning", which requires humans to label and categorize the underlying data. However promising new techniques are emerging to overcome these data bottlenecks, such as reinforcement learning, generative adversarial networks, transfer learning, and one-shot learning.8 Unlike reinforcement learning, in which systems learn to perform tasks by trial and error, one-shot learning allows a trained Al model to learn about a subject based on a small number of real- world demonstrations or examples-and sometimes just one.

Nonetheless, our research shows that almost three-quarters of the impact from advanced analytics is tied to use cases requiring millions of labeled data examples. This means that organizations will have to adopt and implement strategies that enable them to collect, integrate, and process data at scale. They will need to ensure that as much of their data as possible is captured electronically, typically by progressing in their overall digitization journeys. Even with large datasets, they will have to guard against "overfitting," in which a model too tightly matches the "noisy" or random features of the training set, resulting in a corresponding lack of accuracy in future performance, and against "underfitting," in which the model fails to capture all of the relevant features. Linking data across customer segments and channels and, where possible, to production data, rather than allowing different sets of data to languish in silos, is especially important to create value. To achieve this linkage, companies will need to create meta-data models, and manage both the internal challenges as well as the regulatory risks of sharing the data across a range of business functions.

Realizing Al's full potential requires a diverse range of data types including images, video, and audio

Neural Al techniques excel at analyzing image, video, and audio data types because of their complex, multi-dimensional nature, known by practitioners as "high dimensionality." Just a single training instance can have many different features, often requiring multiple levels of analysis. These systems can thus require orders of magnitude more training data than other machine learning systems with lower dimensionality data.

However, while images, video, and audio data are particularly well-suited for use with modern deep learning techniques, even more value can be extracted from mining insights from traditional structured and time series data types. Exhibit 7 highlights the range of value from our use cases based on the types of data used.

In the past few years, advances in deep learning have pushed Al-driven image classification tasks beyond human performance in some cases. An image of a face, for example, consists of thousands of pixels that can be combined to form eyes, ears, and other features. When arranged in the right way, they form the face of a specific person. Neural networks are good at dealing with high dimensionality, as multiple layers in a network can learn to represent the many different features present in the data. Thus, for facial recognition, the first layer in the network could focus on raw pixels, the next on edges and lines, another on generic facial features, and the final layer might identify the face. Unlike previous generations of Al, which often required human expertise to do "feature engineering," these neural network techniques are often able to learn to represent these features in their simulated neural networks as part of the training process.

8 Michael Chui, James Manyika, and Mehdi Miremadi, "What Al can and can't do (yet) for your business," Mckinsey Quarterly, January 2018; Matthew Hutson, "The future of Al depends on a huge workforce of human teachers," Bloomberg Businessweek, September 7, 2017.

14

Mckinsey Global Institute

2. Insights from use cases

An example of the progress that has been made can be found in the results of the annual ImageNet Large Scale Visual Recognition Challenge (Exhibit 8).9 Since 2010 machine learning researchers have competed by submitting algorithms for detecting objects within a public database of 14 million labeled images. The increase in accuracy observed in 2012 is widely considered the harbinger of the deep learning revolution; for the first time, a deep neural net was used to address the problem and showed dramatic improvement over previous efforts. The accuracy of the best-performing algorithms (all now using deep learning) now exceeds "human level performance"-the accuracy level expected of a human performing the same task.

Exhibit 7

## Range of potential Al value impact by data type

% of total value potential

:unselected: Range

Structured

55-94

Time series

50-83

Data type

Image

Video

25-42

17-30

Text

16-26

Audio

7-13

## Exhibit 8

The ability of Al systems to recognize objects has improved markedly to the point where the best systems now exceed human performance

Accuracy %

100

Best Al system Human performance

95

90

85

80

75

70

0

2010

11

12

13

14

15

16

2017

SOURCE: ImageNet Large Scale Visual Recognition Challenge; Mckinsey Global Institute analysis

9 Olga Russakovsky et al., "ImageNet Large Scale Visual Recognition Challenge," International Journal of Computer Vision, volume 115, issue 3, December 2015.

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

15

These increases in performance using deep learning techniques enabled many of the consumer products we already take for granted, including services such as Siri, Alexa, and Cortana. Improved image-processing technology underpins some of the capabilities that are being tested in self-driving cars today.

Ongoing data acquisition for retraining Al systems is necessary; one out of three use cases requires model refreshes at least monthly and sometimes daily An analysis of our use cases shows that, along with issues around the volume and variety of data, velocity is also a requirement: Al techniques require models to be retrained to match potential changing conditions, so the training data must be refreshed frequently. In one-third of the cases, the model needs to be refreshed at least monthly, and almost one in four cases requires a daily refresh; this is especially true in marketing and sales and in supply-chain management and manufacturing (Exhibit 9).

## Exhibit 9

For about one-third of use cases, the models require frequent updating: three-quarters of those cases require monthly refreshes, while nearly one-quarter are at least weekly

Share of use cases

## Frequency of refresh required

At least monthly refreshes 77

23

34

66

Less frequent refreshes

:selected: At least monthly

:selected: At least weekly

NOTE: Numbers may not sum due to rounding.

SOURCE: Mckinsey Global Institute analysis

16

Mckinsey Global Institute

2. Insights from use cases

## 3. SIZING THE POTENTIAL VALUE OF AI

An analysis of the value derived from our use cases suggests that Al can generate considerable value. We estimate that the Al techniques we cite in this report-feed forward neural networks and convolutional neural networks-together have the potential to create between $3.5 trillion and $5.8 trillion in value annually across nine business functions in 19 industries. The value as measured by percentage of industry revenue varies significantly among industries, depending on the specific applicable use cases, the availability of abundant and complex data, and regulatory and other constraints. While we found patterns in the potential of Al to create value within industries and functions, every company will need to look at the details of its business to estimate the opportunities to create value enabled by Al.

AI COULD POTENTIALLY CREATE $3.5 TRILLION TO $5.8 TRILLION IN ANNUAL VALUE IN THE GLOBAL ECONOMY

We estimated a range of annual value to the global economy for both Al and other analytics techniques, based on the value we observed being created in current use cases and the potential value in projected future ones. The total annual value potential of Al alone across 19 industries and nine business functions in the global economy came to between $3.5 trillion and $5.8 trillion. This constitutes about 40 percent of the overall $9.5 trillion to $15.4 trillion annual impact that could potentially be enabled by all analytical techniques (Exhibit 10).

Per industry, we estimate that Al's potential value amounts to between 1 and 9 percent of 2016 revenue. Even the industry with the smallest potential value at stake, aerospace and defense (less than $50 billion) could enable the annual creation of value that is equivalent to the GDP of Lebanon.

These figures are not forecasts for a particular period in time, but they are indicative of the considerable potential for the global economy that advanced analytics represents. The percentage of this potential that individual organizations, sectors, and functions can achieve will be the product of competitive and market dynamics, as well as of many choices and decisions-and indeed business model choices-by organizations and others. They include the developers of technology, policy makers who set the overall context, and customers who choose what to purchase. Some of this value will be captured in a variety of ways, for example it may result in more valued products and services, revenue growth, cost savings, or indeed consumer surplus. While the aggregate numbers may appear modest, in some use cases the advancements amount to radical transformation.

For Al to realize a substantial portion of the potential value we have estimated will require companies to deploy these techniques comprehensively in areas where they can most effectively harness their ability to make the complexity of data an advantage. Take the travel industry (by which we refer to all aspects of commercial passenger travel, from travel agents and airlines to hotels and online providers), in which the potential Al impact can more than double what is achievable using traditional analytic methods, amounting to between 7 and almost 12 percent of total revenue for the industry. To achieve that potential will require Al deployment in top-line revenue-related marketing and sales use cases, and bottom-line operations use cases, where in both cases the data are rich and the value of each incremental percentage point performance increase is significant. As an example of one single Al use case of the many that would be required for this industry to achieve its full potential, Hawaii's state tourism authority, working with a major online travel company, uses facial recognition software to monitor travelers' expressions through their computer webcams and deliver personalized offers.10

10 The Hawai'i tourism authority and Expedia Media Solutions use custom-built facial recognition software to create personalized travel marketing campaign, Expedia Group, press release, September 26, 2016.

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

17

Exhibit 10

Al has the potential to create annual value across sectors totaling $3.5 trillion to $5.8 trillion, or 40 percent of the overall potential impact from all analytics techniques

Al impact $ billion

700

600

·- Retail

Transport

500

and logistics

Public and social sector

400

:selected:

Consumer

Health-care systems and services

Automotive

300

Banking

packaged goods

and assembly

Advanced electronics/ semiconductors

High tech

-Basic materials

200

Insurance

Agriculture

:unselected:

-Oil and gas

Telecommunications

-Chemicals

100

Aerospace

Pharmaceuticals

Media and

and defense.

and medical products

0

entertainment

0

20

25

30

35

40

45

50

Travel

55

60

Al impact as % of total impact derived from analytics

## Aggregate dollar impact ($ trillion)

Impact as % of industry revenues



|Retail||||0.4-0.8|3.2-5.7|||
|---|---|---|---|---|---|---|---|
|Transport and logistics||||0.4-0.5|4.9-6.4|||
|Travel|||0.3-0.5||||7.2-11.6|
|Consumer packaged goods||0.2-0.5|||2.5-4.9|||
|Public and social sector|||0.3-0.4||1.1-1.4|||
|Automotive and assembly|||0.3-0.4||2.6-4.0|||
|Health-care systems and services||0.2-0.3|||2.9-3.7|||
|Banking||0.2-0.3|||2.5-5.2|||
|Advanced electronics/semiconductors||0.2-0.3|||3.3-5.3|||
|Basic materials||0.2-0.3|||1.6-3.1|||
|High tech||0.2-0.3|||||5.7-10.2|
|Oil and gas||0.2-0.2|||1.8-1.9|||
|Insurance|0.1-0.3||||3.2-7.1|||
|Agriculture|0.1-0.2||||2.4-3.7|||
|Chemicals|0.1-0.2||||1.0-2.3|||
|Media and entertainment|0.1-0.2||||2.9-6.9|||
|Telecommunications|0.1-0.2||||2.9-6.3|||
|Pharmaceuticals and medical products|0.1-0.1||||4.2-6.1|||
|Aerospace and defense|<0.1T||||1.8-3.2|||
|NOTE: Artificial Intelligence here includes neural networks only. Numbers may not sum due to rounding.||||||||
|SOURCE: Mckinsey Global Institute analysis||||||||


18

Mckinsey Global Institute

3. Sizing the potential value of Al

By contrast, as a percentage of overall revenues, the potential annual value of the Al use cases we identified in telecommunications is between about 3 and 6 percent of industry revenue (still amounting to over $100 billion in potential annual impact). While telecommunications operators have a large volume of customer data, much of that data is in structured forms for which firms can just as easily use more conventional analytics and machine learning techniques to leverage that data. The public sector also has a large volume of data, and a range of data types and use cases that make it a ripe area for Al applications. However, regulations and requirements for data privacy and interpretability, particularly in developed markets, present significant challenges to its use, and thus constrain the value potential.

Even with those caveats, industries for which we have estimated lower Al impact in terms of percentages of overall revenue compared with other sectors, such as aerospace, defense, and the public sector, nonetheless have the potential to create billions or even hundreds of billions of dollars of value from its deployment where appropriate. A key benefit of this exercise across industries is to provide executives and leaders in each industry with a perspective for where the largest potential opportunities lie. This will help them set priorities as well as identifying where they can benefit from Al.

THE BIGGEST VALUE OPPORTUNITIES FOR AI ARE IN MARKETING AND SALES AND IN SUPPLY-CHAIN MANAGEMENT AND MANUFACTURING

From the use cases we have examined, we find that the greatest potential value impact from using Al are both in top-line-oriented functions, such as marketing and sales, and in bottom- line-oriented operational functions, including supply-chain management and manufacturing (Exhibit 11). At a company level, every firm will need to examine its mix of functions to find the most attractive opportunities to use Al, and determine where it makes most sense to invest in Al deployment.

From the analysis of our use cases we can see broad applications of Al in marketing and sales across industries including consumer packaged goods, banking, retail, telecommunications, high tech, travel, insurance, and media and entertainment. Indeed, marketing and sales and supply-chain management together constitute some of the biggest areas of opportunity for Al (Exhibit 12). As noted earlier, Al is a powerful tool for personalizing product recommendations including through analyzing aggregated user data to understand individual customer preferences. Companies will nonetheless still need to think through business models that involve data use in such cases.

Consumer industries such as retail and high tech will tend to see more potential from marketing and sales Al applications because frequent and digital interactions between business and customers generate larger data sets for Al techniques to tap into. E-commerce platforms, in particular, stand to benefit. This is because of the ease with which these platforms collect customer information, such as click data or time spent on a web page, and can then customize promotions, prices, and products for each customer dynamically and in real time. For their part, brick-and-mortar retailers can implement Al applications to improve product assortment and inventory management per store, and to optimize their supply chains end-to-end. Indeed, they can take advantage of the Internet of Things to generate data usable by Al techniques to both improve the performance of their supply chains and apply some of the top-line innovations from the online world to the offline world, for example, by viewing dwell time in front of a physical display as analogous to spending more time viewing web or mobile content.11

11 See The Internet of Things: Mapping the value beyond the hype, Mckinsey Global Institute, June 2015.

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

19

Exhibit 11

## Al's potential impact is greatest in marketing and sales and supply-chain management and manufacturing, based on our use cases

Value potential $ trillion

Marketing and sales 3.3-6.0

1.4-2.6

Value potential

By all analytics (darker color) $9.5 trillion-15.4 trillion

By Al (lighter color) $3.5 trillion-5.8 trillion

Risk

0.5-0.9

0.2

Finance and IT

0.2

HR

0.2

0.1

0.1

Supply-chain management and manufacturing 3.6-5.6

0.6

1.2-2.0

0.3

0.3

0.2

0.1

0.9-1.3

<0.1

Service operations

Product development

Strategy and corporate finance

0.2-0.4

NOTE: Numbers may not sum due to rounding.

SOURCE: Mckinsey Global Institute analysis

20

Other operations

Mckinsey Global Institute

3. Sizing the potential value of Al

Exhibit 12

## Marketing and sales and supply-chain management and manufacturing are among the functions where Al can create the most incremental value

Highest potential impact business problems per functional area Impact size comparison by chart area) $ trillion

Marketing and sales

Supply-chain management and manufacturing

Other



|Customer service management 0.4-0.8|Next product to buy (NPTB) individual- ized offering 0.3-0.5|Price and promotion 0.3-0.5|Predictive maintenance 0.5-0.7|Yield optimization 0.3-0.6|Workforce productivity and efficiency 0.1-0.2||Predictive service/ interven- tion 0.2|
|---|---|---|---|---|---|---|---|
||||||Task automation 0.1-0.2||Product develop- ment cycle 0.1|
||||||Fraud and debt analy- tics|Risk 0.1|Product feature optimiza- tion <0.1|
|||||||||


Customer acquisition/ lead generation 0.1-0.3

Churn reduction 0.1-0.2

Channel manage- ment 0.1-0.2

Procurement and spend analytics 0.1-0.2

0.1

0.1

Inventory and parts optimization 0.1-0.2

Marketing budget allocation

Logistics network and warehouse optimization

NOTE: Numbers may not sum due to rounding.

SOURCE: Mckinsey Global Institute analysis

0.1

Analytics- driven accounting and IT 0.1-0.2

0.1

Sales and demand forecast

Smart capex <0.1

Analytics- driven HR 0.1

In our use cases, for example, we found that using real-time data to predict hyper- regional demand trends can increase sales by 0.25 percent to 0.75 percent, with margin improvements from lower waste and spoilage amounting to as much as half of one percentage point of sales. The impact can be considerably larger in pharmaceutical and medical products, in which predicting hyper-regional product demand and relevant health trends to inform inventory levels and reduce spoilage has the potential to raise sales by 5 to 10 percent.

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

21

Al's ability to conduct preventive maintenance and field force scheduling, as well as optimizing production and assembly processes, means that it also has considerable application possibilities and value potential across sectors including advanced electronics and semiconductors, automotive and assembly, chemicals, basic materials, transportation and logistics, oil and gas, pharmaceuticals and medical products, aerospace and defense, agriculture, and consumer packaged goods. In advanced electronics and semiconductors, for example, harnessing data to adjust production and supply-chain operations can minimize spending on utilities and raw materials, cutting overall production costs by 5 to 10 percent in our use cases.

THE OPPORTUNITIES TO CREATE VALUE WITH AI CORRESPOND TO THE VALUE DRIVERS WITHIN INDUSTRIES

Identifying the opportunity for Al deployment depends on a range of factors that are specific to individual sectors and, within those sectors, to different types of businesses. Given the wide range of applicability of Al techniques, broadly speaking, if you want to know where Al can create the most value, you need to follow the money. For industries in which the main drivers of value are related to marketing and sales, including many consumer-facing industries, that is where the greatest value from deploying Al can be found. However, for industries in which the key driver of value is operational excellence, such as in advanced manufacturing and oil and gas, functions such as supply chain and manufacturing are those in which Al can create the most value.

It is instructive to compare industry sectors in terms of where Al has the greatest value potential. A detailed breakdown by sector is available on our interactive chart online. Here, by way of illustration, we take a snapshot of three sectors-retail, consumer packaged goods, and banking-where we have seen Al's impact (Exhibits 13-15). In retail, marketing and sales is the area with the most significant potential value from Al, and within that function, pricing and promotion and customer service management are the main value areas. Our use cases show that using customer data to personalize promotions, for example, including tailoring individual offers every day, can lead to a 1 to 2 percent increase in incremental sales for brick-and-mortar retailers alone. In packaged goods, supply- chain management is the key function that could benefit from Al deployment. Among the examples in our use cases, we see how forecasting based on underlying causal drivers of demand rather than prior outcomes can improve forecasting accuracy by 10 to 20 percent, which translates into a potential 5 percent reduction in inventory costs and revenue increases of 2 to 3 percent. In banking, particularly retail banking, Al has significant value potential in marketing and sales, much as it does in retail. Although the banking industry has been among the fastest to adopt Al and capture the value in risk management, the benefits could be even greater for other industries. For example, Al is helping insurers price risk more accurately, pharmaceutical companies are using Al to reduce risk in clinical trials, and mining firms have deployed the technologies to anticipate disruptions to production.

22

Mckinsey Global Institute

3. Sizing the potential value of Al

Exhibit 13

In retail, Al has the most potential impact in pricing and promotion and other marketing and sales areas

Retail examples $ trillion

Product development

Strategy and corporate finance

<0.05

Other operations 0.1-0.2

<0.05

Marketing and sales 0.3-0.5

Pricing and promotion 0.1-0.2

Customer service management ~0.1

Next product

to buy

<0.05

Finance and IT <0.05

HR <0.05

~0.1

Supply-chain management and manufacturing

Logistics network

Customer acquisition and generation <0.1

Task automation 0.1-0.2

Inventory and parts optimization <0.1

<0.05

<0.05

<0.05

<0.05 <0.05

<0.05

<0.05

Marketing budget

Workplace Analytics-driven Analytics-driven productivity accounting and IT hiring and retention allocation and efficiency

Product feature corporate finance

Strategy and

optimization

NOTE: Numbers may not sum due to rounding. Not to scale.

SOURCE: Mckinsey Global Institute analysis

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

23

Exhibit 14

In consumer packaged goods, Al's greatest potential is in supply-chain management and manufacturing, including predictive maintenance

Packaged goods examples $ trillion

Supply-chain management and manufacturing 0.2-0.3

Marketing and sales ~0.1

Product develop- ment 0.05

HR <0.05

Other opera- tions <0.05

Finance and IT <0.05

Procurement and Marketing budget Product development spend analytics allocation cycle optimization

Analytics-driven hiring and retention



|Predictive maintenance ~0.1|Yield optimization <0.1|<0.05|Channel manage- ment <0.05|0.05|<0.05|<0.05|
|---|---|---|---|---|---|---|
|Inventory and parts optimization ~0.1|<0.05|<0.05||<0.05|<0.05|<0.05|


Sales and demand forecasting

Logistics network and warehouse optimization

Pricing and promotion

NOTE: Numbers may not sum due to rounding. Not to scale.

SOURCE: Mckinsey Global Institute analysis

Analytics-driven Other accounting and IT operations

As our library of use cases evolves, we expect to see significant value in some areas that is not fully captured in these figures. One example is risk in banking. We believe that this could be one of the biggest areas of impact for deep learning using neural networks. For example, incorporating Al into underwriting models could allow banks to underwrite entirely new types of customers, such as the unbanked or semi-banked, and capture significant value through improved fraud detection. The application of neural network techniques to these new use cases in risk will need to be further tested before we can size the impact.

24

Mckinsey Global Institute

3. Sizing the potential value of Al

Exhibit 15

## In banking, marketing and sales and risk are among the areas with the most potential value from Al

Banking example $ trillion

Marketing and sales 0.1-0.2

Risk 0-0.1

Finance and IT <0.05

Other operations <0.05

HR <0.05



|Channel management 0.1|Customer service management 0-0.1|Customer acquisition/ lead generation <0.05|Fraud and debt analytics 0-0.1|||
|---|---|---|---|---|---|
|||Next product to buy (NPTB) <0.05|Analytics- driven finance|Analytics- driven hiring|Workforce productivity|
||Churn reduction 0.05|Pricing and promotion <0.05|and IT <0.05|and retention <0.05|and efficiency <0.05|


NOTE: Numbers may not sum due to rounding. Not to scale.

SOURCE: Mckinsey Global Institute analysis

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

25

4. THE ROAD TO IMPACT AND VALUE

Artificial intelligence is attracting growing amounts of corporate investment, and as the technologies develop, the potential value that can be unlocked is likely to grow. So far, however, only a few pioneering firms have adopted Al at scale. Prior research suggests that even among Al-aware firms, only about 20 percent are using one or more of the technologies in a core business process or at scale.12 For all their promise, Al technologies have plenty of limitations that will need to be overcome, including not just data-related issues but also regulatory obstacles, and social and user acceptance. Yet the potential value to be harnessed provides a clear incentive for technology developers, companies, policy-makers, and users to try to tackle these issues.

WHILE AI IS PROMISING, ITS USE STILL FACES LIMITATIONS AND CHALLENGES As discussed, factors that could limit Al use include the requirements around the volume, type, and labeling of data. Other limitations are also significant, for now, although the evolving technologies themselves are starting to provide some solutions.

Limitations include the need for massive data sets, difficulties in explaining results, generalizing learning, and potential bias in data and algorithms Among the limitations we have identified, five stand out.13 First is the challenge of labeling training data, which often must be done manually and is necessary for supervised learning. Ironically, machine learning often requires large amounts of manual effort; in supervised learning, the set of machine learning techniques that is most often used, machines are taught; they don't learn "by themselves." Promising new techniques are emerging to address this challenge, such as reinforcement learning (discussed earlier) and in-stream supervision, in which data can be labeled in the course of natural usage.14 Second is the difficulty of obtaining data sets that are sufficiently large and comprehensive to be used for training; for many business use cases, creating or obtaining such massive data sets can be difficult-for example, limited clinical-trial data to predict health-care treatment outcomes more accurately. Third is the difficulty of explaining in human terms results from large and complex models: why was a certain decision reached? Product certifications in health care, as well as in the automotive, chemicals, and aerospace industries, for example, can be an obstacle; among other constraints, regulators often want rules and choice criteria to be clearly explainable. Some nascent approaches to increasing model transparency, including local-interpretable-model-agnostic explanations (LIME), may help resolve this explanation challenge in many cases.15 Fourth is the generalizability of learning: Al models continue to have difficulties in carrying their experiences from one set of circumstances to another. That means companies must commit resources to train new models even for use cases that are similar to previous ones. Transfer learning-in which an Al model is trained to accomplish a certain task and then quickly applies that learning to a similar but distinct activity, is one promising response to this challenge.16

The fifth limitation concerns the risk of bias in data and algorithms. Unlike the other limitations listed, which may eventually be resolved by technical advances, this issue of bias touches on concerns that are more social in nature and which could require broader steps to resolve, such as understanding how the processes used to collect training data can

12 Ibid. Mckinsey Global institute, Artificial intelligence, June 2017.

13 Ibid. Michael Chui, James Manyika, and Mehdi Miremadi, "What Al can and can't do (yet) for your business," Mckinsey Quarterly, January 2018.

14 Eric Horvitz, "Machine learning, reasoning, and intelligence in daily life: Directions and challenges," Proceedings of Artificial Intelligence Techniques for Ambient Intelligence, Hyderabad, India, January 2007. 15 LIME attempts to identify which parts of input data a trained model relies on most to make predictions.

16 For an early example application, see John Guttag, Eric Horvitz, and Jenna Wiens, "A study in transfer learning: Leveraging data from multiple hospitals to enhance hospital-specific predictions," Journal of the American Medical Informatics Association, volume 21, number 4, 2014.

26

McKinsey Global Institute

4. The road to impact and value

influence the behavior of models they are used to train. In certain instances, when applied incorrectly, Al models risk perpetuating existing social and cultural biases. For example, unintended biases can be introduced when training data are not representative of the larger population to which an Al model is applied. Thus, data collected from a city-wide video camera network will likely show more instances of all kinds of signals, from crime to outdoor advertising engagements, in areas where the density of deployed cameras is higher, which might not be representative of the number of instances of these occurrences in a city as a whole. Similarly, facial recognition models trained on a population of faces corresponding to the demographics of artificial intelligence developers could struggle when applied to populations with more diverse characteristics.17

Moreover, a recent report on the malicious use of Al highlights a range of security threats, from sophisticated automation of hacking to hyper-personalized political disinformation campaigns.18 Among the risks it lists are threats associated with privacy invasion and social manipulation from the use of Al to automate tasks involved in surveillance, such as analyzing mass-collected data, persuasion, including creating targeted propaganda, and deception, for example with manipulated videos. Multiple research efforts are under way to identify best practices and address such issues in academic, non-profit, and private-sector research.

Organizational challenges around technology, processes, and people can slow or impede Al adoption

Organizations planning to adopt significant deep learning efforts will need to consider a spectrum of options about how to do so. The range of options includes building a complete in-house Al capability either gradually in an organic way or more rapidly through acquisitions, outsourcing these capabilities, or leveraging Al-as-a-service offerings.

Given the importance of data, it is vital for organizations to develop strategies for the creation and/or acquisition of training data. But the effective application of Al also requires organizations to address other key data challenges, including establishing effective data governance, defining ontologies, data engineering around the "pipes" from data sources, managing models over time, building the data pipes from Al insights to either human or machine actions, and managing regulatory constraints.

Given the significant computational requirements of deep learning, some organizations will maintain their own data centers, because of regulations or security concerns, but the capital expenditures could be considerable, particularly when using specialized hardware. Cloud vendors offer another option.

Process can also become an impediment to successful adoption unless organizations are digitally mature. On the technical side, organizations will have to develop robust data maintenance and governance processes, and implement modern software disciplines such as Agile and DevOps. Even more challenging, in terms of scale, is overcoming the "last mile" problem of making sure the superior insights provided by Al are instantiated in the behavior of the people and processes of an enterprise.

On the people front, much of the construction and optimization of deep neural networks remains something of an art requiring real experts to deliver step-change performance increases. Demand for these skills far outstrips supply at present; according to some estimates fewer than 10,000 people have the skills necessary to tackle serious Al problems

17 Joy Buolamwini and Timnit Gebru. "Gender shades: Intersectional accuracy disparities in commercial gender classification," Proceedings of Machine Learning Research, 2018. http://proceedings.mlr.press/v81/ buolamwini18a/buolamwini18a.pdf

18 Miles Brundage et al., The malicious use of artificial intelligence: Forecasting, prevention, and mitigation, Future of Humanity Institute, February 2018.

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

27

and competition for them is fierce amongst the tech giants.19 Companies wanting to build their own Al solutions will need to consider whether they have the capacity to attract and retain these specialized skills.

## Al can seem an elusive business case for now

Where Al techniques and data are available and the value is clearly proven, organizations can already pursue the opportunity. But in some areas, the techniques today may be mature and the data available, but the cost and complexity of deploying Al may simply not be worthwhile, given the value that could be generated. For example, an airline could use facial recognition and other biometric scanning technology to streamline aircraft boarding, but the value of doing so may not justify the cost and issues around privacy and personal identification. A recent Stanford University study found that deep neural networks can make highly accurate bond price predictions, but took hours to come up with the answer, whereas other "simpler" techniques produced an answer that was only slightly less accurate but very rapid-just four seconds.20 For a bond trader that timing difference is critical.

Similarly, we can see potential cases in which the data and the techniques are maturing, but the value is not yet clear. For example, in mining, Al could potentially play a significant role in providing ore body insights, thereby allowing for more efficient exploration, drilling, and mine planning. Given the high capital expenditure costs usually involved in this sector, the benefits could be very significant, but for now are unmeasurable. In other sectors, including banking, opportunities that may exist are sometimes in areas closely guarded as competitive secrets.

In the most unpredictable scenario of all, either the data (both the types and volume) or the techniques are simply too new and untested to know how much value they could unlock. For example, in health care, if Al could build on the superhuman precision we are already starting to see with X-ray analysis and broaden that to more accurate diagnoses and even automated medical procedures, the economic value could be very significant. At the same time, the complexities and costs of arriving at this frontier are also daunting. Among other issues, it would require flawless technical execution and resolving issues of malpractice insurance and other legal concerns.

## Societal concerns and regulations can constrain Al use

Societal concerns and regulations can affect potential value capture from Al, including in use cases related to personally identifiable information. This is particularly relevant at a time of growing public debate about the use and commercialization of individual data on some online platforms.21 Use and storage of personal information is especially sensitive in sectors such as banking, health care, and pharmaceutical and medical products, as well as in the public and social sector. Alongside these questions about privacy, issues of fairness and equity may arise from bias in data, as well as concerns about transparency and accountability in the use of massively complex algorithms. In addition to addressing these issues, businesses and other users of data for Al will need to continue to evolve business models related to data use in order to address societies' concerns. Furthermore, regulatory requirements and restrictions can differ from country to country, as well from sector to sector. In the European Union, for example, automated individual decision making-that is, algorithms that make decisions based on user-level predictors-will be shaped by the EU- wide general data protection regulation taking effect in 2018, which provides for a right to an explanation for some decisions made by machines. This could affect the insurance industry,

19 Cade Metz, "Tech giants are paying huge salaries for scarce Al talent," The New York Times, October 22, 2017.

20 "Neural networks face unexpected problems in analyzing financial data," MIT Technology Review, May 10, 2017.

21 Julia Angwin, Dragnet Nation: A quest for privacy, security, and freedom in a world of relentless surveillance, Times Books, 2014; see also Anna Bernasek and D. T. Mongan, All you can pay: How companies use our data to empty our wallets, Nation Books, 2015.

28

Mckinsey Global Institute

4. The road to impact and value

for example, in which underwriters could be required to explain how machines derived their answers about whether to underwrite the risk or explain why the premium was set at a certain level.

## IMPLICATIONS FOR STAKEHOLDERS

As we have seen, it is a company's ability to execute against Al models, rather than the models themselves, that creates value. In prior publications, we have detailed some of the general implications for companies as they adopt Al and analytics.22 In this final section, we sketch out some of the high-level implications of our study of Al use cases for providers of Al technology, appliers of Al technology, and policy makers who set the context for both.

## For Al technology provider companies

Many companies that develop or provide Al to others have considerable strength in the technology itself and the data scientists needed to make it work, but they can lack a deep understanding of end markets. This is a challenge, since our research has shown that most of the potential impact of Al comes from improving the performance in existing use cases-in other words, the fundamental drivers of the businesses of their potential customers. Furthermore, many of these companies are asking how they should prioritize their resources, whether it is R&D, marketing and sales, or other functions to take advantage of Al opportunities.

Understanding the value potential of Al across sectors and functions can help shape the portfolios of these Al technology companies. That said, they shouldn't necessarily only prioritize the areas of highest potential value. Instead, they can combine that data with complementary analyses of the competitor landscape, of their own existing strengths including technology and data strengths, their sector or function knowledge, and their customer relationships, to shape their investment portfolios.

On the technical side, the mapping of problem types and techniques to sectors and functions of potential value can guide a company with specific areas of expertise as to where to focus. Similarly, for technology companies that have access to certain types of data, this mapping can help guide them to where their access to data can provide them with the most leverage, and toward data gaps needing to be filled. Finally, more innovation is needed to continue to advance the frontier of Al and address some ongoing technical limitations.

For companies adopting Al to transform and power their own businesses Many companies seeking to adopt Al in their operations have started machine learning and Al experiments across their business-and are likely to be bombarded by technology companies trying to sell them "Al solutions." Before launching more pilots or testing solutions, it is useful to step back and take a holistic approach to the issue, moving to create a prioritized portfolio of initiatives across the enterprise, including Al and the wider analytic and digital techniques available. For a business leader to create an appropriate portfolio, it is important to develop an understanding about which use cases and domains have the potential to drive the most value for a company, as well as which Al and other analytical techniques will need to be deployed to capture that value. This portfolio ought to be informed not only by where the theoretical value can be captured, but by the question of how the techniques can be deployed at scale across the enterprise. The question of how analytical techniques are scaling is driven less by the techniques themselves and more by a company's skills, capabilities, and data. Companies will need to consider efforts on the "first mile," that is, how to acquire and organize data and efforts, as well as on the "last mile", or how to integrate the output of Al models into work flows, ranging from clinical trial managers and sales force managers to procurement officers. Previous MGI research suggests that

22 See for example, Artificial intelligence: The next digital frontier? Mckinsey Global Institute, June 2017 and The age of analytics: Competing in a data-driven world, Mckinsey Global Institute, December 2016.

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

29

Al leaders invest heavily in these first- and last-mile efforts.23 In addition, given growing user and societal concerns, companies deploying Al will need to think through their safe and responsible data use and the business models they employ that make use of the user or customer data.

For companies adopting Al to transform and power their own businesses Many companies seeking to adopt Al in their operations have started machine learning and Al experiments across their business-and are likely to be bombarded by technology companies trying to sell them "Al solutions." Before launching more pilots or testing solutions, it is useful to step back and take a holistic approach to the issue, moving to create a prioritized portfolio of initiatives across the enterprise, including Al and the wider analytic and digital techniques available. For a business leader to create an appropriate portfolio, it is important to develop an understanding about which use cases and domains have the potential to drive the most value for a company, as well as which Al and other analytical techniques will need to be deployed to capture that value. This portfolio ought to be informed not only by where the theoretical value can be captured, but by the question of how the techniques can be deployed at scale across the enterprise. The question of how analytical techniques are scaling is driven less by the techniques themselves and more by a company's skills, capabilities, and data. Companies will need to consider efforts on the "first mile," that is, how to acquire and organize data and efforts, as well as on the "last mile", or how to integrate the output of Al models into work flows, ranging from clinical trial managers and sales force managers to procurement officers. Previous MGI research suggests that

22 See for example, Artificial intelligence: The next digital frontier? Mckinsey Global Institute, June 2017 and The age of analytics: Competing in a data-driven world, Mckinsey Global Institute, December 2016.

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

29

Al leaders invest heavily in these first- and last-mile efforts.23 In addition, given growing user and societal concerns, companies deploying Al will need to think through their safe and responsible data use and the business models they employ that make use of the user or customer data.

Policy makers will need to strike a balance between supporting the development of Al technologies and managing any risks from bad actors, as well as irresponsible use of Al techniques and the data they employ. They have an interest in supporting broad adoption, since Al can lead to higher labor productivity, economic growth, and societal prosperity. Tools to help them include public investments in research and development as well as support for a variety of training programs, which can help nurture Al talent. On the issue of data, governments can spur the development of training data directly through open data initiatives. Opening up public-sector data can spur private-sector innovation. Setting common data standards can also help.

Al is also raising new questions for policy makers to grapple with for which historical tools and frameworks may not be adequate.24 Therefore, some policy innovations will likely be needed to cope with these rapidly evolving technologies. But given the scale of the beneficial impact on business, the economy, and society, the goal should not be to constrain the adoption and application of Al, but rather to encourage its beneficial and safe use.

The several hundred use cases we examined underscore the value and performance enhancement that adoption of Al technologies can bring, and provide some indication of where Al can most usefully be deployed. To capture that value, CEOs and other C-suite executives will need to ramp up and staff their analytics capabilities; as our use cases show, Al can most often be adopted and create value where other analytics methods and techniques are also creating value. For companies seeking to deploy Al, that means the same basics will need to be in place, especially moving forward on digitizing their enterprises. As we have seen, abundant volumes of rich data from images, audio, and video, and large-scale text are the essential starting point and lifeblood of creating value with Al. Above all, our analysis of use cases suggests that successful Al adoption will require focus and setting of priorities. Its value is tremendous-and looks set to become even more so as the technologies themselves advance. Identifying where and how that value can be captured looks likely to become one of the key business challenges of our era.

23 The age of analytics: Competing in a data-driven world, Mckinsey Global Institute, December 2016.

24 Bank risk management is one example. See Ignacio Crespo, Pankaj Kumar, Peter Noteboom, and Marc Taymans, The evolution of model risk management, Mckinsey & Company, February 2017.

30

Mckinsey Global Institute

4. The road to impact and value

ACKNOWLEDGMENTS

This discussion paper was produced as part of the Mckinsey Global Institute's research on the impact of technology on business and society, and specifically our on-going research program on the future of work and the potential effects on the global economy of data and analytics, automation, robotics, and artificial intelligence.

The research was led by Michael Chui, an MGI partner in San Francisco; James Manyika, chairman and director of the Mckinsey Global Institute and Mckinsey senior partner based in San Francisco; Mehdi Miremadi, a Mckinsey partner based in Chicago; and Nicolaus Henke, a Mckinsey senior partner in London who co-leads McKinsey Analytics and is chairman of Quantum Black, a Mckinsey company. Martin Harrysson, Martin McQuade, Roger Roberts, and Tamim Saleh helped guide the research. Rita Chung, Ira Chadha, and Sankalp Malhotra headed the working team, which comprised Ali Akhtar, Adib Ayay, and Pieter Nel.

We are grateful to colleagues within Mckinsey who provided valuable advice and analytical support: Luis Almeida, Ramnath Balasubramanian, Shubham Banerjee, Gaurav Batra, Harold Bauer, Michele Bertoncello, Patrick Briest, Bede Broome, Ondrej Burkacky, Mary Calam, Brian Carpizo, Michael Chen, Frank Coleman, Alex Cosmas, Reed Doucette, Carlos Fernandes, David Fiacco, Kevin Goering, Ben Goodier, Taras Gorishnyy, Pete Grove, Ludwig Hausmann, Michael van Hoey, Aaron Horowitz, Minha Hwang, Venkat Inumella, Pallav Jain, Harold Janin, Mithun Kamat, Matthias Klasser, Rohit Kumar, Shannon Lijek, Oskar Linqvist, Carl March, Brian McCarthy, Ryan McCullough, Doug McElhaney, Andres Meza, Jordi Monso, Sumit Mundra, Florian Neuhaus, Kris Otis, Naveen Sastry, Eric Schweikert, Jules Seeley, Richard Sellschop, Abdul Wahab Shaikh, Owen Stockdale, Chris Thomas, Jeffrey Thompson, Richard Ward, Kate Whittington, Georg Winkler, and Christoph Wollersheim.

We would like to thank Sandeep Gupta, Rajat Monga, and Martin Wicke of the Google Brain team for their input on some of the technical issues. We have also benefited greatly from the research of a range of leading practitioners and thinkers on Al and our dialogues with them, including on its limitations and the technical advances to address them. They include Jack Clark, strategy and communications director at OpenAI, Jeffrey Dean, lead of Google Brain, Barbara J. Grosz, Higgins Professor of Natural Sciences at Harvard University, Demis Hassabis, founder and CEO of DeepMind, Eric Horvitz, director of Microsoft Research Labs, Kai-Fu Lee, CEO of Sinovation Ventures, Fei-Fei Li, director of Stanford University's Artificial Intelligence Lab, and Andrew Ng, adjunct professor at Stanford University. We also would like to thank and acknowledge the insights of Jacomo Corbo, chief scientist, and other colleagues at Quantum Black, a Mckinsey company.

This discussion paper was edited and produced by MGI editorial director Peter Gumbel, editorial production manager Julie Philpot, and senior graphic designers Marisa Carder and Patrick White, and graphic design specialist Margo Shimasaki. Rebeca Robboy, MGI director of external communications, managed dissemination and publicity, while digital editor Lauren Meling provided support for online and social media treatments.

This report contributes to MGI's mission to help business and policy leaders understand the forces transforming the global economy, identify strategic locations, and prepare for the next wave of growth. As with all MGI research, this work is independent and has not been commissioned or sponsored in any way by any business, government, or other institution. While we are grateful for all the input we have received, the report is ours, including any errors. We welcome your comments on this research at MGI@mckinsey.com.

Mckinsey Global Institute

Notes from the Al frontier: Insights from hundreds of use cases

31

Mckinsey Global Institute April 2018 Copyright @ Mckinsey & Company www.mckinsey.com/mgi

:selected: @Mckinsey_MGI :selected: f MckinseyGlobalInstitute
