# Local Storage 

## [Local Storage and How to Use it on Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

- Why would a developer use local storage for a web application?
  - Using just the site's HTTPS will reset saved data every time an application is visited; it's stateless. Using local storage will allow information to be stored in a database on your machine so that information can be easily accessed/not deleted upon reset.
- What information should not be stored in local storage?
  - Sensitive information like passwords, personal information that could be exploited, account numbers, etc. 
- Local storage can store what type of data? How would you convert it to that type before storing?
  - Local storage can only store strings. You can use the  `JSON.stringify()` and `JSON.parse()` methods.

### From [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify)

- The `JSON.stringify()` method converts a Javascript object or value to a JSON string. 
 *example*
 `JSON.stringify(42);`
 *the expected output would be '42'.*

- The `JSON.parse()` method parses a JSON string, constructing the JS value or object described by the string.
