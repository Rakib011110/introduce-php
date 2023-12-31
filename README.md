# introduce-php

### What is Php ?

- PHP একটি সার্ভার সাইড স্ক্রিপ্টিং ল্যাঙ্গুয়েজ যা ওয়েব ডেভেলপমেন্টে ব্যবহৃত হয়। PHP এর পূর্ণরূপ হল "Hypertext Preprocessor" যা একটি বৃদ্ধি পেয়েছে "PHP: Hypertext Preprocessor"।

PHP একটি ওয়েব সার্ভার সাইড স্ক্রিপ্টিং ল্যাঙ্গুয়েজ, অর্থাৎ এটি সার্ভার সাইডে চলার জন্য ডিজাইন করা হয়েছে এবং এটি ওয়েব সার্ভারে প্রয়োজনীয় সেটিংস সাপোর্ট করে। PHP দ্বারা তৈরি স্ক্রিপ্টগুলি ওয়েব সার্ভারে প্রসেস হয় এবং ব্রাউজারে প্রেরণ করা হয় যাতে ইউজারগুলি ওয়েব পেজগুলি দেখতে পারে।

PHP এর সাহায্যে ওয়েব সাইট ডাইনামিক করা যায়, ডেটাবেস সংযোগ করা যায়, ফর্ম প্রসেসিং করা যায়, কোনও ধরণের উপযুক্ত ওয়েব এ্যাপ্লিকেশন তৈরি করা যায় এবং আরও অনেক কিছু। PHP এর বিশেষ একটি উপকারিতা হল যে দ্বারা ইউজারের ইনপুট স্টোর এবং প্রসেস করার সাথে সাথে প্রদর্শন করার জন্য HTML কোড লেখা যাতে ডাইনামিক ওয়েব পেজ তৈরি করা যায়।

সংক্ষেপে, PHP একটি ওয়েব সার্ভার সাইড স্ক্রিপ্টিং ল্যাঙ্গুয়েজ যা ওয়েব ডেভেলপমেন্টে ব্যবহৃত হয় এবং ডাইনামিক ওয়েব পেজ তৈরি এবং প্রসেস করার জন্য ব্যবহৃত হয়।

</details>

<details>
<summary>
What i have to know about PHP ??

</summary>
Certainly! Here's a step-by-step list of what you need to learn in PHP programming:

**Step 1: Introduction to PHP**

1. Understand what PHP is and its role in web development.
2. Learn about PHP's syntax, variables, and data types.
3. Set up a local development environment with PHP (using XAMPP, WAMP, MAMP, or similar tools).

**Step 2: Basic PHP Concepts**

1. Operators: Learn about arithmetic, assignment, comparison, logical, and other operators.
2. Conditional Statements: Study if statements, else statements, and switch cases.
3. Loops: Learn about for loops, while loops, and foreach loops for array iteration.

**Step 3: Functions**

1. Learn how to define and call functions in PHP.
2. Understand the concepts of parameters and return values.
3. Study built-in PHP functions and how to create your own custom functions.

**Step 4: Arrays**

1. Understand indexed arrays and associative arrays.
2. Learn how to manipulate arrays, such as adding, updating, and removing elements.
3. Explore array functions like `array_push`, `array_pop`, `array_shift`, and more.

**Step 5: Strings**

1. Learn about string manipulation functions like concatenation, substring, and length.
2. Understand the concept of escaping characters and using different quotes.
3. Study string formatting and interpolation.

**Step 6: Superglobals and Form Handling**

1. Learn about PHP's superglobal variables ($\_GET, $\_POST, $\_REQUEST, etc.).
2. Understand how to handle form submissions and process user input.

**Step 7: Working with Files and Directories**

1. Learn how to read from and write to files in PHP.
2. Understand file permissions and error handling when working with files.

**Step 8: Object-Oriented Programming (OOP) Basics**

1. Introduction to classes and objects.
2. Learn about properties and methods in PHP classes.
3. Understand constructors and destructors.

