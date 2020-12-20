# UUID
UUID(v4) Generator and Parser for Node.js and Javascript(Web)

## UUID.fromString()

```
import UUID from "./UUID.js"

const uuid = UUID.fromString( "B264ABE9-287E-4C6C-9C2C-FDCB55A2338D" ) //ignore case
console.log( uuid instanceof UUID ) //true

//ng, throw TypeError
UUID.fromString( "777" ) //ilegal string
UUID.fromString( "B264ABE9287E4C6C9C2CFDCB55A2338D" ) //without hyphen
```

## UUID.randomUUID()

```
import UUID from "./UUID.js"

const uuid = UUID.ramdomUUID()
console.log( uuid instanceof UUID ) //true
```

## UUID.prototype.mostSignificantBits
readonly
The most significant 64 bits.

## UUID.prototype.leastSignificantBits
readonly
The least significant 64 bits.

## UUID.prototype.toString()

```
import UUID from "./UUID.js"

const uuid = UUID.ramdomUUID()
console.log( uuid.toString() ) //e.g. B264ABE9-287E-4C6C-9C2C-FDCB55A2338D
```

