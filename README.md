Create a class called Timer. Its constructor accepts three arguments representing hours (a value from the range [0..23] – we will be using military time), minutes 
(from the range [0..59]) and seconds (from the range [0..59]).

Zero is the default value for all of the above parameters. There is no need to perform any validation checks.

The class itself should provide the following facilities:

objects of the class should be "printable", i.e. they should be able to implicitly convert themselves into strings of the following form: "hh:mm:ss", with leading zeros added
when any of the values is less than 10;
the class should be equipped with parameterless methods called next_second() and previous_second(), incrementing the time stored inside the objects by +1/-1 second respectively.
Use the following hints:

all object properties should be private;
consider writing a separate function (not method!) to format the time string.
