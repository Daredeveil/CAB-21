### Now is time to solve some interesting problems.

1. Given, there are 5 numbers in the data set: (8, 12, 16, 24, 4). What will be the sum of *deviations* of individual data points from their mean? <br/>
<br/>
Mean = (8+12+16+24+4)/5 = 12.8 <br/>
<br/>
variance = ((12.8-8)^2 + (12.8-12)^2 + (16-12.8)^2 + (24-12.8)^2 + (12.8-4)^2) / (5-1)<br/>
		 = (23.04 + 0.64 + 10.24 + 125.44 + 77.44) / 4 <br/>
		 = 59.2
<br/>
standard deviation = sqrt(59.2) = 7.69 <br/>
<br/>
<br/>

2. If some *outliers* are introduced to the dataset, what will happen to the Standard Deviation ? 
 
- [ ] Standard Deviation is robust to outliers
- [X] Standard Deviation will increase with the introduction of outliers
- [ ] Standard Deviation will decrease with the introduction of outliers
- [ ] Can not be determined <br/>
<br/>
<br/>

3. Suppose the below *positively skewed* distribution has a median of 30, which of the following statement is true? [CAB link!](https://i0.wp.com/dsft.code-data-ai.com/wp-content/uploads/2019/12/1-stat-11.jpg?w=402&ssl=1)

- [ ] Mean is greater than 30
- [ ] Mean is less than 30
- [ ] Mode is greater than 30
- [ ] Mode is less than 30
- [ ] Both A and D
- [X] Both B and C<br/>
<br/>
<br/>

4. Which value can be the possible value for the *median* of the below distribution? (Hint: You will have to add frequencies) [CAB link!](https://i0.wp.com/dsft.code-data-ai.com/wp-content/uploads/2019/12/1-stat-12.jpg?w=328&ssl=1)

- [ ] 40
- [X] 26
- [ ] 16
- [ ] 50 <br/>
<br>

Solution: [Solution link for more explanation!](https://math.stackexchange.com/questions/2591946/how-to-find-median-from-a-histogram)<br/>
On a *histogram*, the *median value* occurs where the whole histogram is *divided into two equal parts*.<br/>

Median = add frequencies / 2 = (36+54+69+82+55+43+25+22+17) / 2
	   = 201.5 
<br/>

The *median* position 201.5 is *greater* than 36+54+69 = 159 but *less* than 36+54+69+82 = 241, therefore *median* lies between 25-30 having frequency of 82.

