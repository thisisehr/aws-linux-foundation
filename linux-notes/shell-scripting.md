Taking User Input

#!/bin/bash

echo "Enter your name"

read name

echo "Welcome $name"


If Condition Example

#!/bin/bash

num=10

if [ $num -gt 5 ]
then
    echo "Number is greater than 5"
fi


For Loop Example

#!/bin/bash

for i in 1 2 3 4 5
do
    echo $i
done


While Loop Example

#!/bin/bash

count=1

while [ $count -le 5 ]
do
    echo $count
    count=$((count + 1))
done


File Check Example

#!/bin/bash

if [ -f test.txt ]
then
    echo "File exists"
else
    echo "File not found"
fi


Basic Arithmetic Example

#!/bin/bash

a=10
b=5

sum=$((a + b))

echo "Sum is $sum"
