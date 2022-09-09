# Exercises 3 - Conditions

## 8 - Math: 

### Instructions
- Create a Console Project named `P8Math` [How To?](https://gist.github.com/marczaku/a8b3c38c37e8876a46194a73ed24b1f2)
- Ask the user for two numbers
- Convert each of them to `double`
- Assign the values to two variables named `first` and `second`
- Print the results of all the mathematical functions, which are shown on the slides, to the user one by one. 
  - For the ones requiring two parameters, pass both variables. 
  - For the ones requiring one parameter, use only the `first` variable. 
  - For the ones requiring three parameters, pass `0` as the second parameter.

### Sample
```
Output:Give me your first number.
Input:3.7
Output:Give me your second number.
Input:2.3
Output:Max:
Output:3.7
Output:Min:
Output:2.3
Output:Sqrt:
Output:1.9235384185619262
Output:Abs:
Output:3.7
Output:Round:
Output:4
Output:Floor:
Output:3
Output:Ceil:
Output:4
Output:Clamp:
Output:2.3
Output:Pow:
Output:20.270476188160853
```

Need Help? [Read the Slides on Math](slides#8-math)

## 9 - Strings: 

### Instructions
- Create a Console Project named `P9Strings` [How To?](https://gist.github.com/marczaku/a8b3c38c37e8876a46194a73ed24b1f2)
- Ask the user for:
  - his first name
  - his last name
  - his age 
- Then, send an output to the console like this: 
  - `Hello John Doe, you are 23 years old!`
### Sample
```
Output:What's your first name?
Input:Marc
Output:What's your last name?
Input:Zaku
Output:What's your age?
Input:31
Output:Hello Marc Zaku, you are 31 years old!
```

Need Help? [Read the Slides on Strings](slides#9-strings)

## 10 - Boolean: 

### Instructions
- Create a Console Project named `P10Boolean` [How To?](https://gist.github.com/marczaku/a8b3c38c37e8876a46194a73ed24b1f2)
- Ask the user for his age. Save it to a variable named `age`
- First, do a few age-checks:
  - Save to a `bool`-variable named `isChild`, whether the age is between 0 and 12
  - Save to a `bool`-variable named `isTeenager`, whether the age is between 13 and 19
  - Save to a `bool`-variable named `isGrownup`, whether the age is greater 19
- Then, print them all to the console like this:
  - `You are a child: True` etc. (see sample below)
### Sample
```
Output:What's your age?
Input:31
Output:You are a child:False
Output:You are a teenager:False
Output:You are a grown-up:True
```

Need Help? [Read the Slides on Booleans](slides#10-boolean)

## 11 - If..Else:

### Instructions
- Create a Console Project named `P11IfElse` [How To?](https://gist.github.com/marczaku/a8b3c38c37e8876a46194a73ed24b1f2)
- Ask the user for his age
- Print one of these statements (the correct one): 
  - You are a grown-up 
  - You are a child 
  - You are a teenager

- Ask the user for another integer
- Tell him, which is the larger number, the number just given, or his age
- Tell him, whether the larger number is 
  - an even (like 2 4 6) number
  - an odd (like 1 3 5) number
- Hint: How you can find out, whether a number is even or odd?
- Hint: There is an arithmetic operator on the operators-slide that helps you here :)
- Hint: Don't feel ashamed asking another student or googling `How to find out if a number is even c#`
- BONUS: Do the age-task using the ternary operator
### Sample
```
Output:What's your age?
Input:31
Output:You are a grown-up.
Output:Give me another integer.
Input:20
Output:The maximum is: 31
Output:Your number is an odd number.
```

Need Help? [Read the Slides on If..Else](slides#11-if--else)

## 12 - Random:

### Instructions
- Create a Console Project named `P12Random` [How To?](https://gist.github.com/marczaku/a8b3c38c37e8876a46194a73ed24b1f2)
- Ask the User for a Seed and store it in a variable.
- Initialize Random with the given Seed.
- Get three Random Numbers between 0 and 5 (including 0, excluding 5) and print them to the Console.
- Get three Random Numbers between 0 and 0.5 (including 0, excluding 0.5) and print them to the Console.
- Get three Random Numbers between 0.2 and 0.7 (including 0.2, excluding 0.7) and print them to the Console.
- Ask the user for a Crit Chance between 0.0 (0%) and 1.0 (100%). 
- Then simulate 5 Attacks and write, whether it’s a Crit. Or No Crit. 
- Hint: Thanks to using the Seed, you should actually receive the same results as me below, if using the same Seed. Test it! :)
### Sample
```
Output:Please pass me a seed (integer).
Input:1234
Output:Three integers between 0 and 5:
Output:1
Output:4
Output:1
Output:Three numbers between 0.0 and 0.5:
Output:0.47336876693804225
Output:0.16971801229273809
Output:0.47438912045880643
Output:Three numbers between 0.2 and 0.7:
Output:0.6039959450736623
Output:0.46036547346057627
Output:0.5219790320480144
Output:Give me a crit chance between 0.0 (0%) and 1.0 (100%)
Input:0.7
Output:Crit
Output:Crit
Output:No Crit
Output:No Crit
Output:Crit
```

Need Help? [Read the Slides on Random](slides#12-random)

## Done?
Return to the [Overview](../../..#3-conditions)