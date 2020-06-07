## About Me
I am a member of the Statistics Group in the Data Science and AI Research Organization at AT&T Labs.  I am interested in problems related to fairness and ethics in data science, data privatization, network modeling, model selection, and unsupervised learning.  I am also one of the organizers of the annual [AT&T Labs Graduate Student Symposium](http://stats.research.att.com/grad-symposium/).

I received by PhD in Statistics from New York University in 2014 under the supervision of Cliff Hurvich, Patrick Perry, and Jeff Simonoff.

Prior to that I received my BA in Economics and Mathematics from McGill University.

## Publications

Farias, V., Brito, F., Flynn, C., Machado, J., Majumdar, S., and Srivastava, D.  Local Dampening: Differential Privacy for Non-numeric Queries via Local Sensitivity.  Submitted, 2020.

Dodwell, E., Flynn, C., Krishnamurthy, B., Majumdar, S., and Mitra, R.  System to Integrate Fairness Transparently: An Industry Approach.  2020.

Flynn, C. and Perry, P. [Profile Likelihood Biclustering](https://projecteuclid.org/euclid.ejs/1580461237). Electronic Journal of Statistics, 14(1):731-768, 2020.

Li, R., Jian, J., Ju, C., Flynn, C., Hsu, W., Wang, J., Wang, W., and Xu, T. [Enhancing Response Generation Using Chat Flow Identification](https://jyunyu.csie.org/docs/pubs/kddcai2018paper.pdf). KDD Workshop on Conversational AI, 2018.

Xi, H., Machanavajjhala, A., Flynn, C., and Srivastava, D. [Composing Differential Privacy and Secure Computation: A case study on scaling private record linkage](https://arxiv.org/abs/1702.00535). In Proceedings of the ACM Conference on Computer and Communications Security, 2017.

Flynn, C., Hurvich, C., and Simonoff, J. S. [On the Sensitivity of the Lasso to the Number of Predictor Variables](https://projecteuclid.org/euclid.ss/1491465629). Statistical Science, 32(1): 88-105, 2017.

Flynn, C., Shirley, K., and Wang, W. [Deconstructing Domain Names to Reveal Latent Topics](https://ieeexplore.ieee.org/document/7796938). In Proceedings of the IEEE International Conference on Data Science and Advanced Analytics, 2016.

Flynn, C., Hurvich, C. M., and Simonoff, J. S. [Discussion: Deterioration of performance of the lasso with many predictors](https://journals.sagepub.com/doi/abs/10.1177/1471082X16642643). Statistical Modelling, 16:212-216, 2016.

Flynn, C., Hurvich, C., and Simonoff, J. [Efficiency for Regularization Parameter Selection in Penalized Likelihood Estimation of Misspecified Models](https://www.tandfonline.com/doi/abs/10.1080/01621459.2013.801775?journalCode=uasa20). Journal of the American Statistical Association, 108(503):1031-1043, 2013.

## Selected Projects

### Detecting and Mitigating Bias in Targeted Advertising

To support AT&T’s new advertising division, our team is developing checks that can be put in place to ensure that the targeted audience for an advertising campaign is not accidentally biased towards certain protected groups of consumers. This talk focuses on using disparate impact to measure discrimination in targeted advertising, and proposes an approach based on machine learning techniques that allow us to infer the relevant audience for a campaign from an initial targeted list provided by an advertiser. The inferred relevant audience can then be used to test for bias across different consumer groups. Our methods can also be used to expand the targeted audience in a way that will help mitigate any detected bias. These proactive steps support AT&T’s long-term commitment to the responsible use of customer information as well as maintaining a brand-safe environment for our advertising clients. 


### How May I Help You? Improving the Online Customer Experience Using Machine Learning

Digital care is a growing and important customer service channel that has the potential to reduce costs while increasing customer satisfaction by shortening wait times. These advantages are contingent on connecting the customer to the best agent to solve his/her problem. Thus, automatically understanding each customer’s contact reason is a key building block. In this talk we use topic model techniques to analyze AT&T’s online customer care chat data, where the chats in our data sample were routed to an initial agent using information such as the chat launch page URL, the customer’s navigation path on the AT&T webpage, and the customer’s chat menu guide selections. Our findings suggest that while a customer’s online activity reflects his/her self-initiated search path for answers, the customer’s true, detailed intent is not revealed until the conversation starts. To improve the customer routing process, we propose an adaptive procedure based on intent identification. In our approach, we first learn each agent group’s expertise from recent chat transcripts using scalable deep learning and topic modeling techniques. We then use these agent group profiles to align each customer’s intent with the correct agent group. We demonstrate the effectiveness of this approach using A/B test results and discuss future directions for intelligent digital care. 