**Step 9: More Advanced PHP Concepts**

1. Error Handling: Learn about try-catch blocks and handling exceptions.
2. Date and Time: Study how to work with dates and times using PHP functions.
3. Regular Expressions: Understand pattern matching using regular expressions.

**Step 10: Working with Databases**

1. Introduction to Databases: Understand the basics of relational databases.
2. SQL Queries: Learn basic SQL queries for CRUD operations (Create, Read, Update, Delete).
3. Connect PHP to Database: Learn how to establish a connection between PHP and databases like MySQL.

**Step 11: Security and Best Practices**

1. Input Validation: Learn how to validate user input to prevent security vulnerabilities.
2. SQL Injection Prevention: Understand how to prevent SQL injection attacks.
3. Cross-Site Scripting (XSS) Prevention: Study methods to prevent XSS attacks.

**Step 12: Sessions and Cookies**

1. Learn how to manage user sessions using PHP's session functions.
2. Understand how to set, retrieve, and manage cookies.

**Step 13: Building Simple PHP Applications**

1. Practice building small web applications that incorporate the concepts you've learned.
2. Apply your knowledge to create a basic CRUD application (e.g., a simple blog or task manager).

**Step 14: Continuous Learning and Practice**

1. Keep up-to-date with PHP's latest features and best practices.
2. Work on more complex projects to deepen your understanding and skills.

Remember that practice is essential to mastering PHP programming. As you progress, you can explore more advanced topics like PHP frameworks (e.g., Laravel, Symfony) and libraries to enhance your development capabilities.

```php

```

</details>

<details>
<summary>
 php তে ভেরিয়েবল লেখার নিয়ম কি কি 
</summary>

<br >
  
- PHP এ ভেরিয়েবল লেখার নিয়ম নিম্নলিখিত মত:

1. ভেরিয়েবল নাম সাধারণভাবে একটি ডলার চিহ্ন (`$`) দিয়ে শুরু হয়। উদাহরণস্বরূপ: `$variable_name`.

2. ভেরিয়েবল নাম একটি অক্ষর (A-Z এবং a-z) বা একটি আন্ডারস্কোর (`_`) দিয়ে শুরু হতে হবে। তবে, নামে সংখ্যা দিয়ে শুরু হতে পারবে না।

3. ভেরিয়েবল নামে কেস-সেনসিটিভ হয়, অর্থাৎ, `$myVariable` এবং `$MyVariable` দুটি আলাদা ভেরিয়েবল মন্তব্য করা হবে।

4. ভেরিয়েবল নামে কেমন অক্ষর ব্যবহার করা যাবে তা নির্ধারণ করে, এবং স্পেস বা সাধারণ বিশেষ চিহ্ন ব্যবহার যোগ্য নয়।

5. ভেরিয়েবল নামে সংখ্যা, অক্ষর এবং আন্ডারস্কোর ছাড়াও অন্য কোনও বিশেষ চিহ্ন বা শব্দ ব্যবহার যোগ্য নয়।

6. স্থিতিশীল ভেরিয়েবলগুলির নামে সাধারণভাবে সব অক্ষর বড় হয়ে থাকে (আপারকেস) এবং আন্ডারস্কোর দ্বারা শুরু হয়। উদাহরণস্বরূপ: `$MY_CONST`.

7. ভেরিয়েবলের মান সেট করতে একটি সমীকরণ (`=`) চিহ্ন ব্যবহার হয়। উদাহরণস্বরূপ: `$age = 25;`.

8. ভেরিয়েবল নামে স্পেস বা অন্যান্য বিশেষ চিহ্ন থাকতে পারবে না। আন্ডারস্কোর এবং হাইফেন (`-`) ব্যবহার করা যাবে ভেরিয়েবল নামে।

</details>

<details>
<summary>
PHP তে type কি কি

</summary>

