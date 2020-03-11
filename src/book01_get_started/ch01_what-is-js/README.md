# What is JS?

## What is with that Name
Just Marketing to entice the Java community with a scripting alternative for the web.

Java and JS share similarities because developers had syntax expectations from C/C++.

Apart from that, "Java is to JavaScript as ham is to hamster." --Jeremy Keith, 2009.

Since Oracle owns the name JavaScript (via NetScape) and due to legal reasons, it is better to use JS or as
specified by TC39 and ECMA: **ECMAScript**.

## Language Specification
TC39 = Technical Committee that approves changes on JS and submit them to ECMA.

ES = defined Syntax and behaviour.

ES2019 === ECMA 10.0

## The Web Rules Everything about JS
Nevertheless, there will be conflicts between what TC39 wants and what the web can offer at the moment.

## Not all Web JS

Environments:
- Web: fetch(), getCurrentLocation()...
- Node.js: fs.write()...

alert(), console.log() are not defined in JS(). It is the environment running the JS engine which provides a behaviour.

## Not always JS
Do not assume native JS behaviour on different console environments, or to behave on the same way as it occurs when engines compile .js files.
