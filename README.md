# Question-1

-The code defines a function called convert_to_indian_currency that takes a number as input.

-It converts the number to a string and reverses it using slicing ([::-1]). For example, the number 123456789 will become the string '987654321'.

-The reversed string is divided into groups of two digits each using list comprehension. For example, the string '987654321' will be divided into ['98', '76', '54', '32', '1'].

-The groups are then joined together using commas and reversed again to get the desired Indian currency format. For example, the groups ['98', '76', '54', '32', '1'] will be joined as '98,76,54,32,1' and reversed to '1,32,54,76,98'.

-Finally, the resulting Indian currency string is returned from the function.

# Question-2

#The code defines a function called minimum_players_shot that takes the number of test cases as input (test_cases).

#It starts a loop that runs test_cases number of times. This loop is used to handle multiple test cases.

#Within each iteration of the loop, the code performs the following steps:

         #It reads two integers, n and k, from the input. These values represent the number of players (n) and the minimum height required (k).

          #It reads a list of n integers representing the heights of the players.

          #It initializes a variable count to keep track of the number of players whose height is greater than k.

            #It loops through each player's height in the heights list and checks if the height is greater than k. If it is, it increments the count variable by 1.

          #After processing all the players' heights, it prints the final value of count, which represents the number of players whose height is     greater than k.

#Finally, the code outside the loop reads an integer t from the input, which represents the number of test cases, and calls the minimum_players_shot function with t as the argument.

![Capture](https://github.com/kuldeepjeengar/simplyfi_test/assets/123317219/7fff492c-ef80-4bcc-90ce-80356d3fc745)
![2](https://github.com/kuldeepjeengar/simplyfi_test/assets/123317219/542ccc13-9812-4726-aef5-327ac8ee20e2)

