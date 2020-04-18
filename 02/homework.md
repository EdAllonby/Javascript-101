# 02

## Prerequisites / 先决条件

Run the following commands to get a working environment

```cmd
git clone https://github.com/EdAllonby/Javascript-101.git
cd Javascript-101
npm install
cd 02
code .
```

In code, download the following extensions:

- ESLint
- Prettier - Code formatter
- Markdown All in One
- markdownlint

Now, whenever you want to run your code, type the following into the console:

```cmd
node .\index.js
```

## Homework / 家庭作业

## Question 1 / 问题一

Run the following in you command line (cmd / powershell), which will run the current `index.js` file:

```cmd
node .\index.js
```

what do you see? Do you understand what is happening?

## Question 2 / 问题二

Make a variable called `catName`. assign the name variable to `"saffy"`.

Use `console.log()` to log `catName` to the console. When running `node .\index.js` in cmd, you should see the following:

```cmd
node .\index.js
saffy
```

## Question 3 / 问题三

We will make an object in JavaScript, and then print it to the console:

Write the following in `index.js`

```javascript
const tabby = {
  name: "Micky",
  age: 2,
  breed: "Tabby",
};

console.log(tabby);
```

Update this object in a new line of code to make the age equal `3`.

## Question 4 / 问题四

We will now log the breed of the cat called `tabby`. Remember that `tabby` is just a variable name. It doesn't matter what you name this variable. We could have called it `cat` if we wanted to.

Now we are just accessing the bit of tabby (known as the property/field). In programming, I would say I am accessing the property of the tabby object.

Write the following in `index.js`

```javascript
const theNameOfTheTabbyCat = tabby.name;

console.log(theNameOfTheTabbyCat);
```

Use the following code to do the same thing as above, but this time log out the breed of the cat. Fill in the `???s`.

```javascript
const theBreedOfTheTabbyCat = tabby.???;

console.log(???);
```

## Question 5 / 问题五

Write some code to do the following:

Create a function called `catDescriber`. This function should use `console.log()` to write the name, age and breed of a `cat object`. As a hint, we can write the following function:

```javascript

function catDescriber(catObject) { // remember here that we are accessing the property of the function.

    const catName = catObject.Name; // the name of the cat
    const catAge = catObject.Age; // the age of the cat
    const catBreed = catObject.Breed; // the breed of the cat

    console.log(???); // what should we add to the `???` so that it prints out the name, age and breed. Remember that we can use Javascript's `My name is ${name} my age is ${age} and my breed is ${breed}` language feature / (语言功能) here

}
```

## Question 6 /问题六

call this function with the following

```javascript
catDescriber(tabby); // Do you understand what running this function does?
```

## Question 7 /问题七

Make an array of cat names. Assign this to a variable called `catNames`

```javascript
const catNames = ["billy", "milly", "sally"];
```

Use a for-loop to loop through each element of the catNames array. For each element, `console.log` the element value. We should see the following when running `node index.js`

```cmd
node .\index.js
billy
milly
sally
```

## Question 8 /问题八 - 格外努力

Copy this.

```javascript
const cats = [
  { name: "Micky", age: 2, breed: "Tabby" },
  { name: "Jimmy", age: 4, breed: "Savannah" },
  { name: "Mimi", age: 1, breed: "British Shorthair" },
  { name: "Timmy", age: 7, breed: "Bengal" },
  { name: "Xixi", age: 888, breed: "Sphynx" },
];
```

1. Write a function called `averageAge`. It takes in an array of cat objects (such as the `cats` variable we just defined), and returns the average age.

2. Write a function called `sortCats` which will return a new list which has sorted all cat objects by their name. i.e. the objects in the array should now be sorted by name like: `Jimmy, Micky, Mimi, Timmy, Xixi`.

3. Write a function called `logCats` which will log each cat object out to the console. It should show this when running `node .\index.js`

```cmd
node .\index.js
The cat's name is Micky who is 2 years old and a Tabby
The cat's name is Jimmy who is 4 years old and a Savannah
The cat's name is Mimi who is 1 years old and a British Shorthair
The cat's name is Timmy who is 7 years old and a Bengal
The cat's name is Xixi who is 888 years old and a Sphynx
```
