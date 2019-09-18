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

**should_get_range_of_primitive_short_type**
1. Short class speficically MAX_VALUE and MIN_VALUE. http://www.java2s.com/Tutorials/Java/Data_Types/Find_out_the_min_value_max_value_and_size_of_Java_Short_types.htm
2. the test failed at first because I still tried to use the MAX_VALUE and MIN_VALUE in Integer class so it has an error
3. since there is already a predefined method in Short class that will get the maximum and minimum values, I just used those methods and put the value to the variables.
4. None

**should_get_range_of_primitive_long_type**
1. Long class specifically MAX_VALUE and MIN_VALUE. https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html
2. the test failed at first because the value of maximumSymbol and minimumSymbol is just 0 which is not similar to the expected.
3. since there is already a predefined method in Long class that will get the maximum and minimum values, I just used those methods and put the value to the variables.
4. None

**should_get_range_of_primitive_byte_type**
1. Byte class specifically MAX_VALUE and MIN_VALUE. https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html
2. the test failed at first because the value of maximumSymbol and minimumSymbol is just 0 which is not similar to the expected.
3. since there is already a predefined method in Byte class that will get the maximum and minimum values, I just used those methods and put the value to the variables.
4. None

**should_overflow_silently**
1. When the value of integer goes beyond the MAX_VALUE. https://stackoverflow.com/questions/5131131/what-happens-when-you-increment-an-integer-beyond-its-max-value
2. the test failed at first because I tried to just simply add 1 to the value
3. when adding 1 to the MAX_VALUE, the value that will be returned will point to the MIN_VALUE
4. None

**should_underflow_silently**
1. When the value of integer goes beyond the MIN_VALUE. https://stackoverflow.com/questions/5131131/what-happens-when-you-increment-an-integer-beyond-its-max-value
2. the test failed at first because the expected result it just set to 0 which is not similar to theNumberWillUnderflow
3. when subtracting 1 to the MIN_VALUE, the value that will be returned will point to the MAX_VALUE
4. None

**should_throw_exception_when_overflow**
1. manually throwing exceptions. https://www.cis.upenn.edu/~bcpierce/courses/629/jdkdocs/api/java.lang.ArithmeticException.html
2. the test failed at first because the method add will throw a different exception
3. I did a validation checking if the parameters is equal or greater than the MAX_VALUE, if it is then I'll throw the exception, if not, i'll simply add the parameters
4. None

**just_prevent_lazy_implementation**
1. manually throwing exceptions. https://www.cis.upenn.edu/~bcpierce/courses/629/jdkdocs/api/java.lang.ArithmeticException.html
2. 
3. I did a validation checking if the parameters is equal or greater than the MAX_VALUE, if it is then I'll throw the exception, if not, i'll simply add the parameters
4. None

**should_increment**
1. the use of ++. https://www.programiz.com/article/increment-decrement-operator-difference-prefix-postfix
2. The test failed at first because I thought that using ++ as suffix and putting it in a variable will get the actual current value. 
3. I set the expectedResult to 3 since integer was incremented after the value was given to expectedResult. I set expectedCurrentInteger to 4 since that is where the value was actually incremented which is variable integer
4. None

**should_increment_2**
1. the use of ++. https://www.programiz.com/article/increment-decrement-operator-difference-prefix-postfix
2. 
3. I set the expectedResult to 4 since ++ was used as a prefix which means that it will increment first then will return the value. I set expectedCurrentInteger to 4 since that is where the value was actually incremented which is variable integer
4. None