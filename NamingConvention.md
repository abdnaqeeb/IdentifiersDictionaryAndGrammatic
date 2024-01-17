# Naming Convention

## Definition

>“Naming convention is a set of rules for choosing the character **sequence** to be used for identifiers which denote variables, types, functions, and other entities in source code and documentation” - Wikipedia

## Aspects

- Letters case
- Prefixes and suffixes
- Singular and plural
- **Words selection and structure (vocabulary & grammatic)**

## What is covered by existing standards

- Letters case
- Prefix and suffix
- Singular and plural

## Standards and guidelines priority list

1. Client
2. Industry
3. Language
4. Community Best Practices
5. Personal preferences

## Sample of Existing Industry Guidelines and Standards

- Automotive and embedded industry [MISRA C/C++](https://misra.org.uk/)   
- Aerospace industry standard [DO-178C](https://www.do178.org/)   
- Medical device standard [IEC 62304](https://en.wikipedia.org/wiki/IEC_62304)   
- Telecommunications standard [3GPP TS 32.105](https://portal.3gpp.org/desktopmodules/Specifications/SpecificationDetails.aspx?specificationId=1842)  
- Government and defense [Common Weakness Enumeration (CWE)](https://cwe.mitre.org/), [Defense Information Systems Agency (DISA),](https://www.disa.mil/) and [Security Technical Implementation Guides (STIGs)](https://public.cyber.mil/stigs/) standards

## Sample of Existing Language Guidelines and Standards

- Python: [PEP8 (Python Enhancement Proposal) Style Guide for Python Code](https://peps.python.org/pep-0008/)  
- Java: [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)  
- JavaScript: [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)  
- C#: [Microsoft C# Coding Conventions](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)   
- C/C++: [SEI CERT for C/C++](https://wiki.sei.cmu.edu/confluence/display/seccode/SEI+CERT+Coding+Standards)  
- PHP: [WordPress PHP Coding Standards](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/php/)  
- R: [Tidyverse R Style Guide](https://style.tidyverse.org/)  
- Objective-C: [Apple’s Cocoa Objective-C Coding Guideline](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/CodingGuidelines/CodingGuidelines.html)  
- TypeScript: [Google TypeScript Style Guide](https://google.github.io/styleguide/tsguide.html)  
- Swift: [Apple Swift Language Guidelines](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html)  
- HTML/CSS: [W3School HTML Style Guide and Coding Conventions](https://www.w3schools.com/html/html5_syntax.asp)


## Vocabulary & Grammatic

### Challenge

>_The hardest thing about choosing good names is that it_ **_requires good descriptive skills_** _and a_ **_shared cultural background_**_. This is a teaching issue rather than a technical, business or management issue_

### Examples of general rules on internet

- Class name should be substantive
- Method name should be verb
	- Boolean methods should be isNameOfMethod

### Four areas to focus on

- Control abbreviations.
	- Establish a controlled list of acceptable abbreviations.
- **Dictionary**: Use single word for each single meaning.
	- Establish terminological meanings for synonymous words.
- **Grammatic**: Use enough words to express the complete meaning.
	- Establish rules to get same results of naming.
- Avoid the very generalized words like Helper, Manager and Utils

### Abbreviations Control Table Sample

| Abbreviation | Description |
| ---- | ---- |
| HTTP | Hypertext Transfer Protocol |
| FTP | File Transfer Protocol |
| GUID | Globally Unique IDentifier |
| GUI | Graphical User Interface |
| UI | User Interface |
| URL | Uniform Resource Locator |
| URI | Uniform Resource Identifier |
| UTF | Unicode Transformation Format |
| UTC | Coordinated Universal Time |
| UX | User Experience |
| UML | Unified Modeling Language |
| VM | Virtual Machine |
https://en.wikipedia.org/wiki/List_of_computing_and_IT_abbreviations

### Grammatic

Here some examples how to use rules to build identifier name:

#### Boolean Variables

1. Ask yes or no question
	- Should start with help verb (is, are, will, should, etc.)
2. Use "this" to represent the current class object
3. "is this" becomes "is", "will this" becomes "will" and so on.
4. "is `adj`" becomes "`adj`", like "is hidden" becomes "hidden".
5. Avoid some words like: the, of,... without disturbing the meaning.
6. Use the language or industry recommended letters case.

#### Boolean Functions

1. Start with the verb "verify", like "verify if the component is loaded".
2. Use "this" to represent the current class object.
3. "is `adj`" becomes "`adj`", like "is hidden" becomes "hidden".
4. Remove some words like: "if", "the", "this". It could be like "verify component loaded".
5.  "verify valid" becomes "validate", "verfiy user form valid" becomes "validate user form".
6. Use the language or industry recommended letters case. The previous example will be "`verifyComponentLoaded`" in js, or "`VerifyComponentLoaded`" in C#.