Bangla :
PHP এ ভেরিয়েবল ডেক্লারেশন ছাড়াও ডাইনামিক টাইপিং সমর্থন করে, অর্থাৎ একটি ভেরিয়েবলে মান সেট করার সময় সে এর ডেটা টাইপ অটোম্যাটিকভাবে চেঞ্জ হতে পারে। নিম্নলিখিত টাইপগুলি PHP এ ব্যবহার করা যায়:

1. **ইন্টিজার (Integers):** পূর্ণসংখ্যা মান প্রকাশ করার জন্য ব্যবহৃত হয়। উদাহরণস্বরূপ: `$age = 25;`

2. **ফ্লোট (Floats or Doubles):** দশমিক সংখ্যা মান প্রকাশ করার জন্য ব্যবহৃত হয়। উদাহরণস্বরূপ: `$price = 12.99;`

3. **স্ট্রিং (Strings):** টেক্সট মান প্রকাশ করার জন্য ব্যবহৃত হয়। সিঙ্গেল কোটেশন (`'`) বা ডাবল কোটেশন (`"`) দ্বারা লেখা হয়। উদাহরণস্বরূপ: `$name = 'John';`

4. **বুলিয়ান (Booleans):** সত্য বা মিথ্যা মান প্রকাশ করার জন্য ব্যবহৃত হয়। মৌলিকভাবে `true` এবং `false` মান ব্যবহার হয়। উদাহরণস্বরূপ: `$is_logged_in = true;`

5. **অ্যারে (Arrays):** মাল্টিপল মানগুলি সংরক্ষণ করার জন্য ব্যবহৃত হয়। উদাহরণস্বরূপ: `$colors = array('red', 'green', 'blue');`

6. **অবজেক্ট (Objects):** অবজেক্ট-অরিয়েন্টেড প্রোগ্রামিং এ অবজেক্ট ব্যবহার করার জন্য ব্যবহৃত হয়।

7. **নাল (Null):** কোনও মান না থাকলে ভেরিয়েবলটি নাল মান ধারণ করতে পারে।

এছাড়া, PHP এ টাইপ চেকিং ফাংশনগুলি ব্যবহার করে ভেরিয়েবলের ডেটা টাইপ পরীক্ষা করা যায়, যেমন `is_int()`, `is_float()`, `is_string()`, `is_bool()` ইত্যাদি।

```php

```

</details>

<details>
<summary>
Arithmatic Operator

</summary>

PHP এ Arithmetic Operators হলো গণিতিক অপারেটরগুলি, যা সংখ্যা মানিয়ে গণনা প্রয়োগ করতে ব্যবহার হয়

- Addition (+): দুটি সংখ্যার যোগফল প্রদান করে।

```php
$a = 5;
$b = 3;
$result = $a + $b; // 5 + 3 = 8
echo $result; // Output: 8

```

-

```php


//  Subtraction (-): একটি সংখ্যা থেকে অপরটি সংখ্যাটি বিয়োগফল প্রদান করে।

$x = 12;
$y= 4;
$resultSub= $x- $y ;
echo "Subtraction is " . $resultSub . "<br> <br>";

```

-

```php

// Multiplication (*): দুটি সংখ্যার গুণফল প্রদান করে।


$x= 10;
$y=2;
$resul_multi= $x *$y ;
echo "Multiplication Result is " . $resul_multi ."<br> <br>";

```

-

```php

// Division (/): একটি সংখ্যা দুটির ভাগফল প্রদান করে।

$x= 20 ;
$y= 2;
$result_Division= $x/$y ;
echo "Division result is " . $result_Division . "<br> <br> ";

```

-

```php

// Modulus (%): একটি সংখ্যা দুটির ভাগশেষ (মডুলাস) প্রদান করে।

$x= 43 ;
$y= 2;

$Modulus_result= $x % $y ;

echo "Modulus ans is " .   $Modulus_result . "<br> <br>";

```

-

