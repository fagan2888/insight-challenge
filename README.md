# insight-challenge
Insight data engineering challenge question

### Takeaways:
* The code has been developed using python2 and libraries like csv, os and sys have been used for file related operations
* There was a slight error in the script( I believe) run_tests.sh. I have modified the script accordingly and it passes the one test case. I had also emailed your team for the same.
* The script has been run and tested on inputs of varying sizes(10,100,1000,10000 and so on)


### Aproach:

#### 1. Sum of order grouped by department
1. Sum products based on order id.
2. Map products to department id.
3. Map products sum to department id based on product id
4. Sum order sum grouped by department id

#### 2. Checking first time order status
1. Map product id to reorder status
2. Map products to department id.
3. Map reorder status/product sum to department id based on product id
4. Sum the ordered for the first time counts by department id

#### 3. Combine 1 & 2 based on department ID

#### 4. Filter departments having > 0 orders

#### 5. Calculate ratio of values obtained in 1 &2 and format them

#### 6. Write to csv files