---
layout: page
title: "8ALib.java Javadoc"
---
# PA1 8ALib.java Javadoc

<style>
table {
    width:100%;
}

.monospace {
    font-family: monospace;
}
</style>

### Method Summary
<table class="table table-striped">
<thead>
  <tr>
    <th>Modifier and Type</th><th>Method</th><th>Description</th>
  </tr>
</thead>
<tr>
  <td class="monospace">java.lang.String</td><a href="#concat" class="monospace">java.lang.String left,<br>java.lang.String right</td><td>Returns a String of two concatentated Strings</td>
</tr>
<tr>
<td class="monospace">int</td><td>[`count`](#count)<br>`(java.lang.String base,`<br>`java.lang.String toFind)`</td><td>Returns the number of times a substring appears in a String</td>
</tr>
<tr>
<td class="monospace">long</td><td>[`dateMonthDayYearTime`](#dateMonthDayYearTime)<br>`(java.lang.String date)`</td><td>Returns the String formatted date as a long</td>
</tr>
<tr>
<td class="monospace">long</td><td>[`dateYearMonthDayTime`](#dateYearMonthDayTime)<br>`(java.lang.String date)`</td><td>Returns the String formatted date as a long</td>
</tr>
<tr>
<td class="monospace">int</td><td>[`indexOf`](#indexOf)<br>`(java.lang.String base,`<br>`java.lang.String toFind)`</td><td>Returns the index within a String of the first occurrence of the specified substring</td>
</tr>
<tr>
<td class="monospace">int</td><td>[`indexOfNth`](#indexOfNth)<br>`(java.lang.String base,`<br>`java.lang.String toFind)`</td><td>Returns the index of the nth occurrence of a substring in a String</td>
</tr>
<tr>
<td class="monospace">java.lang.String</td><td>[`intToString`](#intToString)<br>`(int n)`</td><td>Returns an integer represented as a String</td>
</tr>
<tr>
<td class="monospace">int</td><td>[`length`](#length)<br>`(java.lang.String s)`</td><td>Returns the length of a String</td>
</tr>
<tr>
<td class="monospace">int</td><td>[`parseInt`](#parseInt)<br>`(java.lang.String s)`</td><td>Parses the String argument and returns its represented integer value</td>
</tr>
<tr>
<td class="monospace">java.lang.String</td><td>[`readFile`](#readFile)<br>`(java.lang.String path)`</td><td>Reads file specified by a path and returns its contents as a String</td>
</tr>
<tr>
<td class="monospace">java.lang.String</td><td>[`readLine`](#readLine)<br>`(java.lang.String path,`<br>`int index)`</td><td>Returns the line index of a file specified by a path</td>
</tr>
<tr>
<td class="monospace">int</td><td>[`roundTo`](#roundTo)<br>`(int n,`<br>`int toRoundTo)`</td><td>Returns an integer rounded to the nearest multiple of another integer.</td>
</tr>
<tr>
<td class="monospace">boolean</td><td>[`show`](#show)<br>`(java.lang.String s,`<br>`int numLines)`</td><td>Prints a specified number of lines of a String and returns true when successfully completed;<br>returns false if the specified number of lines is greater than the number of lines in the String</td>
</tr>
<tr>
<td class="monospace">int</td><td>[`sign`](#sign)<br>`(int n)`</td><td>Returns -1, 0, or 1 based on the sign of an integer</td>
</tr>
<tr>
<td class="monospace">int</td><td>[`square`](#square)<br>`(int n)`</td><td>Returns the square of an integer</td>
</tr>
<tr>
<td class="monospace">boolean</td><td>[`stringEquals`](#stringEquals)<br>`(java.lang.String s1,`<br>`java.lang.String s2)`</td><td>Compares two Strings and returns true if they are equal, false otherwise</td>
</tr>
<tr>
<td class="monospace">java.lang.String</td><td>[`substring`](#substring)<br>`(java.lang.String base,`<br>`int beginIndex,`<br>`int endIndex)`</td><td>Returns the substring of a String from one specified index until the second specified index.</td>
</tr>
<tr>
<td class="monospace">java.lang.String</td><td>[`trim`](#trim)<br>`(java.lang.String base s)`</td><td>Returns a copy of a string with leading and trailing white space removed</td>
</tr>
</table>




### Method Detail

<a id="square"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>square</th>
  </tr>
</thead>
<tr>
  <td><pre>int square(int n)</pre>Returns the square of an integer<br><br><b>Parameters:</b><br>``n`` - an integer<br><br><b>Returns:</b><br>returns the square of n</td>
</tr>
</table>

<a id="sign"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>sign</th>
  </tr>
</thead>
<tr>
  <td><pre>int sign(int n)</pre>Returns -1, 0, or 1 based on the sign of an integer<br><br><b>Parameters:</b><br>``n`` - an integer<br><br><b>Returns:</b><br>returns -1 if n is negative, 0 if n is 0, 1 if n is positive</td>
</tr>
</table>

<a id="roundTo"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>roundTo</th>
  </tr>
</thead>
<tr>
  <td><pre>int roundTo​(int n,<br>            int toRoundTo)</pre>Returns an integer rounded to the nearest multiple of another integer. If the integer is equidistant between two multiples, the lesser value is returned.<br><br><b>Parameters:</b><br>``n`` - an integer<br><br><b>Returns:</b><br>returns n rounded to the nearest multiple of toRoundTo</td>
</tr>
</table>

<a id="length"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>length</th>
  </tr>
</thead>
<tr>
  <td><pre>int length​(java.lang.String s)</pre>Returns the length of a String<br><br><b>Parameters:</b><br>``s`` - a String<br><br><b>Returns:</b><br>returns the length of String s</td>
</tr>
</table>

<a id="substring"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>substring</th>
  </tr>
</thead>
<tr>
  <td><pre>java.lang.String substring(java.lang.String base,<br>                           int beginIndex,<br>                           int endIndex)</pre>Returns the substring of a String from one specified index until the second specified index.<br><br><b>Parameters:</b><br>``base`` - a String<br>``beginIndex`` - integer start index of substring<br>``endIndex`` - integer end index of substring, not inclusive<br><br><b>Returns:</b><br>returns the substring from beginIndex until endIndex of base</td>
</tr>
</table>

<a id="concat"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>concat</th>
  </tr>
</thead>
<tr>
  <td><pre>java.lang.String concat​(java.lang.String left,<br>                        java.lang.String right)</pre>Returns a String of two concatenated Strings<br><br><b>Parameters:</b><br>``left`` - first string in concatenation<br>``right`` - second string in concatenation<br><br><b>Returns:</b><br>returns the concatenated String of left and right</td>
</tr>
</table>

<a id="indexOf"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>indexOf</th>
  </tr>
</thead>
<tr>
  <td><pre>int indexOf​(java.lang.String base,<br>            java.lang.String toFind)</pre>Returns the index within a String of the first occurrence of the specified substring<br><br><b>Parameters:</b><br>``base`` - String being searched<br>``toFind`` - substring to be found<br><br><b>Returns:</b><br>returns the index of the first occurrence of toFind in base</td>
</tr>
</table>

<a id="indexOfNth"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>indexOfNth</th>
  </tr>
</thead>
|<tr>
  <td><pre>int indexOf​Nth(java.lang.String base,<br>               java.lang.String toFind,<br>               int n)</pre>Returns the index of the nth occurrence of a substring in a String<br><br><b>Parameters:</b><br>``base`` - String being searched<br>``toFind`` - substring to be found<br>``n`` - which occurrence of toFind to return the index of<br><br><b>Returns:</b><br>returns the index of the nth occurrence of toFind in base</td>
</tr>
</table>

<a id="parseInt"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>parseInt</th>
  </tr>
</thead>
<tr>
  <td><pre>int parseInt(java.lang.String s)</pre>Parses the String argument and returns its represented integer value<br><br><b>Parameters:</b><br>``s`` - String to be parsed<br><br><b>Returns:</b><br>returns String s represented as an integer</td>
</tr>
</table>

<a id="readLine"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>readLine</th>
  </tr>
</thead>
<tr>
  <td><pre>java.lang.String readLine​(java.lang.String path,<br>                          int index)<br>                          throws java.io.IOException</pre>Returns the line index of a file specified by a path<br><br><b>Parameters:</b><br>``path`` - String path of the file to be read<br>``index`` - integer line index to be read from the file specified by path<br><br><b>Returns:</b><br>returns the line specified by index as a String<br><br><b>Throws:</b><br>`java.io.IOException` - if file at path cannot be read or found</td>
</tr>
</table>

<a id="count"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>count</th>
  </tr>
</thead>
<tr>
  <td><pre>int count(java.lang.String base,<br>          java.lang.String toFind)</pre>Returns the number of times a substring appears in a String<br><br><b>Parameters:</b><br>``base`` - String being searched<br>``toFind`` - substring to be found<br><br><b>Returns:</b><br>returns the number of occurrences of toFind in base</td>
</tr>
</table>

<a id="dateMonthDayYearTime"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>dateMonthDayYearTime</th>
  </tr>
</thead>
<tr>
  <td><pre>long dateMonthDayYearTime(java.lang.String date)</pre>Returns the String formatted date as a long<br><br><b>Parameters:</b><br>``date`` - String in month, day, year, time format "MMMMM dd yyyy hh:mm z"<br><br><b>Returns:</b><br>returns how many milliseconds have passed since January 1, 1970, 00:00:00 GMT</td>
</tr>
</table>

<a id="dateYearMonthDayTime"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>dateYearMonthDayTime</th>
  </tr>
</thead>
<tr>
  <td><pre>long dateYearMonthDayTime(java.lang.String date)</pre>Returns the String formatted date as a long<br><br><b>Parameters:</b><br>``date`` - String in year, month, day, time format "yyyy-MM-dd'T'HH:mm:ss"<br><br><b>Returns:</b><br>returns how many milliseconds have passed since January 1, 1970, 00:00:00 GMT</td>
</tr>
</table>

<a id="show"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>show</th>
  </tr>
</thead>
<tr>
  <td><pre>boolean show(java.lang.String s,<br>             int numLines)</pre>Prints a specified number of lines of a String and returns true when successfully completed; returns false if the specified number of lines is greater than the number of lines in the String<br><br><b>Parameters:</b><br>``s`` - String part or all of which will be printed<br>``numLines`` - integer number of lines of s to print<br><br><b>Returns:</b><br>returns true upon successfully printing all numLines number of lines; returns false if numLines is greater than the number of lines in s</td>
</tr>
</table>

<a id="readFile"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>readFile</th>
  </tr>
</thead>
<tr>
  <td><pre>java.lang.String readFile(java.lang.String path)<br>                          throws java.io.IOException</pre>Reads file specified by a path and returns its contents as a String<br><br><b>Parameters:</b><br>``path`` - String path of the file to be read<br><br><b>Returns:</b><br>returns the file contents of path as a String<br><br><b>Throws:</b><br>`java.io.IOException` - if file at path cannot be read or found</td>
</tr>
</table>

<a id="intToString"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>intToString</th>
  </tr>
</thead>
<tr>
  <td><pre>java.lang.String intToString(int n)</pre>Returns an integer represented as a String<br><br><b>Parameters:</b><br>``n`` - integer to be represented as a String<br><br><b>Returns:</b><br>returns a String object representing the specified integer</td>
</tr>
</table>

<a id="trim"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>trim</th>
  </tr>
</thead>
<tr>
  <td><pre>java.lang.String trim(java.lang.String s)</pre>Returns a copy of a string with leading and trailing white space removed<br><br><b>Parameters:</b><br>``s`` - String to be trimmed<br><br><b>Returns:</b><br>returns a copy of s with leading and trailing white space removed</td>
</tr>
</table>

<a id="stringEquals"></a>
<table class="table table-striped">
<thead>
  <tr>
    <th>stringEquals</th>
  </tr>
</thead>
<tr>
  <td><pre>boolean stringEquals(java.lang.String s1,<br>                     java.lang.String s2)</pre>Compares two Strings and returns true if they are equal, false otherwise<br><br><b>Parameters:</b><br>``s1`` - first String to be compared<br>``s2`` - second String to be compared<br><br><b>Returns:</b><br>returns true if s1 and s2 are equal, false otherwise</td>
</tr>
</table>