```php

// Exponentiation (**): একটি সংখ্যার উপর অপরটির বর্গ প্রদান করে।

$a = 2;
$b = 3;
$result_Exponentiation = $a ** $b; // 2^3 = 8
echo " Exponentiation ans is " . $result_Exponentiation ; // Output: 8

```

</details>

<details>
<summary>
What is Array

</summary>

**PHP Arrays:** Arrays in PHP are a way to store multiple values in a single variable. Each value has a numeric or associative index. They allow you to group related data together for easier manipulation and access.

For example:

```php
$colors = array("Red", "Green", "Blue");

echo $color;
echo $colors[0];

$person = array("name" => "John", "age" => 30); // Associative array
echo $person["name"];
```

Bangla: অ্যারে" (Array) হলো একধরণের ডেটা স্ট্রাকচার যা একাধিক মান (উপাদান) ধারণ করতে ব্যবহৃত হয়। এই মানগুলি সাজানো থাকে একটি লিস্ট বা কোলেকশন আকারে, যাতে আপনি একটি একক ভ্যারিয়েবলে বেশি মান সংরক্ষণ করতে পারেন।

একটি অ্যারে অধিকতর ইনডেক্স ভিত্তিক (অথবা কী-ভিত্তিক) হয়, অর্থাৎ প্রতিটি মানকে একটি ইনডেক্স দ্বারা আলাদা করা হয়। আমরা প্রায়শই 0 থেকে শুরু করে ইনডেক্স নামাতে সাধারণভাবে সুযোগ পাই।

```php

//  PHP Arrays
$colors = array("Red", "Green", "Blue");

// if i want to see index
echo "index is "  . $colors[2] . "<br> <br>";

echo $colors[0] . "<br> <br>";

$person = array("name" => "John", "age" => 30);
echo $person["name"] . "<br> <br>";


//  if i want to see all output

$student= ["rakib ", "sadiya ", "ariyan ", "sinthiya",344,434,2,32,23] ;
array_pop($student); // শেষের মান মুছে ফেলা

$student[]="shohan";    // add in last

$output =implode($student) ;
echo $output;



// echo ($fruits)





// Associative Arrays (এসোসিয়েটিভ অ্যারে):
// এই অ্যারেগুলি কী-ভিত্তিক ইনডেক্স ব্যবহার করে, অর্থাৎ মানের জন্য একটি কী (স্ট্রিং বা নম্বর) ব্যবহার করে।

$person = array("name" => "John", "age" => 30);
$person["occupation"] = "Engineer"; // "occupation" কী-তে "Engineer" মান যোগ করা
```

</details>

<details>
<summary>
What is operator in PHP

</summary>

Bangla :
PHP এ অপারেটরগুলি প্রোগ্রামিং ভাষায় বৈশিষ্ট্যিকভাবে ভ্যারিয়েবল, মান, এক্সপ্রেশন এবং অন্যান্য ডাটা প্রকাশনা এবং গণনা করতে ব্যবহৃত হয়।

1. **Arithmetic Operators (গণিতিক অপারেটর):**

   - `+` (Addition): Adds two numbers together. (দুটি সংখ্যা যোগ করে)
   - `-` (Subtraction): Subtracts one number from another. (একটি সংখ্যা থেকে অপরটি সংখ্যাটি বিয়োগ করে)
   - `*` (Multiplication): Multiplies two numbers. (দুটি সংখ্যার গুণফল প্রদান করে)
   - `/` (Division): Divides one number by another. (একটি সংখ্যা দুটির ভাগফল প্রদান করে)
   - `%` (Modulus): Provides the remainder of a division. (একটি সংখ্যা দুটির ভাগশেষ প্রদান করে)
   - `**` (Exponentiation): Raises a number to the power of another. (একটি সংখ্যার উপর অপরটির বর্গ প্রদান করে)

2. **String Concatenation Operator (সমলীঙ্গী অপারেটর):**

   - `.` (Concatenation): Joins two strings together. (দুটি স্ট্রিং যোগফল প্রদান করে)

