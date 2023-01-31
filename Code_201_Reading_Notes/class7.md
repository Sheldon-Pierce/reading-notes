[Home](../README.md)

## Domain Modeling

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

## Tables

- Layout tables reduce accessibility for visually impaired users: screen readers, used by blind people, interpret the tags that exist in an HTML page and read out the contents to the user. Because tables are not the right tool for layout, and the markup is more complex than with CSS layout techniques, the screen readers' output will be confusing to their users.
- Tables produce tag soup: As mentioned above, table layouts generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.
- Tables are not automatically responsive: When you use proper layout containers (such as <header>, <section>, <article>, or <div>), their width defaults to 100% of their parent element. Tables on the other hand are sized according to their content by default, so extra measures are needed to get table layout styling to effectively work across a variety of devices.

td, tr, th are all apart of the table.

## Constructors

When you call a constructor, it will:

- create a new object
- bind this to the new object, so you can refer to this in your constructor code
- run the code in the constructor
- return the new object.
Constructors, by convention, start with a capital letter and are named for the type of object they create.

When used in a constructor, this refers to anything that is put into the constructor. When in the object it refers to the object.

Prototypes and inheritance is kind of like onboarding, it is attached to the company and can be done by whoever, but each new employee goes through the onboarding process.

## Things I want to know more about