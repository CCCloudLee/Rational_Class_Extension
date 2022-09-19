# Rational_Class_Extension
Extend the Rational class for storing fractions in arithmetic. This time use a private C structure data member that integrates two integer variables int numerator and int denominator to hold the two parts of a fraction. 
1. Create a C structure Rational with two integer variable fields for the numerator and denominator of a fraction.
2. Create a class RationalClass that has a data member of Rational structure. Define a constructor that accepts two arguments, e.g. 3 and 4 and uses member initializer syntax to set the data fields of the fields of the structure data member.
3. Create a constructor that prevents a 0 denominator in a fraction, reduces or simplifies, and fractions that are not in reduced form and avoids negative denominators.
4. Overload the addition, subtraction, multiplication and division operators for this class.
5. Overload the relational and equality operators for this class.