3. **Assignment Operators (বন্ধনী অপারেটর):**

   - `=` (Assignment): Assigns a value to a variable. (মান ভেরিয়েবলে অ্যাসাইন করে)
   - `+=` (Addition Assignment): Adds and assigns a value to a variable. (মানের সাথে যোগ করে এবং অ্যাসাইন করে)
   - `-=` (Subtraction Assignment): Subtracts and assigns a value to a variable. (মান থেকে বিয়োগ করে এবং অ্যাসাইন করে)
   - `*=` (Multiplication Assignment): Multiplies and assigns a value to a variable. (মানের সাথে গুণ করে এবং অ্যাসাইন করে)
   - `/=` (Division Assignment): Divides and assigns a value to a variable. (মান দ্বারা ভাগ করে এবং অ্যাসাইন করে)
   - `%=` (Modulus Assignment): Performs modulus operation and assigns a value to a variable. (মান দ্বারা মডুলাস অপারেশন করে এবং অ্যাসাইন করে)

4. **Increment and Decrement Operators (ইনক্রিমেন্ট এবং ডিক্রিমেন্ট অপারেটর):**

   - `++` (Increment): Adds 1 to a number. (একটি সংখ্যা থেকে ১ যোগ করে)
   - `--` (Decrement): Subtracts 1 from a number. (একটি সংখ্যা থেকে ১ বিয়োগ করে)

5. **Comparison Operators (সমান্তরাল অপারেটর):**
   - `==` (Equal): Checks if two values are equal. (দুটি মান সমান কিনা পরীক্ষা করে)
   - `!=` (Not Equal): Checks if two values are not equal. (দুটি ম

ান সমান নয় কিনা পরীক্ষা করে)

- `>` (Greater Than): Checks if one value is greater than another. (একটি মান অপরটির চেয়ে বড় কিনা পরীক্ষা করে)
- `<` (Less Than): Checks if one value is less than another. (একটি মান অপরটির চেয়ে ছোট কিনা পরীক্ষা করে)
- `>=` (Greater Than or Equal To): Checks if one value is greater than or equal to another. (একটি মান অপরটির চেয়ে বড় বা সমান কিনা পরীক্ষা করে)
- `<=` (Less Than or Equal To): Checks if one value is less than or equal to another. (একটি মান অপরটির চেয়ে ছোট বা সমান কিনা পরীক্ষা করে)

These are some of the main operators used in PHP for various purposes like mathematical calculations, string manipulation, logical evaluations, and more.

```php

```

</details>

#### IFELSE IN PHP

<details>
<summary>
if else Math example
</summary>

// Here is the if ELS EXAMPLE

echo "<h1> Here is The example of if Else statement : </h1>";

$number = 7 ;

if($number % 2 == 0) {
echo "even";
}
else{
echo "odd";
}

echo "<h3>Write a program to check if a given number is positive, negative, or zero.

</h3> : " ;

$number= -1;

if($number> 0){
echo "positive";
}

elseif($number <0){
echo "nagative";

}
else{
echo "zero";
}

echo "<h3> প্রশ্ন 3:
দুটি সংখ্যা প্রদান করা আছে। সংখ্যা A বড় হলে A বড় , সংখ্যা B বড় হলে B বড়, আর তাদের সমান হলে সমান প্রিন্ট করুন। </h3>";

$a= 21;

$b=21;

if($a>$b){
echo "A is Greter t";
}

elseif($b>$a){
echo "B is greater ";

}
else{
echo "Equal";
}

echo "<h3>একটি সংখ্যা প্রদান করা আছে। সংখ্যাটি খুব বড় হলে Very Large, ২৫ এর চেয়ে বড় হলে Large, ১০ এর চেয়ে বড় হলে Medium, আর এর বাইরে হলে Small প্রিন্ট করুন। </h3> ";

$number = 10;

