# Groovy NullPointerException in eachWithIndex

This example demonstrates a NullPointerException that can occur when using the `eachWithIndex` method in Groovy with a null list. The `eachWithIndex` method throws an exception when the list is null, even though one might expect it to simply not iterate. This is a common pitfall for Groovy developers who are accustomed to other languages with more forgiving null handling.

## Steps to Reproduce
1. Copy the code in `bug.groovy`
2. Run the script using `groovy bug.groovy`