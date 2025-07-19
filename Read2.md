# Java 8 Stream API - Questions and Answers

## 📋 Questions List

1. [Write a Java 8 program to find the common elements between two arrays using streams](#1-write-a-java-8-program-to-find-the-common-elements-between-two-arrays-using-streams)
2. [Reverse each word of a string using Java 8 streams](#2-reverse-each-word-of-a-string-using-java-8-streams)
3. [Write a Java 8 program to reverse each word of a given string using the stream API and lambda expressions](#3-write-a-java-8-program-to-reverse-each-word-of-a-given-string-using-the-stream-api-and-lambda-expressions)
4. [Find the sum of the first 10 natural numbers](#4-find-the-sum-of-the-first-10-natural-numbers)
5. [Write a Java 8 program to find the sum of the first 10 natural numbers using streams](#5-write-a-java-8-program-to-find-the-sum-of-the-first-10-natural-numbers-using-streams)
6. [Reverse an integer array](#6-reverse-an-integer-array)
7. [Write a Java 8 program to reverse an integer array](#7-write-a-java-8-program-to-reverse-an-integer-array)
8. [Print the first 10 even numbers](#8-print-the-first-10-even-numbers)
9. [Write a Java 8 program to print the first 10 even numbers](#9-write-a-java-8-program-to-print-the-first-10-even-numbers)
10. [Find the most repeated element in an array](#10-find-the-most-repeated-element-in-an-array)
11. [Write a Java 8 program to find the most repeated element in an array](#11-write-a-java-8-program-to-find-the-most-repeated-element-in-an-array)
12. [Check if a string is a palindrome using Java 8 streams](#12-check-if-a-string-is-a-palindrome-using-java-8-streams)
13. [Write a Java 8 program to check if a given string is a palindrome using the stream API and lambda expressions](#13-write-a-java-8-program-to-check-if-a-given-string-is-a-palindrome-using-the-stream-api-and-lambda-expressions)
14. [Find strings in a list that start with a number](#14-find-strings-in-a-list-that-start-with-a-number)
15. [Given a list of strings, write a Java 8 program to find the strings that start with a number](#15-given-a-list-of-strings-write-a-java-8-program-to-find-the-strings-that-start-with-a-number)
16. [Extract duplicate elements from an array](#16-extract-duplicate-elements-from-an-array)
17. [Write a Java 8 program to extract duplicate elements from an array](#17-write-a-java-8-program-to-extract-duplicate-elements-from-an-array)
18. [Print duplicate characters in a string](#18-print-duplicate-characters-in-a-string)
19. [Write a Java 8 program to print the duplicate characters in a string](#19-write-a-java-8-program-to-print-the-duplicate-characters-in-a-string)
20. [Find the first repeated character in a string](#20-find-the-first-repeated-character-in-a-string)
21. [Write a Java 8 program to find the first repeated character in a string](#21-write-a-java-8-program-to-find-the-first-repeated-character-in-a-string)
22. [Find the first non-repeated character in a string](#22-find-the-first-non-repeated-character-in-a-string)
23. [Write a Java 8 program to find the first non-repeated character in a string](#23-write-a-java-8-program-to-find-the-first-non-repeated-character-in-a-string)
24. [Generate the Fibonacci series](#24-generate-the-fibonacci-series)
25. [Write a Java 8 program to generate the Fibonacci series](#25-write-a-java-8-program-to-generate-the-fibonacci-series)
26. [Print the first 10 odd numbers](#26-print-the-first-10-odd-numbers)
27. [Write a Java 8 program to print the first 10 odd numbers](#27-write-a-java-8-program-to-print-the-first-10-odd-numbers)
28. [Get the last element of an array](#28-get-the-last-element-of-an-array)
29. [Write a Java 8 program to get the last element of an array](#29-write-a-java-8-program-to-get-the-last-element-of-an-array)
30. [Calculate the age of a person in years](#30-calculate-the-age-of-a-person-in-years)
31. [Write a Java 8 program to calculate the age of a person in years given their birthday](#31-write-a-java-8-program-to-calculate-the-age-of-a-person-in-years-given-their-birthday)

---

## 💻 Answers with Code Solutions

### 1. Write a Java 8 program to find the common elements between two arrays using streams

```java
Integer[] array1 = {1, 2, 3, 4, 5, 6};
Integer[] array2 = {4, 5, 6, 7, 8, 9};

List<Integer> commonElements = Arrays.stream(array1)
    .filter(element -> Arrays.stream(array2).anyMatch(e -> e.equals(element)))
    .collect(Collectors.toList());
    
System.out.println("Common elements: " + commonElements);
// Output: Common elements: [4, 5, 6]
```

[⬆️ Back to Questions](#-questions-list)

---

### 2. Reverse each word of a string using Java 8 streams

```java
String stmt = "java is OOP language";
String reverseEachWord = Arrays.stream(stmt.split(" "))
        .map(word -> new StringBuffer(word).reverse())
        .collect(joining(" "));
System.out.println(reverseEachWord);
// Output: avaj si POO egaugnal
```

[⬆️ Back to Questions](#-questions-list)

---

### 3. Write a Java 8 program to reverse each word of a given string using the stream API and lambda expressions

```java
String stmt = "java is OOP language";
String reverseEachWord = Arrays.stream(stmt.split(" "))
        .map(word -> new StringBuilder(word).reverse().toString())
        .collect(joining(" "));
System.out.println("Reversed words: " + reverseEachWord);

// Also reverse an array
int[] numberArray = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
System.out.println("Original array: " + Arrays.toString(numberArray));
int[] reversedArray = IntStream.rangeClosed(1, numberArray.length)
        .map(number -> numberArray[numberArray.length - number])
        .toArray();
System.out.println("Reversed Array: " + Arrays.toString(reversedArray));
// Output: Reversed words: avaj si POO egaugnal
// Output: Original array: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
// Output: Reversed Array: [10, 9, 8, 7, 6, 5, 4, 3, 2, 1]
```

[⬆️ Back to Questions](#-questions-list)

---

### 4. Find the sum of the first 10 natural numbers

```java
int sum = IntStream.rangeClosed(1, 10)  // generates numbers from 1 to 10
                   .sum();              // sums the numbers
System.out.println("Sum of first 10 natural numbers: " + sum);
// Output: Sum of first 10 natural numbers: 55
```

[⬆️ Back to Questions](#-questions-list)

---

### 5. Write a Java 8 program to find the sum of the first 10 natural numbers using streams

```java
int sum = IntStream.rangeClosed(1, 10).sum();
System.out.println("Sum of first 10 natural numbers: " + sum);

// Alternative approach
int sumAlternative = IntStream.iterate(1, n -> n + 1)
                            .limit(10)
                            .sum();
System.out.println("Sum (alternative): " + sumAlternative);
// Output: Sum of first 10 natural numbers: 55
// Output: Sum (alternative): 55
```

[⬆️ Back to Questions](#-questions-list)

---

### 6. Reverse an integer array

```java
Integer[] numbers = {1, 2, 3, 4, 5};

// Convert array to List and reverse
List<Integer> reversedList = Arrays.stream(numbers)
                                   .collect(Collectors.toList());
Collections.reverse(reversedList);
System.out.println("Reversed array: " + reversedList);
// Output: Reversed array: [5, 4, 3, 2, 1]
```

[⬆️ Back to Questions](#-questions-list)

---

### 7. Write a Java 8 program to reverse an integer array

```java
Integer[] numbers = {1, 2, 3, 4, 5};

// Method 1: Using Collections.reverse
List<Integer> reversedList = Arrays.stream(numbers)
                                   .collect(Collectors.toList());
Collections.reverse(reversedList);
System.out.println("Method 1 - Reversed array: " + reversedList);

// Method 2: Using IntStream with indexing
Integer[] reversed = IntStream.range(0, numbers.length)
                            .map(i -> numbers[numbers.length - 1 - i])
                            .boxed()
                            .toArray(Integer[]::new);
System.out.println("Method 2 - Reversed array: " + Arrays.toString(reversed));
// Output: Method 1 - Reversed array: [5, 4, 3, 2, 1]
// Output: Method 2 - Reversed array: [5, 4, 3, 2, 1]
```

[⬆️ Back to Questions](#-questions-list)

---

### 8. Print the first 10 even numbers

```java
IntStream.iterate(2, n -> n + 2)  // Start at 2, increment by 2
         .limit(10)               // Take first 10 even numbers
         .forEach(System.out::println); // Print each
// Output: 2, 4, 6, 8, 10, 12, 14, 16, 18, 20
```

[⬆️ Back to Questions](#-questions-list)

---

### 9. Write a Java 8 program to print the first 10 even numbers

```java
System.out.println("First 10 even numbers:");
IntStream.iterate(2, n -> n + 2)
         .limit(10)
         .forEach(System.out::println);

// Alternative approach using filter
System.out.println("\nAlternative approach:");
IntStream.iterate(1, n -> n + 1)
         .filter(n -> n % 2 == 0)
         .limit(10)
         .forEach(System.out::println);
// Output: First 10 even numbers: 2, 4, 6, 8, 10, 12, 14, 16, 18, 20
```

[⬆️ Back to Questions](#-questions-list)

---

### 10. Find the most repeated element in an array

```java
Integer[] numbers = {1, 3, 2, 3, 4, 2, 3, 1, 2, 2};

// Step 1: Count frequency using groupingBy
Map<Integer, Long> frequencyMap = Arrays.stream(numbers)
        .collect(Collectors.groupingBy(Function.identity(), Collectors.counting()));

// Step 2: Find the entry with the max value
Map.Entry<Integer, Long> mostFrequent = frequencyMap.entrySet()
        .stream()
        .max(Map.Entry.comparingByValue())
        .orElse(null);

if (mostFrequent != null) {
    System.out.println("Most frequent element: " + mostFrequent.getKey());
    System.out.println("Frequency: " + mostFrequent.getValue());
} else {
    System.out.println("Array is empty.");
}
// Output: Most frequent element: 2
// Output: Frequency: 3
```

[⬆️ Back to Questions](#-questions-list)

---

### 11. Write a Java 8 program to find the most repeated element in an array

```java
Integer[] numbers = {1, 3, 2, 3, 4, 2, 3, 1, 2, 2};

Optional<Map.Entry<Integer, Long>> mostFrequent = Arrays.stream(numbers)
    .collect(Collectors.groupingBy(Function.identity(), Collectors.counting()))
    .entrySet()
    .stream()
    .max(Map.Entry.comparingByValue());
    
mostFrequent.ifPresent(entry -> 
    System.out.println("Most repeated element: " + entry.getKey() + 
                     " (appears " + entry.getValue() + " times)"));
// Output: Most repeated element: 2 (appears 3 times)
```

[⬆️ Back to Questions](#-questions-list)

---

### 12. Check if a string is a palindrome using Java 8 streams

```java
String input = "madam";  // Try with other inputs like "racecar", "hello"

boolean isPalindrome = IntStream.range(0, input.length() / 2)
        .allMatch(i -> input.charAt(i) == input.charAt(input.length() - i - 1));

if (isPalindrome) {
    System.out.println(input + " is a palindrome.");
} else {
    System.out.println(input + " is not a palindrome.");
}
// Output: madam is a palindrome.
```

[⬆️ Back to Questions](#-questions-list)

---

### 13. Write a Java 8 program to check if a given string is a palindrome using the stream API and lambda expressions

```java
String[] testStrings = {"madam", "racecar", "hello", "level"};

for (String input : testStrings) {
    boolean isPalindrome = IntStream.range(0, input.length() / 2)
            .allMatch(i -> input.charAt(i) == input.charAt(input.length() - i - 1));
    
    System.out.println(input + " is " + (isPalindrome ? "" : "not ") + "a palindrome.");
}
// Output: madam is a palindrome.
// Output: racecar is a palindrome.
// Output: hello is not a palindrome.
// Output: level is a palindrome.
```

[⬆️ Back to Questions](#-questions-list)

---

### 14. Find strings in a list that start with a number

```java
String[] words = {"rohit", "foo", "nemo", "target1", "12Target", "2robot"};

List<String> stringStartNumber = Arrays.stream(words)
         .filter(word -> Character.isDigit(word.charAt(0)))
         .toList();
System.out.println("Strings started with a number: " + stringStartNumber);
// Output: Strings started with a number: [12Target, 2robot]
```

[⬆️ Back to Questions](#-questions-list)

---

### 15. Given a list of strings, write a Java 8 program to find the strings that start with a number

```java
List<String> words = Arrays.asList("rohit", "foo", "nemo", "target1", "12Target", "2robot", "3fast");

List<String> stringsStartingWithNumber = words.stream()
        .filter(word -> !word.isEmpty() && Character.isDigit(word.charAt(0)))
        .collect(Collectors.toList());

System.out.println("Original list: " + words);
System.out.println("Strings starting with number: " + stringsStartingWithNumber);
// Output: Original list: [rohit, foo, nemo, target1, 12Target, 2robot, 3fast]
// Output: Strings starting with number: [12Target, 2robot, 3fast]
```

[⬆️ Back to Questions](#-questions-list)

---

### 16. Extract duplicate elements from an array

```java
List<Integer> duplicateElements = of(1, 2, 2, 2, 3, 3, 4, 5, 1, 1, 56, 7, 8, 9, 10);

System.out.println("Original Elements: " + duplicateElements);

List<Integer> extractDuplicateElements = duplicateElements.stream()
        .filter(element -> duplicateElements.indexOf(element) != duplicateElements.lastIndexOf(element))
        .distinct()
        .collect(Collectors.toList());

System.out.println("Duplicate elements: " + extractDuplicateElements);
// Output: Original Elements: [1, 2, 2, 2, 3, 3, 4, 5, 1, 1, 56, 7, 8, 9, 10]
// Output: Duplicate elements: [1, 2, 3]
```

[⬆️ Back to Questions](#-questions-list)

---

### 17. Write a Java 8 program to extract duplicate elements from an array

```java
List<Integer> numbers = Arrays.asList(1, 2, 2, 2, 3, 3, 4, 5, 1, 1, 56, 7, 8, 9, 10);

// Method 1: Using indexOf and lastIndexOf
List<Integer> duplicates1 = numbers.stream()
        .filter(element -> numbers.indexOf(element) != numbers.lastIndexOf(element))
        .distinct()
        .collect(Collectors.toList());

// Method 2: Using frequency map
List<Integer> duplicates2 = numbers.stream()
        .collect(Collectors.groupingBy(Function.identity(), Collectors.counting()))
        .entrySet()
        .stream()
        .filter(entry -> entry.getValue() > 1)
        .map(Map.Entry::getKey)
        .collect(Collectors.toList());

System.out.println("Original list: " + numbers);
System.out.println("Duplicates (Method 1): " + duplicates1);
System.out.println("Duplicates (Method 2): " + duplicates2);
// Output: Duplicates (Method 1): [1, 2, 3]
// Output: Duplicates (Method 2): [1, 2, 3]
```

[⬆️ Back to Questions](#-questions-list)

---

### 18. Print duplicate characters in a string

```java
String word = "rohttoh";
System.out.println("Original String: " + word);

System.out.println(Arrays.stream(word.split(""))
        .filter(str -> word.indexOf(str) != word.lastIndexOf(str))
        .map(str -> str.charAt(0))
        .collect(toList()));
// Output: Original String: rohttoh
// Output: [r, o, h, t]
```

[⬆️ Back to Questions](#-questions-list)

---

### 19. Write a Java 8 program to print the duplicate characters in a string

```java
String input = "programming";  // Try with other strings like "character", "hello world"

List<Character> duplicates = input.chars()  // IntStream of character codes
        .mapToObj(c -> (char) c)            // Convert to Character Stream
        .collect(Collectors.groupingBy(Function.identity(), Collectors.counting())) // Count frequencies
        .entrySet()
        .stream()
        .filter(entry -> entry.getValue() > 1) // Only duplicates
        .map(Map.Entry::getKey)
        .collect(Collectors.toList());

System.out.println("Input string: " + input);
System.out.println("Duplicate characters: " + duplicates);
// Output: Input string: programming
// Output: Duplicate characters: [r, g, m]
```

[⬆️ Back to Questions](#-questions-list)

---

### 20. Find the first repeated character in a string

```java
String word = "rohttoh";
System.out.println("Original String: " + word);

String firstRepeated = Arrays.stream(word.split(""))
        .filter(str -> word.indexOf(str) != word.lastIndexOf(str))
        .findFirst()
        .orElse("");

System.out.println("First repeated character: " + firstRepeated);
// Output: Original String: rohttoh
// Output: First repeated character: r
```

[⬆️ Back to Questions](#-questions-list)

---

### 21. Write a Java 8 program to find the first repeated character in a string

```java
String word = "rohttoh";
System.out.println("Original String: " + word);

// Method 1: Using indexOf and lastIndexOf
Optional<String> firstRepeated = Arrays.stream(word.split(""))
        .filter(str -> word.indexOf(str) != word.lastIndexOf(str))
        .findFirst();

System.out.println("First repeated character: " + firstRepeated.orElse("None"));

// Method 2: Using Set to track seen characters
Set<Character> seen = new HashSet<>();
Optional<Character> firstDuplicate = word.chars()
        .mapToObj(c -> (char) c)
        .filter(c -> !seen.add(c))
        .findFirst();

System.out.println("First repeated character (Method 2): " + firstDuplicate.orElse(null));
// Output: First repeated character: r
// Output: First repeated character (Method 2): o
```

[⬆️ Back to Questions](#-questions-list)

---

### 22. Find the first non-repeated character in a string

```java
String tempStr = "rohitrohi";
System.out.println("Original String: " + tempStr);

String firstNonRepeated = Arrays.stream(tempStr.split(""))
        .filter(str -> tempStr.indexOf(str) == tempStr.lastIndexOf(str))
        .findFirst()
        .orElse("");

System.out.println("First non-repeated character: " + firstNonRepeated);
// Output: Original String: rohitrohi
// Output: First non-repeated character: t
```

[⬆️ Back to Questions](#-questions-list)

---

### 23. Write a Java 8 program to find the first non-repeated character in a string

```java
String tempStr = "rohitrohi";
System.out.println("Original String: " + tempStr);

// Method 1: Using indexOf and lastIndexOf
Optional<String> firstNonRepeated = Arrays.stream(tempStr.split(""))
        .filter(str -> tempStr.indexOf(str) == tempStr.lastIndexOf(str))
        .findFirst();

System.out.println("First non-repeated character (Method 1): " + firstNonRepeated.orElse("None"));

// Method 2: Using frequency map
Optional<Character> firstNonRepeatedChar = tempStr.chars()
        .mapToObj(c -> (char) c)
        .collect(Collectors.groupingBy(Function.identity(), LinkedHashMap::new, Collectors.counting()))
        .entrySet()
        .stream()
        .filter(entry -> entry.getValue() == 1)
        .map(Map.Entry::getKey)
        .findFirst();

System.out.println("First non-repeated character (Method 2): " + firstNonRepeatedChar.orElse(null));
// Output: First non-repeated character (Method 1): t
// Output: First non-repeated character (Method 2): t
```

[⬆️ Back to Questions](#-questions-list)

---

### 24. Generate the Fibonacci series

```java
System.out.println("Fibonacci series (first 10 numbers):");
Stream.iterate(new int[]{0, 1}, t -> new int[]{t[1], t[0] + t[1]})
        .limit(10)
        .map(t -> t[0])
        .forEach(System.out::println);

// Alternative approach with distinct collection
Function<int[], List<Integer>> intArraytoListOFInt = array -> Arrays.stream(array).boxed()
        .collect(toList());
List<Integer> fibonacciList = Stream.iterate(new int[]{0, 1}, t -> new int[]{t[1], t[0] + t[1]})
        .limit(10)
        .map(intArraytoListOFInt)
        .flatMap(List::stream)
        .distinct()
        .collect(toList());
System.out.println("Fibonacci as list: " + fibonacciList);
// Output: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34
// Output: Fibonacci as list: [0, 1, 2, 3, 5, 8, 13, 21, 34, 55]
```

[⬆️ Back to Questions](#-questions-list)

---

### 25. Write a Java 8 program to generate the Fibonacci series

```java
int n = 15; // Generate first 15 Fibonacci numbers

System.out.println("Fibonacci Series (first " + n + " numbers):");

// Method 1: Using iterate with array
Stream.iterate(new int[]{0, 1}, fib -> new int[]{fib[1], fib[0] + fib[1]})
        .limit(n)
        .map(fib -> fib[0])
        .forEach(num -> System.out.print(num + " "));

System.out.println("\n");

// Method 2: Collecting to list
List<Integer> fibonacciNumbers = Stream.iterate(new int[]{0, 1}, fib -> new int[]{fib[1], fib[0] + fib[1]})
        .limit(n)
        .map(fib -> fib[0])
        .collect(ArrayList::new, ArrayList::add, ArrayList::addAll);

System.out.println("Fibonacci as List: " + fibonacciNumbers);
// Output: 0 1 1 2 3 5 8 13 21 34 55 89 144 233 377
// Output: Fibonacci as List: [0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, 377]
```

[⬆️ Back to Questions](#-questions-list)

---

### 26. Print the first 10 odd numbers

```java
System.out.println("First 10 odd numbers:");
Stream.iterate(1, i -> i + 2)
        .limit(10)
        .forEach(System.out::println);
// Output: 1, 3, 5, 7, 9, 11, 13, 15, 17, 19
```

[⬆️ Back to Questions](#-questions-list)

---

### 27. Write a Java 8 program to print the first 10 odd numbers

```java
System.out.println("First 10 odd numbers (Method 1):");
Stream.iterate(1, i -> i + 2)
        .limit(10)
        .forEach(System.out::println);

System.out.println("\nFirst 10 odd numbers (Method 2):");
IntStream.iterate(1, n -> n + 1)
        .filter(n -> n % 2 == 1)
        .limit(10)
        .forEach(System.out::println);

System.out.println("\nFirst 10 odd numbers (Method 3):");
IntStream.range(0, 10)
        .map(i -> 2 * i + 1)
        .forEach(System.out::println);
// Output: 1, 3, 5, 7, 9, 11, 13, 15, 17, 19
```

[⬆️ Back to Questions](#-questions-list)

---

### 28. Get the last element of an array

```java
int[] intArray = {0, 1, 2, 3, 4, 5};
Integer lastElementInTheArray = Arrays.stream(intArray)
        .boxed()
        .reduce((first, second) -> second)
        .orElse(-1);
System.out.println("Last element in the array: " + lastElementInTheArray);
// Output: Last element in the array: 5
```

[⬆️ Back to Questions](#-questions-list)

---

### 29. Write a Java 8 program to get the last element of an array

```java
int[] intArray = {0, 1, 2, 3, 4, 5};
String[] stringArray = {"apple", "banana", "cherry", "date"};

// Method 1: Using reduce
Optional<Integer> lastInt = Arrays.stream(intArray)
        .boxed()
        .reduce((first, second) -> second);
System.out.println("Last integer element: " + lastInt.orElse(-1));

// Method 2: Using skip
Optional<Integer> lastIntSkip = Arrays.stream(intArray)
        .boxed()
        .skip(Math.max(0, intArray.length - 1))
        .findFirst();
System.out.println("Last integer element (skip method): " + lastIntSkip.orElse(-1));

// Method 3: For string array
Optional<String> lastString = Arrays.stream(stringArray)
        .reduce((first, second) -> second);
System.out.println("Last string element: " + lastString.orElse(""));
// Output: Last integer element: 5
// Output: Last integer element (skip method): 5
// Output: Last string element: date
```

[⬆️ Back to Questions](#-questions-list)

---

### 30. Calculate the age of a person in years

```java
LocalDate birthDate = LocalDate.of(1998, 8, 17);
LocalDate currentDate = LocalDate.now();
int age = Period.between(birthDate, currentDate).getYears();
System.out.println("Age of the person is: " + age);
// Output: Age of the person is: 26 (varies based on current date)
```

[⬆️ Back to Questions](#-questions-list)

---

### 31. Write a Java 8 program to calculate the age of a person in years given their birthday

```java
// Example birth dates
LocalDate birthDate1 = LocalDate.of(1998, 8, 17);
LocalDate birthDate2 = LocalDate.of(1985, 12, 25);
LocalDate birthDate3 = LocalDate.of(2000, 1, 1);

LocalDate currentDate = LocalDate.now();
DateTimeFormatter formatter = DateTimeFormatter.ofPattern("dd/MM/yyyy");

// Calculate ages
int age1 = Period.between(birthDate1, currentDate).getYears();
int age2 = Period.between(birthDate2, currentDate).getYears();
int age3 = Period.between(birthDate3, currentDate).getYears();

System.out.println("Current date: " + currentDate.format(formatter));
System.out.println("Person born on " + birthDate1.format(formatter) + " is " + age1 + " years old");
System.out.println("Person born on " + birthDate2.format(formatter) + " is " + age2 + " years old");