if($number >25 ){
  echo "Very Large";
}
elseif($number >10){
echo "large";
}
elseif($number > 5){
echo "medium";

}

else{
echo "small";
}
// echo "<h3> </h3>";
echo "<h3>একটি সংখ্যা প্রদান করা আছে। সংখ্যাটি ২ দ্বারা বিভাজ্য হলে Divisible by 2, সংখ্যাটি ৩ দ্বারা বিভাজ্য হলে Divisible by 3, আর উভয়ই নয় হলে Not Divisible by 2 or 3 প্রিন্ট করুন। </h3>";

//

$number= 12;

if($number % 2==0){
echo "Divisible by 2";

}
elseif($number % 3==0 ){
echo "Divisible by 3";
}
else{
echo "Not Divisible by 2 or 3";
}

echo "<h3> প্রশ্ন 6:
দুটি সংখ্যা প্রদান করা আছে। দ্বিতীয় সংখ্যাটি প্রথম সংখ্যার গুণফল হলে Product of First Number, প্রথম সংখ্যাটি দ্বিতীয় সংখ্যার গুণফল হলে Product of Second Number, আর তাদের গুণফল নয় হলে Not a Product প্রিন্ট করুন।</h3>";

$firstNumber = 5;
$secondNumber = 10;

$product= $firstNumber \* $secondNumber;

if($secondNumber== $firstNumber \* $secondNumber){
echo " Product of First Number";

}
elseif ($firstNumber == $firstNumber \* $secondNumber) {
echo "Product of Second Number";
} else {
echo "Not a Product";
}

```php

```

</details>
<details>
<summary>
What is PHP switch Case ??

</summary>
switch স্টেটমেন্ট একটি প্রোগ্রামিং স্টেটমেন্ট যা একটি এক্সপ্রেশন এর মান এবং একাধিক মানের সাথে তুলনা করে এবং সমর্থন প্রদান করে সব সমান মানের ক্যাস প্রোগ্রামের প্রবলেম সমাধানে ব্যবহার করা হয়।

```php
switch (expression) {
    case value1:
        // কোড ব্লক যখন expression এর মান value1 এর সাথে মিলে
        break;
    case value2:
        // কোড ব্লক যখন expression এর মান value2 এর সাথে মিলে
        break;
    // আরও ক্যাস যোগ করা যায়
    default:
        // যখন কোনো ক্যাস সাথে মিলে না
        break;
}

```

</details>

<details>
<summary>
What is Array

</summary>

```php

```

</details>
<details>
<summary>
What is Array

</summary>

```php

```

</details>

#### FUNCTION

<details>
<summary>
What Is Function in php

</summary>
PHP প্রোগ্রামিং ভাষায়, ফাংশন একটি নিজস্ব ব্লক কোড সেট বা প্রোগ্রাম সেট এর রেফারেন্স একটি নামের মাধ্যমে রাখা হয় যা প্রোগ্রামের বিভিন্ন জায়গায় ব্যবহৃত হতে পারে। এটি একটি বিশেষ কাজ সম্পাদনের জন্য ডিজাইন করা হয় যাতে প্রোগ্রামে একই কাজটি পুনরাবৃত্তি না করে বারবার ব্যবহার করা যায়।

ফাংশন নির্দিষ্ট কাজ সম্পাদন করে এবং যেখানেই প্রোগ্রামে সেই কাজটি প্রয়োজন সেখানেই ফাংশন কল করে সেটি প্রোগ্রামে সহজে ব্যবহার করা যায়। এটি প্রোগ্রাম মডুলারিটির সুবিধা প্রদান করে, যাতে একটি বড় প্রোগ্রামকে ছোট এবং সহজ ভাবে বিভিন্ন ফাংশনে ভাগ করা যায়।

```php
function functionName(parameters) {
    // ফাংশনের কোড ব্লক
    return value; // অপশনাল, ফাংশন থেকে মান রিটার্ন করতে ব্যবহার করা যায়
}

```

</details>
