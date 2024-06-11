#ArraySequence
Define the Function Signature: Create a function rotLeft that takes an array a of integers and the number of rotations d as parameters.

Initialize Variables: Declare variables n to store the length of the array a, and create a new array rotatedArray of the same length as a to store the rotated elements.

Perform Left Rotations: Iterate over each element of the array a:

Calculate the new index for the current element after performing d left rotations. The new index can be calculated as (i + n - d) % n, where i is the current index and n is the length of the array.

Assign the value of the current element of a to the calculated new index in the rotatedArray.

Return Rotated Array: After iterating through all elements of a, return the rotatedArray.

