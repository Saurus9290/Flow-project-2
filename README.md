## SomeContract
This contract implements the SomeContract smart contract, which consists of a struct, functions, and a resource. It showcases various access control modifiers and demonstrates how to interact with them.

## Structure
SomeStruct
The SomeStruct struct represents a data structure with four variables:

a (String): A publicly settable variable.
b (String): A publicly readable variable.
c (String): A variable accessible only within the contract.
d (String): A variable accessible only within the struct itself.
The struct also includes three functions:

publicFunc(): A publicly accessible function.
contractFunc(): A function accessible only within the contract.
privateFunc(): A function accessible only within the struct itself.
The structFunc() function demonstrates the usage of the struct and is the entry point for Area 1.

## SomeResource
The SomeResource resource represents a resource with a single variable:

e (Int): A publicly accessible variable.
The resource includes a function:

resourceFunc(): A function demonstrating the usage of the resource. This function serves as the entry point for Area 2.
## Functions
The contract includes the following additional functions:

createSomeResource(): A function that creates and returns an instance of SomeResource.
questsAreFun(): A function showcasing an action within the contract. This function serves as the entry point for Area 3.
## Usage
To interact with this contract, you can perform the following actions:

Access Area 1: Call the structFunc() function to execute the code within Area 1 of the SomeStruct struct.
Access Area 2: Call the resourceFunc() function on an instance of SomeResource to execute the code within Area 2 of the resource.
Access Area 3: Call the questsAreFun() function to execute the code within Area 3 of the contract.
Please note that certain variables and functions have specific access control modifiers, which limit their accessibility based on the context in which they are called.

## Initialization
Upon contract initialization, an instance of SomeStruct is created and assigned to the testStruct variable.
