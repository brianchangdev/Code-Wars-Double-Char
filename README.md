# Code-Wars-Double-Char

Description:
Given a string, you have to return a string in which each character (case-sensitive) is repeated once.

doubleChar("String") ==> "SSttrriinngg"

doubleChar("Hello World") ==> "HHeelllloo  WWoorrlldd"

doubleChar("1234!_ ") ==> "11223344!!__  "






MY SOLUTION:

    function doubleChar(str) {
      var newStr = '';
      for (var i = 0; i < str.length; i++) {
        newStr += str.charAt(i) + str.charAt(i);
      }
      return newStr;
    };
    
    
BEST PRACTICE SOLUTION:

    function doubleChar(str) {
      var newStr = '';
      for (var i = 0; i < str.length; i++){
        newStr += str[i] + str[i];
      }
      return newStr;
    };
