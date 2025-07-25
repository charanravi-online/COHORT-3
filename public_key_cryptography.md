# banks vs blockchain
## banks auth
username + password -> bank -> view the account balance

## blockchain auth
if you ever want to create an account on the blockchain, you need to generate a public-private keypair.
### public private keypair
"Not your keys, not your crypto"

### public key
the public key is a string that can be shared openly.
pub key -> blockchain -> view account balance

### private key
the private key is a secret string that must be kept confidential.
priv key -> blockchain -> can send money (we don't want others sending our whole wallet to their wallet)

# Bits and Bytes
## bit
A bit is a smallest unit of data in a computer and can have one of two values - 0, 1.
0- off, 1- on.
## byte
A byte is a group of 8 bits.
It is the standard unit of data used to represent a single characeter in memory. Since each bit can either be 0 or 1, byte can have 2^8 (257) possible values, ranging from 0 to 255.

## string to binary
according to the ascii values, each character gets converted to a byte.

## base64
base64 encoding uses 64 different characters (A-Z, a-z, 0-9,+,/), means each character can represent one of 64 possible values.

## base58
It is similar to base64 but uses a different set of characters to avoid viaually similar characters and to make the encoded output more use friendly.
base58 uses 58 different characters: A-Z (excluding I and O), a-z (excluding l), 1-9 (excluding 0)

