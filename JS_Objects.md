<details>
<summary>What is an object in JS?</summary>
An object is a collection of properties, and a property is an association between a name (or key) and a value. A property's value can be a function, in which case the property is known as a method. In addition to objects that are predefined in the browser, you can define your own objects.
</details>
<br>
<details>
<summary>Are arrays objects?</summary>
Yes.
</details>
<br>
<details>
<summary>How can we check if a variable is an array?</summary>
Array.isArray(variable_name)
</details>
<br>
<details>
<summary>When we need to use [ ] instead dot notation to access values of the object?</summary>
When the key is not supposed to be string literal. When working with bracket notation, property identifiers only have to be a String. They can include any characters, including spaces. Variables may also be used as long as the variable resolves to a String.
</details>
<br>
<details>
<summary>What is difference between bracket and dot notation?</summary>
<b>Dot notation:</b>

- Property identifies can only be alphanumeric (and \_ and \$)
- Property identifiers cannot start with a number.
- Property identifiers cannot contain variables.
- OK — obj.prop_1, obj.prop\$
- Not OK — obj.1prop, obj.prop name

<b>Bracket notation:</b>

- Property identifiers have to be a String or a variable that references a String.
- It is okay to use variables, spaces, and Strings that start with numbers
- OK — obj["1prop"], obj["prop name"]

</details>
