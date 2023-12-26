## <center> Final Project Instructions

### 1.  instructions of calss and functions
In this project, I have three files including "bigint hpp", "demon.cpp" and this "Readme.md".

"bigint.hpp" has a class named "bigint", I define all the functions in this head file, the details are following:

#### 1.1 functions statements
<span style="color:red;">"bigint()"</span> : initial function, the default is "0";

<span style="color:red;">"bigint(const string)"</span> : define an integer with an input string;

<span style="color:red;">"bool is_negative() const"</span> : test if an integer is negative;

<span style="color:red;">"string get_integer() const"</span> : get the string of an integer;

<span style="color:red;">"string get_pure_figures() const"</span> : get the string without sign of an integer;

<span style="color:red;">"void set(const string)"</span> : test if input is an integer, detect the numbers of invalid "0" and give a new string to existed value;

<span style="color:red;">"string two_positives_max_minus_min(const bigint min_number) const"</span> : a bigger integer minus a smaller integer, return a string;

<span style="color:red;">"string two_positives_max_plus_min(const bigint min_number) const"</span> : a bigger integer plus a smaller integer, return a string;

<span style="color:red;">"bigint& operator +=(const bigint&)"</span> : function "+=" ;

<span style="color:red;">"bigint& operator -=(const bigint&)"</span> : function "-=";

<span style="color:red;">"bigint& operator *=(const bigint&)"</span> : function "*=";

<span style="color:red;">"bigint& operator /=(const bigint&)"</span> : function "/=";

<span style="color:red;">"bigint& operator =(const bigint&)"</span> : give a new integer to an existed integer;

<span style="color:red;">"bigint operator -() const"</span> : add "-" or delete "-";

<span style="color:red;">"friend ostream& operator<<(ostream&, const bigint&)"</span> : overload "<<";

<span style="color:red;">"friend bool operator >(bigint, const bigint&)"</span> : test if an integer ">" another integer;

<span style="color:red;">"friend bool operator >=(bigint, const bigint&)"</span> : test if an integer ">=" another integer;

<span style="color:red;">"friend bool operator ==(bigint, const bigint&)"</span> : test if an integer "==" another integer;

<span style="color:red;">"friend bool operator !=(bigint, const bigint&)"</span> : test if an integer "!=" another integer;

<span style="color:red;">"friend bool operator <(bigint, const bigint&)"</span> : test if an integer "<>" another integer;

<span style="color:red;">"friend bool operator <=(bigint, const bigint&)"</span> : test if an integer "<=" another integer;

<span style="color:red;">"bigint operator +(bigint first_number, const bigint& second_number)"</span> : add one integer to another integer and store the result in a new integer, return this new integer;

<span style="color:red;">"bigint operator -(bigint first_number, const bigint& second_number)"</span> : substract one integer by another integer and store the result in a new integer, return this new integer;

<span style="color:red;">"bigint operator *(bigint first_number, const bigint& second_number)"</span> : multiple one integer with another integer and store the result in a new integer, return this new integer;

<span style="color:red;">"bigint operator /(bigint first_number, const bigint& second_number)"</span> : divide one integer by another integer and store the result in a new integer, return this new integer;

#### 1.2 details of main functions and examples to demonstrate them

">" : I use "for" loop to compare two integers. for example, "123" > "120": at first, I test the sign and length ,they are same so that I can start "for" loop, then I compare "1" with "1", then I compare "2" with "2", after that I compare "3" with "0", here I break the loop because they are different. 

"<" : "123" < "120" -> "120" > "123";

"==" : "123" == "120" ->   ! "123" > "120" and ! "123" < "120";

">=" : combine ">" and "==";

"<=" : combine "<" and "==";

"!=" : "123" != "120" -> ! "123" == "120";

"+=" : 

"-=" : 

"*=" : 

"/=" : 

"+" : 

"-" : 

"*" : 

"/" : 

"- ("1" -> "-1")" : 

"<<" : 


## 2.  Test (demon.cpp)