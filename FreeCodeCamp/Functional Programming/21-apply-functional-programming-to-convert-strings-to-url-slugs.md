# Functional Programming: Apply Functional Programming to Convert Strings to URL Slugs
Fill in the urlSlug function so it converts a string title and returns the hyphenated version for the URL. You can use any of the methods covered in this section, and don't use replace. Here are the requirements:

The input is a string with spaces and title-cased words

The output is a string with the spaces between words replaced by a hyphen (-)

The output should be all lower-cased letters

The output should not have any spaces
# Solution:
```javascript
// Only change code below this line
function urlSlug(title) {
 let url = title.toLowerCase().trim().split(/\s+/).join("-");
 return url;
}
// Only change code above this line
console.log(urlSlug(" Winter Is  Coming"));
```