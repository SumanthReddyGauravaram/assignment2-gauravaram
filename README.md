assignment2-gauravaram

# Sumanth Kumar Reddy Gauravaram

###### Hyderabad
<br><br/>
I was **brought** up in hyderabad and since then I was adapted to its **climate** and atmosphere.

---

# Directions from Los Angeles to Maryville

1. Take a cab and go to airport in Los Angeles and reach Kansas city
2. After reaching Kansas City tab a bus or cab to maryville
3. Maryville is a beautiful place where you can see the beauty of nature.

List of items to carry with you for maximum enjoyment.

* Umbrella
* Water bottle
* Bag with couple of clothes
* Come home

---
# Food Items 
<br>
Here are the List of food items that needs to be tried in maryville.

| Item   | Location      | Price |
|--------| ------------- | ----- |
| Burger | Zen Fast Food | 2$    |
| Egg Puf| Chick Fil A   | 5$    |
| Pizza  | Mooyah        | 7$    |
| Coke   | KFC           | 2$    | 

About Me - **[My Pic](AboutMe.md)**

---
# Pithy Quotes
> The art of life is to know how to enjoy a little and to endure very much *Bertrand Russell*

> The good life is one inspired by love and guided by knowledge *William Hazlitt*

---
# Code Fencing in Finding Power of Factorial Divisor

> The idea is based on Legendre’s formula which finds largest power of a prime number that divides fact!. We find all prime factors of n. For every prime factor we find largest power of it that divides fact!. Finally we return minimum of all found powers. <https://www.geeksforgeeks.org/find-maximum-power-number-divides-factorial/>

~~~
int fact_pow (int n, int k) {
    int res = 0;
    while (n) {
        n /= k;
        res += n;
    }
    return res;
}
~~~
<https://cp-algorithms.com/algebra/factorial-divisors.html>