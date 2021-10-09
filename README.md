# Portfolio Optimization Using Python

I. **Why Portfolio ?**

Investing is one of the best things to do with the money which is left after all the necesaary expenses occured. It makes oneself financially independent, and not rely on the money of others in times of financial crisis.

So why do we need a Portfolio? Why don't we just find out simple on the net as to which company gives the best returns currently, and invest all our money into it ? Well, this strategy actually works quite well, but somehow it doesn't sound too safe, does it?

To put it plainly, when we invest in any company's stock, there are two types of risks associated with it:
1. **Systematic Risk** - This Risk is caused due to macroeconomic factors like inflation and stuff, which happens across the market segment i.e. the risk is inherent to the entire market. So minimizing these risks are just not in the hand of investor. That is why this risk is also called "Volatality Risk" or "Non-Diversifiable Risk".

2. **Unsystematic Risk**- Also known as "Diversifiable Risk", is the risk which corresponds to the internal affairs of a company or organization, lets say like resignation of some higher official of company, or riots of workers of the company etc. Minimizing the unsystematic risk is possible as well as necesaary before investing.

Hence it is not advisable to follow the startegy we came up with in the start of discussion, as investing all our money in the stock which is presently giving best returns is too risky because if some internal affair of the company occur, we might loose all our money. That is why making a Portfolio is a must, which represent a combination of financial instruments like stocks, bonds etc. of different companies, thereby nullifying the unsystematic part of the risk. Having a diverse portfolio would protect ivestor from any potential threat due to events which are company-specific.

II. ****Making a Portfolio**** - 

Now that we have decided to invest in a certain group of companies, we have to find out the best combination of weightages of each stock in our portfolio, to get best risk return combination. For this, the concept of Efficient Frontier is pivotal.
So initially, I took a hypothetical portfolio (not optimized yet) made out of FAANG group of companies:
1. Facebook
2. Apple
3. Amazon
4. Netflix
5. Google

Yeah, feeling rich (lol). So, initially taking the weightage of each stock to be equal (0.2 each) , we calcualted the daily returns received using this portfolio.
The data was extracted from **Yahoo Finance**, and we calculate the **Sharpe ratio** and **Volatility** also to compare effectively.

III. ****Portfolio Optimization**** - 

Now its time to get our hands dirty with **Machine Learning**. So to optimize, I made use of the library **PyPortfolioOpt** short for Python Portfolio Optimization. This is a very useful library which uses the concept of Efficient Frontier and maximizing Sharpe ratio, to return a list of modified weightages of the componenets of the portfolio. So with the modified weights, I calculated the Sharpe ratio, Expected Returns and Volataility again, to see how much have we optimized our Portfolio. 

IV. ****Mentions**** - 

I want to take this opportunity to thank **Prof. Gaurav Nagpal Sir**, off-campus faculty of BITS Pilani, under the guidance of whom, I did my project. It was really a great learning outcome for me and opened a new door of researching in the world of Finance. I also appreciate my mentor **Dr. Pranesh Bhargava Sir**, for constantly motivating me throughout the project.

