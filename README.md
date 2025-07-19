# Java8-coding-question
# Java 8 Stream API - Questions and Answers

A comprehensive collection of Java 8 Stream API questions with practical code solutions. Click on any question to navigate to its answer.

---

## 📋 All Questions

**List Operations:**
1. [Separate odd and even numbers in a list of integers](#1-separate-odd-and-even-numbers-in-a-list-of-integers)
2. [Given a list of integers, write a Java 8 program to separate the odd and even numbers into two separate lists](#2-given-a-list-of-integers-write-a-java-8-program-to-separate-the-odd-and-even-numbers-into-two-separate-lists)
3. [Remove duplicate elements from a list using Java 8 streams](#3-remove-duplicate-elements-from-a-list-using-java-8-streams)
4. [Write a Java 8 program to remove duplicate elements from a list using the stream API and lambda expressions](#4-write-a-java-8-program-to-remove-duplicate-elements-from-a-list-using-the-stream-api-and-lambda-expressions)
5. [Find the frequency of each character in a string using Java 8 streams](#5-find-the-frequency-of-each-character-in-a-string-using-java-8-streams)
6. [Sort a given list of decimals in reverse order](#6-sort-a-given-list-of-decimals-in-reverse-order)
7. [Write a Java 8 program to sort a given list of decimal numbers in reverse order](#7-write-a-java-8-program-to-sort-a-given-list-of-decimal-numbers-in-reverse-order)
8. [Join a list of strings with '[' as prefix, ']' as suffix, and ',' as delimiter](#8-join-a-list-of-strings-with--as-prefix--as-suffix-and--as-delimiter)
9. [Given a list of strings, write a Java 8 program to join the strings with '[' as a prefix, ']' as a suffix, and ',' as a delimiter](#9-given-a-list-of-strings-write-a-java-8-program-to-join-the-strings-with--as-a-prefix--as-a-suffix-and--as-a-delimiter)
10. [Print the numbers from a given list of integers that are multiples of 5](#10-print-the-numbers-from-a-given-list-of-integers-that-are-multiples-of-5)
11. [Write a Java 8 program to print the numbers from a given list of integers that are multiples of 5](#11-write-a-java-8-program-to-print-the-numbers-from-a-given-list-of-integers-that-are-multiples-of-5)
12. [Find the maximum and minimum of a list of integers](#12-find-the-maximum-and-minimum-of-a-list-of-integers)
13. [Given a list of integers, write a Java 8 program to find the maximum and minimum numbers in the list](#13-given-a-list-of-integers-write-a-java-8-program-to-find-the-maximum-and-minimum-numbers-in-the-list)
14. [Merge two unsorted arrays into a single sorted array using Java 8 streams](#14-merge-two-unsorted-arrays-into-a-single-sorted-array-using-java-8-streams)
15. [Write a Java 8 program to merge two unsorted arrays into a single sorted array using the stream API](#15-write-a-java-8-program-to-merge-two-unsorted-arrays-into-a-single-sorted-array-using-the-stream-api)
16. [Merge two unsorted arrays into a single sorted array without duplicates](#16-merge-two-unsorted-arrays-into-a-single-sorted-array-without-duplicates)
17. [Write a Java 8 program to merge two unsorted arrays into a single sorted array without duplicates](#17-write-a-java-8-program-to-merge-two-unsorted-arrays-into-a-single-sorted-array-without-duplicates)
18. [Get the three maximum and three minimum numbers from a given list of integers](#18-get-the-three-maximum-and-three-minimum-numbers-from-a-given-list-of-integers)
19. [Write a Java 8 program to get the three maximum and three minimum numbers from a given list of integers](#19-write-a-java-8-program-to-get-the-three-maximum-and-three-minimum-numbers-from-a-given-list-of-integers)
20. [Check if two strings are anagrams or not using Java 8 streams](#20-check-if-two-strings-are-anagrams-or-not-using-java-8-streams)
21. [Write a Java 8 program to check if two strings are anagrams or not using the stream API and lambda expressions](#21-write-a-java-8-program-to-check-if-two-strings-are-anagrams-or-not-using-the-stream-api-and-lambda-expressions)
22. [Find the sum of all digits of a number in Java 8](#22-find-the-sum-of-all-digits-of-a-number-in-java-8)
23. [Write a Java 8 program to find the sum of all digits of a given number](#23-write-a-java-8-program-to-find-the-sum-of-all-digits-of-a-given-number)
24. [Find the second largest number in an integer array](#24-find-the-second-largest-number-in-an-integer-array)
25. [Write a Java 8 program to find the second largest number in an integer array](#25-write-a-java-8-program-to-find-the-second-largest-number-in-an-integer-array)
26. [Sort a list of strings according to the increasing order of their length](#26-sort-a-list-of-strings-according-to-the-increasing-order-of-their-length)
27. [Write a Java 8 program to sort a given list of strings according to the increasing order of their length](#27-write-a-java-8-program-to-sort-a-given-list-of-strings-according-to-the-increasing-order-of-their-length)
28. [Find the sum and average of all elements in an integer array](#28-find-the-sum-and-average-of-all-elements-in-an-integer-array)
29. [Write a Java 8 program to find the sum and average of all elements in an integer array](#29-write-a-java-8-program-to-find-the-sum-and-average-of-all-elements-in-an-integer-array)
30. [Find the common elements between two arrays](#30-find-the-common-elements-between-two-arrays)
31. [Write a Java 8 program to find the common elements between two arrays using streams](#31-write-a-java-8-program-to-find-the-common-elements-between-two-arrays-using-streams)
32. [Reverse each word of a string using Java 8 streams](#32-reverse-each-word-of-a-string-using-java-8-streams)
33. [Write a Java 8 program to reverse each word of a given string using the stream API and lambda expressions](#33-write-a-java-8-program-to-reverse-each-word-of-a-given-string-using-the-stream-api-and-lambda-expressions)
34. [Find the sum of the first 10 natural numbers](#34-find-the-sum-of-the-first-10-natural-numbers)
35. [Write a Java 8 program to find the sum of the first 10 natural numbers using streams](#35-write-a-java-8-program-to-find-the-sum-of-the-first-10-natural-numbers-using-streams)
36. [Reverse an integer array](#36-reverse-an-integer-array)
37. [Write a Java 8 program to reverse an integer array](#37-write-a-java-8-program-to-reverse-an-integer-array)
38. [Print the first 10 even numbers](#38-print-the-first-10-even-numbers)
39. [Write a Java 8 program to print the first 10 even numbers](#39-write-a-java-8-program-to-print-the-first-10-even-numbers)
40. [Find the most repeated element in an array](#40-find-the-most-repeated-element-in-an-array)
41. [Write a Java 8 program to find the most repeated element in an array](#41-write-a-java-8-program-to-find-the-most-repeated-element-in-an-array)
42. [Check if a string is a palindrome using Java 8 streams](#42-check-if-a-string-is-a-palindrome-using-java-8-streams)
43. [Write a Java 8 program to check if a given string is a palindrome using the stream API and lambda expressions](#43-write-a-java-8-program-to-check-if-a-given-string-is-a-palindrome-using-the-stream-api-and-lambda-expressions)
44. [Find strings in a list that start with a number](#44-find-strings-in-a-list-that-start-with-a-number)
45. [Given a list of strings, write a Java 8 program to find the strings that start with a number](#45-given-a-list-of-strings-write-a-java-8-program-to-find-the-strings-that-start-with-a-number)
46. [Extract duplicate elements from an array](#46-extract-duplicate-elements-from-an-array)
47. [Write a Java 8 program to extract duplicate elements from an array](#47-write-a-java-8-program-to-extract-duplicate-elements-from-an-array)
48. [Print duplicate characters in a string](#48-print-duplicate-characters-in-a-string)
49. [Write a Java 8 program to print the duplicate characters in a string](#49-write-a-java-8-program-to-print-the-duplicate-characters-in-a-string)
50. [Find the first repeated character in a string](#50-find-the-first-repeated-character-in-a-string)
51. [Write a Java 8 program to find the first repeated character in a string](#51-write-a-java-8-program-to-find-the-first-repeated-character-in-a-string)
52. [Find the first non-repeated character in a string](#52-find-the-first-non-repeated-character-in-a-string)
53. [Write a Java 8 program to find the first non-repeated character in a string](#53-write-a-java-8-program-to-find-the-first-non-repeated-character-in-a-string)
54. [Generate the Fibonacci series](#54-generate-the-fibonacci-series)
55. [Write a Java 8 program to generate the Fibonacci series](#55-write-a-java-8-program-to-generate-the-fibonacci-series)
56. [Print the first 10 odd numbers](#56-print-the-first-10-odd-numbers)
57. [Write a Java 8 program to print the first 10 odd numbers](#57-write-a-java-8-program-to-print-the-first-10-odd-numbers)
58. [Get the last element of an array](#58-get-the-last-element-of-an-array)
59. [Write a Java 8 program to get the last element of an array](#59-write-a-java-8-program-to-get-the-last-element-of-an-array)
60. [Calculate the age of a person in years](#60-calculate-the-age-of-a-person-in-years)
61. [Write a Java 8 program to calculate the age of a person in years given their birthday](#61-write-a-java-8-program-to-calculate-the-age-of-a-person-in-years-given-their-birthday)

---

## 💻 Answers with Code Solutions

### 1. Separate odd and even numbers in a list of integers

```java
List<Integer> oneToTen = List.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);

Map<Boolean, List<Integer>> evenOddSeparation = oneToTen.stream()
        .collect(partitioningBy(i -> i % 2 == 0));

System.out.println(evenOddSeparation);
// Output: {false=[1, 3, 5, 7, 9], true=[2, 4, 6, 8, 10]}
```

[⬆️ Back to Questions](#-all-questions)

---

### 2. Given a list of integers, write a Java 8 program to separate the odd and even numbers into two separate lists

```java
List<Integer> oneToTen = List.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);

Collection<List<Integer>> evenOddList = oneToTen.stream()
        .collect(collectingAndThen(partitioningBy(i -> i % 2 == 0),
                Map::values));

System.out.println(evenOddList);
// Output: [[1, 3, 5, 7, 9], [2, 4, 6, 8, 10]]
```

[⬆️ Back to Questions](#-all-questions)

---

### 3. Remove duplicate elements from a list using Java 8 streams

```java
List<Integer> oneToTen = List.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);
List<Integer> removeDuplicate = oneToTen.stream()
        .distinct()
        .collect(toList());

System.out.println(removeDuplicate);
```

[⬆️ Back to Questions](#-all-questions)

---

### 4. Write a Java 8 program to remove duplicate elements from a list using the stream API and lambda expressions

```java
// Alternative approach using Set
List<Integer> oneToTen = List.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);
Set<Integer> removeDuplicateWithoutOrder = oneToTen.stream()
        .collect(toSet());

System.out.println(removeDuplicateWithoutOrder);
```

[⬆️ Back to Questions](#-all-questions)

---

### 5. Find the frequency of each character in a string using Java 8 streams

```java
String name = "rohitroh";
Map<String, Integer> countCharacter = Arrays.stream(name.split(""))
        .collect(groupingBy(Function.identity(),
                collectingAndThen(counting(), Long::intValue)));
System.out.println(countCharacter);
// Output: {r=2, o=2, h=2, i=1, t=1}
```

[⬆️ Back to Questions](#-all-questions)

---

### 6. Sort a given list of decimals in reverse order

```java
List<Integer> randomNumbers = List.of(12, 32, 2, 4, 777, 5, 32, 890, 422, 44, 99, 43);
List<Integer> sortListReverse = randomNumbers.stream()
        .sorted(reverseOrder())
        .collect(toList());
System.out.println(sortListReverse);
// Output: [890, 777, 422, 99, 44, 43, 32, 32, 12, 5, 4, 2]
```

[⬆️ Back to Questions](#-all-questions)

---

### 7. Write a Java 8 program to sort a given list of decimal numbers in reverse order

```java
// Same as above - sorting in reverse order
List<Integer> randomNumbers = List.of(12, 32, 2, 4, 777, 5, 32, 890, 422, 44, 99, 43);
List<Integer> sortListReverse = randomNumbers.stream()
        .sorted(Collections.reverseOrder())
        .collect(toList());
System.out.println(sortListReverse);
```

[⬆️ Back to Questions](#-all-questions)

---

### 8. Join a list of strings with '[' as prefix, ']' as suffix, and ',' as delimiter

```java
List<String> languageList = List.of("java", "c++", "c", "C sharp", "python", "kotlin", "scala");
String joinWithPrefixSuffixAndDelimiter = languageList
        .stream()
        .collect(joining(",", "[", "]"));
System.out.println(joinWithPrefixSuffixAndDelimiter);
// Output: [java,c++,c,C sharp,python,kotlin,scala]
```

[⬆️ Back to Questions](#-all-questions)

---

### 9. Given a list of strings, write a Java 8 program to join the strings with '[' as a prefix, ']' as a suffix, and ',' as a delimiter

```java
// Same as above
List<String> languageList = List.of("java", "c++", "c", "C sharp", "python", "kotlin", "scala");
String result = languageList.stream()
        .collect(joining(",", "[", "]"));
System.out.println(result);
```

[⬆️ Back to Questions](#-all-questions)

---

### 10. Print the numbers from a given list of integers that are multiples of 5

```java
List<Integer> randomNumbers = List.of(12, 32, 2, 4, 777, 5, 32, 890, 422, 44, 99, 43);
List<Integer> multipleOf5 = randomNumbers.stream()
        .filter(n -> n % 5 == 0)
        .collect(toList());
System.out.println(multipleOf5);
// Output: [5, 890]
```

[⬆️ Back to Questions](#-all-questions)

---

### 11. Write a Java 8 program to print the numbers from a given list of integers that are multiples of 5

```java
// Same as above
List<Integer> randomNumbers = List.of(12, 32, 2, 4, 777, 5, 32, 890, 422, 44, 99, 43);
randomNumbers.stream()
        .filter(n -> n % 5 == 0)
        .forEach(System.out::println);
```

[⬆️ Back to Questions](#-all-questions)

---

### 12. Find the maximum and minimum of a list of integers

```java
List<Integer> randomNumbers = List.of(12, 32, 2, 4, 777, 5, 32, 890, 422, 44, 99, 43);

Integer maxNumber = randomNumbers.stream()
        .max(Integer::compareTo)
        .orElse(Integer.MAX_VALUE);

Integer minValue = randomNumbers.stream()
        .min(Integer::compareTo)
        .orElse(Integer.MIN_VALUE);

System.out.println("Max: " + maxNumber + ", Min: " + minValue);
// Output: Max: 890, Min: 2
```

[⬆️ Back to Questions](#-all-questions)

---

### 13. Given a list of integers, write a Java 8 program to find the maximum and minimum numbers in the list

```java
// Same as above
List<Integer> randomNumbers = List.of(12, 32, 2, 4, 777, 5, 32, 890, 422, 44, 99, 43);

Optional<Integer> max = randomNumbers.stream().max(Integer::compareTo);
Optional<Integer> min = randomNumbers.stream().min(Integer::compareTo);

max.ifPresent(value -> System.out.println("Maximum: " + value));
min.ifPresent(value -> System.out.println("Minimum: " + value));
```

[⬆️ Back to Questions](#-all-questions)

---

### 14. Merge two unsorted arrays into a single sorted array using Java 8 streams

```java
int[] randomNumbers = {12, 32, 2, 4, 777, 5, 32, 890, 422, 44, 99, 43};
int[] randomNumber2 = {4, 3, 2, 5, 6, 78, 98, 53, 90};

int[] sortedArrayByMergingTwoArray = IntStream.concat(Arrays.stream(randomNumbers),
        Arrays.stream(randomNumber2))
        .sorted()
        .toArray();
        
System.out.println(Arrays.toString(sortedArrayByMergingTwoArray));
// Output: [2, 2, 3, 4, 4, 5, 5, 6, 12, 32, 32, 43, 44, 53, 78, 90, 98, 99, 422, 777, 890]
```

[⬆️ Back to Questions](#-all-questions)

---

### 15. Write a Java 8 program to merge two unsorted arrays into a single sorted array using the stream API

```java
// Same as above
int[] array1 = {12, 32, 2, 4, 777, 5, 32, 890, 422, 44, 99, 43};
int[] array2 = {4, 3, 2, 5, 6, 78, 98, 53, 90};

int[] mergedSortedArray = IntStream.concat(
        Arrays.stream(array1),
        Arrays.stream(array2)
).sorted().toArray();

System.out.println(Arrays.toString(mergedSortedArray));
```

[⬆️ Back to Questions](#-all-questions)

---

### 16. Merge two unsorted arrays into a single sorted array without duplicates

```java
int[] randomNumbers = {12, 32, 2, 4, 777, 5, 32, 890, 422, 44, 99, 43};
int[] randomNumber2 = {4, 32, 2, 5, 6, 78, 98, 53, 90};

int[] result = IntStream.concat(Arrays.stream(randomNumbers), Arrays.stream(randomNumber2))
        .distinct()
        .sorted()
        .toArray();
        
System.out.println(Arrays.toString(result));
// Output: [2, 4, 5, 6, 12, 32, 43, 44, 53, 78, 90, 98, 99, 422, 777, 890]
```

[⬆️ Back to Questions](#-all-questions)

---

### 17. Write a Java 8 program to merge two unsorted arrays into a single sorted array without duplicates

```java
// Same as above
int[] array1 = {12, 32, 2, 4, 777, 5, 32, 890, 422, 44, 99, 43};
int[] array2 = {4, 32, 2, 5, 6, 78, 98, 53, 90};

System.out.println(Arrays.toString(
    IntStream.concat(Arrays.stream(array1), Arrays.stream(array2))
            .distinct()
            .sorted()
            .toArray()
));
```

[⬆️ Back to Questions](#-all-questions)

---

### 18. Get the three maximum and three minimum numbers from a given list of integers

```java
List<Integer> randomNumbers = List.of(12, 32, 2, 4, 777, 5, 32, 890, 422, 44, 99, 43);

List<Integer> min3 = randomNumbers.stream()
        .sorted(Integer::compare)
        .limit(3)
        .collect(toList());

List<Integer> max3 = randomNumbers.stream()
        .sorted((x, y) -> Integer.compare(y, x))
        .limit(3)
        .collect(toList());
        
System.out.println("Min 3: " + min3);  // [2, 4, 5]
System.out.println("Max 3: " + max3);  // [890, 777, 422]
```

[⬆️ Back to Questions](#-all-questions)

---

### 19. Write a Java 8 program to get the three maximum and three minimum numbers from a given list of integers

```java
// Same as above - alternative approach
List<Integer> randomNumbers = List.of(12, 32, 2, 4, 777, 5, 32, 890, 422, 44, 99, 43);

List<Integer> top3 = randomNumbers.stream()
        .sorted(Collections.reverseOrder())
        .limit(3)
        .collect(toList());

List<Integer> bottom3 = randomNumbers.stream()
        .sorted()
        .limit(3)
        .collect(toList());

System.out.println("Top 3: " + top3);
System.out.println("Bottom 3: " + bottom3);
```

[⬆️ Back to Questions](#-all-questions)

---

### 20. Check if two strings are anagrams or not using Java 8 streams

```java
char[] splitIt = "listen".toCharArray();
char[] splitIt2 = "silent".toCharArray();

Arrays.sort(splitIt);
Arrays.sort(splitIt2);

if (Arrays.equals(splitIt, splitIt2)) {
    System.out.println("is Anagram");
} else {
    System.out.println("is not anagram");
}
```

[⬆️ Back to Questions](#-all-questions)

---

### 21. Write a Java 8 program to check if two strings are anagrams or not using the stream API and lambda expressions

```java
String string1 = "listen";
String string2 = "silent";

String join1 = Arrays.stream(string1.split(""))
        .sorted()
        .collect(joining(""));
        
String join2 = Arrays.stream(string2.split(""))
        .sorted()
        .collect(joining(""));
        
boolean isAnagram = join1.equals(join2);
System.out.println("Is Anagram: " + isAnagram);  // true
```

[⬆️ Back to Questions](#-all-questions)

---

### 22. Find the sum of all digits of a number in Java 8

```java
List<Integer> oneToTen = List.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);
int sum = oneToTen.stream()
        .mapToInt(Integer::intValue)
        .sum();
System.out.println("Sum: " + sum);  // 55
```

[⬆️ Back to Questions](#-all-questions)

---

### 23. Write a Java 8 program to find the sum of all digits of a given number

```java
// For individual digits of a number
int number = 12345;
int digitSum = String.valueOf(number)
        .chars()
        .map(Character::getNumericValue)
        .sum();
System.out.println("Sum of digits: " + digitSum);  // 15
```

[⬆️ Back to Questions](#-all-questions)

---

### 24. Find the second largest number in an integer array

```java
List<Integer> oneToTen = List.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);
Integer secondLarge = oneToTen.stream()
        .sorted(reverseOrder())
        .skip(1)
        .findFirst()
        .orElse(Integer.MAX_VALUE);

System.out.println("Second Largest: " + secondLarge);  // 9
```

[⬆️ Back to Questions](#-all-questions)

---

### 25. Write a Java 8 program to find the second largest number in an integer array

```java
// Same as above - alternative approach with distinct
List<Integer> numbers = List.of(10, 20, 20, 10, 30, 40, 40, 50);
Integer secondLargest = numbers.stream()
        .distinct()
        .sorted(Collections.reverseOrder())
        .skip(1)
        .findFirst()
        .orElse(null);

System.out.println("Second Largest: " + secondLargest);  // 40
```

[⬆️ Back to Questions](#-all-questions)

---

### 26. Sort a list of strings according to the increasing order of their length

```java
List<String> names = Arrays.asList("rohit", "urmila", "rohit", "urmila", "ram", "sham", "sita", "gita");
names.stream()
     .sorted(Comparator.comparingInt(String::length))
     .forEach(System.out::println);
// Output: ram, sham, sita, gita, rohit, rohit, urmila, urmila
```

[⬆️ Back to Questions](#-all-questions)

---

### 27. Write a Java 8 program to sort a given list of strings according to the increasing order of their length

```java
// Same as above - collecting to list
List<String> names = Arrays.asList("rohit", "urmila", "rohit", "urmila", "ram", "sham", "sita", "gita");
List<String> sortedByLength = names.stream()
        .sorted(Comparator.comparingInt(String::length))
        .collect(toList());

System.out.println(sortedByLength);
```

[⬆️ Back to Questions](#-all-questions)

---

### 28. Find the sum and average of all elements in an integer array

```java
List<Integer> oneToTen = List.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);

IntSummaryStatistics summaryStatistics = oneToTen.stream()
        .collect(summarizingInt(Integer::intValue));
        
System.out.println("Sum: " + summaryStatistics.getSum());        // 55
System.out.println("Average: " + summaryStatistics.getAverage()); // 5.5
```

[⬆️ Back to Questions](#-all-questions)

---

### 29. Write a Java 8 program to find the sum and average of all elements in an integer array

```java
// Same as above - alternative approach
List<Integer> numbers = List.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);

int sum = numbers.stream().mapToInt(Integer::intValue).sum();
double average = numbers.stream().mapToInt(Integer::intValue).average().orElse(0.0);

System.out.println("Sum: " + sum);
System.out.println("Average: " + average);
```

[⬆️ Back to Questions](#-all-questions)

---

### 30. Find the common elements between two arrays

```java
List<Integer> oneToTen = List.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);
List<Integer> twoToTen = List.of(2, 3, 4, 5, 6, 7, 8, 9, 10);

List<Integer> commonElements = oneToTen.stream()
        .filter(twoToTen::contains)
        .collect(toList());
        
System.out.println(commonElements);  // [2, 3, 4, 5, 6, 7, 8, 9, 10]
```

[⬆️ Back to Questions](#-all-questions)

---

## 💻 Answers with Code Solutions

### 31. Write a Java 8 program to find the common elements between two arrays using streams

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

### 32. Reverse each word of a string using Java 8 streams

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

### 33. Write a Java 8 program to reverse each word of a given string using the stream API and lambda expressions

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

### 34. Find the sum of the first 10 natural numbers

```java
int sum = IntStream.rangeClosed(1, 10)  // generates numbers from 1 to 10
                   .sum();              // sums the numbers
System.out.println("Sum of first 10 natural numbers: " + sum);
// Output: Sum of first 10 natural numbers: 55
```

[⬆️ Back to Questions](#-questions-list)

---

### 35. Write a Java 8 program to find the sum of the first 10 natural numbers using streams

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

### 36. Reverse an integer array

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

### 37. Write a Java 8 program to reverse an integer array

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

### 38. Print the first 10 even numbers

```java
IntStream.iterate(2, n -> n + 2)  // Start at 2, increment by 2
         .limit(10)               // Take first 10 even numbers
         .forEach(System.out::println); // Print each
// Output: 2, 4, 6, 8, 10, 12, 14, 16, 18, 20
```

[⬆️ Back to Questions](#-questions-list)

---

### 39. Write a Java 8 program to print the first 10 even numbers

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

### 40. Find the most repeated element in an array

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

### 41. Write a Java 8 program to find the most repeated element in an array

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

### 42. Check if a string is a palindrome using Java 8 streams

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

### 43. Write a Java 8 program to check if a given string is a palindrome using the stream API and lambda expressions

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

### 44. Find strings in a list that start with a number

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

### 45. Given a list of strings, write a Java 8 program to find the strings that start with a number

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

### 46. Extract duplicate elements from an array

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

### 47. Write a Java 8 program to extract duplicate elements from an array

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

### 48. Print duplicate characters in a string

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

### 49. Write a Java 8 program to print the duplicate characters in a string

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

### 50. Find the first repeated character in a string

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

### 51. Write a Java 8 program to find the first repeated character in a string

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

### 52. Find the first non-repeated character in a string

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

### 53. Write a Java 8 program to find the first non-repeated character in a string

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

### 54. Generate the Fibonacci series

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

### 55. Write a Java 8 program to generate the Fibonacci series

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

### 56. Print the first 10 odd numbers

```java
System.out.println("First 10 odd numbers:");
Stream.iterate(1, i -> i + 2)
        .limit(10)
        .forEach(System.out::println);
// Output: 1, 3, 5, 7, 9, 11, 13, 15, 17, 19
```

[⬆️ Back to Questions](#-questions-list)

---

### 57. Write a Java 8 program to print the first 10 odd numbers

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

### 58. Get the last element of an array

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

### 59. Write a Java 8 program to get the last element of an array

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

### 60. Calculate the age of a person in years

```java
LocalDate birthDate = LocalDate.of(1998, 8, 17);
LocalDate currentDate = LocalDate.now();
int age = Period.between(birthDate, currentDate).getYears();
System.out.println("Age of the person is: " + age);
// Output: Age of the person is: 26 (varies based on current date)
```

[⬆️ Back to Questions](#-questions-list)

---

### 61. Write a Java 8 program to calculate the age of a person in years given their birthday

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
```

[⬆️ Back to Questions](#-questions-list)

---
