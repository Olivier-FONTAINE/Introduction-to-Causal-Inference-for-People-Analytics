# Introduction-to-Causal-Inference-for-People-Analytics

## Simpson paradox & Gender pay gap
To illustrate the Simpson paradox, I created a typical salary right skewed distribution from 4 salary normal distributions:
- Female non management (Number: 950 employees, Mean: 2,600 EUR, Standard deviation: 700 EUR) 
- Female management (Number: 50 employees, Mean: 4,200 EUR, Standard deviation: 1,000 EUR) 
- Male non management (Number: 750 employees, Mean: 2,400 EUR, Standard deviation: 700 EUR) 
- Male management (Number: 250 employees, Mean: 4,000 EUR, Standard deviation: 1,000 EUR)
   
![Simpson paradox-Gender pay gap-4 normal distributions](https://github.com/Olivier-FONTAINE/Introduction-to-Causal-Inference-for-People-Analytics/assets/86404915/c890460a-7994-4ee8-b1aa-c0bf1aabc13d)

You can visualize the different distributions:
- The salary right skewed distribution
- The salary distribution by gender
- The salary distribution by gender & job family
- The salary distribution by job family
  
![Simpson paradox-Gender pay gap-4 density plots](https://github.com/Olivier-FONTAINE/Introduction-to-Causal-Inference-for-People-Analytics/assets/86404915/1370feaa-7995-4bb6-bcd4-e355ecab94e5)

Eventually, you realize that:
- while, the mean salary for males is higher than the mean salary for females
- the mean salary for males is lower than the mean salary for females when you consider job families

![Simpson paradox-Gender pay gap-Means differences](https://github.com/Olivier-FONTAINE/Introduction-to-Causal-Inference-for-People-Analytics/assets/86404915/bf5898ef-2688-46c8-aa92-317f9cd01b3d)
