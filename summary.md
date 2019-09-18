**should_perform_logical_boolean_operations**
1. the diferrence between &, |, || and &&. https://stackoverflow.com/questions/7199666/difference-between-and-in-java
2. first I do not know the difference between the operators so I kind of guessed. but then I learned that when with boolean the behavior of bitwise is actually similar to the logical operators
3. I used basic logical operator knowledge, since it's only boolean, then I figure that it is similar. 
4. None

**should_do_bitwise_and_boolean_operation**
1. how & works. https://www.geeksforgeeks.org/operators-in-java/
2. I do not know how & works at first.
3. & will convert the values to binary and compare it with AND operator, in this case 1001010101100000000 = 305920
4. None

**should_do_bitwise_or_boolean_operation**
1. how | works. https://www.geeksforgeeks.org/operators-in-java/
2. I do not know how | works at first.
3. | will convert the values to binary and compare it with OR operator, in this case 10010001101001010101111001101 = 305441741
4. None

**should_do_bitwise_not_operation**
1. how ~ works. https://www.geeksforgeeks.org/operators-in-java/
2. I do not know how ~ works, but since the expected variable at first is 0. then it should not be similar with the actual value
3. ~ will just inverse the binary conversion of the value. meaning it will convert the value to binary and returns the compliment representation in this case, -65536.
4. None

**should_describe_escaped_chars**
1. how escaping character can be understood by java. https://stackoverflow.com/questions/1367322/what-are-all-the-escape-characters
2. first I tried actually input the literal values but it is encountering an error because some are not seen as character.
3. based on the method name I figure that I should use escape characters to satisfy the expected output
4. None

**should_not_get_rounded_result_if_convert_floating_number_to_integer**
1. how casting float to int can automatically convert the value into integer. https://www.java67.com/2015/10/how-to-convert-float-to-int-in-java-example.html
2. since the first value of variable expected is Integer.MAX_VALUE
3. based on my knowledge, casting a float to int will just remove the decimal places of the value and will just make it a whole number so I just set the value to 2
4. None

**should_judge_special_double_cases**
1. the use of Double class specifically about inifinite and NaN. https://docs.oracle.com/javase/7/docs/api/java/lang/Double.html
2. it failed at first because I used (Double.NaN == realNumber) which is always returning false. Then I noticed that there is a method Double.isNaN.
3. since dividing decimals except 0.0 by 0.0 will always return infinite and dividing 0.0 by 0.0 return NaN, I just used the predefined method in Double class to check the values.
4. None

**should_not_round_number_when_convert_to_integer**
1. how casting float to int can automatically convert the value into integer. https://www.java67.com/2015/10/how-to-convert-float-to-int-in-java-example.html
2. since the first value of variable expected is Integer.MAX_VALUE
3. based on my knowledge, casting a float to int will just remove the decimal places of the value and will just make it a whole number so I just set the value to 2
4. None

**should_round_number**
1. Math.ceil(). https://stackoverflow.com/questions/8753959/round-a-floating-point-number-to-the-next-integer-value-in-java
2. the test failed at first because I just cast the floatingPointNumber to long assuming that it will automatically round up
3. I manually rounded up floatingPointNumber by using Math.ceil() then casted it to long
4. None

**should_get_range_of_primitive_int_type**
1. Integer class speficically MAX_VALUE and MIN_VALUE. http://www.java2s.com/Tutorial/Java/0040__Data-Type/IntegerMAXMINVALUE.htm
2. the test failed at first because the value of maximumSymbol and minimumSymbol is just 0 which is not similar to the expected.
3. since there is already a predefined method in Integer class that will get the maximum and minimum values, I just used those methods and put the value to the variables.
4. None